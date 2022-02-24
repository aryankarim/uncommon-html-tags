# Uncommon HTML Tags

`<abbr>` Defines an abbreviation or an acronym

```html
<abbr title="World Health Organization">WHO</abbr>
```

`<address>` Defines contact information for the author/owner of a document

```html
<address>
  Written by <a href="mailto:webmaster@example.com">Jon Doe</a>.<br />
  Visit us at:<br />
  Example.com<br />
  Box 564, Disneyland<br />
  USA
</address>
```

`<area>` Defines an area inside an image map
`<map>` Defines an image map

```html
<map name="workmap">
  <area
    shape="rect"
    coords="34,44,270,350"
    alt="Computer"
    href="computer.htm"
  />
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm" />
  <area
    shape="circle"
    coords="337,300,44"
    alt="Cup of coffee"
    href="coffee.htm"
  />
</map>
```

`<article>` Defines an article

```html
<article>
  <h2>Microsoft Edge</h2>
  <p>
    Microsoft Edge is a web browser developed by Microsoft, released in 2015.
    Microsoft Edge replaced Internet Explorer.
  </p>
</article>
```

`<aside>` Defines content aside from the page content

```html
<aside>
  <h4>Epcot Center</h4>
  <p>
    Epcot is a theme park at Walt Disney World Resort featuring exciting
    attractions, international pavilions, award-winning fireworks and seasonal
    special events.
  </p>
</aside>
```

`<audio>` Defines embedded sound content
`<source>` Defines multiple media resources for media elements `<video>` and `<audio>`

```html
<audio controls>
  <source src="horse.ogg" type="audio/ogg" />
  <source src="horse.mp3" type="audio/mpeg" />
  Your browser does not support the audio tag.
</audio>
```

`<base>` Specifies the base URL/target for all relative URLs in a document

```html
<!DOCTYPE html>
<html>
  <head>
    <base href="https://www.w3schools.com/" target="_blank" />
  </head>
  <body>
    <h1>The base element</h1>

    <p>
      <img src="images/stickman.gif" width="24" height="39" alt="Stickman" /> -
      Notice that we have only specified a relative address for the image. Since
      we have specified a base URL in the head section, the browser will look
      for the image at "https://www.w3schools.com/images/stickman.gif".
    </p>

    <p>
      <a href="tags/tag_base.asp">HTML base tag</a> - Notice that the link opens
      in a new window, even if it has no target="_blank" attribute. This is
      because the target attribute of the base element is set to "_blank".
    </p>
  </body>
</html>
```

`<bdi>` Isolates a part of text that might be formatted in a different direction from other text outside it.keeps the direction as is.

```html
<bdo dir="rtl"> This text will go right-to-left. </bdo>
```

`<bdo>` Overrides the current text direction

```html
<p><bdo>This paragraph will go right-to-left.</bdo></p>
```

`<blockquote>` Defines a section that is quoted from another source

```html
<blockquote cite="http://www.worldwildlife.org/who/index.html">
  For 50 years, WWF has been protecting the future of nature. The world's
  leading conservation organization, WWF works in 100 countries and is supported
  by 1.2 million members in the United States and close to 5 million globally.
</blockquote>
```

`<caption>` Defines a table caption

```html
<table>
  <caption>
    Monthly savings
  </caption>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
</table>
```

`<cite>` Defines the title of a work

```html
<p><cite>The Scream</cite> by Edward Munch. Painted in 1893.</p>
```

`<code>` Defines a piece of computer code
`<pre>` Defines preformatted text

```html
<p>
  The CSS <code>background-color</code> property defines the background color of
  an element.
</p>
```

`<col>` Specifies column properties for each column within a `<colgroup>` element
`<colgroup>` Specifies a group of one or more columns in a table for formatting

```html
<table>
  <colgroup>
    <col span="2" style="background-color:red" />
    <col style="background-color:yellow" />
  </colgroup>
  <tr>
    <th>ISBN</th>
    <th>Title</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>3476896</td>
    <td>My first HTML</td>
    <td>$53</td>
  </tr>
  <tr>
    <td>5869207</td>
    <td>My first CSS</td>
    <td>$49</td>
  </tr>
</table>
```

`<data>` Adds a machine-readable translation of a given content

