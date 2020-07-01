# OBS Browser Source Layout
Honestly this was just some dumb weekend project that I wanted to see if I could do, don't use this lol

Go download Amber_CXC's layouts, honestly I kinda just wanted to see if I could do it:
* 	https://twitter.com/amber_cxc/status/1277308317958844420
* 	https://twitter.com/amber_cxc/status/1276616701069713408
* 	https://twitter.com/amber_cxc/
---

If you want to align the Face Cam / Split Box to the right: add the following CSS to the custom CSS:<br>
```css
.Container { justify-content: flex-end }
```

By default it's aligned to the left
If you want to customize the background of each element, add .[Class] { background: [CSS Background] } to the custom CSS in OBS
If you want to change the size of 16:9 to 4:3, Add the following CSS to your custom CSS:<br>
```css
	.TopBorder { display: none; } 
	.FaceCamBox { height: 302px; width: 536px; } 
	.SplitBox { height: 734px; width: 536px;  bottom: -734px} 
	.BottomBorder { height: 44px; }
```