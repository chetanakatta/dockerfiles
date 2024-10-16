#ARG can be 1st instruction in only one case...used to supply the version for FROM instruction
ARG version
#FROM almalinux:${version} --->commandline
FROM almalinux:${version:-8}
#setting default value can be overriden by command line
#RUN cat /etc/*release
ARG course=docker
#or we can set default value like this also
ARG trainer=chetana
ARG duration=120hrs
ENV duration=${duration}
##by setting env with same name as arg..we can access arg inside the container
RUN echo "course is: ${course}, trainer is: ${trainer}, duration is: ${duration}}"
CMD ["sleep", "100"]