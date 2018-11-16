# Vue Notes

Vuenotes is Vue.js Plugin you can embed in your project. To run it requires:

* Latest Version Of Vue.js v2 Download Vue
* Latest Version Of httpVueLoader.js v2 Download From Github
* Latest Version Of fontawesome.css Download From Github
* Version 3 bootstrap.css Download

## Content

<pre>
Vuenotes/
	└── plugin/
		├── components/
		│   ├── multiNotes.vue
		│   ├── sharedNote.vue
		│   └── singleNote.vue
		├── css/
		│   └── vuenotes.css
		├── js/
		│   └── vuenotes.js
		└── fonts/
			├── Poppins-Light.ttf
			├── Poppins-Medium.ttf
			├── Poppins-Regular.ttf
			├── Poppins-SemiBold.ttf
			├── toriom-light.ttf
			└── toriom-medium.ttf
</pre>


## How To Embed

Just use the tag &lt;sticky-notes&gt; inside a div with id="notes" and class="notes"

<pre>
&lt;div id="notes" class="notes"&gt;
  &lt;div class="container"&gt;
   &lt;sticky-notes></sticky-notes&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>

<p>To make your note sharable you need to create HTML page called shared.html and use &lt;shared-note&gt; tag as following :</p>

<pre>
&lt;div id="notes" class="notes"&gt;
  &lt;div class="container">
   &lt;shared-note></shared-note&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>


