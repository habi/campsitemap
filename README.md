# Detailed map of campings

Howto:
- Install [`map-machine`](https://github.com/enzet/map-machine/blob/main/doc/INSTALL.md), preferrably in a new conda environment (via `conda create -n map-machine python=3.9`).
- Test the installation by issuing `map-machine render -b=2.284,48.860,2.290,48.865` and you should have an image in the file `out/map.svg`.
- To render a detailed map of the [Camping VD 8](https://www.openstreetmap.org/way/359338758), you could issue the command 
````
map-machine render \
    --boundary-box=6.712,46.802,6.723,46.807 \
    --zoom=16 \
    --output=out/vd8.svg
````
