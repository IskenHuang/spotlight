# spotlight
This is an [KISSY](http://docs.kissyui.com/) ui plugin. support ie9+. Mouse hover animation.

# how to use
```
<a href="#" class="spotlight">ItemA</a>
<a href="#" class="spotlight">ItemA</a>
<a href="#" class="spotlight">ItemA</a>
...

<script>
KISSY.use('spotlight', function(S, Spotlight){
    new Spotlight({
        elName: '.spotlight',
        maskColor: '#333',
        opacity: 0.7,
        animationSeconds: 1.0
    });
});
</script>
```

# params
| params | type | default value | description |
| --- | --- | --- | --- |
| elName | string | .spotlight | selector. put at spotlight dom element |
| rootElName | string | ''(empty string) | elName's parent selector |
| maskColor | string | '#333' | Mask color of the element |
| opacity | float | 0.5 | mask opacity. scope from 0.0 to 1.0 |
| animationSeconds | float | 0.5 | mask appear and disappear transition seconds |
