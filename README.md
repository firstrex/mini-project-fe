# Unison Frontend Engineer Mini-Project

## Task

For this mini-project, you will create a config driven website builder. We primarily focus on your thought process to architecting and designing frontend applications so please feel free to use any scaffolding tool like [Create React App](https://create-react-app.dev/) or reach for any library that you feel comfortable using. This project is designed to take less than two hours.

## Requirements

_**Please feel free to send us the Github link when you are finished.**_

The application is a simple website builder application that allows users to submit a JSON schema that creates elements on a page. The application should have a form to submit the schema and a UI to display the elements.

### Example JSON Schema and Output

```json
{
  "element": "div",
  "children": [
    { "element": "h1", "children": "Hello World!" },
    { "element": "p", "children": "I love pizza!" },
    {
      "element": "div",
      "children": [
        {
          "element": "a",
          "children": "Order pizza!",
          "props": { "href": "https://unison.com" }
        }
      ]
    }
  ]
}
```

```html
<div>
  <h1>Hello World!</h1>
  <p>I love pizza!</p>
  <div>
    <a href="https://unison.com">Order pizza!</a>
  </div>
</div>
```

### Extra Credit

- Add a feature that allows a user to change the order of child elements via drag and drop. The JSON schema should also update to reflect the order change.
