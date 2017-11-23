# Beat Step X
## About the Project

[![Video](http://img.youtube.com/vi/s6vm0xBc-rA/0.jpg)](https://www.youtube.com/watch?v=s6vm0xBc-rA)

[YouTube Link](https://www.youtube.com/watch?v=s6vm0xBc-rA)

The main concept is you can play any mode (k3, k4, k5...), with different judgments types.


### Server API
A REST API to be used on the Web Site and Desktop Client.
- [Laravel](https://laravel.com)

### Site
The site is built as SPA (Single-page Application), so you can go through pages listen to music without stop (like SoundCloud).
- [Angular](https://angular.io)


### Game
The game is built in JS (TypeScript compiled to JS) using WebGL.
- [TypeScript](https://www.typescriptlang.org/)
- [Phaser](https://github.com/photonstorm/phaser-ce)


### Desktop Wrapper
Using [Electron](https://electron.atom.io/) to wrap the site.


## How the project is separate
Currently, I'm using Git repositories hosted on GitLab.
- Server API
- Web App
- Game Core
- Game Render
- Multiplayer Server
- Desktop App (Standalone version)
- Map (Map system for the Campaign Mode)