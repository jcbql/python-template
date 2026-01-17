FROM template:latest as devcontainer

WORKDIR /workspace

ARG REMOTE_USER
ARG REMOTE_UID
ARG REMOTE_GID
RUN groupadd -r -g ${REMOTE_GID} ${REMOTE_USER}
RUN useradd -r -m -u ${REMOTE_GID} ${REMOTE_USER}
