<p></p>
<h1> Spotlight - Photo Gallery </h1>

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Whats in 1.0??

The new version includes tons of fixes, new features and improvements which was collected over the last two years. Read the <a href="CHANGELOG.md">Changelog</a> to get all new features.

- No additional Javascript coding
- No additional HTML snippets
- No additional CSS resources
- No additional icons/assets
- No additional handling of dynamic content and event listener

<a name="features" id="features"></a>
## Features

```
- Video Support
- Mounting HTML node fragments as slides (you can add just everything as a slide!)
- Gallery groups:
  - group images to specific galleries
  - group options inheritance
- Toolbar & Gallery tools:
  - Fullscreen
  - Zoom in/out
  - Toggle resize
  - Switch theme
  - Autoslide
  - Download
  - Progress Bar
  - Page
  - Title (also inherits from image "alt"-attribute)
  - Description
  - Customizable button
- Adaptive responsive images (by viewport size, pixel ratio and available internet bandwidth)
- Auto-fit images and videos (as "contain" or as "cover")
- Custom Controls
- Fully configurable via markup
- Loading Spinner
- Smart Preloading (prefetch next image including cancellation)
- Customize via standard options
- Simply customize via markup (data-attributes)
- Built-in animations
- Custom themes
- Custom animations
- Supported controls:
  - Keyboard
  - Touch
  - Mouse (Move + Wheel)
- Back-Button (Android)
- Callbacks (onclick, onshow, onclose, onchange)
- Global API for programmatic usage
```

__Technical properties:__

```
- Outstanding performance
- Memory optimized, tiny footprint, fully cleans up
- Event capturing (just one single global event listener)
- Bind additional global event listener dynamically:
  - install when gallery opens
  - cleanup when gallery was closed
- No dependencies, no jQuery
- Fully Responsive
- Touch-friendly mobile support
- Super-lightweight, all in all just 9kb gzip (js + css + html + icons)
- Support for ES6 module system
```

#### Pending Feature Suggestions:

```
- Inline Gallery
- Pinch Zoom Support
- 2-Panel-Paging Strategy
- Swipe down to close
```

__Get Latest (NPM):__

```cmd
npm install spotlight.js
```

__Get Latest Nightly (Do not use for production!):__

Just exchange the version number from the URLs above with "master", e.g.: "/spotlight/__0.7.8__/dist/" into "/spotlight/__master__/dist".

> When using markup on anchor elements to inject the library, it is advisable to load the library in the head section of the document. This helps prevent the original behavior of the anchor tag from occurring (such as when the library hasn't fully loaded at page start).

---

Copyright 2023 Talo <alphaotuken>
Released under the <a href="http://www.apache.org/licenses/LICENSE-2.0.html" target="_blank">Apache 2.0 License</a><br>
