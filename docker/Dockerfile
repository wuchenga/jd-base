FROM node:15.9.0-alpine3.12
LABEL maintainer="Evine Deng"
ARG JD_BASE_URL=https://gitee.com/superbei666/jd-base
ARG JD_BASE_BRANCH=master
ENV PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin \
    LANG=zh_CN.UTF-8 \
    SHELL=/bin/bash \
    PS1="\u@\h:\w \$ " \
    JD_DIR=/jd \
    ENABLE_HANGUP=true \
    ENABLE_WEB_PANEL=true
ARG KEY="-----BEGIN OPENSSH PRIVATE KEY-----\n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\n-----END OPENSSH PRIVATE KEY-----"
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.aliyun.com/g' /etc/apk/repositories \
    && apk update -f \
    && apk upgrade \
    && apk --no-cache add -f bash \
                             coreutils \
                             moreutils \
                             git \
                             wget \
                             curl \
                             nano \
                             tzdata \
                             perl \
                             openssl \
                             openssh \
    && rm -rf /var/cache/apk/* \
    && ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
    && echo "Asia/Shanghai" > /etc/timezone \
    && mkdir -p /root/.ssh \
    && chmod 700 /root/.ssh \
    && cd /root/.ssh \
    && echo -e $KEY > /root/.ssh/id_rsa \
    && chmod 600 /root/.ssh/id_rsa \
    && ssh-keyscan gitee.com > /root/.ssh/known_hosts \
    && git clone -b ${JD_BASE_BRANCH} ${JD_BASE_URL} ${JD_DIR} \
    && cd ${JD_DIR}/panel \
    && npm install \
    && npm install -g pm2 \
    && ln -sf ${JD_DIR}/jd.sh /usr/local/bin/jd \
    && ln -sf ${JD_DIR}/git_pull.sh /usr/local/bin/git_pull \
    && ln -sf ${JD_DIR}/rm_log.sh /usr/local/bin/rm_log \
    && ln -sf ${JD_DIR}/export_sharecodes.sh /usr/local/bin/export_sharecodes \
    && cp -f ${JD_DIR}/docker/docker-entrypoint.sh /usr/local/bin/docker-entrypoint.sh \
    && chmod 777 /usr/local/bin/docker-entrypoint.sh \
    && rm -rf /root/.npm
WORKDIR ${JD_DIR}
ENTRYPOINT ["docker-entrypoint.sh"]