# web-optimize-checklist
h5 performance optimization checklist


### ttfb
* cdn: js, css, img, svg, font, video, audio
* http header: cache-control (cache clean)
* resources loading order & async load
* Split router
* Split chunk: balance packages
* first patch: only include reachable code
* Offline package
* Data cache: local storage
* App api data pre-fetch
* Move un-used code to async patch

### [rail](https://developers.google.com/web/fundamentals/performance/rail)
* [Chrome performance](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/): white page time
* 60 fps
* 线框图
* Api Concurrent
* Dllreference
* gif click load
* Img size
* garbage collection & memory release
* Lazy img
* Lazy component, lazy package
* Infinite list
* opt algorithm
