## responsive website
#### According to the device website will response
- landscape: width > height
- portrait: height > width


## Understanding Units

- px: it's not responding with viewport. It's fixed
- '%': depends upon parent div. it can be (0-100)%
- vh: viewport-height
- vw: viewport-width
    - vh, vw depends to viewport, not depends upon parent
- vmax: viewport-max
    - viewport-height > viewport-width ==> vmax become vh
    - viewport-width > viewport-height ==> vmax become vw
- vmin: viewport-min
    - viewport-height < viewport-width ==> vmin become vh
    - viewport-width < viewport-height ==> vmin become vw
- em: emphemeral unit
    - 1 em = parent's size
    - 2 em = 2 * parent's size 
- rem: root em
    - 1 rem = 16px, 2 rem = 32px

<br>

## Layout of website
- position: absolute; ==> very tough to make it responsive
    - it's static

- display: flex; ==> makes container flexiable
    - #### when i decrease the width of viewportgit 
        - using flex containers shrink automatically without scroll-bar.
        - if we use flex-wrap: wrap; ==> without shrink it will go under. Also can add scroll-bar for single container.
    - flex-direction: colume; ==> it will distribute container vertically

<br>

## CSS Media Queries*
==> according to the screen-size(viewport) website will behave

- @media (max-width: 600px) {
    - if my screen-size <= 600px then this section will work
    - specifically i took 600px because mostly mobile screens are less than 600px
}


### some tips:
- position: relative; ==> give at parent div. So, its child divs are always exist within parent div
- calc(): we do arithmatic calcultation
    - calc(100% - 100px): there must have to give space around of '-'