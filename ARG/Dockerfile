ARG version 
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG COURSE=Docker
ARG TRAINER=Sivakumar
ENV Duration=100hrs
RUN echo "Course Name is ${COURSE}"
RUN echo "Trainer Name is ${TRAINER}"
RUN echo "Course Duration is ${Duration}"
CMD [ "sleep", "100" ]