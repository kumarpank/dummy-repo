Q.1 What are some of the advantages of HTML5 over its previous versions?

-It has multimedia support -javascript can run in the background. -HTML5
also allows users to draw various shaped like rectangles ,
circles,triangles tec. -included new semantic tags and form controls
tag.

Q.2 How we can include audio and video in a webpage?

Html 5 provides two tags \<audio\> and \<video\> tags using which we can
add the audio or video in our webpage.

Q.3 Inline and block elements in HTML5

-Inline elements just take up the space that is absoulte necessary for
the content and does not start form a new line. Ex- \<span\> \<a\>,
\<strong\>, \<img\>,\<button\>, \<em\>, \<select\>,\<label\>,\<script\>,
\<input\>

-Block elemts starts on a new line and consume the full width of the
page avaliable.

Ex-\<div\>, \<p\>, \<header\>, \<footer\>, \<h1\>\...\<h6\>, \<form\>,
\<table\>, \<canvas\>, \<video\>, \<blockquote\>, \<pre\>, \<ul\>,
\<ol\>, \<figcaption\>, \<figure\>, \<hr\>, \<article\>, \<section\>

Q.4 What is the difference between \<figure\> tag and \<img\> tag?

-The \<figure\> tag specifies the self-contained content, like diagrams,
images, code snippets \<figure\> tag i used to semantically organise the
contents of an image like image and image caption. whereas the \<img\>
tag is used to embed the picture in the HTML5 document.

Q.5 How to specify the metadata in HTML5?

-to specify we can use \<meta\> tag which is a void tag it does not have
a closing tag some of the attrivutes used with meta tage are name,
content.

```<meta name=\"keywords\" content=\"HTML, Meta, Metadata\"/\>```

Q.6 Is the \<datalist\> tag and \<select\> tag same?

-In the case of \<select\> tag a user will have to choose from a list of
options. -whereas \<datalist\> when used along with the \<input\> tag
provide a suggestion that the user selects one of the options given or
can enter some entirely different value.

Q.7 Define Image Map?

-Image Map lets a developer map/link differnent parts of images with the
different web pages it an be acheived by the \<map\> tag in HTML5, using
which we can link images with clickable areas.

```
  <img src="image_url" , usemap="#workspace" /\> \<map name="workspace"\>
      <area shape="rect" coords="34, 44, 270, 350" , href="xyz.html" /\>
      <area shape="rect" coords="10, 120, 250, 360" , href="xyz.html" /\>
    </map\>
```

Q.8 What are semantic elemets?

-semantic elements are those which describe the perticuler meaning to
the browser and the developer, elements like \<form\>,\<table\>,
\<article\>,\<figure\>, etc, are semantic elements.

Q.9 What is the difference between \<meter\> tag and \<progress\> tag?
-\<progress\> tag should be used when we want to show the completion
progress of a task, whereas if we just want a scalar measurement within
a known range of fraction value. also, we can specify mulitple ectra
attributes for \<meter\> tags like \'form\',\'low\', \'high\',\'min\'
etc.

Q.10 Difference between SVG and Canvas in HTML5.

-svg -svg is a vector based i.e., composed of shapes. -svg works better
with a larger surface. -svg can be modified using css and scripts. -svg
is highly scalable,So we can print ar high wuality with high resolution
-canvas -It is Raster based composed of pixels. -canva works better with
a smallwe surface. -canvas can only be modified using scripts. -it is
less scalable.

Q.11 What type of audio files can be played using HTML5.

-Mp3 -Wav -Ogg

Q.12 what are the significant goals of the HTML5 specification?

-Introduction of new elements tags to better structure the web page such
as header -Forming a standard in cross-browser behavior and support for
diff devices and plateforms. -Backword compatible with the older
version. -Introduced Audio and Video tags.

Q.13 Explain the comcept of web storage. -this web page helps in storing
some of the static data in the browser, so we dont need to fetch it form
the server every time we need it. -the web storage API provides
mechanisms by which browsers can store data in key value pairs.

