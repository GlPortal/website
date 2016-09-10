# GlPortal Website
## Docker
- Clone this repository
- Install Docker

### Develop with docker compose
```
docker-compose up
```
Now visit the test site by pointing your browser to http://localhost:1100/.
### Develop with docker
```
docker run -it --rm -p 1100:1313 -v $(pwd):/data mbentley/hugo server --bind 0.0.0.0
```

Now visit the test site by pointing your browser to http://localhost:1100/.
### Run with docker
```
docker run -it --rm -v $(pwd):/data mbentley/hugo -v
```
This creates a static version of the page in the sub-directory public.
Use the webserver of your choice to host it.
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
