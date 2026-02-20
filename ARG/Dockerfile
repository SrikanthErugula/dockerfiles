ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER" \
    TRAINER="SIVAKUMAR"
#ENV COURSE=${COURSE}
# the above cmd valla course name anedhi inside container lo kuda access avuthundhi .. ala ivvakapothe it can't be add 
RUN echo "Trainer: ${TRAINER}, Course: ${COURSE}, Version: ${VERSION}"
CMD ["sleep", "1000"]