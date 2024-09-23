# my-portfolio

Portfolio website written in HTML, CSS and JS.

URI of website deployed on Akash: https://8hch8191j9ccp62754ivum269g.ingress.dal.leet.haus/

Spotify integration: [Spotify-Readme](https://github.com/tthn0/Spotify-Readme)

## Building your own image
The process involves modifying the code as desired and building it into a Docker image for deployment on Akash.

```
git clone https://github.com/rexayop/my-portfolio.git
docker build -t portfolio .
docker login -u $username
docker push portfolio
```
## Deploying
Deploy on [Akash Console](https://console.akash.network/) with the configured [deploy.yaml](deploy.yaml) file.
