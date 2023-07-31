#### Project Setup

In order to spin up the project, in the root create .env with these two variables, with your own values.

MONGO_URI
JWT_SECRET

After that run this command

```bash
npm install && npm start
```

//137f02641cee66f3c765c40a2cc6deb8

Swagger UI

```yaml
/jobs/{id}:
  parameters:
    - in: path
      name: id
      schema:
        type: string
      required: true
      description: the job id
```
