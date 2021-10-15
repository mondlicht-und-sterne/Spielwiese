# Spielwiese

[![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/Crazy-Marvin/ToDont/CI/development)](https://github.com/Crazy-Marvin/ToDont/actions)
[![License](https://img.shields.io/github/license/Crazy-Marvin/ToDont.svg)](https://github.com/Crazy-Marvin/ToDont/blob/development/LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/Crazy-Marvin/ToDont.svg?style=flat)](https://github.com/Crazy-Marvin/ToDont/commits)
[![Releases](https://img.shields.io/github/downloads/Crazy-Marvin/ToDont/total.svg?style=flat)](https://github.com/Crazy-Marvin/ToDont/releases)
[![Latest tag](https://img.shields.io/github/tag/Crazy-Marvin/ToDont.svg?style=flat)](https://github.com/Crazy-Marvin/ToDont/tags)
[![Issues](https://img.shields.io/github/issues/Crazy-Marvin/ToDont.svg?style=flat)](https://github.com/Crazy-Marvin/ToDont/issues)
[![Pull requests](https://img.shields.io/github/issues-pr/Crazy-Marvin/ToDont.svg?style=flat)](https://github.com/Crazy-Marvin/ToDont/pulls)
[![codecov](https://codecov.io/gh/Crazy-Marvin/ToDont/branch/master/graph/badge.svg)](https://codecov.io/gh/Crazy-Marvin/ToDont)
[![Hosted Weblate](https://hosted.weblate.org/widgets/todont/-/svg-badge.svg)](https://hosted.weblate.org/engage/todont/)
[![F-Droid](https://img.shields.io/f-droid/v/rocks.poopjournal.todont.svg)](https://f-droid.org/en/packages/rocks.poopjournal.todont/)

# To Don't



<a href="https://f-droid.org/packages/rocks.poopjournal.todont/">
    <img alt="Get it on F-Droid"
        height="80"
        src="https://user-images.githubusercontent.com/15004217/36919296-19b8524e-1e5d-11e8-8962-48463b1cec8a.png" />
        </a>



# markitUp! - Markdown

Hier findest Du die snippets für die Auszeichnungssprache markdown - jeweils mit Ausgabe (= Vorschau) und dem einzugebendem Code:

- [Überschriften](#Überschriften)
- [Texte formatieren](#texte)
	- [Font-Formate](#formate)
	- [Hoch-/Tief-Stellen von Texten](#sub)
- [Links](#links)
- [Anker](#anker)
	- [Anker definieren](#anker-definieren)
	- [Text auf Anker verlinken](#anker-link)
	- [Inhaltsverzeichnis erstellen](#inhalt)
- [Listen](#listen)
- [Tabellen](#tabellen)
- [Code](#code)
- [Zitieren](#zitieren) (in REX auch Hinweise)
- [Bilder](#images)

## Überschriften

<!DOCTYPE html>
<!--
================================================================================
 _  __     _     _ _    ____  _          _
| |/ _   _| |__ (_| | _|  _ \(___  _____| |
| ' | | | | '_ \| | |/ | |_) | \ \/ / _ | |
| . | |_| | |_) | |   <|  __/| |>  |  __| |
|_|\_\__,_|_.__/|_|_|\_|_|   |_/_/\_\___|_|

================================================================================
[Verifying my OpenPGP key: openpgp4fpr:e8923e0f9c7c84a663a37f850be1a9ae16f417a2]
================================================================================
You can hire me for a job in Switzerland or remote, you can see my contact on
this website.

My skills are:
- PHP, JavaScript, CSS, HTML
- WebGL, Blender, AutoCAD, FreeCAD, BIMserver
- Python, Lisp, Shell, Rust
- MySQL, PostgreSQL
- VB Script (yes I know...)
- Linux (Ubuntu, Debian, Manjaro) admin
================================================================================
-->
<html lang="en">
  <head>
		<title>KubikPixel - Profile and Contact</title>
		<meta charset="UTF-8">
    <meta name="author" content="KubikPixel">
    <meta name="keywords" content="portfolio, kubikpixel, contact, blog, mastodon, email, jabber, matrix, pgp, pgp key, social media">
    <meta name="description" content="Portfolio and contact site from KubikPixel. You find here my Blog, PGP keys and verified social media accounts.">
		<meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, user-scalable=no">
    <meta name="HandheldFriendly" content="true">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="google-site-verification" content="K_vnwLzHKnys18riiUXabt_md6pDe01rlEKK5WacBd0">
    <link rel="canonical" href="https://thunix.net/~kubikpixel/">
    <link rel=”alternate” hreflang=”en-GB” href=”https://thunix.net/~kubikpixel/index.php”>
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <link rel="me" href="https://github.com/KubikPixel">
    <!-- Open Graph -->
    <meta property="og:title" content="KubikPixel - Profile and Contact">
    <meta property="og:site_name" content="KubikPixel">
    <meta property="og:url" content="https://thunix.net/~kubikpixel/">
    <meta property="og:locale" content="de_DE">
    <meta property="og:locale:alternate" content="de_AT">
    <meta property="og:locale:alternate" content="de_CH">
    <meta property="og:locale:alternate" content="en_GB">
    <meta property="og:locale:alternate" content="en_US">
    <meta property="og:description" content="Portfolio and contact site from KubikPixel. You find here my PGP keys and verified social media accounts.">
    <meta property="og:type" content="website">
    <meta property="og:type:website" content="https://thunix.net/~kubikpixel/">
    <meta property="og:image" content="https://thunix.net/~kubikpixel/assets/img/ogava.jpeg">
    <meta property="og:image:type" content="image/jpeg">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="627">
    <meta property="og:image:alt" content="KubikPixel Avatar: Safety pin on red fabric">
    <!-- Style and Fonts -->
    <link type="text/css" rel="stylesheet" href="assets/css/mini-nord.min.css" media="all">
		<link type="text/css" rel="stylesheet" href="assets/css/style.css" media="all">
    <link type="text/css" rel="stylesheet" href="assets/css/line-awesome.min.css" media="all">
    <link type="text/css" rel="stylesheet" href="assets/css/toastify.css">

    <script type="text/javascript" src="assets/js/three.min.js"></script>
    <script type="text/javascript" src="assets/js/WebGL.js"></script>
  </head>
	<body>

    <canvas id="bg"></canvas>
    <script type="text/javascript">
      /* import * as THREE from './assets/js/three.min.js'; */
      /* import * as WEBGL from './assets/js/WebGL.js'; */

      function animate() {
        requestAnimationFrame(animate);

        octahedron.rotation.x += 0.002;
        octahedron.rotation.y += 0.004;
        octahedron.rotation.z += 0.001;

        icosahedron.rotation.x -= 0.002;
        icosahedron.rotation.y -= 0.004;
        icosahedron.rotation.z -= 0.001;

        renderer.render(scene, camera);
      }

      const scene = new THREE.Scene();
      const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
      const renderer = new THREE.WebGLRenderer({
        canvas: document.querySelector('#bg'),
        alpha: true,
      });

      renderer.setPixelRatio(window.devicePixelRatio);
      renderer.setSize(window.innerWidth, window.innerHeight);
      camera.position.setZ(80);

      var radius = window.innerHeight / 10;

      const materialb = new THREE.MeshBasicMaterial({
        color: 0x2698e6,
        wireframe: true,
      });
      const materialw = new THREE.MeshBasicMaterial({
        color: 0x7db6a7,
        wireframe: true,
      });

      const geometry00 = new THREE.OctahedronGeometry(radius);
      const octahedron = new THREE.Mesh(geometry00, materialw);
      const geometry01 = new THREE.IcosahedronGeometry(radius / 1.5);
      const icosahedron = new THREE.Mesh(geometry01, materialb);
      scene.add(octahedron, icosahedron);

      /* if (WEBGL.isWebGLAvailable()) { */
        animate();
      /* } else { */
      /*   const warning = WEBGL.getWebGLErrorMessage(); */
      /*   document.getElementById('bg').appendChild(warning); */
      /* } */

    </script>

		<header>
   		 <h1 class="section">KubikPixel</h1>
        <label for="modal-control">
           <i class="las la-share" title="Share"></i>
        </label>
		</header>

    <!-- Share -->
    <input type="checkbox" id="modal-control" class="modal">
    <div role="dialog" aria-labelledby="dialog-title">
      <div class="card shadowed">
        <h2 class="section" id="dialog-title">Share</h2>
        <label for="modal-control" class="modal-close"></label>
			  <img class="section media" src="assets/img/qrcode.png" alt="QR-Code with link to this site">
        <p class="section">
          <a href="https://twitter.com/intent/tweet?url=https://thunix.net/~kubikpixel/&text=KubikPixel&via=KubikPixel%20-%20Profile%20and%20Contact" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="Twitter">
            <i class="lab la-twitter"></i>
            </span>
          </a>
          <a href="https://www.facebook.com/sharer.php?u=https://thunix.net/~kubikpixel/" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="Facebook">
            <i class="lab la-facebook"></i>
            </span>
          </a>
          <a href="https://reddit.com/submit?url=https://thunix.net/~kubikpixel/&title=KubikPixel" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="Reddit">
            <i class="lab la-reddit"></i>
            </span>
          </a>
          <a href="https://vk.com/share.php?url=https://thunix.net/~kubikpixel/" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="VK">
            <i class="lab la-vk"></i>
            </span>
          </a>
          <a href="https://share.diasporafoundation.org/?url=https://thunix.net/~kubikpixel/&title=KubikPixel" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="Diaspora">
            <i class="lab la-diaspora"></i>
            </span>
          </a>
          <a href="https://www.linkedin.com/shareArticle?url=https://thunix.net/~kubikpixel/&title=KubikPixel" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="LinkedIn">
            <i class="lab la-linkedin-in"></i>
            </span>
          </a>
          <a href="https://www.xing.com/app/user?op=share&url=https://thunix.net/~kubikpixel/" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="Xing">
            <i class="lab la-xing"></i>
            </span>
          </a>
          <a href="mailto:%7Bemail_address%7D?subject=KubikPixel&body=https://thunix.net/~kubikpixel/%20KubikPixel%20-%20Profile%20and%20Contact" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="Email">
            <i class="las la-at"></i>
            </span>
          </a>
        </p>
        <p class="section">
          <a href="https://mail.google.com/mail/?view=cm&to=%7Bemail_address%7D&su=KubikPixel&body=https://thunix.net/~kubikpixel/&bcc=%7Bemail_address%7D&cc=%7Bemail_address%7D" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="Gmail">
            <i class="las la-envelope"></i>
            </span>
          </a>
          <a href="https://compose.mail.yahoo.com/?body=https://thunix.net/~kubikpixel/" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="Yahoo">
            <i class="lab la-yahoo"></i>
            </span>
          </a>
          <a href="whatsapp://send?text=https://thunix.net/~kubikpixel/" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="WhatsApp">
            <i class="lab la-whatsapp"></i>
            </span>
          </a>
          <a href="https://telegram.me/share/url?url=https://thunix.net/~kubikpixel/&text=KubikPixel" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="Telegram">
            <i class="lab la-telegram"></i>
            </span>
          </a>
          <a href="https://web.skype.com/share?url=https://thunix.net/~kubikpixel/" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="Skype">
            <i class="lab la-skype"></i>
            </span>
          </a>
          <a
            href="sms:%7Bphone_number%7D?body=KubikPixel%20-%20Profile%20and%20Contact%20https://thunix.net/~kubikpixel/" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="SMS">
            <i class="las la-sms"></i>
            </span>
          </a>
          <a href="https://www.evernote.com/clip.action?url=https://thunix.net/~kubikpixel/" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="Evernote">
            <i class="lab la-evernote"></i>
            </span>
          </a>
          <a href="https://getpocket.com/save?url=https://thunix.net/~kubikpixel/" target="_blank" rel="nofollow">
            <span class="tooltip" aria-label="Pocket">
            <i class="lab la-get-pocket"></i>
            </span>
          </a>
        </p>
      </div>
    </div>

    <main>
    <article>
		<div class="row">

    <!-- Avatar -->
		<section class="card shadowed">
			<h2 class="section">Avatar</h2>
      <img class="section dark circular" src="assets/img/avatar.jpeg" alt="KubikPixel Avatar: Safety pin on red fabric">
		</section>

    <!-- About -->
		<section class="card shadowed">
			<h2 class="section">About</h2>
			<p class="section about">
			I'm a Web &amp; App <mark class="tertiary tag">developer</mark> with
      <mark class="tertiary tag">3D</mark> experience and a Geek with a Punk
      attitude. I'm a <mark class="tertiary tag">open source</mark> evangelist
      and a <a href="https://1x.engineer/" target="_blank" rel="nofollow">1x
      Engineer</a> who uses Linux (Debian, Manjaro) on a daily basis.
      You can contact me in either English or German for a complete CV.
			</p>
		</section>

    <!-- Coding -->
		<section class="card shadowed">
			<h2 class="section">IT &amp; Coding</h2>
			<ul class="section">
        <li><i class="las la-hand-pointer"></i> PHP, JS, CSS, HTML</li>
        <li><i class="las la-code"></i> <mark class="tertiary tag">Python</mark>, Rust, Lisp, Shell</li>
        <li><i class="las la-database"></i> MySQL, <mark class="tertiary tag">MariaDB</mark>, PostgreSQL</li>
        <li><i class="las la-terminal"></i> <mark class="tertiary tag">Linux</mark>, Debian &amp; Manjaro</li>
        <li><i class="las la-file-code"></i> Git, Vim, SSH</li>
			</ul>
		</section>

    <!-- 3D Graphics -->
		<section class="card shadowed">
			<h2 class="section">3D &amp; Graphics</h2>
			<ul class="section">
        <li><i class="las la-cube"></i> <mark class="tertiary tag">WebGL</mark>, Blender, Godot</li>
        <li><i class="las la-drafting-compass"></i> AutoCAD, <mark class="tertiary tag">FreeCAD</mark>, BIMserver</li>
        <li><i class="las la-project-diagram"></i> BIM, <mark class="tertiary tag">CAM</mark>, PLM</li>
        <li><i class="las la-paint-brush"></i> Inkscape, Gimp, Krita</li>
			</ul>
		</section>

    <!-- Projects -->
		<section class="card shadowed">
			<h2 class="section">Projects</h2>
      <p class="section">
        The current 💻 projects I am working on in my spare time:
      </p>
			<ul class="section">
        <li><i class="las la-download"></i> <a href="downloads.php">Downloads</a>: 3D Assets &amp; Scripts</li>
        <li><i class="lab la-css3"></i> <a href="https://codeberg.org/KubikPixel/aclue">aclue</a>: A CSS icon color library</li>
        <li><i class="las la-code"></i> cURLcard: <code>curl -sL 0x0.st/NlpO</code></li>
<!-- <li><i class="las la-hand-point-right"></i> <a href="https://kubikpixel.github.io/pipeinstall/">Pipe Inslall</a>: A curated list of bad behavior</li> -->
			</ul>
		</section>

    <!-- Support -->
		<section class="card shadowed">
			<h2 class="section">Support</h2>
      <p class="section">
        If you would like to support me and my work, you can do so to spend my a ☕ through Liberapay or a paid itch.io download.
      </p>
			<p class="section">
        <script src="https://liberapay.com/KubikPixel/widgets/button.js"></script>
        <noscript><a href="https://liberapay.com/KubikPixel/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>
        <a rel="external" href="https://saarta.itch.io/" class="btn-itchio"><i class="lab la-itch-io"></i> itch.io</a>
 			</p>
		</section>

    <!-- Internet -->
		<section class="card shadowed">
			<h2 class="section">Internet</h2>
			<ul class="section">
				<li><i class="las la-rss"></i> <a href="https://paper.wf/kubikpixel/">Blog</a> (<a href="https://paper.wf/kubikpixel/feed/">Feed</a>)</li>
				<li><i class="lab la-mastodon"></i> <a rel="me" href="https://chaos.social/@kubikpixel">Mastodon</a></li>
				<li><i class="lab la-reddit"></i> <a href="https://www.reddit.com/user/KubikPixel">Reddit</a></li>
				<li><i class="lab la-git"></i> <a rel="me" href="https://codeberg.org/KubikPixel">Git repo</a></li>
				<li><i class="las la-rocket"></i> <a href="gemini://tilde.pink/~kubikpixel/">Gemini</a></li>
				<li><i class="las la-link"></i> <a rel="author" href="https://thunix.net/~kubikpixel/">Website</a></li>
			</ul>
		</section>

    <!-- Contact -->
		<section class="card shadowed">
			<h2 class="section">Contact</h2>
			<ul class="section">
				<li><i class="las la-address-card"></i> <a href="https://qcard.link/card/#QkVHSU46VkNBUkQNCkZOOkt1YmlrUGl4ZWwNCk46O0t1YmlrUGl4ZWw7OzsNCkVNQUlMOmt1YmlrcGl4ZWxAZGlzbWFpbC5kZQ0KVVJMOmh0dHBzOi8vdGh1bml4Lm5ldC9+a3ViaWtwaXhlbC8NCk5PVEU6V2ViICYgQXBwIGRldmVsb3BlciBmb3IgM0QgZ3JhcGhpY3MNClgtSkFCQkVSOmt1YmlrcGl4ZWxAZGlzbWFpbC5kZQ0KVkVSU0lPTjozLjANClVJRDpkZjExNGNiMC05NTY2LTIxMTMtYzkzNy00ZTlmZjI0MWU2ZGMNCkVORDpWQ0FSRA==">vCard</a></li>
				<li><i class="las la-user-check"></i> <a href="https://keyoxide.org/e8923e0f9c7c84a663a37f850be1a9ae16f417a2">Verified Accounts</a></li>
				<li><i class="las la-envelope"></i> <a rel="me" href="mailto:kubikpixel@dismail.de">Email</a> (see below for encryption)</li>
				<li><i class="las la-comments"></i> <a href="xmpp:kubikpixel@dismail.de">Jabber / XMPP</a></li>
				<li><i class="las la-comment"></i> <a href="https://matrix.to/#/@kubikpixel:tchncs.de">Matrix</a></li>
        <li><i class="las la-cloud-upload-alt"></i> <a target="_blank" rel="noreferrer noopener" href="https://nextcloud.com/sharing#kubikpixel@dismail.de@cloud3.linuxfabrik.io">Nextcloud</a></li>
 			</ul>
		</section>

    <!-- Social -->
		<section class="card shadowed">
			<h2 class="section">Fediverse</h2>
      <iframe class="section media" allowfullscreen sandbox="allow-top-navigation allow-scripts" width="322" height="200" src="https://www.mastofeed.com/apiv2/feed?userurl=https%3A%2F%2Fchaos.social%2Fusers%2Fkubikpixel&theme=light&size=100&header=false&replies=false&boosts=false"></iframe>
		</section>
    </div>
    <hr>
    <!-- PGP & SSh Key and Fingerprint -->
		<section>
        <blockquote class="shadowed">
          <h2>Encrypted Emails</h2>
          If you want to send me an <strong>email</strong>, then I ask you please to do this <strong>encrypted</strong>.<br>
          How this works and what you have to do for it and why I published my key here and what the fingerprint is you can read <a href="https://emailselfdefense.fsf.org/" target="_new" title="fsf.org">here...</a>
        </blockquote>
        <div>
          <h3>PGP Fingerprint</h3>
          <span class="tooltip" aria-label="Copy PGP Fingerprint to clipboard">
            <button id="btn-fpr" class="small primary shadowed" type="button">
              <i class="las la-clipboard"></i>
            </button>
          </span>
        </div>
        <label for="pgp-fpr">GPG Key ID: 0BE1A9AE16F417A2</label>
        <input type="text" class="shadowed" id="pgp-fpr" readonly="readonly" value="E892 3E0F 9C7C 84A6 63A3 7F85 0BE1 A9AE 16F4 17A2">
        <div>
          <h3>PGP Public Key</h3>
            <span class="tooltip" aria-label="Copy PGP Public Key to clipboard">
              <button id="btn-key" class="small primary shadowed" type="button">
                <i class="las la-clipboard"></i>
            </button>
            </span>
        </div>
      <label for="pgp-key">GPG Key ID: 0BE1A9AE16F417A2</label>
      <textarea class="shadowed" id="pgp-key" readonly="readonly">
-----BEGIN PGP PUBLIC KEY BLOCK-----

mDMEXz0j+RYJKwYBBAHaRw8BAQdAdrN+hX1MB/IRvfcocZmxbGkAPJ/uocyYpl6D
0tOYJG20Ikt1YmlrUGl4ZWwgPGt1YmlrcGl4ZWxAZGlzbWFpbC5kZT6JA1sEExYI
AwMCGwMFCQlmAYAFCwkIBwIGFQoJCAsCBBYCAwECHgECF4AWIQTokj4PnHyEpmOj
f4UL4amuFvQXogUCYQZcDUoUgAAAAAASAC9wcm9vZkBtZXRhY29kZS5iaXpodHRw
czovL25ld3MueWNvbWJpbmF0b3IuY29tL3VzZXI/aWQ9S3ViaWtQaXhlbMAgFIAA
AAAAEgDFcHJvb2ZAbWV0YWNvZGUuYml6eG1wcDprdWJpa3BpeGVsQGRpc21haWwu
ZGU/b21lbW8tc2lkLTEyNjY3NTA4MD1lNmVmM2E1MDQ0YTAzZjgwYzBjNWU4MzU5
YzYyOTEzZTY0NmQ2ZjE5MTc1MmU4YWYwMmMwM2JlYWI3OTBjYTAzO29tZW1vLXNp
ZC0xNDg1NTAzNDg1PTFjNTI1MWM4YTEwODYyOTgxNzAzMmNkODA3NzEzMjRjNTcy
YjNkNmEzOWYzZGRjNmRkZjJjZjRlMGViN2NhN2FGFIAAAAAAEgArcHJvb2ZAbWV0
YWNvZGUuYml6aHR0cHM6Ly9jb2RlYmVyZy5vcmcvS3ViaWtQaXhlbC9naXRlYV9w
cm9vZnAUgAAAAAASAFVwcm9vZkBtZXRhY29kZS5iaXpodHRwczovL3d3dy5yZWRk
aXQuY29tL3VzZXIvS3ViaWtQaXhlbC9jb21tZW50cy9pcW1yMXMva2V5b3hpZGVf
b3BlbnBncF92ZXJpZmljYXRpb24vOxSAAAAAABIAIHByb29mQG1ldGFjb2RlLmJp
emh0dHBzOi8vY2hhb3Muc29jaWFsL0BrdWJpa3BpeGVsoxSAAAAAABIAiHByb29m
QG1ldGFjb2RlLmJpem1hdHJpeDp1L0BrdWJpa3BpeGVsOnRjaG5jcy5kZT9vcmcu
a2V5b3hpZGUucj0hZEJmUVp4Q29HVm1TVHVqZml2Om1hdHJpeC5vcmcmb3JnLmtl
eW94aWRlLmU9JFIxOWFDMTBpUUx4UEFVTGVYMnZUM0pmWDJOYTNxVUZVM1BFbnNW
M3NLN28ACgkQC+Gprhb0F6JZxwEAnoQg0I/mMWugWrDLHaSI0eNijJz5ELLvDNzj
6d7a/LkBAPjFRUD8rM1gHm82ZNQCPU2QFWK5RQLsTFgd3uhjwv0K0dGl0aMBEAAB
AQAAAAAAAAAAAAAAAP/Y/+AAEEpGSUYAAQEAAAEAAQAA/9sAQwAIBgYHBgUIBwcH
CQkICgwUDQwLCwwZEhMPFB0aHx4dGhwcICQuJyAiLCMcHCg3KSwwMTQ0NB8nOT04
MjwuMzQy/9sAQwEJCQkMCwwYDQ0YMiEcITIyMjIyMjIyMjIyMjIyMjIyMjIyMjIy
MjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIy/8AAEQgAhwCHAwEiAAIRAQMRAf/E
AB8AAAEFAQEBAQEBAAAAAAAAAAABAgMEBQYHCAkKC//EALUQAAIBAwMCBAMFBQQE
AAABfQECAwAEEQUSITFBBhNRYQcicRQygZGhCCNCscEVUtHwJDNicoIJChYXGBka
JSYnKCkqNDU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6g4SF
hoeIiYqSk5SVlpeYmZqio6Slpqeoqaqys7S1tre4ubrCw8TFxsfIycrS09TV1tfY
2drh4uPk5ebn6Onq8fLz9PX29/j5+v/EAB8BAAMBAQEBAQEBAQEAAAAAAAABAgME
BQYHCAkKC//EALURAAIBAgQEAwQHBQQEAAECdwABAgMRBAUhMQYSQVEHYXETIjKB
CBRCkaGxwQkjM1LwFWJy0QoWJDThJfEXGBkaJicoKSo1Njc4OTpDREVGR0hJSlNU
VVZXWFlaY2RlZmdoaWpzdHV2d3h5eoKDhIWGh4iJipKTlJWWl5iZmqKjpKWmp6ip
qrKztLW2t7i5usLDxMXGx8jJytLT1NXW19jZ2uLj5OXm5+jp6vLz9PX29/j5+v/a
AAwDAQACEQMRAD8A5qSdQWHnO3AIKg/jVed0+fMch4HLH6VPK7IcmWLJH3VGT/8A
qrNuJR97zmLFew4z+VeSfobdtgnnx5mIlUggnPb2qtLeOcguBjkY9apzzAnqeR1N
VS5Pc1aiYymaDXrEsC5IPvikF0HYgAsSOnrWepywGMk8AV6b4L8DCeAapqo2W4GQ
p43f/Wqow5nZHNXxkKMeaTMLSdE1PVCTb27bCOT0C/jUt7AulztDd3ixSdGUDPSt
bxV4/wDLt/7M8NxiGIOImnUYxn09PrXKaF4VfxLrgtmu2LeV5km4ZbPcc/n+NdEc
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
6sosMhAVZJW29WPGfzoooCxa2llAS3jQSKcFjngdajy0qhV2KjLkgZ6UUUgGXUZD
N5r9FxjYPyHWsC8KrgBsnHRScZ/KiiqI3Ktkw+0KCu8nj0rtPDLD+3LFdgXO9fr8
hooq4fGjlxn+7T9GdPfpn4dacEJHlXUkfTOetcW8kK4BmkLMMlVGBmiiqxPxnJkW
uG+Y5FSVVKxM7H5cs1Pj3bFKxxRqMjPJNFFYHsvQVS4ZS8wTPHCdPaiiimI//9mJ
AqMEExYIAksCGwMFCQlmAYAFCwkIBwIGFQoJCAsCBBYCAwECHgECF4AWIQTokj4P
nHyEpmOjf4UL4amuFvQXogUCYEvBA6MUgAAAAAASAIhwcm9vZkBtZXRhY29kZS5i
aXptYXRyaXg6dS9Aa3ViaWtwaXhlbDp0Y2huY3MuZGU/b3JnLmtleW94aWRlLnI9
IWRCZlFaeENvR1ZtU1R1amZpdjptYXRyaXgub3JnJm9yZy5rZXlveGlkZS5lPSRS
MTlhQzEwaVFMeFBBVUxlWDJ2VDNKZlgyTmEzcVVGVTNQRW5zVjNzSzdvwCAUgAAA
AAASAMVwcm9vZkBtZXRhY29kZS5iaXp4bXBwOmt1YmlrcGl4ZWxAZGlzbWFpbC5k
ZT9vbWVtby1zaWQtMTI2Njc1MDgwPWU2ZWYzYTUwNDRhMDNmODBjMGM1ZTgzNTlj
NjI5MTNlNjQ2ZDZmMTkxNzUyZThhZjAyYzAzYmVhYjc5MGNhMDM7b21lbW8tc2lk
LTE0ODU1MDM0ODU9MWM1MjUxYzhhMTA4NjI5ODE3MDMyY2Q4MDc3MTMyNGM1NzJi
M2Q2YTM5ZjNkZGM2ZGRmMmNmNGUwZWI3Y2E3YTsUgAAAAAASACBwcm9vZkBtZXRh
Y29kZS5iaXpodHRwczovL2NoYW9zLnNvY2lhbC9Aa3ViaWtwaXhlbEoUgAAAAAAS
AC9wcm9vZkBtZXRhY29kZS5iaXpodHRwczovL25ld3MueWNvbWJpbmF0b3IuY29t
L3VzZXI/aWQ9S3ViaWtQaXhlbAAKCRAL4amuFvQXooKBAQDXdu/q2VFPb7O3R+vi
B+5O4kn1tHnuUdt7zPdNg4nwEQD+Nen0wCbhGSUE4hPpluHREr+HYS04U4I8c4GW
68fuWg+4OARfPSP5EgorBgEEAZdVAQUBAQdAWtqXzyNhaiuY797OAaiOJOZiYsj2
R1pvE+L4Lpv0VCsDAQgHiH4EGBYIACYWIQTokj4PnHyEpmOjf4UL4amuFvQXogUC
Xz0j+QIbDAUJCWYBgAAKCRAL4amuFvQXoo3nAP9NHPloYq01YXReZ9vNwUKvqE0r
Zj1dZd2PloSBjAbVAAD+J4QGMUv3rUb5nr5BcgfoLzrPiRgHB8EHWQeqmInRjwc=
=HhXB
-----END PGP PUBLIC KEY BLOCK-----
</textarea>
          <p>
          My PGP Public Key on <a href="https://keys.openpgp.org/search?q=E8923E0F9C7C84A663A37F850BE1A9AE16F417A2" target="_new" title="Key on keys.openpgp.org">keys.openpgp.org</a> or download it <a rel="pgpkey" href="E8923E0F9C7C84A663A37F850BE1A9AE16F417A2.txt" target="_new" title="Download PGP Public Key">here</a>.
          </p>
          <div>
            <h3>SSH Public Key</h3>
              <span class="tooltip" aria-label="Copy SSH Public Key to clipboard">
                <button id="btn-ssh" class="small primary shadowed" type="button">
                    <i class="las la-clipboard"></i>
                </button>
              </span>
          </div>
        <label for="ssh-key">SSH Key kubikpixel@dismail.de</label>
        <input type="text" class="shadowed" id="ssh-key" readonly="readonly" value="ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDLtKAGW7yeRIx5Hzz5Whv30PMaSOgF7cTQsDWFARI47Z2va4729knmoiHu0Utht7R4ob00rzqgmT04rciAtKhjJO4DpMaSoUl5TI6zRRjDIk4kfwnGFZySiVGlOJIMD9ShvmaNN6vuUhm/h1NRQRyqrKshRKU5MLJXB4eEnx2+oVxNvYpODJNQTb0nKyxf0JapGBaehaP2vUc9VH09r3VBj00e/xjdPpeldk5TUwly+mnNI1RGI9e7CObJtyDtp1t1AAAeq5M/iay2BAuGCSNTm+kX3WObSfPvNipMWqvUY9h26EVelhAAPvvFwskmFuZt8yrQNcTYwfWUzyz1FWhL kubikpixel@dismail.de">
      </section>
    </article>
		</main>
    <hr>
		<footer>
		 	<p>&copy; &amp; &lt;&check;&gt; with &hearts; 2021 by KubikPixel</p>
		</footer>
    <script type="text/javascript" src="assets/js/toastify.js"></script>
    <script type="text/javascript">
/* return content of input field to variable text */
var pgpfpr = document.getElementById("pgp-fpr");
var pgpkey = document.getElementById("pgp-key");
var sshkey = document.getElementById("ssh-key");

/* return button to variable btn */
var btnfpr = document.getElementById("btn-fpr");
var btnkey = document.getElementById("btn-key");
var btnssh= document.getElementById("btn-ssh");

/* call function on button click */
btnfpr.onclick = function() {
  pgpfpr.select();
  document.execCommand("copy");
  Toastify({
    text: "PGP Fingerprint was successfully copied to your clipboard.",
    backgroundColor: "linear-gradient(to right, #00b09b, #06c09d)",
    duration: 4500,
    stopOnFocus: true,
    close: true,
  }).showToast();
}
btnkey.onclick = function() {
  pgpkey.select();
  document.execCommand("copy");
  Toastify({
    text: "PGP Public Key was successfully copied to your clipboard.",
    backgroundColor: "linear-gradient(to right, #00b09b, #06c09d)",
    duration: 4500,
    stopOnFocus: true,
    close: true,
  }).showToast();
}
btnssh.onclick = function() {
  sshkey.select();
  document.execCommand("copy");
  Toastify({
    text: "SSH Public Key was successfully copied to your clipboard.",
    backgroundColor: "linear-gradient(to right, #00b09b, #06c09d)",
    duration: 4500,
    stopOnFocus: true,
    close: true,
  }).showToast();
}
  </script>
  </body>
</html>
<!-- Try this in our terminal: "curl -sL thunix.net/~kubikpixel"
[2J[m
[36m╔═════════════════════════════════════════════════════════╗
[36m║[m          [31m__ __     __   _ __    ___  _          __      [36m║
[36m║[m         [31m/ //_/_ __/ /  (_) /__ / _ \(_)_ _____ / /[m      [36m║
[36m║[m        [31m/ ,< / // / _ \/ /  '_// ___/ /\ \ / -_) /[m       [36m║
[36m║[m       [31m/_/|_|\_,_/_.__/_/_/\_\/_/  /_//_\_\\__/_/[m        [36m║
[36m║[m          [31m-~=# 161 = floss = cypher = nrk #=~-[m           [36m║
[36m║                                                         ║
[36m╠═════════════════════════════════════════════════════════╣
[36m║                                                         ║
[36m║[m [31m■[m [4m[1mKubikPixel:[m  [1mWeb & App developer with 3D experience[m [31m■[m [36m║
[36m║                                                         ║
[36m║[m        [4m[1mEmail:[m  [32mkubikpixel@dismail.de                    [36m║
[36m║[m      [4m[1mPGP FPR:[m  [2mE892 3E0F 9C7C 84A6 63A3                 [36m║
[36m║[m                [2m7F85 0BE1 A9AE 16F4 17A2                 [36m║
[36m║[m         [4m[1mXMPP:[m  [33mkubikpixel@dismail.de                    [36m║
[36m║[m       [4m[1mMatrix:[m  [36m@kubikpixel:tchncs.de                    [36m║
[36m║                                                         ║
[36m║[m          [4m[1mWeb:[m  [2mhttps://thunix.net/[m[31m~kubikpixel/          [36m║
[36m║[m         [4m[1mBlog:[m  [2mhttps://paper.wf/[m[32mkubikpixel/             [36m║
[36m║[m       [4m[1mGemini:[m  [2mgemini://tilde.pink/[m[37m~kubikpixel/         [36m║
[36m║                                                         ║
[36m║[m     [4m[1mMastodon:[m  [2mhttps://chaos.social/[m[34m@kubikpixel         [36m║
[36m║[m       [4m[1mReddit:[m  [2mhttps://www.reddit.com/user/[m[31mKubikPixel   [36m║
[36m║[m     [4m[1mGit repo:[m  [2mhttps://codeberg.org/[m[36mKubikPixel          [36m║
[36m║                                                         ║
[36m║[m         [4m[1mCard:[m  [33mcurl -sL 0x0.st/NlpO                     [36m║
[36m║                                                         ║
[36m╚═════════════════════════════════════════════════════════╝[m

-->


