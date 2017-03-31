# OctoPrint Slicer

Slicer plugin offers useful features that OctoPrint's built-in slicer doesn't have:

- Rotate, scale, and move STL models.
- Slice multiple STLs at a time. Split 1 STL into unconnected parts.
- Slice based on Cura profiles you upload to OctoPrint.
- Customizable slicing settings, including Basic (layer height, bed temperature ...) and Advanced (print speed, start/end G-code ...).
- Slic3r support (when Slic3r plugin is installed).
- More is coming...

![Slicer plugin screenshot](/docs/screenshot1.png?raw=true "Slicer Screen Shot")


## Setup

Install via the bundled [Plugin Manager](https://github.com/foosel/OctoPrint/wiki/Plugin:-Plugin-Manager)
or manually using this URL:

    https://github.com/kennethjiang/OctoPrint-Slicer/archive/master.zip

## Contribute

Are you a proud developer? Do you want to pitch in? I have made it as easy as 1-2-3:

1. [Install Docker](https://docs.docker.com/engine/installation/). Make sure [Docker compose](https://docs.docker.com/compose/) is also installed.

1. Clone OctoPrint-Slicer and run it

```bash
git clone https://github.com/kennethjiang/OctoPrint-Slicer.git
cd OctoPrint-Slicer
docker-compose up
```

1. Open [http://localhost:5000/](http://localhost:5000/) in your browser

## Thanks
![BrowserStack](https://d3but80xmlhqzj.cloudfront.net/production/images/static/header/header-logo.svg "BrowserStack") BrowserStack generously sponsors a free license so that I can test Slicer Plugin on different browsers/versions.

