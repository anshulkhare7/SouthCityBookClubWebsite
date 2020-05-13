# South City Book Club Static Website

[![Netlify Status](https://api.netlify.com/api/v1/badges/9b7e8a64-bb76-4ae6-b5f6-ad77f0e12eba/deploy-status)](https://app.netlify.com/sites/scbookclub/deploys)

Built using Jekyll. Served by Netlify.

## Docker

Using docker for [local setup](https://dev.to/michael/compile-a-jekyll-project-without-installing-jekyll-or-ruby-by-using-docker-4184)

Run this docker command from inside the root folder of the project.

`docker run --rm --volume="$PWD:/srv/jekyll" --volume="$PWD/vendor/bundle:/usr/local/bundle" --env JEKYLL_ENV=development -p 4000:4000 jekyll/jekyll:3.8 jekyll serve`

