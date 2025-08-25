ARG VERSION
FROM almalinux:${VERSION:-9}
ENV COURSE="devops" \
    TRAINER="Venu"
ARG DURATION="120HRS"
ENV DURATION=$DURATION
RUN echo "hi course is: ${COURSE}, trainer is: ${TRAINER}, duration is: ${DURATION}" 
CMD ["sleep", "1000"]           