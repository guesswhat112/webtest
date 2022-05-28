# CSS 3D Cake 🍰

A Pen created on CodePen.io. Original URL: [https://codepen.io/ShadowShahriar/pen/ZEJerdX](https://codepen.io/ShadowShahriar/pen/ZEJerdX).

<p>Surprise!</p>
<p>
  Happiest birthday, didi. Wishing you a beautiful year ahead and all the
  happiness you deserve.
</p>

<p>
  <b>Overview</b><br />
  This pen consists of a textured three-dimensional cake model made with pure
  CSS. Everything we see here is made out of two
  <code>&lt;sections&gt;</code>, a handful of <code>&lt;DIV&gt;</code>s and
  pseudo-elements. Interactions, especially camera movements, may use
  Javascript.
</p>
<br />

<details>
  <summary><b>Camera and Gestures</b></summary>
  <p>
    Unlike my former CSS 3D projects, this one has no control UI. It offers
    to view the model through dragging, panning, and more. Here are the
    basic gestures that it supports:
  </p>
  <ul>
    <li><i>Drag:</i> Rotate</li>
    <li><kbd>ctrl</kbd>&nbsp;+&nbsp;<i>Drag:</i> Pan (XY)</li>
    <li><kbd>alt</kbd>&nbsp;+&nbsp;<i>Drag:</i> Pan (Z)</li>
    <li><kbd>shift</kbd>&nbsp;+&nbsp;<i>Drag:</i> Perspective</li>
    <li><i>Wheel:</i> Zoom</li>
    <li><kbd>ctrl</kbd>&nbsp;+&nbsp;<i>Wheel:</i> Fast Zoom</li>
    <li><i>Double click:</i> Toggle auto-rotate (Z)</li>
  </ul>
  <p>These gestures are supported* on mobile devices (I am unable to test at the moment):</p>
  <ul>
    <li><i>Drag:</i> Rotate</li>
    <li><i>Pinch:</i> Zoom</li>
    <li><i>Double tap:</i> Toggle auto-rotate (Z)</li>
  </ul>
</details>

<details>
  <summary><b>Motivation</b></summary>
  <p>
    Everyone loves surprises. I just wanted to put a smile on someone's
    face. :)
  </p>
</details>

<details>
  <summary><b>Reference</b></summary>
  <p>
    The design was mainly influenced by
    <a href="https://www.artstation.com/artwork/69knr">this artwork</a> from
    <a href="https://www.artstation.com/">ArtStation</a> (shout out to
    <a href="https://www.artstation.com/elysiaart">Elysia</a>!). No, my end
    goal wasn't to recreate it. I used it as a
    <a
      href="https://forum.wordreference.com/threads/high-level.814580/#post-4395337"
      >high-level overview</a
    >
    to get things in shape in my own way. (Yes, CSS rocks!)
  </p>
</details>

<details>
  <summary><b>Time and Preparation</b></summary>
  <p>
    This was a fun project to work on. It took me a week to bake (lol), two
    days to finalize the textures, and another day to polish the overall
    code. I could have improved it if I were able to spend some more time.
  </p>
</details>

<details>
  <summary><b>Performance and Compatibility</b></summary>
  <p>
    Chrome has developed a lot in terms of rendering of 3D
    <code>transform</code> since its <u>v94</u> release. Best performance
    and appearance were observed on <b>Chrome ^94 (x64/Windows)</b> and
    <b>Firefox 79 (x64/Windows)</b> with 4 Gigabytes of RAM. Have tested it
    on stable releases of Firefox, Chrome, and Chrome-based browsers.
  </p>
  <p>
    If you are using <b>Firefox >=83</b>, you might notice flashes during
    the presentation. This is because Firefox seems to render 3D
    <code>transform</code> in a different way than it used to be. I am
    positive this is not a bug with the <code>clip-path</code>.
  </p>
  <p>
    <a href="https://caniuse.com/css-conic-gradients"
      >Conic gradients are fully supported since <b>Firefox v83</b></a
    >
    and can be enabled with the
    <code>layout.css.conic-gradient.enabled</code> flag in older versions.
  </p>
  <blockquote>
    Keep in mind that visible content rendered is <code>&lt;DIV&gt;</code>s.
    There are precisely <b>65 <code>&lt;DIV&gt;</code>s</b> and
    <b>108 pseudo-elements</b>, which is a decent amount to blow up the CPU
    cooler.
  </blockquote>
</details>

<details>
  <summary><b>Assets</b></summary>
  <p>
    All textures are hosted on my GitHub pages which you can
    <a href="https://github.com/ShadowShahriar/assets/tree/main/codepen/css3d-cake"
      >find here</a
    >. All modifications have been made under their license, and
    attributions were given where necessary.
  </p>
</details>

<details>
  <summary><b>Memorable Things to note</b></summary>
  <br />
  <ul>
    <li>This is my first CSS 3D pen of 2021.</li>
    <li>
      This is also the most geometrical pen I have written in a while. See
      this
      <a href="https://calcresource.com/geom-ngon.html#anchor-13"
        >Regular n-gon theory</a
      >.
    </li>
    <li>Yesterday (25th October) was my birthday 😄</li>
  </ul>
</details>

<br />
<p>
  Made with Cream, Sugar, Strawberries, and lots of Love by S. Shahriar. Heart
  (🤍) this pen to show your Love!
</p>

<p><code>20211026-uPnc85bth</code></p>
