ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG COURSE=Docker
ARG TRAINER=Neelareddy
ARG DURATION=120HRS
ENV Duration=${DURATION}
RUN echo "Course is: ${COURSE},Trainer is: ${TRAINER},Duration is: ${DURATION}"
#CMD ["cat /etc/*release"]
CMD ["sleep","60"]