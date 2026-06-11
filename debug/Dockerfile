FROM almalinux:9
# Added bind-utils for nslookup and dig
RUN dnf install telnet net-tools iputils bind-utils -y 
RUN useradd roboshop
USER roboshop
CMD ["sleep", "10000"]