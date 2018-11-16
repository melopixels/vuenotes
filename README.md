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

Just use the tag <sticky-notes> inside a div with id="notes" and class="notes"
	
<pre>
<div id="notes" class="notes">
  <div class="container">
   <sticky-notes></sticky-notes>
  </div>
</div>
</pre>


To make your note sharable you need to create HTML page called shared.html and use <shared-note> tag as following :

<pre>
<div id="notes" class="notes">
  <div class="container">
   <shared-note></shared-note>
  </div>
</div>
</pre>


