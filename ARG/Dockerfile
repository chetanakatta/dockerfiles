#ARG can be 1st instruction in only one case...used to supply the version for FROM instruction
ARG version
#FROM almalinux:${version} --->commandline
FROM almalinux:${version:-8}
#setting default value can be overriden by command line
#RUN cat /etc/*release
ARG course
#or we can set default value like this also
ARG trainer
#RUN echo "course is: ${course}, trainer is: ${trainer}"
RUN echo "course is: ${course:-docker}, trainer is: ${trainer:-siva}"
CMD ["sleep", "100"]
