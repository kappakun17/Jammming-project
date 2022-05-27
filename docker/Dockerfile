ARG NODE_VERSION

FROM node:${NODE_VERSION}


ARG SHARED_FRONT_WORKSPACE_CONTAINER


RUN apt-get update \
    && apt-get install -y \
        vim \
        wget \
        curl \
        git \
    && echo ${NODE_VERSION}

WORKDIR ${SHARED_FRONT_WORKSPACE_CONTAINER}


