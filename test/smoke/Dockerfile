FROM alpine:3.17.4
RUN apk add curl

COPY smoke-test.sh smoke-test.sh

COPY smoke-test.sh smoke-test.sh

ADD smoke-test.sh smoke-test.sh

CMD ["sh", "smoke-test.sh", "http://app:3000"]
