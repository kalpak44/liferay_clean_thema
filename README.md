# clean bootstrap thema for liferay 7

### Tech

Dillinger uses a number of open source projects to work properly:

* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [node.js] - evented I/O for the backend
* [Gulp] - the streaming build system
* [FreeMarker] - Java Template Engine
* [jQuery] - duh

### Setup

```sh
$ gulp deploy:gogo
```
or can build and paste in the tomcat deploy folder
```sh
$ gulp build
```
PS. do'nt forget tо refresh modules your Felix Gogo Shell

```sh
$ telnet 127.0.0.1 11311
```
```sh
$ g! refresh
```
