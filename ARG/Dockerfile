ARG version
FROM almalinux:${version:-9}
ARG course="Devops with AWS" \
    duration="2hrs"
ENV duration=$duration
RUN echo "Course: $course, Duration: $duration"
CMD ["sleep", "100"]    