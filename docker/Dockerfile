FROM node:14.10
COPY work /work
WORKDIR /work
RUN yarn add graphql @graphql-mesh/runtime @graphql-mesh/cli @graphql-mesh/openapi
CMD if [ -f "init.sh" ]; then sh init.sh; fi && yarn start