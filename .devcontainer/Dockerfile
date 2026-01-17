FROM template:latest as devcontainer

WORKDIR /workspace

ARG REMOTE_USER
ARG REMOTE_UID
ARG REMOTE_GID
RUN useradd -r -m -u ${REMOTE_UID} -g ${REMOTE_GID} ${REMOTE_USER}
