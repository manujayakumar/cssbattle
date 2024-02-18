# Battle #1 - Pilot Battle

## #2 - Carrom

[Link to the problem](https://cssbattle.dev/play/2)

![result](./img/2-carrom.png)

```html
<p a><p b><p c><p d> <!-- instead of using class(<p class="a"></p>) or id(<p id="a">) simply uses <p a></p> or <p> -->
  <style>
    *{
        margin:0;
        background:#62374e;
    }
    p {
        width: 50px;
        height:50px;
        background:#fdc57b;
        position:fixed;
    }  
    p[a],p[c]{ /*instead of using .a(for class) or #a(for id) can be called p[a] with p tag or just [a] with square brackets*/
        left:50px
    } 
    p[a],p[b]{
        top:50px
    }
    p[b],p[d]{
        left:300px
    }
    p[c],p[d]{
        top:200px
    }
  </style>
```