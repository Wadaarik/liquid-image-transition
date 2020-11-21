# liquid-image-transition
---
### Based on [hover-effect](https://github.com/robin-dela/hover-effect) from [robin-dela](https://github.com/robin-dela)
## NEED
- Three.js
- Gsap.js
- [Hover effect](https://github.com/robin-dela/hover-effect/blob/master/dist/hover-effect.umd.js)

---
### STEP 1

You need to create a HTML file with a simple div :
```html
<!-- Div to draw the effect -->
<div class="my-div"></div>
```

### STEP 2

You need to link three.js and gsap.js :
```html
<!-- library needed -->
<script src="three.min.js"></script>
<script src="TweenMax.min.js"></script>
```

### STEP 3

You need to link the hover effect script :
```html
<script src="dist/hover.umd.js"></script>
```

### STEP 4

Finally, create the script for hover effect :
```html
<script>
new hoverEffect({
        parent: document.querySelector('.my-div'), //div which is selected
        intensity: 0.3, //intensity of the event
        image1: 'images/myImage1.jpg', //image visible at first
        image2: 'images/myImage2.jpg', //image at the hover
        displacementImage: 'images/myDistorsionImage.png' // filter beetween images
    });
</script>
```