```html
<ul>
  <li><data value="21053">Cherry Tomato</data></li>
  <li><data value="21054">Beef Tomato</data></li>
  <li><data value="21055">Snack Tomato</data></li>
</ul>
```

`<datalist>` Specifies a list of pre-defined options for input controls

```html
<input list="browsers" name="browser" id="browser" />
<datalist id="browsers">
  <option value="Edge"></option>
  <option value="Firefox"></option>
  <option value="Chrome"></option>
  <option value="Opera"></option>
  <option value="Safari"></option>
</datalist>
```

`<dd>` Defines a description/value of a term in a description list
`<dl>` Defines a description list
`<dt>` Defines a term/name in a description list

```html
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>
```

`<del>` Defines text that has been deleted from a document
`<ins>` Defines a text that has been inserted into a document

```html
<p>My favorite color is <del>blue</del> <ins>red</ins>!</p>
```

`<details>` Defines additional details that the user can view or hide
`<summary>` Defines a visible heading for a `<details>` element

```html
<details>
  <summary>Epcot Center</summary>
  <p>
    Epcot is a theme park at Walt Disney World Resort featuring exciting
    attractions, international pavilions, award-winning fireworks and seasonal
    special events.
  </p>
</details>
```

`<dfn>` Specifies a term that is going to be defined within the content

```html
<p>
  <dfn title="HyperText Markup Language">HTML</dfn> is the standard markup
  language for creating web pages.
</p>
```

`<dialog>` Defines a dialog box or window

```html
<h1>The dialog element</h1>

<p>This is some text.</p>
<dialog close>This is an open dialog window</dialog>
<p>This is some text.</p>
```

`<em>` Defines emphasized text

```html
<p>We <em>cannot</em> live like this.</p>
```

`<embed>` Defines a container for an external application

```html
<embed type="text/html" src="snippet.html" width="500" height="200" />
```

`<fieldset>` Groups related elements in a form
`<legend>` Defines a caption for a `<fieldset>` element

```html
<fieldset>
  <legend>Personalia:</legend>
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname" /><br /><br />
</fieldset>
```

`<figcaption>` Defines a caption for a `<figure>` element
`<figure>` Specifies self-contained content

```html
<figure>
  <img src="pic_trulli.jpg" alt="Trulli" style="width:100%" />
  <figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>
</figure>
```

`<iframe>` Defines an inline frame

```html
<iframe
  src="https://www.w3schools.com"
  title="W3Schools Free Online Web Tutorials"
>
</iframe>
```

`<kbd>` Defines keyboard input

```html
<p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy text (Windows).</p>
```

`<link>` Defines the relationship between a document and an external resource (most used to link to style sheets)

```html
<head>
  <link rel="stylesheet" href="styles.css" />
</head>
```

`<mark>` Defines marked/highlighted text

```html
<p>Do not forget to buy <mark>milk</mark> today.</p>
```

`<meter>` Defines a scalar measurement within a known range (a gauge)

```html
<label for="disk_c">Disk usage C:</label>
<meter id="disk_c" value="2" min="0" max="10">2 out of 10</meter><br />

<label for="disk_d">Disk usage D:</label>
<meter id="disk_d" value="0.6">60%</meter>
```

`<noscript>` Defines an alternate content for users that do not support client-side scripts

```html
<noscript>Your browser does not support JavaScript!</noscript>
```

`<object>` Defines a container for an external application

```html
<object data="snippet.html" width="500" height="200"></object>
<object data="video.mp4" width="400" height="300"></object>
```

`<optgroup>` Defines a group of related options in a drop-down list

```html
<select name="cars" id="cars">
  <optgroup label="Swedish Cars">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
  </optgroup>
  <optgroup label="German Cars">
    <option value="mercedes">Mercedes</option>
    <option value="audi">Audi</option>
  </optgroup>
</select>
```

`<output>` Defines the result of a calculation

```html
<form oninput="x.value=parseInt(a.value)+parseInt(b.value)">
  <input type="range" id="a" value="50" /><!-- hihi -->
  +<input type="number" id="b" value="25" /> =<output
    name="x"
    for="a b"
  ></output>
</form>
```

`<param>` Defines a parameter for an object

```html
<object data="horse.wav">
  <param name="autoplay" value="true" />
</object>
```

`<picture>` Defines a container for multiple image resources
`<source>` Defines multiple media resources for media elements `<video>` and `<audio>`

