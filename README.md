<h1>GOIT Markup Homework #06 — Responsive Design</h1>

<p>
  This homework focuses on implementing a <strong>responsive, mobile-first layout</strong> with multiple breakpoints
  and a fully functional <strong>mobile menu</strong>. The design is optimized for different devices and screen densities.
  All styles are written in <code>css/styles.css</code>, with <strong>modern-normalize</strong> enabled and
  <strong>Prettier</strong> used for formatting.
</p>

<p><strong>Live Demo:</strong> <a href="#" target="_blank" rel="noopener">https://kutluhangil.github.io/goit-markup-hw-06/</a></p>

<hr>

<h2>📚 Table of Contents</h2>
<ol>
  <li><a href="#about">About the Project</a></li>
  <li><a href="#acceptance">Acceptance Criteria (Mentor Checklist)</a></li>
  <li><a href="#responsiveness">Responsiveness Requirements</a></li>
  <li><a href="#mobile-menu">Mobile Menu Requirements</a></li>
  <li><a href="#design">Design Approach</a></li>
  <li><a href="#structure">Project Structure</a></li>
  <li><a href="#validation">Validation & Formatting</a></li>
  <li><a href="#setup">How to Run</a></li>
</ol>

<hr>

<h2 id="about">📖 About the Project</h2>
<ul>
  <li>Layout adapts to three breakpoints: <strong>320px, 768px, 1158px</strong>.</li>
  <li>Responsive images support <strong>x1 and x2 pixel densities</strong>.</li>
  <li>Background images adapt via <code>min-resolution</code> media queries.</li>
  <li>Mobile-first CSS approach with <code>min-width</code> queries.</li>
  <li>Fully styled <strong>mobile navigation menu</strong> with toggle class <code>.is-open</code>.</li>
</ul>

<hr>

<h2 id="acceptance">✅ Acceptance Criteria (Mentor Checklist)</h2>

<h3>A. Project</h3>
<ul>
  <li><strong>A1</strong> — On any device ≥320px wide, no horizontal scrollbars appear.</li>
  <li><strong>A2</strong> — Code formatted with <strong>Prettier</strong>.</li>
  <li><strong>A3</strong> — All images and text taken from the mockup.</li>
  <li><strong>A4</strong> — <strong>modern-normalize</strong> is enabled.</li>
  <li><strong>A5</strong> — Code follows guidelines.</li>
</ul>

<hr>

<h2 id="responsiveness">📱 Responsiveness Requirements</h2>
<ul>
  <li><strong>B1</strong> — Each page includes the <code>&lt;meta name="viewport"&gt;</code> tag.</li>
  <li><strong>B2</strong> — Layout adapts to three breakpoints: 320px, 768px, 1158px.</li>
  <li><strong>B3</strong> — Backgrounds and content bitmaps are responsive and support x1 and x2 densities.</li>
  <li><strong>B4</strong> — Background images are set with <code>min-resolution</code> media queries.</li>
  <li><strong>B5</strong> — Styles follow the <strong>mobile-first</strong> approach with <code>min-width</code> queries.</li>
  <li><strong>B6</strong> — Styles needed only within a range are wrapped in <code>(min-width) and (max-width)</code> queries.</li>
  <li><strong>B7</strong> — Media queries avoid redundant style duplication.</li>
</ul>

<hr>

<h2 id="mobile-menu">📋 Mobile Menu Requirements</h2>
<ul>
  <li><strong>C1</strong> — All mobile menu elements are implemented.</li>
  <li><strong>C2</strong> — Mobile menu elements are styled.</li>
  <li><strong>C3</strong> — Menu width matches the design.</li>
  <li><strong>C4</strong> — Menu covers the full viewport height.</li>
  <li><strong>C5</strong> — Menu is hidden by default.</li>
  <li><strong>C6</strong> — Adding <code>.is-open</code> makes the menu visible.</li>
</ul>

<hr>

<h2 id="design">🎨 Design Approach</h2>
<ul>
  <li><strong>Mobile First</strong> — Base styles are defined for mobile, enhanced progressively for tablet and desktop.</li>
  <li><strong>Responsive Images</strong> — Bitmap assets exported in both x1 and x2 resolutions.</li>
  <li><strong>Accessible Menu</strong> — Mobile menu toggled with a class, spans full screen height.</li>
  <li><strong>Consistent Media Queries</strong> — No repeated or conflicting styles.</li>
</ul>

<hr>

<h2 id="structure">📁 Project Structure</h2>
<pre><code>.
├─ index.html
├─ css/
│  └─ styles.css
├─ images/
│  ├─ ... responsive images (x1, x2)
│  └─ ...
└─ README.md
</code></pre>

<hr>

<h2 id="validation">🧪 Validation & Formatting</h2>
<ul>
  <li>HTML passes <a href="https://validator.w3.org/" target="_blank">W3C Validator</a> without errors.</li>
  <li>CSS passes <a href="https://jigsaw.w3.org/css-validator/" target="_blank">W3C CSS Validator</a>.</li>
  <li>Code formatted with <strong>Prettier</strong>.</li>
  <li>Tested on multiple devices to ensure no horizontal scrollbars.</li>
</ul>

<hr>

<h2 id="setup">🚀 How to Run</h2>
<ol>
  <li>Clone the repo and open <code>index.html</code> in a browser.</li>
  <li>Check the responsive layout at <strong>320px, 768px, 1158px</strong> widths.</li>
  <li>Verify x2 images load on high-density displays.</li>
  <li>Test mobile menu: add/remove <code>.is-open</code> to the menu container.</li>
  <li>Publish via GitHub Pages and add the link in the repo’s About section.</li>
</ol>
