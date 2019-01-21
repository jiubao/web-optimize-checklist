# web-optimize-checklist
h5 performance optimization checklist


### ttfb
* cdn: js, css, img, svg, font, video, audio
* http header: cache-control (cache clean)
* resources loading order & async load
* Split router
* Split chunk: balance packages
* first patch: only include reachable code(first page or event first screen)
  move un-used code to async patch
* Offline package
* Data cache: local storage
* App api data pre-fetch
* Dllreference

### [rail](https://developers.google.com/web/fundamentals/performance/rail)
* 60 fps
* 线框图
* gif click load
* Img size
* Lazy img
* Lazy component, lazy package
* Infinite list

### script -> style -> layout -> paint -> composite
* [Chrome performance](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/): white page time
* raf instead of setTimeout
* web workers
* micro-tasks
* reduce selector complexity
* try to avoid layout
* flexbox
* avoid forced sync layout
* use transforms & opactiy
* moving elements with translateZ
* avoid overuse promotion
* Api Concurrent
* garbage collection & memory release
* opt algorithm
