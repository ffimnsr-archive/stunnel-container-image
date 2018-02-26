FROM alpine:3.7
RUN apk --no-cache add stunnel ca-certificates
COPY entrypoint.sh /
ENTRYPOINT ["/entrypoint.sh"]
CMD ["stunnel"]

# Metadata
LABEL org.label-schema.vendor="ffimnsr" \
      org.label-schema.url="https://stunnel.org" \
      org.label-schema.name="Stunnel" \
      org.label-schema.description="Stunnel is a proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the programs code" \
      org.label-schema.version="1.0.0" \
      org.label-schema.docker.schema-version="1.0"
