## Build Dockerfile

I have attached Dockerfile to this repo to build it run:

```sh
docker build --tag ubuntu_jupyter_notebook .
```

## Run Dockerfile:

```
docker run --name ubuntu_jupyter_notebook -p 8888:8888 -d ubuntu_jupyter_notebook
```

Now open: [127.0.0.1:8888](https://127.0.0.1:8888)

In your browser and enter password `root`

