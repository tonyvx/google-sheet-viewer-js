# Purpose

To embed google sheet in website for displaying in a responsive format.

Google Sheet embed on a website doesnot support mobile view

**Important**

Google sheet should be public. _Anyone can view_

# Usage

Embed below 3 tags in your website


```html
<div id="SheetViewer"></div>
```

```html
<div id="sheet" data-sheet-id="<<sheet-id obtained from sheet url>>" data-range="<< Sheet name & column range eg:Coins by Nation!A:H>>" data-column-filter="region=Polynesia"
  data-column-names="continent:Continents,region:Regions,nation:Country,currency:Currency,cOUNTAOfNation:Coin Count,sUMOfUnit:Curreny Total"
  data-column-summarized="continent,region,nation"
 data-column-summarized-sum="cOUNTAOfNation"
  data-header-style="fontFamily: 'Ubuntu',fontWeight:500, background:grey, color:white"
  data-body-style="fontFamily: 'Ubuntu',fontWeight:200, 
  background: "#1abc9c", color:black" ></div>
```

```html
<script  src="https://cdn.jsdelivr.net/gh/tonyvx/google-sheet-viewer-js@1.1/main.js"></script>
```
