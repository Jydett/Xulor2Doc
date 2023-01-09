## Color
Denotes a color in RGBA format

#### Format:
``color="#[<r>][<g>][<b>][<a>]"``<br>
r,g,b,a = HEX value on 2 chars

#### Default value:
```
r = "00"
g = "00"
b = "00"
a = "FF"
```

#### Exemples:
``color="#0011AAFF"``<br>
``color="#FFFF"``<br>


### OR

#### Format:

``color="[<r>][,<g>][,<b>][,<a>]"``<br>
r,g,b,a = Float value ('.' for separator) between 1.0 and 0.0
#### Default value:

```
r = 0.0
g = 0.0
b = 0.0
a = 1.0
```

#### Exemples:
``color="1.0,1.0,0.0,0.0"``<br>
``color="1.0"``<br>
