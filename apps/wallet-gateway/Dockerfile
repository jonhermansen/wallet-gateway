FROM europe-docker.pkg.dev/da-images/public-unstable/docker/da-base-image:node
ARG version=REQUIRED
WORKDIR /app
RUN npm install @canton-network/wallet-gateway-remote@${version}
ENTRYPOINT ["./node_modules/.bin/wallet-gateway-remote"]
