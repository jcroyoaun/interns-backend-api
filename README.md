## interns-backend-api

This is a study case on how to approach the container creation and architecture for a FastAPI app as a DevOps engineer using an nginx reverse proxy to the Python backend and a postgres DB for persisting data.

This app works in conjunction with repos

* interns-db
* interns-webserver

1. Interns DB should get started first
2. interns Backend API should get started second
3. Lastly, we start interns Webserver


### Step #2 to run interns Backend API
Build a local image with the backend interns api code
```
minikube image build -t interns-backend-container .
```

Start the kubernetes deployment and services
