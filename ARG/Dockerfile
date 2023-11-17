# arg is we can define on top of the from instruction on only 1 exception arg command will work untilfrom only it can acces on image not in 
# container level,we can set the defualt value of version if user was not provide the value, we can give the value through command line the 
# command id ( docker build --build-arg version=8 -t arg:v1 .)
# if u want to use the arg variable in container u need to fallow some steps below
ARG version
FROM almalinux:${version:-8}
ARG greeting
ENV greet=${greeting}
RUN echo ${greeting}
