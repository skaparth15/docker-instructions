FROM almalinux:9
RUN mkdir app
WORKDIR /app
ARG seconds=100
ENV seconds=${seconds}
RUN pwd
CMD ["sleep" ,"${seconds}" ]