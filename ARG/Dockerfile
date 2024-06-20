ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG ${COURSE:-Docker}
ARG ${TRAINER:-Neelareddy}
RUN echo "Course is: ${COURSE},Trainer is: ${TRAINER}"
#CMD ["cat /etc/*release"]
CMD ["sleep","60"]