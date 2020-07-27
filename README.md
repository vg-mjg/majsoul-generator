# majsoul-generator
Python program to generate majsoul hands pictures. Forked and translated from [here](https://github.com/Neutralization/majsoul-generator). It also calculates the score using this [site](https://www.diving-fish.com/mahjong/point), so it actually needs an internet connection. Just run it with 
```bash
$ python3 main.py
```
## Requirements
- [Python](https://www.python.org/)
- [Pillow](https://github.com/python-pillow/Pillow)

## Tileset resources
[Mahjong Soul](https://www.maj-soul.com/#/home)

## Manual
- 123456789m stands for man 🀇🀈🀉🀊🀋🀌🀍🀎🀏
- 123456789p stands for pin 🀙🀚🀛🀜🀝🀞🀟🀠🀡
- 123456789s stands for sou 🀐🀑🀒🀓🀔🀕🀖🀗🀘
- 1234567z stands for ton-nan-xia-pei-haku-hatsu-chun 🀀🀁🀂🀃🀆🀅🀄
- 0m 0p 0s stands for aka
- x stands for Mahjong Tile Back 🀫

## Examples
- 1112345678999m 0m
![](img/1112345678999m_0m.png)

- 19m19p19s1234567z 1p
![](img/19m19p19s1234567z_1p.png)

- 223344666888s6z 6z
![](img/223344666888s6z_6z.png)

- 123456789p5z x44xz 5z
![](img/123456789p5z_x44xz_5z.png)

- 1m 123m123p123s111z 1m
![](img/1m_123m123p123s111z_1m.png)
