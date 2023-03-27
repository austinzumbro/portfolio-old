# Portfolio

## Description

It seems prudent to get a page together where I can publicly and concisely share my work and contact information, so that is what I'm doing this week.

### My Approach

#### Page Building

I already have some experience building webpages in Wordpress and Squarespace environments, but this is the first time I've ever built a page from completely from scratch. I was struck by how similar the experience was working with the code as opposed to a third-party GUI. In many ways, it's an easier workflow because nothing is hidden behind menus. It is a visual challenge to scan through large bodies of text, but I'm sure that gets easier with more experience.

It is also much harder to build a page about myself. I never know what to write, so every time I need to generate copy, it slows me down. (I should probably just use lorem ipsum, but then I feel like I'll just have to come back to it, so why not get it out of the way.) But all of that is nothing compared how much I struggled with the visual aspect.

#### Colors

The most challenging part of this project was the design aspect. I feel very comfortable working with HTML elements and CSS selectors, and I can look up and follow documentation when I'm unsure, but there is no clear cut documentation for how a page should look, and visual/graphic arts are not my strong suit.

For that reason, I started by looking for reference texts online to see if I could slap together some "design rules" to follow so I didn't have to agonize so much over my options. I've heard the words "material design" bandied about a lot, so I started there.

Poking around on [material.io](https://m3.material.io/) wasn't particularly fruitful, but I did appreciate their "[color system](https://m3.material.io/styles/color/the-color-system/key-colors-tones)," which included some helpful guidelines for how to layout colors legibly. I was able to pick some colors off of a Japanese woodblock print, pop my favorite into a [Material Design Palette Generator](https://materialpalettes.com/), and then copy a bunch of those colors into :root variables for use throughout the project.

```css
--primary-key-color-10: #e7f1f6;
--primary-key-color-20: #c5ddea;
--primary-key-color-30: #a5c9dd;
--primary-key-color-40: #89b3cd;
--primary-key-color-50: #77a4c3;
--primary-key-color-60: #6996ba;
--primary-key-color-70: #5f89ae;
--primary-key-color-80: #53789d;
--primary-key-color-90: #4a688a;
--primary-key-color-100: #3a4c69;

--secondary-key-color-10: #e3f8f8;
--secondary-key-color-20: #bbedee;
--secondary-key-color-30: #93e2e5;
--secondary-key-color-40: #72d6da;
--secondary-key-color-50: #62ccd3;
--secondary-key-color-60: #5cc3cd;
--secondary-key-color-70: #56b2ba;
--secondary-key-color-80: #4f9da1;
--secondary-key-color-90: #4a888a;
--secondary-key-color-100: #3f6462;

--tertiary-key-color-10: #ece8f0;
--tertiary-key-color-20: #d1c7dc;
--tertiary-key-color-30: #b3a2c4;
--tertiary-key-color-40: #967ead;
--tertiary-key-color-50: #80639b;
--tertiary-key-color-60: #6c4a8a;
--tertiary-key-color-70: #654485;
--tertiary-key-color-80: #5b3c7b;
--tertiary-key-color-90: #513671;
--tertiary-key-color-100: #422c5e;

--neutral-key-color-10: #ffffff;
--neutral-key-color-20: #fafafa;
--neutral-key-color-30: #f5f5f5;
--neutral-key-color-40: #f0f0f0;
--neutral-key-color-50: #dedede;
--neutral-key-color-60: #c2c2c2;
--neutral-key-color-70: #979797;
--neutral-key-color-80: #818181;
--neutral-key-color-90: #606060;
--neutral-key-color-100: #3c3c3c;

--neutral-variant-color-10: #f7e9d5;
--neutral-variant-color-20: #dfcab3;
--neutral-variant-color-30: #c1a78d;
--neutral-variant-color-40: #a18667;
--neutral-variant-color-50: #8a6c4a;
--neutral-variant-color-60: #73542d;
--neutral-variant-color-70: #694a27;
--neutral-variant-color-80: #5a3e1f;
--neutral-variant-color-90: #4d3117;
--neutral-variant-color-100: #3e230d;
```

It took me a long time to arrive at this list, which arguably wasn't the best use of my time, but once I had it, I really enjoyed it. Once the page was built and I got to start tweaking, it made it super simple to try on different tones of the same color.

If I felt like the page was complete, I could go back and remove any unused colors. But given the scope of this project, I'm not too concerned.

(I will say, while I enjoyed doing all this research on Material Design, I don't particularly enjoy my results, nor have I particularly enjoyed any of the examples I've seen... So, while I will withhold judgement until I have a better understanding of the concept, I suspect I may just not like Material Design. I'll need to do more research on web/graphic designs to find out what I do like.)

#### Typography

I similarly agonized over the typography, but there was a lot less to agonize over. I found a tool called [Fontjoy](fontjoy.com) that will generate a trio of Google Fonts. I clicked around until I got something I could live with, then agonized over it a little more, and then decided it was good enough.

I've never had to import Google Fonts before, but the documentation was clear. I did somehow gloss over the part about importing different font styles, so I spent a few minutes confused about why I couldn't make anything bold. (Of course, right after I figured it out, I decided I didn't like the way those bolded things looked.)

## Credits

I referenced all of the following:

- [material.io](https://material.io)
- [Material Design Palette Generator](https://materialpalettes.com/)
- [CSS-Tricks' Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS-Tricks' Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- General Googling

## License

MIT License

Copyright (c) 2023 Austin Zumbro

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
