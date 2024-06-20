ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG COURSE=Docker
ARG TRAINER=Neelareddy
ENV DURATION=120HRS
RUN echo "Course is: ${COURSE},Trainer is: ${TRAINER},Duration is: ${DURATION}"
#CMD ["cat /etc/*release"]
CMD ["sleep","60"]