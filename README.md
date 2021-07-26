# Memake
The tighter the nicer. `Memake` is the library's name itself. Use `Colmake` for color.

```c++
#include "Memake.h"
Memake mmk(800, 800, "memake window");

void draw() {
    mmk.drawRect(300, 600, 80, 70, Colmake.red);
}

int main() {
    mmk.update(draw);
    return 0;
}
```

## Dependencies
1. SDL2: `pacman -S sdl2` || `apt-get install libsdl2-dev`

- Since I am using Arch-btw, I just copy the `apt` command from internet without testing. So, I am not sure it will work on Ubuntu or not.

## Run
1. `git clone https://github.com/krehwell/PSM-2.git`
2. `cd PSM-2`
3. `make build`
4. `./main`

## Why This Exists?
Well by default SDL never provides you function like to Draw Circle nor Ellipse or even to Draw Triangle/Polygon. What SDL provides is
just Draw Rectangle and Draw Dot on screen. This Library can draw those 2D which SDL not provides by default. The more playground the more
imagination can be expressed. Also hey, there is a premade colors too with `Colmake`.

That's all the words I made up so that it seems a perfect project like everyone's make, but what I actually want is just to graduate. Who knows that someday, somebody use this library
to hack Elon Musk's Rocket.
