ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="Rajesh MRK" \
    duration="120 HRS"
#here user1 is key, someuser is default value
ARG USERNAME=Rajeshkumar
ENV USERNAME=$USERNAME
RUN echo "Hello user: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]