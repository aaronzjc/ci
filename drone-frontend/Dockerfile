FROM node:alpine

LABEL maintainer="zjc"

RUN apk add --update make

# install cnpm & vue tools
RUN npm install -g cnpm --registry=https://registry.npm.taobao.org && \
 	cnpm install -g @vue/cli && \
 	cnpm install -g @vue/cli-service-global
