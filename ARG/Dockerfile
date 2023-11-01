ARG version
FROM almalinux:${version:-8}
# arg variable before from will not work after from
RUN echo "version passed by user is: ${version}"
ARG COURSE
ARG TRAINER
RUN echo "course is:${COURSE}, trainer is:${TRAINER}"