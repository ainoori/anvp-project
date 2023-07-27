FROM nginx
LABEL "Project"="anvp"
LABEL "Author"="an"


RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginanvpapp.conf /etc/nginx/conf.d/anvpapp.conf
