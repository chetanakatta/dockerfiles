#ARG can be 1st instruction in only one case...used to supply the version for FROM instruction
ARG version
FROM almalinux:${version}
RUN cat /etc/*release
CMD ["sleep", "100"]
