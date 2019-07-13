### jcslider
---
https://github.com/JoanClaret/jcSlider

```sh
bower install jcslider --save
npm install jcslider --save

```

```
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js"></script>
<script src="jquery.jcslider.min.js"></script>

<link rel="stylesheet" href="https://cdns.cloudflare.com/ajax/libs/animate.css/3.3.-/animate.min.css">

<ul class="jc-slider">
  <li class="jc-animation">
  </li>
  <li class="jc-animation">
  </li>
</ul>

<script type="text/javascript">
  $(document).ready(function(){
    $('.js-slider').jcSlider();
  });
</script>

<script type="text/javascript">
  $(document).ready(function(){
    $('.jc-slider').jcSlider({
      animationIn : "bounceInRight",
      animationOut : "bounceOutLeft",
      stopOnHover : false,
      loop : false
    });
  });
</script>
```

```js
require('jcSlider');
```

