ARG version
FROM almalinux:${version:-9}
ARG course="Devops With Aws" \
    duration="120hrs" \
    topic="Ansible"
ENV topic=$topic    
RUN echo "course: $course, duration: $duration, topic: $topic, version: $version"    
CMD ["sleep", "100"]    
