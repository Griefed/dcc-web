# Sources, GitHub, GitLab and Mirroring and all that good stuff

Repositories on GitHub are now for issues only. I've set up my own installation of GitLab and moved all my repositories over to [Git.Griefed.de](https://git.griefed.de/users/Griefed/projects). Make sure to check there first for the latest code before opening an issue on GitHub.

For questions, you can always join my [Discord server](https://discord.griefed.de) and talk to me there.

---

# docker-compose Converter Web

[[_TOC_]]

I've changed the index.html and .css under [/gh-pages](https://github.com/Griefed/dcc-web/tree/gh-pages) in order for the website to be deployed with regular apache's, for example a httpd:alpine docker container. 

---

Convert docker run/create commands to docker-compose.yml files.

[Webapp](https://bucherfa.github.io/dcc-web/)

Uses [docker-compose-converter](https://www.npmjs.com/package/docker-compose-converter)-library for the conversion. Submit issues for conversion at the [docker-compose-converter repo](https://github.com/bucherfa/docker-compose-converter/issues).

![alt text](.readme/fullpage_screenshot.png)

## General Project Setup

Build with the [vuejs cli](https://cli.vuejs.org/).

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files
```
npm run lint
```
