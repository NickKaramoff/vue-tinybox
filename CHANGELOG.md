# CHANGELOG

## 0.3.0

### 🛑 BREAKING

- ".min.js" version is removed in favor of ".umd.js"

### Improved

- package size went down ~170 bytes
- build configs are more readable now
- source code is more readable now

## 0.2.0

### New

- slide animation when navigating through photos (#3)
- on mobile devices images can now be navigated via swiping (#4)
    - this feature has limited support in MS Edge
- on computers images can now be navigated with arrow keys (#9)

### Fixed

- images weren't aligned vertically under some conditions (#8)
- user was able to scroll the content behind the lightbox (#11)

## 0.1.0

Initial pre-release of `vue-tinybox`

### New

- ability to open and close lightbox
- ability to pass photos as props
- ability to loop photos
