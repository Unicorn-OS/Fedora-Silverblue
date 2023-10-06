# Solution: Fix ffmpeg RPMfusion conflict!
Discuss:
- https://discussion.fedoraproject.org/t/cant-update-to-silverblue-38-libavcodec-free-conflicts-with-ffmpeg-libs/81265
- https://discussion.fedoraproject.org/t/unable-to-install-ffmpeg-libs-on-fedora-38-silverblue-beta/79632

```
rpm-ostree upgrade --install ffmpeg-libs --uninstall libavcodec-free
# or
rpm-ostree override remove libavcodec-free --install ffmpeg-lbs
```

old:
- https://discussion.fedoraproject.org/t/fedora-kinoite-37-ffmpeg-libs-conflict-error/75771/3
