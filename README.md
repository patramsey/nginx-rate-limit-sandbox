# NGINX Rate Limit test
Test if we can rate limit on a HTTP query string variable. In the default setup this will hang until the request is allowed at 3r/m

## Build it
    in the same dir..
    docker build -t nginx-rate .
## Run it
    docker run -it --rm -p 80:80 nginx-rate
