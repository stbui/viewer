#

```
<a class="test" href="#" data-original="images/tibet-8.jpg">test</a>

$('.test').viewer();
```

```
$('body').on('click', '[data-stbui="viewer"]', function(event) {
  $(event.currentTarget).viewer({url: 'data-original'});
  return false;
});
```
