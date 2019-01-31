### BigText
---
https://github.com/zachleat/BigText

```js
$('#bigtext').bigtext();

if( 'querySelectorAll' in document ){
  $('#bigtext').bigtext();
}

$('#bigtext').bigtext();

$('#bigtext').bigtext({
  childSelector: '> p'
});

$('#bigtext').bigtext();

$('#bigtext').bigtext();

$(function(){
  WebFont.load({
    custom: {
      families: ['LeagueGothicRegular'],
      urls : ['css/fonts/league-gothic/stylesheet.css']
    },
    active: function(){
      $('#bigtext').bigtext();
    }
  });
});

$('#bigtext').bigtext({
  maxfontsize: 60
});

$('#bigtext').bigtext({
  minfontsize: 16
});
```

```
BigText.DEBUG_MODE = true;
```

```
```

