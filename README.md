
<h1 align="center">
  <br>
  <a href="https://colorlib.com/wp/template/colid/"><img src="https://i.imgur.com/09sup5P.png" alt="Colid Template" width=100% height=auto></a>
  <br>
  AcademiesHacks Hackathon Website
  <br>
</h1>

<h4 align="center">A minimal, single page hackathon website built on top of <a href="https://colorlib.com/wp/template/colid/" target="_blank">Colid</a>.</h4>


<p align="center">
  <a href="#design-goals">Design Goals</a> •
  <a href="#process-overview">Process Overview</a> •
  <a href="#download">Download</a> •
  <a href="#credits">Credits</a> •
  <a href="#related">Related</a> •
  <a href="#license">License</a>
</p>

## Design Goals

* Simple, easy to navigate, information - based
  - Only necessary resources (images, etc) included
  - Minimal amount of text
  - Large, eye - catching buttons with clear purposes
* Smooth User Experience
  - CSS minimized
  - Resource size minimized
  - Javascript placed at bottom


## Process Overview


* Day 1:
  - Finding template
  - Identified multiple potential templates to uses
  - Narrowed choices down to three
  - Chose Colid-Colorlib because of simplicity (single page) and similarity to HackTJ Template
* Day 2:
  - Created Wireframe
  - Altered template to fit basic structure of wireframe
<br>
   ![Image](images/wireframe.PNG)
* Day 3:
  - Added FAQs
  - Removed overlay from template and added aclrendering [cover image for landing page]
  - Deleted unused sections and gifs that greatly increased landing time
* Challenges
  - Loading time, especially for resources such as images and gifs
    - Used unusedcss.com to remove boilerplate css that was part of template, but was not used in final website
    - This introduced some challenges in itself because the unusedcss removed important code, such as the navbar
    - Overall useful; some small issues
* Slow Scrolling speed
  - Somewhat helped by removing resources and optimizing CSS





## Prerequisites

Install Bootstrap using Node Package Manager

<p>Install Bootstrap in your Node powered apps with <a href="https://www.npmjs.org/package/bootstrap">the npm package</a>:</p>

<figure class="highlight"><pre><code class="language-bash" data-lang="bash">npm install bootstrap@4.0.0-alpha.6</code></pre></figure>

<p><code class="highlighter-rouge">require('bootstrap')</code> will load all of Bootstrap’s jQuery plugins onto the jQuery object. The <code class="highlighter-rouge">bootstrap</code> module itself does not export anything. You can manually load Bootstrap’s jQuery plugins individually by loading the <code class="highlighter-rouge">/js/*.js</code> files under the package’s top-level directory.</p>

<p>Bootstrap’s <code class="highlighter-rouge">package.json</code> contains some additional metadata under the following keys:</p>

<ul>
  <li><code class="highlighter-rouge">sass</code> - path to Bootstrap’s main <a href="http://sass-lang.com/">Sass</a> source file</li>
  <li><code class="highlighter-rouge">style</code> - path to Bootstrap’s non-minified CSS that’s been precompiled using the default settings (no customization)</li>
</ul>

*from bootstrapcdn.com



## Credits

This software uses the following open source packages and softwares:

- [Colid Template](https://colorlib.com/wp/template/colid)
- [Bootstrap](https://getbootstrap.com/)




## License

MIT
