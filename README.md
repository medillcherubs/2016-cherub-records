# 2016-cherub-records
Cherub Guinness records

https://medillcherubs.github.io/2016-cherub-records/

Paste this into your Wordpress post, under the "Text" tab instead of the "Visual" tab:

```
[raw]
<div id="cherub-records"></div>
<script> var pymParent = new pym.Parent("cherub-records", "//medillcherubs.github.io/2016-cherub-records/index.html", {}); </script>

<!-- Edit: https://github.com/medillcherubs/2016-cherub-records/edit/gh-pages/index.html -->
[/raw]
```

Paste this into the bottom of your `index.html`:

```
<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script> <script src="https://cdnjs.cloudflare.com/ajax/libs/pym/0.4.5/pym.min.js"></script> <script> $(function(){ var pymChild = new pym.Child({polling: 500}); }); </script> 
```
