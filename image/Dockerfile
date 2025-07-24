FROM alpine:latest as builder
COPY run.sh /app/run.sh

FROM alpine:latest
COPY --from=builder /app/run.sh /run.sh
ENTRYPOINT ["/run.sh"]
