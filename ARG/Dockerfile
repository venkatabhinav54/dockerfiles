ARG version
FROM almalinux:${version:-9}  
ARG course="DevOps with AWS" \
    duration="120hrs"
ENV duration="$duration"    
RUN echo "Course= $course, Duration= $duration, version: $version"
CMD ["sleep", "100"] 

#commad  -->  docker build -t arg:v1 --build-arg course=docker .
# this command is used for override the args

#${version: is a arg, and -9 is default version  }