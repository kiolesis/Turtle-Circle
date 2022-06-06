# Biblioteka żółwia (Turtle library)
PL: Repozytorium zawierające udokumentowany projekt oparty na bibliotece Turtle.\n
ENG: Repositorium containing documented project based on Turtle library)

### Zależności (Dependencies):
```python
from turtle import *
```

### Kod źródłowy (Source code):
```python
from turtle import *

color('red', 'yellow')

hideturtle()

begin_fill()
forward(200)
left(90)
forward(200)
left(135)
forward(284)
end_fill()

color("blue")
right(135)
forward(200)
right(90)
forward(200)
right(180)
forward(100)

begin_fill()
color("black")
circle(99, 500, 196)
end_fill()

color("white")
begin_fill()
circle(50, 190, 150)
circle(-49, 185, 55)
end_fill()

showturtle()

done()
```


### Zrzuty ekranu (Screenshots):
[[picture_turtle.png](https://github.com/kiolesis/Turtle-Circle/blob/main/picture_turtle.png)]
