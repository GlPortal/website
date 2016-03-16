# GlPortal Website
## Docker
### Clone this repository

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
