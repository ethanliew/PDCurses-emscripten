## PDCursed compiled with emscripten
(uglily) hacked by Lu Wang 

### Demos (most interesting first)

- [xmas](http://coolwanglu.github.io/PDCurses-emscripten/web/xmas.html)
    - [xmas2 (different porting approach)](http://coolwanglu.github.io/PDCurses-emscripten/web/xmas2.html)
- [newdemo](http://coolwanglu.github.io/PDCurses-emscripten/web/newdemo.html)
- [worm](http://coolwanglu.github.io/PDCurses-emscripten/web/worm.html)
- [firework](http://coolwanglu.github.io/PDCurses-emscripten/web/firework.html)
- [rain](http://coolwanglu.github.io/PDCurses-emscripten/web/rain.html)
- [sdltest](http://coolwanglu.github.io/PDCurses-emscripten/web/sdltest.html)
- [ptest](http://coolwanglu.github.io/PDCurses-emscripten/web/ptest.html)


### Status

This repo is supposed to demonstrate the power of emscripten as well as PDCurses,
and to inspire people who would like to hack those.

Due to the limitation of JS, synchronized functions like `napms` and `getch` may not work.
Async versions are provided for some of them.

There is no further documentation or support right now.

### Instructions

- Get your self familiar with emscripten, curses and SDL
- Prepare the dependencies 
- Set up path of emscripten in `build.sh`
- Run `build.sh`
- Trail, error, google


### License
Read `README` in different folders 
