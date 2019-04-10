ARG TIMEZONE
ARG VERSION_NGINX

FROM nginx:${VERSION_NGINX}

ENV TZ=${TIMEZONE}
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
