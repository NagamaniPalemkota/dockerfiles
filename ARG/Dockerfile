ARG Version
FROM almalinux:${Version:-8} 
#can set default arg for Version using :-
ARG ${COURSE=DEVOPS}
ARG ${TRAINER=SIVA}
RUN echo "course is ${COURSE} and trainer is ${TRAINER}"
RUN cat /etc/*release
CMD ["sleep","80"]