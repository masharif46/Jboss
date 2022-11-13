# Podman build


podman build --tag root/jboss .

podman images

podman run -dit --name jboss -p 80:8080  localhost/root/jboss

podman ps

podman exec -it jboss /bin/bash

