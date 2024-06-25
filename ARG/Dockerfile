ARG Version
FROM almalinux:${Version:-8} 
#can set default arg for Version using :-
ARG COURSE=DEVOPS 
ARG TRAINER=SIVA
ARG Duration="3 months"
ENV Duration=${Duration}
RUN echo "course is ${COURSE} and trainer is ${TRAINER}"
RUN adduser EXPENSE
USER EXPENSE
RUN cat /etc/*release
CMD ["sleep","80"]