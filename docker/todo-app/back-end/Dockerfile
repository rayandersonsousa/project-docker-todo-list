FROM node:14-alpine AS todobackend

WORKDIR /backend

EXPOSE 3001

ADD ./node_modules.tar.gz .

COPY . .

ENTRYPOINT ["npm"]
CMD ["start"]
