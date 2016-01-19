# File Location Conventions

Conventions regarding **all** systems.

## service configuration files

the directory `/etc/protonet/<container-name>/` on the host is mounted into `/config` on the container.


## data persistence

the directory `/data/<container-name>/` on the host is mounted into `/data` on the container.


# Naming Conventions

## Images vs. Containers vs. Services

Container names are expected to be a short variant of the image name. For example the container corresponding  to image `experimentalplatform/ptw:development` is named `ptw`. The corresponding systemd service unit contains this short form and the string `protonet`, for example `ptw-protonet.service`.