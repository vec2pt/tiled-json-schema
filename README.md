# Tiled Map JSON Schema

Unofficial repository with a JSON schema for the [Tiled](https://www.mapeditor.org/) Map format. The schema is based on the documentation: [JSON Map Format](https://doc.mapeditor.org/en/stable/reference/json-map-format/) (for version 1.12).

## TODO
- Map: Make the required `staggerindex` / `staggeraxis` based on the value of parameter `orientation`.
- Map: Make the required `hexsidelength` based on the value of parameter `orientation`.
- Layer: Check if the `offsetx` / `offsety` parameter is indeed a double and not an int.
- Layer: Make the required `chunks` / `compression` / `data` / `encoding` / `height` / `image` / `imageheight` / `imagewidth` / `layers` / `objects` / `repeatx` / `repeaty` / `transparentcolor` / `width` based on the value of parameter `type`.
- Object: Check if the `height` / `width` / `x` / `y` parameter is indeed a double and not an int.
