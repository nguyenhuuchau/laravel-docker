FROM nginx:stable-alpine

# ADD Custom Config
ADD ./docker/production/nginx/nginx.conf /etc/nginx/nginx.conf
ADD ./docker/production/nginx/default.conf /etc/nginx/conf.d/default.conf

## Make Directory - Workspace
#RUN mkdir -p /var/www/html
#
## ADD and set Group
#RUN addgroup -g 1000 laravel && adduser -G laravel -g 1000 -s /bin/sh -D laravel
#
## Set Group to Workspace
#RUN chown laravel:laravel /var/www/html
