`ART3402`

# Interactive Design

- **Spring 2021**
- Wednesday, 1:25–4:05 p.m., online/remote via Zoom, Slack, and GitHub
- [Zoom Meeting](https://emmanuel.zoom.us/j/3352305835) (`Passcode` via [EC Learn](https://eclearn.emmanuel.edu/courses/3148012))
- [Slack Workspace](https://id-sp20-ec.slack.com)
- Office Hours: Wednesday, 12:15–1:15 p.m. before class or by appointment via Zoom and Slack
- Instructor: Justin Gagne
- Email: `gagnej@emmanuel.edu`
- Work: Design lead for [Gymnasium](https://thegymnasium.com) at [Aquent](https://aquent.com) in Boston, MA.

- - -

- [Schedule](#schedule)
- [Tools](#tools)
- [Books](#books)
- [Resources](#resources)

- - -

## Schedule

Wednesday, 1:25–4:05 p.m.

1. [Week 1](#week-1), January 27
2. [Week 2](#week-2), February 3
3. [Week 3](#week-3), February 10
4. [Week 4](#week-4), February 17
5. [Week 5](#week-5), February 24
6. [Week 6](#week-6), March 3
7. [Week 7](#week-7), March 10
8. [Week 8](#week-8), March 17
9. [Week 9](#week-9), March 24
10. [Week 10](#week-10), March 31, *No class*, mid-semester break
11. [Week 11](#week-11), April 7
12. [Week 12](#week-12), April 14
13. [Week 13](#week-13), April 21
14. [Week 14](#week-14), April 28
15. [Week 15](#week-15), May 5, *Last class*, Cinco de Mayo
16. [Week 16](#week-16), May 12, *Optional class*; work session; update all projects (repos) and rubrics (see repo **Issues** tab) for final grading
17. [Week 17](#week-17), May 19, *Final grades due*


## Week 1

> What separates design from art is that design is meant to be functional.
>
> —[Cameron Moll](http://cameronmoll.com), designer, writer, and speaker

> Real web designers write code. Always have, always will.
>
> —[Jeffrey Zeldman](https://www.zeldman.com), designer, writer, and publisher

### Hello World

- [The World Wide Web project](http://info.cern.ch/hypertext/WWW/TheProject.html)
- [This is a web page.](https://justinjackson.ca/words.html)
- [This is a motherfucking website.](http://motherfuckingwebsite.com)

### Homework

Working in HTML only, update your *naked* homepage via GitHub with some real content, maybe about what you’re interested in, what you like about the web, a few cool links, etc., using a handful of HTML elements, [sans CSS](https://laurakalbag.com/css-naked-day-2020/), and no [deprecated tag soup](https://css-tricks.com/why-do-some-html-elements-become-deprecated/).

#### Goals

1. Focus on content first.
2. How to define and separate content, semantics, and structure from visual presentation (look and feel, that’ll come later).
3. Overview of [HTML vocabulary](http://apps.workflower.fi/vocabs/html/en).
4. Overview of [HTML elements](http://html5doctor.com/#glossary).

#### Handoff

- Create a GitHub repo, with a `README.md` and an `index.html`, in all-lowercase, and separate words with a hyphen (no spaces or underscores).
  - For example:
    - `hello-world`
      - `index.html`
      - `README.md`
  - See [demo repo](https://github.com/ec-student/hello-world) for details.
  - See also [Naming guidelines](https://developers.google.com/style/filenames) and [Dashes vs. underscores](https://www.mattcutts.com/blog/dashes-vs-underscores/) for details.
- Add your URL to the `01-hello-world` channel in Slack.

#### Read Me

- [The unreasonable effectiveness of simple HTML](https://shkspr.mobi/blog/2021/01/the-unreasonable-effectiveness-of-simple-html) by Terence Eden
- [Web History, Chapter 1: Birth](https://css-tricks.com/chapter-1-birth/) by [Jay Hoffmann](https://thehistoryoftheweb.com) (with audio by Jeremy Keith)
- [A Brief History of Markup](https://html5forwebdesigners.com/history/) by [Jeremy Keith](https://adactio.com)
- [Why Do We Call it a Homepage?](https://thehistoryoftheweb.com/why-do-we-call-it-a-homepage/) by Jay Hoffmann
- [Content First — Design Last](https://www.smashingmagazine.com/2015/02/design-last/) by [Rik Schennink](http://rikschennink.nl)

#### Watch Me

- [The Layers Of The Web](https://vimeo.com/373128517) by Jeremy Keith [`45:14`]

#### See Also

- [HTML Basics](https://marksheet.io/html-basics.html)
- [HTML5 Element Index](http://html5doctor.com/#glossary)
- [HTML Reference](https://htmlreference.io)
- [HTML Vocabulary](http://apps.workflower.fi/vocabs/html/en)
- [Hello World · GitHub Guides](https://guides.github.com/activities/hello-world/)
  - ↑ **Note:** **Only Steps 1 and 3 apply** for the majority of the work we’ll do.
- [Format your messages in Slack](https://slack.com/intl/en-cz/help/articles/202288908-Format-your-messages)

#### Et Cetera

- ["Hello, World!" program](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program)


## Week 2

> Content precedes design. Design in the absence of content is not design, it’s decoration.
>
> —[Jeffrey Zeldman](https://twitter.com/zeldman/status/804159148?lang=en)

> Good design and good markup provide structure to content. Good markup is a fundamental part of good design: beautiful on the inside, beautiful on the outside.
>
> —[Frank Chimero](https://frankchimero.com), designer, illustrator, and writer

### Markup & Style

- [W3Fools](https://www.w3fools.com) – Better web education for all
- [Wayback Machine](https://web.archive.org)
- [CSS Zen Garden](http://www.csszengarden.com)
- [Do websites need to look exactly the same in every browser?](http://dowebsitesneedtolookexactlythesameineverybrowser.com)

### Homework

Validate, update, and rework your HTML, then enhance your homepage with basic CSS typography, color, and layout. Continue to focus on content and accessibility while looking great, all at the same time. Content first; design second. Oh, and design for mobile first.

#### Handoff

- Add an external style sheet to your homepage, `main.css` in a `css` folder, in all-lowercase, and `<link>` to it from `index.html`.
  - For example:
    - `hello-world` (or `3d-printing`, `pumpkin-pie`, etc.)
      - `css`
        - `main.css`
      - `index.html`
      - `README.md`
    - See [demo repo](https://github.com/ec-student/hello-world) for details.
- Use [web safe colors](https://htmlcolorcodes.com/color-chart/web-safe-color-chart/) in shorthand hex (hexadecimal) color codes.
  - For example: A solid blue is `#00f` as a shorthand hex color code (versus `#0000ff`).
- Use [accessible color combinations](#color-pickers) to meet AA and/or AAA criteria.
- Use basic [typography](https://cssreference.io/typography/) properties for setting text case (`text-transform`), weight (`font-weight`), style (`font-style`), leading (`line-height`), etc.
- Use proper typographic characters for fractions (½), degrees (℉), quotes (“”), etc.
  - Use the human readable character, *not the code*, from [HTML Symbols, Entities, Characters and Codes](https://htmlarrows.com).
- Use basic [web safe fonts](https://web.mit.edu/jmorzins/www/fonts.html) in a [CSS font stack](https://www.cssfontstack.com) (system fonts with almost equal support on Mac and PC).
- Use basic [box model](https://cssreference.io/box-model/) properties for spacing (`padding` and `margin`) and rules (`border`). And maybe even add a [`background-color`](https://cssreference.io/backgrounds/#background-color).
- Write meaningful and concise alt text descriptions (when using images).
  - Aim for a single sentence in under 100 characters (120 characters at max) for each alt text description.
- Validate [HTML](https://validator.w3.org/nu/) and [CSS](https://jigsaw.w3.org/css-validator/), and [check links](https://validator.w3.org/checklink).

#### Read Me

- [
The Design Of HTML5](https://html5forwebdesigners.com/design/) by [Jeremy Keith](https://adactio.com)
- [A Look Back at the History of CSS](https://css-tricks.com/look-back-history-css/) by [Jay Hoffmann](https://thehistoryoftheweb.com)
- [Alt text is part of your site’s content](https://www.centercentre.com/2016/06/30/2016-06-30-alt-text-is-part-of-your-sites-content/) by [Jessica Ivins](https://jessicaivins.net/)
  - [When writing alt text, ask yourself this question](https://www.centercentre.com/2016/06/09/2016-06-09-when-writing-alt-text-ask-yourself-this-question/)
- [Typography Matters](https://alistapart.com/article/typography/) by [Erin Kissane](http://incisive.nu/about/)
- [Fonts on the Web: Web-safe Fonts](https://www.fonts.com/content/learning/fyti/using-type-tools/fonts-on-the-web) by [Ilene Strizver](http://thetypestudio.com)
- [Colour contrast - why does it matter?](https://accessibility.blog.gov.uk/2016/06/17/colour-contrast-why-does-it-matter/) by Richard Morton

#### Watch Me

- [Remembrance of Tags Past](https://codetalks.tv/talk/remembrance-of-tags-past-eric-a-meyer-css-minsk-js-2019-tyxfxvm-8zu) by [Eric A. Meyer](https://meyerweb.com/) `[46:33]`

#### See Also

- [CSS Basics](https://marksheet.io/css-basics.html)
- [CSS Reference](https://cssreference.io)
- [CSS Vocabulary](http://apps.workflower.fi/vocabs/css/en)
- [Working With Typography](https://learn.shayhowe.com/html-css/working-with-typography/)

#### Et Cetera

- [Short note: The abbreviation appreciation society](https://developer.paciellogroup.com/blog/2019/03/short-note-the-abbreviation-appreciation-society/) by Steve Faulkner
- [Setting Height And Width On Images Is Important Again](https://www.smashingmagazine.com/2020/03/setting-height-width-images-important-again/) by [Barry Pollard](https://www.tunetheweb.com/)
- [What does "HREF" stand for?](https://tomayko.com/blog/2008/wtf-is-an-href-anyway) by Ryan Tomayko


## Week 3

### Homework

Markup and style a webpage focusing on content related to [procedural instructions](https://www.literacyideas.com/procedural-texts). From a meal on the cheap recipe to a lockdown fitness exercise, and beyond — how-to, tutorial, etc. You may use existing content *with* attribution. Use of your photographs or illustrations for imagery is *optional* but encouraged.

#### Markup

- Use headings: `h1`, `h2`, `h3`, etc.
  - See [The HTML Section Heading elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)
- Use lists: `dl`, `ol`, and `ul`
  - See [HTML content is 90% text](https://marksheet.io/html-text.html)
- Use images, figures, and captions: `img`, `figure`, and `figucaption`
  - See [The figure & figcaption elements](http://html5doctor.com/the-figure-figcaption-elements/)
- Use text-level elements: `em`, `strong`, `sup`, `time`,  `mark`, etc.
  - See [The small parts within a block of text](https://marksheet.io/html-inline-semantics.html)
- Write meaningful and concise alt text descriptions (when using images).
  - Aim for a single sentence in under 100 characters (120 characters at max) for each alt text description.
    - See [Alt text is part of your site’s content](https://www.centercentre.com/2016/06/30/2016-06-30-alt-text-is-part-of-your-sites-content/) by [Jessica Ivins](https://jessicaivins.net/)
    - See also [When writing alt text, ask yourself this question](https://www.centercentre.com/2016/06/09/2016-06-09-when-writing-alt-text-ask-yourself-this-question/)
- Use of proper typographic characters for fractions (½), degrees (℉), quotes (“”), etc.
  - Use human readable characters, *not codes*, from [HTML Symbols, Entities, Characters and Codes](https://htmlarrows.com).

#### Style

- Use type and class selectors
  - See [How to target HTML elements](https://marksheet.io/css-selectors.html)
- Use font styling with web safe fonts and colors
  - Use typography properties for setting text case (`text-transform`), weight (`font-weight`), style (`font-style`), leading (`line-height`), etc.
    - See [The Web is 90% text, so let's style it first](https://marksheet.io/css-text.html)
    - See also [Fundamental text and font styling
](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)
  - Use [web safe colors](https://htmlcolorcodes.com/color-chart/web-safe-color-chart/) in shorthand hex (hexadecimal) color codes.
    - For example: A solid blue is `#00f` as a shorthand hex color code (versus `#0000ff`).
  - Use [accessible color combinations](#color-pickers) to meet AA and/or AAA criteria.
    - See [Colour contrast - why does it matter?](https://accessibility.blog.gov.uk/2016/06/17/colour-contrast-why-does-it-matter/) by Richard Morton
  - Use [web safe fonts](https://web.mit.edu/jmorzins/www/fonts.html) in a [CSS font stack](https://www.cssfontstack.com) (system fonts with almost equal support on Mac and PC).
- Use [box model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model) properties for spacing ([padding](https://marksheet.io/css-padding.html) and [margin](https://marksheet.io/css-margin.html)) and rules ([border](https://marksheet.io/css-border.html)).

#### Handoff

- Add an external style sheet to your homepage, `main.css` in a `css` folder, in all-lowercase, and `<link>` to it from `index.html`.
  - For example:
    - `how-to`
      - `css`
        - `main.css`
      - `index.html`
      - `README.md`
- Validate [HTML](https://validator.w3.org/nu/) and [CSS](https://jigsaw.w3.org/css-validator/), and [check links](https://validator.w3.org/checklink).
- Add your URL to the `02-how-to` channel in Slack.

#### Read Me

- [Opening the Box Model](https://learn.shayhowe.com/html-css/opening-the-box-model/)
- [Naming CSS Stuff Is Really Hard](https://sparkbox.com/foundry/naming_css_stuff_is_really_hard) by [Ethan Muller](https://www.ethanmuller.com)

#### See Also

- [HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)


## Week 4

### Homework

Continue to work on your how-to webpage with the following semantic, accessible, interactive, and visual enhancements:
  - Add semantic elements for meaningful structure and design.
  - Add in-page navigation and link to external content.
  - Style links and lists for readability and accessibility.
  - Choose one external example as inspiration to progressively enhance the visual style of an element on your webpage.
    - **Note:** Capture (screenshot or link to) the source of inspiration to later share.

#### Read Me

- [
Semantics](https://html5forwebdesigners.com/semantics/) by [Jeremy Keith](https://adactio.com)
- [Semantic navigation with the nav element](http://html5doctor.com/nav-element/)
- [When do the :hover, :focus, and :active pseudo-classes apply?](https://bitsofco.de/when-do-the-hover-focus-and-active-pseudo-classes-apply/) by [Ire Aderinokun](https://ireaderinokun.com)
- [Anchors OK? Re-Assessing In-Page Links](https://www.nngroup.com/articles/in-page-links/)
- [Understanding Progressive Enhancement](https://alistapart.com/article/understandingprogressiveenhancement/) by [Aaron Gustafson](https://www.aaron-gustafson.com)

#### See Also

- [CSS selectors](https://www.quirksmode.org/css/selectors/) by Peter-Paul Koch
- [Learn CSS Positioning](https://ishadeed.com/article/learn-css-positioning/) by Ahmad Shadeed

#### Recap

- [Colors in CSS](https://ishadeed.com/article/css-color/)
- [Spacing in CSS](https://ishadeed.com/article/spacing-in-css/)
- [Using alt text properly](https://www.a11yproject.com/posts/2013-01-14-alt-text/)


## Week 5

### Homework

Continue to work on your how-to webpage with the following accessible, interactive, and visual enhancements:
  - Add a visual progress enhancement with CSS pseudo-elements `::before`, `::after`, and `::marker`.
  - Add a disclosure widget to supplemental content with the HTML `details` element.

**Note:** Full support for `::marker` in all browsers is limited to the `li` element within an ordered or unordered list. All other elements, such as the `summary` element within the `details` element, are not yet supported natively in Chrome and Safari. <mark>Test `::marker` in Firefox for full support.</mark>

#### Demo

- [CSS Generated Content and Visual Enhancements With Pseudo-Elements](https://jsbin.com/tetorob/edit?html,css,output)

#### Read Me

- [CSS Lists, Markers, And Counters](https://www.smashingmagazine.com/2019/07/css-lists-markers-counters/)
- [Custom bullets with CSS ::marker](https://web.dev/css-marker-pseudo-element/)
- [&lt;details&gt;: The Details disclosure element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details)

#### See Also

- [Diving into the ::before and ::after Pseudo-Elements](https://codersblock.com/blog/diving-into-the-before-and-after-pseudo-elements/)
- [Switchin’ to Firefox](https://www.robinrendle.com/notes/switchin-to-firefox)

#### Recap

- [Understanding Progressive Enhancement](https://alistapart.com/article/understandingprogressiveenhancement/) by [Aaron Gustafson](https://www.aaron-gustafson.com)
- [Naming CSS Stuff Is Really Hard](https://sparkbox.com/foundry/naming_css_stuff_is_really_hard) by [Ethan Muller](https://www.ethanmuller.com)


## Week 6

### Homework

1. Start to wrap-up work on your how-to webpage focusing on accessibility and performance best practices:
    - Review and update color contrast ratio to improve the accessibility of content. Remember — typography, color, and layout are visual enhancements — content and accessibility first.
      - See [Color Pickers](#color-pickers) tools.
    - Resize and optimize images to the size they appear in the browser or at a maximum, double the width for retina and super retina displays, and aim for an optimized file size around `150 KB` and below (`200 KB` at max, please).
      - See [Image Optimization](#image-optimization) tools.
2. Select a single topic (page) from [Wikipedia](https://wikipedia.org) to redesign the mobile and desktop experience as one web, single- or multi-page website for everyone.
    - For example — <i>Hypertext</i>: [mobile version](https://en.m.wikipedia.org/wiki/Hypertext) (`m-dot`) and [desktop version](https://en.wikipedia.org/wiki/Hypertext).

#### Demo

- [Decoding & Loading Images](https://github.com/ec-student/img-async-lazy)

#### Read Me

- [Choose the right image format](https://web.dev/choose-the-right-image-format/)
- [Optimizing Images for Web: A Practical Guide](https://www.abetterlemonadestand.com/optimizing-images-for-web/)

#### Try Me

- [Color Contrast Accessibility Validator](https://color.a11y.com/)

#### See Also

- [Pausing a GIF with details/summary](https://css-tricks.com/pause-gif-details-summary/)
- [Synchronous / Asynchronous Image Decode using〈img decoding〉Attribute](https://usefulangle.com/post/277/img-decoding-attribute)
- [Browser-level image lazy-loading for the web](https://web.dev/browser-level-image-lazy-loading/)

#### Recap

- [Writing Good Alt Text](https://www.youtube.com/watch?v=flf2vS0IoRs) `[9:56]`

#### Et Cetera

- [Lazy loading via attribute for images & iframes](https://caniuse.com/loading-lazy-attr)


## Week 7

### Homework

1. Working with your selected wiki topic from [Wikipedia](https://wikipedia.org), create a barebones HTML website, single- or multi-page, that focuses on the structure and semantics of your content.
    - **Note:** Avoid use of images and CSS, for now, focus on content first.
2. Develop a style tile to later transcribe to CSS
    - Select free fonts via [Google Fonts](https://fonts.google.com)
    - Compare web safe (system) fonts and web fonts via [Webfont Test](http://webfont-test.com)
    - Select colors via [HTML Color Codes](https://htmlcolorcodes.com)
      - See [Color Codes](#color-codes)
    - Create an accessible color palette via [Accessible color palette builder](https://toolness.github.io/accessible-color-matrix/)
    - Download a template via [Style Tiles](http://styletil.es)
3. Wrap-up how-to webpage
    - Project rubric (task list) to be announced.

#### Demo

- [Multi-Page Wiki](https://ec-student.github.io/multi-page/)

#### Read Me

- [Responsive Web Design](https://alistapart.com/article/responsive-web-design/) by [Ethan Marcotte](https://ethanmarcotte.com)
- [Style Tiles and How They Work](https://alistapart.com/article/style-tiles-and-how-they-work/) by [Samantha Warren](https://samanthawarren.design)

### Try Me

- [Textise](https://www.textise.net)

### Recap

- [alt attributes like paragraphs](https://daverupert.com/2020/09/alt-attributes-like-paragraphs/) by Dave Rupert


## Week 8

### Homework

Continue work on your wiki web page or site with the following visual enhancements:

1. Add `em`-based typography
2. Add `em`-based breakpoint for type scale update for wider layout
3. Add `rem`-based box model dimensions and spacing
4. Add `em`-based breakpoint using `grid` layout for a horizontal navigation
5. Add `em`-based breakpoint using `float` to create a text wrap around a figure and/or image

#### Demo

- [CSS Responsive Typography, Breakpoints, and Layout](https://jsbin.com/fuvejiz/edit?html,css,output)

#### Read Me

- [Web Layout History](http://grid-layout.com/history.html) by [Dr. Steven D. Anderson](https://drsteveanderson.com)
- [A History of CSS Through Fifteen Years of 24 ways](https://24ways.org/2019/a-history-of-css-through-15-years-of-24-ways/) by [Rachel Andrew](https://rachelandrew.co.uk)
- [The New CSS Layout, An Excerpt](https://alistapart.com/article/the-new-css-layout-excerpt/) by Rachel Andrew

#### Watch Me

- [Ethan Marcotte Live: A Dao of Flexibility](https://aneventapart.com/news/post/ethan-marcotte-a-dao-of-flexibility-video) `[56:32]`
- [Creating CSS Grid](https://channel9.msdn.com/Blogs/msedgedev/Creating-CSS-Grid) `[2:45]`

#### See Also

- [How we learned to leave default font-size alone and embrace the em](https://www.filamentgroup.com/lab/how-we-learned-to-leave-body-font-size-alone.html)
- [The EMs have it: Proportional Media Queries FTW!](https://cloudfour.com/thinks/the-ems-have-it-proportional-media-queries-ftw/)
- [float CSS property](https://developer.mozilla.org/en-US/docs/Web/CSS/float)
- [Learn CSS Grid](https://learncssgrid.com)

#### Recap

- [Responsive Web Design](https://alistapart.com/article/responsive-web-design/) by [Ethan Marcotte](https://ethanmarcotte.com)


## Week 9

### Homework

Continue work on your wiki web page or site with the following visual enhancements:

1. Add a web font for headings via Google Fonts
2. Review and apply Week 7 and 8 homework into current project

### Wrap-Up

- Complete How-To: Rubric Task List; to be announced as an Issue in your repo

#### Read Me

- [The Decade-Long Path to Web Fonts](https://thehistoryoftheweb.com/web-fonts/)
- [System fonts don’t have to be ugly](https://iainbean.com/posts/2021/system-fonts-dont-have-to-be-ugly/?ref=betterwebtype&mc_cid=3fd365001a&mc_eid=e2a9a05ded)

#### See Also

- [How to use Google Fonts in your next web design project](https://www.freecodecamp.org/news/how-to-use-google-fonts-in-your-next-web-design-project-e1ad48f1adfa/)
- [Google Fonts](https://fonts.google.com)

#### Recap

- [Webfont Test](http://webfont-test.com)


## Week 10

- *No class*, mid-semester break


## Week 11

### Sync

- Wiki Web work-in-progress review
- How-To: Rubric Task List due
  - Review, complete, and check off tasks, as best as possible.
- Discussion of final project
  - Single Serving: Design a modern responsive single serving website — a single-page with a single-theme using your own content; focusing on type, color, image, and layout.
    - Keep it simple and fun, for example:
      - [Books on Graphic Design (and Typography)](https://booksongraphicdesign.com)
      - [How to Order Eggs](https://onepagelove.com/how-to-order-eggs)

## Week 12

### Milestone

- Wiki Web page/site due

## Week 13

### Milestone

- Single-Serving work-in-progress review
- Wiki Web: Rubric Task List due

## Week 14

- Workshop (Code Time)

## Week 15

### Milestone

- Single Serving page/site due
- Single Serving: Rubric Task List due


## Tools

### Text Editors

Choose your brand or flavor; free-range, open, or locally sourced.

- [Atom](https://atom.io) (GitHub/Microsoft)
- [BBEdit](https://www.barebones.com/products/bbedit/) (Mac only; made in North Chelmsford, Massachusetts since 1993)
- [Brackets](http://brackets.io) (Adobe)
- [Visual Studio Code](https://code.visualstudio.com) (Microsoft)
- [JS Bin](https://jsbin.com) (web-based; made in Brighton, England with blood, sweat, and code)

### Browsers

Browsers *other than* Chrome (or Safari). See [Switchin’ to Firefox](https://robinrendle.com/notes/switchin-to-firefox/)

- [Firefox](https://www.mozilla.org/en-US/firefox/new/)
- [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/)
- [Microsoft Edge](https://www.microsoft.com/en-us/edge)
- [Opera](https://www.opera.com)

### Developer Tools

Validate HTML, CSS, links, and accessibility of colors.

- [W3C Developer Tools](https://www.w3.org/developers/tools/)
- [Color Contrast Accessibility Validator](https://color.a11y.com/)

### Color Codes

- [HTML Color Codes](https://htmlcolorcodes.com)
  - [Web Safe Color Chart](https://htmlcolorcodes.com/color-chart/web-safe-color-chart/)
- [Hex Color Picker Tool](https://hexcolor.co/color-picker)
- [Web Safe Colors](https://websafecolors.info)
- [Tint & Shade Generator](https://maketintsandshades.com)

### Color Pickers

Simple color pickers for checking the accessibility of text against the Web Content Accessibility Guidelines (WCAG).

- [Accessible Colors](https://accessible-colors.com)
- [Contraste](https://contrasteapp.com) (Mac 10.13+)
- [Pika](https://superhighfives.com/pika) (Mac 10.15+)

### Image Optimization

- [ImageOptim](https://imageoptim.com/mac) (Mac only)
- [JPG.rocks](https://jpeg.rocks/) — Privacy-aware JPEG optimizer
- [Squoosh](https://squoosh.app)

### Text Only

- [Textise](https://www.textise.net)

### Writing, Grammar, and Punctuation

- [Grammarly](https://app.grammarly.com)
- [Hemingway Editor](http://www.hemingwayapp.com)
- [The Punctuation Guide](https://www.thepunctuationguide.com)

### HTML Special Characters

- [HTML Symbols, Entities, Characters and Codes](https://htmlarrows.com)
- [Charcod.es](https://charcod.es)


## Books

Nice-to-have, but *not required*.

- [HTML5 for Web Designers](https://abookapart.com/products/html5-for-web-designers) by Jeremy Keith (Second Edition)
- [Responsive Web Design](https://abookapart.com/products/responsive-web-design) by Ethan Marcotte (Second Edition)
- [Designing with Web Standards](https://www.amazon.com/Designing-Web-Standards-Jeffrey-Zeldman/dp/0321616952) by Jeffrey Zeldman (Third Edition)
- [The Art and Science of Web Design](https://www.amazon.com/Art-Science-Web-Design/dp/0789723700) by Jeffrey Veen *(Oldie, but goodie.)*


## Resources

- [HTML5 For Web Designers](https://html5forwebdesigners.com) by [Jeremy Keith](https://adactio.com)
- [Learn to Code HTML & CSS](https://learn.shayhowe.com/html-css/) by [Shaw Howe](https://shayhowe.com)
- [Dive Into HTML5](http://diveinto.html5doctor.com) by Mark Pilgrim
- [Modern Web Design](https://thegymnasium.com/courses/GYM/107/0/about) by [Aaron Gustafson](https://www.aaron-gustafson.com) for [Aquent Gymnasium](https://thegymnasium.com)
