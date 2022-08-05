# svt-av1-homebrew-testdata

This repo contains a videofile used for testing in the svt-av1 brew formula. The file was generated with the below command.

```
ffmpeg -y -f rawvideo -pixel_format yuv420p -video_size 64:64 -i /dev/zero -pix_fmt yuv420p -t 1 -c:v rawvideo video_64x64_yuv420p_25frames.yuv
```

sha256 checksum: 0c5cc90b079d0d9c1ded1376357d23a9782a704a83e01731f50ccd162e246492
