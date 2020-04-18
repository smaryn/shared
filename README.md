# Shared resources

##### Some files to be pasted into readme or other markdown files.

- Install imageMagick
```bash
sudo apt install imagemagick
```

- Convert md in [docs](./docs/shared.md) to png in [imgs](./imgs/67-md.png):
```bash
convert -background white -size 800x -fill black -font Noto-Mono -pointsize 18 caption:"$(cat docs/shared.md)" imgs/67-md.png
```

- Convert txt in [txt](./txt/123.txt) to png in [imgs](./imgs/123-txt.png):
```bash
convert -background white -size 860x -fill black -font Noto-Mono -pointsize 18 caption:"$(cat txt/123.txt)" imgs/123-txt.png
```
