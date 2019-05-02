# Todos List

The source code can be viewed at [https://github.com/ragasubekti/todo-api-firestore](https://github.com/ragasubekti/todo-api-firestore)

Host: [https://us-central1-coba-23d3c.cloudfunctions.net/v1](https://us-central1-coba-23d3c.cloudfunctions.net/v1)

| Endpoint            | Method        | Description       | Body              |
|-----------------    |---------------|-------------------|-------------------|
| /todos              | `GET`         | Get All Todos     |                   |
| /todos              | `POST`        | Create todos      | `{"content": ""}` |
| /todos/?id=:id      | `PUT`         | Edit Todos        | `{"content": ""}` |
| /todos/done?id=:id  | `PUT`         | Mark todo as done |                   |
| /todos/?id=:id      | `DELETE`      | Delete a todo     |                   |
