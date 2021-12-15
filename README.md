# Heureka sample widgets
Collects examples for frontend applications using the widget concept of Heureka!.

## Vanilla JS
The first example is using the [heureka-widget-navigation](https://github.com/SOTETO/heureka-widget-navigation-2021) to 
show its usage for a plain HTML, JavaScript and CSS application. The _LyricsSearch_ app is copied from 
[vanillawebprojects](https://github.com/bradtraversy/vanillawebprojects/tree/master/lyrics-search).

### Setup
Running `docker-compose up` in the directory of the cloned repository will start an NGINX that is serving the _LyricsSearch_
app on `localhost://8080/test/`. To use it in the context of Heureka! and therefore getting all required CSS styles, you
just have to start the `INFRA` environment of the [Heureka-CLI](https://github.com/SOTETO/heureka) and call `http://localhost/test/`.
