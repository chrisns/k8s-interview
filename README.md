# Pre-Interview Exercise

## Scenario

You have been given a docker image by a developer but they've unhelpfully not supplied any documentation, it is your responsibility to figure out what on earth they've done in order to start the application.

## Instructions

Make the docker container [chrisns/docker-devtest](https://hub.docker.com/r/chrisns/docker-devtest) run, you'll be told when you've reached the end.

You're expected to capture **your full shell history** while you're working on this, we're mostly interested in seeing your workings rather than the finished end result, so please annotate this with your thinking on what you're exploring and what you learn from the output each time.

Once you've got a working `docker run` you should convert it to `version: 3` [docker-compose](https://docs.docker.com/compose/).

Finally you should then translate it to work in a highly available and scalable implementation with Kubernetes with [minikube](https://github.com/kubernetes/minikube). Hint: `minikube start --addons=ingress` to get an ingress controller.

## Expected outputs

- `shell_history.txt` - annotated shell history.
- `docker-compose.yaml` - a working Docker Compose implementation of the app
- `deployment.yaml` - a working deployment yaml for Kubernetes that can be deployed to minikube
- `service.yaml` - a working service yaml for Kubernetes that can be deployed to minikube
- `ingress.yaml` - a working ingress yaml for Kubernetes that can be deployed to minikube
- `notes.txt` - any thoughts or notes you'd like to share with the assessor
- `web-history` - google/stackoverflow/etc is allowed but we do ask to see your history while you're working on it