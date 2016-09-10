# GlPortal Website
## Docker
### Clone this repository

# Install Docker
Install docker on the system you want to run the website on.

### Develop with docker compose
```
docker-compose up
```
### Develop with docker
```
docker run -it --rm -p 1313:1313 -v $(pwd):/data mbentley/hugo server --bind 0.0.0.0
```
### Run with docker
```
docker run -it --rm -v $(pwd):/data mbentley/hugo -v
```
## Hugo
### Run with Hugo
Get hugo:
```
go get -u -v github.com/spf13/hugo
```

Clone the repository and run the following command to run the testserver:
```
hugo server
```
