ARG version
FROM almalinux:${version:-8}
ARG name=Srinath
ARG age=27
ARG learning=DevOps
ENV learning=${learning}
RUN echo "my name is: ${name},age:${age}, learning:${learning}}"
CMD [ "sleep", "1000" ]