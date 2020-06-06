# Notes

## Design Ideas

* [See mobile design for NYTimes](https://www.nytimes.com/2019/01/14/opinion/government-shutdown-trump.html?): The app design is also very good. Mobile first!
* [Color palettes](https://refactoringui.com/previews/building-your-color-palette/)

## Links

* (VERY COOL) [CSS Style Guide][style-guide]
* (COOL) [CSS Only hamburger menu](https://codepen.io/mutedblues/pen/MmPNPG)
* (MEH) [Dropdown Responsive menu using only CSS](https://codepen.io/markcaron/pen/pPZVWO). Blog post explaining the Codepen is [here](https://medium.com/@heyoka/responsive-pure-css-off-canvas-hamburger-menu-aebc8d11d793) 
* [Using SASS in the hugo pipeline][hugo-pipes]
* [Using flexbox and CSS to move the sidebar without media queries][flexbox-youtube-video]

```css
.grid {
  display: grid;
  grid-template-columsn: repeat(auto-fill, minmax(15rem, 1fr));
  grid-gap: 1rem;
}
```

## Tools I'm not yet using or learning

* [PostCSS](https://postcss.org/): Not interested yet because I'm not sure it's necessary for my website, and also because I want to minimize my use of JS


[flexbox-youtube-video]: https://www.youtube.com/watch?v=qOUtkN6M52M "Flexbox youtube video"
[hugo-pipes]: https://regisphilibert.com/blog/2018/07/hugo-pipes-and-asset-processing-pipeline/
[style-guide]: https://kaliop.github.io/frontend-style-guide/2.0/css/#important