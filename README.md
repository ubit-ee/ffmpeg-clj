# ffmpeg-clj

A FFmpeg wrapper for Clojure

```clojure
ffmpeg-clj.core> (version)
"2.0.2"
ffmpeg-clj.core> (cmd :i "vid1.mp4" "vid1.avi")
["ffmpeg" "-i" "vid1.mp4" "vid1.avi"]
ffmpeg-clj.core> (ffmpeg! :i "1.mp4" "1.avi")
""
```
## License

Copyright © 2013 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
