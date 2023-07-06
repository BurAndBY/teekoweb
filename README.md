# Tee K.O. Web

An rehostable version of [this site](https://teeko.jackboxgames.com). 
To translate use [this file](https://github.com/JackboxArchivists/teekoweb/blob/main/bundles.jackbox.tv/main/%40teeko-web/80627b6f.js).

Live current site version: [click me](https://tee.burs.ml/)

## Requirements

* A web server
* ~~SSL certificate~~ Not required anymore

## Installation instructions
1. **Clone this repository**
```bash
     git clone https://github.com/burandby/teekoweb.git/
```
2. **Use a webserver of your choice.**

**How to use web-server on python:**
```bash
python3 -m http.server
```
or
```py
import functools
    
Handler = functools.partial(http.server.SimpleHTTPRequestHandler, directory='location/of/your/teekoweb/folder')
```


---
This project is not endorsed or made by Jackbox Games.
