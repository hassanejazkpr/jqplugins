It is a simple notification plugin built in jquery.

It includes 2 folders, one is with jquery and the other is without jquery.

the notify.js and notify.min.js in with jquery folder already have jquery written in it so you don't have to include jquery separately.

Installation:
just include css in header like below:
`<link rel="stylesheet" href="notify.css" type="text/css" />`
or
`<link rel="stylesheet" href="notify.min.css" type="text/css" />`

& include js using:
`<script src="notify.js" type="text/javascript"></script>`
or
`<script src="notify.min.js" type="text/javascript"></script>`

Usage:
just make a `<div id="notify"></div>` anywhere in your page.
below is the example usage:
```
<script>
            $("notify").notify({
            title: 'A title for notification',
            text: 'Some text for notification',
            theme: 'dark',
            });
</script>
```
Supported themes:

light
dark
success
info
warning
danger
contact me on "hassanejazkpr@gmail.com" for any suggestion or question.
