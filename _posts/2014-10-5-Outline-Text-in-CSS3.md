I found it difficult to outline text in HTML/CSS.  The text-shadow property is the best way around this that I've tried, producing better outcome was in Safari and Firefox, weaker/more lo-fi results in Chrome.

.outline {
    background-color: #000000;
    color: #000000;
    text-shadow: -1.5px 0 white, 0 1.5px white,
    1.5px 0 white, 0 -1.5px white;
    font-size: 3.5em;
}
