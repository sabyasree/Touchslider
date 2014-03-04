TouchSlider jQuery Plugin - Mobile | Tablet | Desktop browsers touch slider
==========


touchslider external events handle


touchSlider — is a free CSS accelerated jQuery plugin optimized for desktop and mobile browsers. It can be used for sliding images and content.

Include the jquery and touchslider scripts to your ```<head> ```tag:
```
<script type="text/javascript" src="/path/jquery-1.9.0.min.js"/>
<script type="text/javascript" src="../vendor/jquery.touchslider.min.js"></script>

<script>
jQuery(function($) {
    $(".touchslider").touchSlider({/*options*/});
});
</script>
```
Add below HTML structure with relevant image URLs:
```
<div class="touchslider">
    <div class="touchslider-viewport" style="width:500px;overflow:hidden"><div>
        <div class="touchslider-item"><!-- your html content --></div>
        <div class="touchslider-item"></div>
        ...
    </div></div>

    <div>
        <span class="touchslider-prev">←</span>
        <span class="touchslider-nav-item touchslider-nav-item-current">1</span>
        <span class="touchslider-nav-item">2</span>
        ...
        <span class="touchslider-next">→</span>
    </div>
</div>

```
External Control 
```
<div class="changeview">
		<div class="changeviewdiv">
				<!-- html content -->		
		</div>
		<div class="secondview">
		    <!-- html content -->	
		</div>
</div>
```

