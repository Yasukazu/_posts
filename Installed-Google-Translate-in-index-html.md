---
title: Installed 'Google Translate' in index.html
date: 2023-01-25 18:11:01
tags: google-translate
---
Changes:
- `index.pug`: Added `div#google_translate_element` before `main`
- `scripts.pug`: Added 
```pug
script.
    function googleTranslateElementInit() {
        new google.translate.TranslateElement({pageLanguage: 'en', layout: google.translate.TranslateElement.InlineLayout.HORIZONTAL}, 'google_translate_element');
    }

script(src="https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit")
```