sessionStorage:-

-maintains a separate storage area for each given origin that\'s
available for the duration of the page session (as long as the browser
is open, including page reloads and restores). Stores data only for a
session, meaning that the data is stored until the browser (or tab) is
closed.

-Data is never transferred to the server.

-Storage limit is larger than a cookie (at most 5MB).

localStorage:- -does the same thing, but persists even when the browser
is closed and reopened. -Stores data with no expiration date, and gets
cleared only through JavaScript, or clearing the Browser cache / Locally
Stored Data. -Storage limit is the maximum amongst the two.

Q.14 What is microdata in html5.

It is used to help extract data for site crawlers and search engins, it
is basically, a group of name-value pairs. the group are called items,
and each name-value pair is a property. most of the search engins like
google, microsoft follow schema.org vocab to extract this microdata.

Q.15 Which tag is used for representing the result of a calculation?

-output tag is used for representing the result of a calculation and
result.

Q.15 Explain HTML5 Graphics.

-HTML 5 supports two kinds of graphics:

-canvas: it is like drawing on a whitepaper or a blank webpage. We ca
add different graphics designs on web pages with avaliable methods for
drawing various geometric shapes.

  ```
  <canvas width=\"300\" height=\"100\" style=\"border:2px
  solid;\"\>\</canvas\>
```

-SVG: svalable vector graphics are used mostly for diagrams or icons. it
follows the xml format.

Q.16 Explain new input types provided by HTML5 for forms?

-Date, Mohths, Week, Time, Datetime, Datetime-local, color,email,
Number, earch,tel,placeholder, range, url.

Q.17: what are the New tags in Media elements in HTML5.

-\<audio\>-used for sound, audio, stream, or music, embed audio content
without and additional plug-in. -\<video\>-used for multiple media
resources in media elements, such as audio, video. -\<embed\>-used for
an external application or embedded content. -\<track\>-used for
subtitles in the media elements such as video or audio.

Q.18 What are drag and drop in html.

\- The drag and drop functionality is a varu intutive way to select
local files. this is similer to what most of the OS have copy
functionality this making it vary easy for the user to comprehend.
Before the native drag and drop API, this was acheivable by writing
complex javascript programming.

Q.19: Why do we need the MathML elements in HTML5.

-MathML stands for Mathematical markup language. it is used for
displaying mathematical expression on web pages for this \<math\> tag is
used.

Q.20: what are the server-sent events in HTML5?

Q.21: what is usage of a novalidate attribute for the form tag that is
introduced in HTML5.

\- Its value is a boolean type that indicates wether or not the data
being submitted by the for will be validateed beforehand. By making this
false, forms can be submitted without validation which helps users to
resume later also.

Q.22 What are raster images and vector images?

-Raster Images: The raster image is defined by the arrangement of pixels
in a grid with exactly what color the pixel should be. few raster file
formats include PNG JPEG.

-Vector Images: The vector image is definded using algorithm with shape
and path definations that can be used to render the image on-screen
written in a similer markup fashion. the file extansion is .svg.

Q.23 How to support svg in old browsers?

-to support old browsers insted of defining the resource o svg in src
attribute of \<img\> tag it should be defined in srcset attribure and in
src the fallback png should be defined.

```
  <img src=\"circle.png\" alt=\"circle\" srcset=\"circle.svg\"\>
```
Q.24 What are different approaches to make an image responsive?

Q.25 What is manifest file in HTML5?

-CACHE Manifest - files needs to be cached -Network- file never to be
cached, always need a network connection. -fallback - fallback files in
case a page is inaccessible.

Q.26: what is geolocation API in HTML5?

-Geolocation API is used to share the physical location of the client
with websites. This helps in serving locale-based content and a unique
experience to the user, based on their location. this works with a new
property of the global navigator object and most of the mordern browser
support this.

var geolocation = navigator.geolocation;

Q.27: Explain web components ans it\'s usage.