```html
<picture>
  <source media="(min-width:650px)" srcset="img_pink_flowers.jpg" />
  <source media="(min-width:465px)" srcset="img_white_flower.jpg" />
  <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;" />
</picture>
```

`<progress>` Represents the progress of a task

```html
<label for="file">Downloading progress:</label>
<progress id="file" value="32" max="100">32%</progress>
```

`<q>` Defines a short quotation, puts quotation automatically

```html
<p>
  WWF's goal is to:
  <q>Build a future where people live in harmony with nature.</q>
  We hope they succeed.
</p>
```

`<ruby>` Defines a ruby annotation (for East Asian typography)
`<rt>` Defines an explanation/pronunciation of characters (for East Asian typography)
`<rp>` Defines what to show in browsers that do not support ruby annotations

```html
<ruby> 漢 <rp>(</rp><rt>ㄏㄢˋ</rt><rp>)</rp> </ruby>
```

`<s>` Defines text that is no longer correct

```html
<p><s>Only 50 tickets left!</s></p>
<p>SOLD OUT!</p>
```

`<samp>` Defines sample output from a computer program, gives it mono/terminal font

```html
<p>Message from my computer:</p>
<p>
  <samp>File not found.<br />Press F1 to continue</samp>
</p>
```

`<section>` Defines a section in a document

```html
<section>
  <h2>WWF History</h2>
  <p>
    The World Wide Fund for Nature (WWF) is an international organization
    working on issues regarding the conservation, research and restoration of
    the environment, formerly named the World Wildlife Fund. WWF was founded in
    1961.
  </p>
</section>

<section>
  <h2>WWF's Symbol</h2>
  <p>
    The Panda has become the symbol of WWF. The well-known panda logo of WWF
    originated from a panda named Chi Chi that was transferred from the Beijing
    Zoo to the London Zoo in the same year of the establishment of WWF.
  </p>
</section>
```

`<small>` Defines smaller text

```html
<p>This is some normal text.</p>
<p><small>This is some smaller text.</small></p>
```

`<strong>` and `b` Defines important text. Makes it bold

```html
<strong>This text is important!</strong> <b>This text is important!</b>
```

`<sub>` Defines subscripted text
`<sup>` Defines superscripted text

```html
<p>This text contains <sub>a</sub> text.</p>
<p>This text contains <sup>a</sup> text.</p>
```

`<template>` Defines a container for content that should be hidden when the page loads

```html
<button onclick="showContent()">Show hidden content</button>

<template>
  <h2>Flower</h2>
  <img src="img_white_flower.jpg" width="214" height="204" />
</template>

<script>
  function showContent() {
    var temp = document.getElementsByTagName("template")[0];
    var clon = temp.content.cloneNode(true);
    document.body.appendChild(clon);
  }
</script>
```

`<time>` Defines a specific time (or datetime)

```html
<p>Open from <time>10:00</time> to <time>21:00</time> every weekday.</p>

<p>I have a date on <time datetime="2008-02-14 20:00">Valentines day</time>.</p>
```

`<track>` Defines text tracks for media elements `<video>` and `<audio>`

```html
<video width="320" height="240" controls>
  <source src="forrest_gump.mp4" type="video/mp4" />
  <source src="forrest_gump.ogg" type="video/ogg" />
  <track
    src="fgsubtitles_en.vtt"
    kind="subtitles"
    srclang="en"
    label="English"
  />
  <track
    src="fgsubtitles_no.vtt"
    kind="subtitles"
    srclang="no"
    label="Norwegian"
  />
</video>
```

`<u>`Defines some text that is unarticulated and styled differently from normal text

```html
<p>This is some <u>mispeled</u> text.</p>
```

`<var>` Defines a variable and gives it a different style

```html
<p>
  The area of a triangle is: 1/2 x <var>b</var> x <var>h</var>, where
  <var>b</var> is the base, and <var>h</var> is the vertical height.
</p>
```

`<video>` Defines embedded video content

```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4" />
  <source src="movie.ogg" type="video/ogg" />
  Your browser does not support the video tag.
</video>
```

`<wbr>` Defines a possible line-break. Conditional break when resizing window

```html
<p>
  To learn AJAX, you must be familiar with the XML<wbr />Httpppppppppppppppppppppppppppppppppppppppppppppppppppppppppppppppppppp<wbr />Request
  Object.
</p>
```
