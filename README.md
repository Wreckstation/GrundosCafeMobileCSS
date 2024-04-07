# GrundosCafeMobileCSS
Enhanced sitewide mobile CSS for grundos.cafe. Main page is located on /~HiImAGrub/.

## Features
* collapsible sidebars
  * nothing goes in sidebar css so it should work with custom sidebars, just make sure nothing overwrites the other
* Because of the zoom, some html5 games may be too large. Switch to landscape mode to resize the ui.
* Sidebars and header will stay in place while scrolling
  * This can be removed by changing this css:
```css
/*Original*/
div#page_content {
min-height:[x];
max-height:[x];
overflow:auto;
}
/*Change to this*/
div#page_content {
overflow:auto;
}
```

## Versions
### `mobilecss.css`
The main css. Both sidebars are collapsible in this version.
### `rightcollapsibleonly.css`.
Version that only collapses the right sidebar. The Classic Neopets look!
### `RightCollapsibleCompatible.css`
Some devices/browsers have difficulty with the original css. This is a different implementation that will work on those devices, but the right sidebar can no longer be scrolled in place.

## Addons
### `NoDescriptionCol.css`
optimizes horizontal space by removing item descriptions. Increases width of remove column.

## Images
### Original
![screenshot of grundos.cafe without any custom css](https://i.imgur.com/u05kzR1.png)

### With CSS
![gif of new layout. everything is bigger and the side navigations are collapsible](https://i.imgur.com/GQJjRbW.gif)
