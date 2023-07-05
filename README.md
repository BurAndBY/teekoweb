# Tee K.O. Web

An rehostable version of [this site](https://teeko.jackboxgames.com). 
To translate use [this file](https://github.com/BurAndBY/tee/blob/main/bundles.jackbox.tv/main/%40teeko-web/80627b6f.js), if someone can help beautify this file please send a pull request.

Live current site version: [click me](https://bur.is-a.dev/tee)

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
*I don't really know what to write here. If you want to help improve this readme, please pull request this repo.*
