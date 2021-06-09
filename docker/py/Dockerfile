FROM python:3.6.13-alpine
LABEL maintainer="Evine Deng"
ARG JD_BASE_URL=https://gitee.com/superbei666/v3
ARG JD_BASE_BRANCH=py
ARG KEY="-----BEGIN OPENSSH PRIVATE KEY-----
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
-----END OPENSSH PRIVATE KEY-----"
ENV PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin \
    LANG=zh_CN.UTF-8 \
    SHELL=/bin/bash \
    PS1="\u@\h:\w \$ " \
    JD_DIR=/jd \
    ENABLE_HANGUP=true \
    ENABLE_WEB_PANEL=true
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.aliyun.com/g' /etc/apk/repositories \
    && apk update -f \
    && apk upgrade \
    && apk --no-cache add -f bash \
                             tzdata \
                             nodejs \
                             npm \
                             coreutils \
                             moreutils \
                             git \
                             wget \
                             curl \
                             nano \
                             tzdata \
                             perl \
                             openssl \
                             make \
                             gcc \
                             g++ \
                             libc-dev \
                             musl-dev \
                             musl \
                             autoconf \ 
                             libtool \
                             openssh \
                             yarn \
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
    && npm install -g pm2 websocketserver \
    && pip --no-cache-dir install aiohttp requests wasmtime rsa \
    && ln -sf ${JD_DIR}/jd.sh /usr/local/bin/jd \
    && ln -sf ${JD_DIR}/git_pull.sh /usr/local/bin/git_pull \
    && ln -sf ${JD_DIR}/rm_log.sh /usr/local/bin/rm_log \
    && ln -sf ${JD_DIR}/export_sharecodes.sh /usr/local/bin/export_sharecodes \
    && cp -f ${JD_DIR}/docker-entrypoint.sh /usr/local/bin/docker-entrypoint.sh \
    && chmod 777 /usr/local/bin/docker-entrypoint.sh \
    && apk del make gcc g++ musl-dev musl autoconf build-base libffi-dev libtool \
    && rm -rf /tmp/* \
    && rm -rf /var/cache/apk/* \
    && rm -rf /root/.npm
WORKDIR ${JD_DIR}
ENTRYPOINT docker-entrypoint.sh