FROM alpine:3.6
WORKDIR /todo-app/front-end/
COPY ./node_modules.tar.gz ./
COPY ./ ./
EXPOSE 3000
ENTRYPOINT [ "npm" ]
CMD [ "start" ]
