# 7yuv snap wrap build from exist binnary
## If you want to buy the product, just goto the author's website
http://datahammer.de/
### Address
- Datahammer Ltd. & Co. KG
- Raoul-Wallenberg-Str. 44
- 12679 Berlin
- GERMANY

### Phone
+49-30-9331472
### Email
support@datahammer.de
## Datahammer 7yuv YUV Viewer, Raw Bayer/RGB Viewer, YUV Editor, and Hex Editor.

7yuv is is a tool for editing and visualizing raw graphics data and binary files. It is a valuable tool to assist development of games, video codecs, and general graphics programming.

A large number of surface formats is supported, including RGB and YUV pixel formats.

## TODO
- [x]  build basic snap package from binary
- [ ] Add start icon in menu
- [ ] Host machine file system access
- [ ] Publish it to snap store
## snap build
```bash
snapcraft --debug --use-lxd
```
## snap install
You may need install it with debug and dangerous mode.
```bash
snap install --dangerous --devmode 7yuv_0.1_amd64.snap
```
## About the snap store release
I am not the software owner, so I will not publish it to the store unless I get the authorization from the owner, I have sent a email about it but no ack

## snap info
- snap plugin: dump
- snap refer : https://github.com/marvinav/qtiplot-wrap
## about the origin 7yuv package
I also put the origin 7yuv package in this repo, because the owner server was down for a very long time, so just backup.
- [x] Win32 exe
- [x] Linux deb, only works on qt4 + debain system
- [x] Linux tar, only works on qt4
- [x] Snap package, should work on snapd system. download it from the release page
