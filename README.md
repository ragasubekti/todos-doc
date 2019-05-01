# Todos List

Host: [https://us-central1-coba-23d3c.cloudfunctions.net/v1](https://us-central1-coba-23d3c.cloudfunctions.net/v1)

| Endpoint        | Method        | Description       | Body              |
|-----------------|---------------|-------------------|-------------------|
| /todos          | `GET`         | Get All Todos     |                   |
| /todos          | `POST`        | Create todos      | `{"content": ""}` |
| /todos/:id      | `PUT`         | Edit Todos        | `{"content": ""}` |
| /todos/:id/done | `PUT`         | Mark todo as done |                   |
| /todos/:id      | `DELETE`      | Delete a todo     |                   |
