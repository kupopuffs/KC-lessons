# CSS Styling Tips
* Try to keep your shared stuff in one file, your page-specific stuff in another
  * e.g. `style.css` for your shared stuff, `about.css` for your `about.html`, etc...
* If you have duplicate rules, the last one wins.
  * `style.css` has a rule `h2 { color: black; }`
  * `home.css` has a rule `h2 { color: white; }`
    * `home.css` is used to style ONLY your `index.html`
  * in your index.html, you reference `style.css` and `home.css`
  * that means, `style.css`'s rule is ignored and `h2`'s color is `white`
  * what we SHOULD do is have only one rule in `style.css` or `home.css`
* in your `.html` code, you can apply multiple classes to a tag
  * separate out your classes by spaces
  * e.g. `<i class="fa fa-2x fa-at"></i>`
  * `fa`, `fa-2x`, and `fa-at` are all classes for this `<i>`
* for centering stuff, see https://www.w3schools.com/css/css_align.asp
* for moving the layers to top/bottom
  * you need both `position: relative` and `z-index: <i>`
  * negative `<i>s` are on bottom, bigger `<i>s` are on top
  * for more info, google `how to have img behind div`

### Fixed div on window, regardless of scrolling?
* What I google `css keep div fixed on screen`
