# Setting up Render
[Back to all labs](../README.md)

---

## Guide
1. Google it
2. ???
3. Profit


## More guide
In the folder `FastAPI-Example`, you'll find the files I've added to my repo. Add them to a repo, in GitHub (or something like that), and go to the [Render Docs](https://render.com/docs/your-first-deploy). (`render > docs > Your first deploy`)

Follow the guide. It references [this](https://github.com/render-examples/fastapi/tree/main) repo.

Use the following start command in the Render settings.

```bash
uvicorn main:app --host 0.0.0.0 --port 8000
```

Here, `main` is the name of the Python file (without the `.py`). It is better to replace `8000` with `$PORT` and then adding the `PORT` as `8000` in the environmental variables, but not important for now.

Now we shuold have a simple API in the cloud. :D


## Sources
| Site   | Description                                                     | Link                                                 |
| ------ | --------------------------------------------------------------- | ---------------------------------------------------- |
| Render | Main site                                                       | https://render.com                                   |
| Render | Documatation                                                    | https://render.com/docs                              |
| Render | Docs > Your first deploy                                        | https://render.com/docs/your-first-deploy            |
| GitHub | Render FastAPI example                                          | https://github.com/render-examples/fastapi/tree/main |
| Render | Render Dashboard (where your projects/web services are located) | https://dashboard.render.com                         |
