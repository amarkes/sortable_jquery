# sortable_jquery
criando um sortable bem fácil

### Requisitos

https://code.jquery.com/jquery-1.12.4.js

https://code.jquery.com/ui/1.12.1/jquery-ui.js

jquery.sortable.js

http://fonts.googleapis.com/css?family=Droid+Serif

### Funções

```sh
$(function() {
  $('.sortable').sortable();      
  $('.connected').sortable({      
    connectWith: '.connected'        
  });

  $('#connected ul').each(function(){      
    console.log( $(this).children('li').size() );        
    for (var i = 0; i <= $(this).children('li').size(); i++) {        
       $(this).children('li').resizable();           
    }        
  });
});
```

### Preview
[![N|Solid](https://s27.postimg.org/pnj8esj77/sortable.png)]
