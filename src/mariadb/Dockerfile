ARG TIMEZONE
ARG VERSION_MARIADB

FROM mariadb:${VERSION_MARIADB}

ENV TZ=${TIMEZONE}
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
