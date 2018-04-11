## How to use ticker widget on your website.

Add this line inside **head** tag

`<script type="text/javascript" src="https://www.atomicexplorer.com/ticker/aeticker.min.js"></script>`

Add the following bit inside **body** tag

`<script>initAETicker('aeTicker', 60000, 'dex', 'dex.png');</script>`

`<div class="ae-ticker" id="aeTicker"></div>`

Params: ticker mount point element id, update interval in msec, coin ticker name, relative/abosulte path to an icon. 