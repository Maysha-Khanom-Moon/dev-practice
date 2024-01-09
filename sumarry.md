## responsive website
<b>According to the device website will response<b>
- landscape: width > height
- portrait: height > width


## Understanding Units

- px: it's not responding with viewport. It's fixed
- '%': depends upon parent div. it can be (0-100)%
- vh: viewport-height.
- vw: viewport-width. 
    - => vh, vw depends to viewport, not depends upon parent
- vmax: viewport-max
    - => viewport-height > viewport-width --> vmax become vh
    - => viewport-width > viewport-height --> vmax become vw
- vmin: viewport-min
    - => viewport-height < viewport-width --> vmin become vh
    - => viewport-width < viewport-height --> vmin become vw
    - => vh, vw, vmax, vmin also can used in font-size