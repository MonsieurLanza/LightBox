![lightbox](https://cloud.githubusercontent.com/assets/10348820/8272933/e4866ce0-1857-11e5-82e0-843641cf8851.png)

# === PL ===
LightBox jest to prosty plugin galeri napisany w czystym JavaScript.

### Jak używać

1. Dodaj style CSS i plik JavaScript do swojego pliku
```
<link rel="stylesheet" type="text/css" href="css/lightbox.css">
<script type="text/javascript" src="js/lightbox.js"></script>
```
2. Wstaw obrazy w takim stylu jak poniżej (caption można pominać)
```
<div data-big="big/ts_img1.jpg" class="lightbox">
	<img src="small/ts_img1.jpg" alt="small">
</div>
```
3. Odpal LightBox'a
```
document.addEventListener("DOMContentLoaded", function() {
	var init = new lightBox();
});
```

# === ENG ===
LightBox is a simple gallery plugin written in pure JavaScript. 

### How to use
1. Add CSS file and JS file
```
<link rel="stylesheet" type="text/css" href="css/lightbox.css">
<script type="text/javascript" src="js/lightbox.js"></script>
```
2. Put your images as below (caption is not required)
```
<div data-big="big/ts_img1.jpg" class="lightbox">
	<img src="small/ts_img1.jpg" alt="small">
</div>
```
3. Run LightBox
```
document.addEventListener("DOMContentLoaded", function() {
	var init = new lightBox();
});
```


# DEMO
http://projects.lukaszduda.com.pl/lightbox
