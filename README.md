# Shared resources

##### Some files to be pasted into readme or other markdown files.

- Install imageMagick
```bash
sudo apt install imagemagick
```

- Convert md in [docs](./docs/shared.md) to png in [imgs](./imgs/67-md.png):
```bash
convert -background white -size 450x -fill black -font Times-Roman -pointsize 14 caption:"$(cat docs/shared.md)" imgs/67-md.png
```
