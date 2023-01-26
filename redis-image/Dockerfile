# Use existing base image
FROM alpine

# download and install a dependency
RUN apk add --update redis

# tell image what to do when starts
CMD ["redis-server"]