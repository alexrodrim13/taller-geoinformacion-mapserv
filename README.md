# mapserver-geoinformacion
Practica MapServer Curso Geoinformacion en WEB


Clone this repo into */var/www/html/geoinformacion/*

```
mkdir tmp
```

### Example 1
```
shp2img -m ejemplo1.map -o tmp/ejemplo1.png -i PNG
```

### Example 2
```
shp2img -m ejemplo2.map -o tmp/ejemplo2.png -i PNG
```

### Example 3
```
shp2img -m ejemplo3.map -o tmp/ejemplo3.png -i PNG
```

### Example 4
```
shp2img -m ejemplo4.map -o tmp/ejemplo4.png -i PNG
```

### Example 5
```
shp2img -m ejemplo5.map -o tmp/ejemplo5.png -i PNG
```

### Example 6
```
shp2img -m ejemplo6.map -o tmp/ejemplo6.png -i PNG
```

### Example 7
```
shp2img -m ejemplo7.map -o tmp/ejemplo7.png -i PNG
```

### Example 8
```
shp2img -m ejemplo8.map -o tmp/ejemplo8.png -i PNG
```
### Example 9

WMS GetCapabilities Request

```
http://localhost:90/cgi-bin/mapserv?map=/var/www/html/geoinformacion/mapserver-geoinformacion/ejemplo9.map&SERVICE=WMS&VERSION=1.1.1&REQUEST=GetCapabilities
```
