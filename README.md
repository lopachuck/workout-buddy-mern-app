# Run a Frontend Server

```shell
cd frontend
```

```shell
yarn
```

```shell
yarn start
```

---

# Run a Backend Server

`[important]` Make sure you have a MongoDB server running on your machine.
You can use a cloud service like MongoDB Atlas.
And update the `backend/.env` file with your MongoDB connection string.

example:

```dotenv
MONGO_URI=mongodb+srv://<DB_NAME>:<DB_PASSWORD>@workout-buddy.mongodb.net/?retryWrites=true&w=majority`
```

```shell
cd backend
```

```shell
yarn
```

```shell
yarn dev
```