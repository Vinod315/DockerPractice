# dockerfiles/ARG/Dockerfile
ARG version
FROM almalinux:${version:-9}      # default to 9 if not supplied; can't be used again after FROM
ARG course="docker" \
    trainer="sivakumar" \
    duration="10hrs"
ENV course=${course} \
    duration=${duration} \
    trainer=${trainer}            # promote build args into runtime env vars
RUN echo "Course is: ${course}, Duration is: ${duration}, Trainer is: ${trainer}, Version is: ${version}"