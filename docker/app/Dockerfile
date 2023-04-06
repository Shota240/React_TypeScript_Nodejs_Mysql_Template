FROM node:16-alpine

WORKDIR ./app

# 初回処理
COPY ./docker-entrypoint.sh /tmp
ENTRYPOINT ["/tmp/docker-entrypoint.sh"]

RUN apk add bash