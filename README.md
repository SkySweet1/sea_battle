# Реализация бота

## Компиляция

```bash
    g++ -std=c++17 \
    main.cpp board.cpp bot.cpp game.cpp render.cpp \
    -I/opt/homebrew/include \
    -L/opt/homebrew/lib \
    -lraylib \
    -framework CoreVideo -framework IOKit \
    -framework Cocoa -framework GLUT -framework OpenGL \
    -o SeaBattle
```

## Запуск

```bash
   ./SeaBattle
```
