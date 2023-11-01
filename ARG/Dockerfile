ARG version
FROM almalinux:${version:-8}
# arg variable before from will not work after from
RUN echo "version passed by user is: ${version}"
ARG COURSE
ARG TRAINER
# if u want to acess values in container then give
ENV COURSE={COURSE}
ENV TRAINER=${TRAINER}
RUN echo "course is:${COURSE}, trainer is:${TRAINER}"