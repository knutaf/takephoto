```
Usage: takephoto.exe [-st milliseconds] [-w width_pixels] [-h height_pixels] [-o outpath] [-int milliseconds] [-count num] [-enum] [-d device_index]
  -?: this help text
  -d: device index to use. Use -enum to list valid device indices.
  -enum: Instead of taking a photo, list camera devices and device
   indices currently available.
  -h: height of output image in pixels. Default: camera's native
   resolution.
  -int: interval between taking pictures. Used only if -count is > 1.
   Default: 1000
  -count: number of photos to take. Use -1 to take infinite pictures.
   Default: 1.
  -o: output path. This path can contain a printf format string, in
   which case it is treated as a format for repeated photos. The
   format string should contain a single numeric format.
   Default: photo.jpg.
  -st milliseconds: stabilization time (time to wait after
   initializing the camera, before taking the first photo)
  -w: width of output image in pixels. Default: camera's native
   resolution.
```
