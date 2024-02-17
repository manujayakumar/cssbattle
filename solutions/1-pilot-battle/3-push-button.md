# Battle #1 - Pilot Battle

## #3 - Push Button

[Link to the problem](https://cssbattle.dev/play/3)

![result](./img/3-push-button.png)

```html
<p c><p o><p i><!-- instead of using class(<p class="a"></p>) or id(<p id="a">) simply uses <p a></p> or <p> -->
<style>
  body {
        margin:0;
        background:#6592CF;
        display:grid;
        place-items:center;
    }
  p {
        position:absolute;
    }
  p[c] {            /*instead of using .a(for class) or #a(for id) can be called p[a] with p tag or just [a] with square brackets*/
        width:300px;
        height:150px;
        background:#243D83;
    }
  p[o],p[i]{
        border-radius:50%;
    }
  p[o] {
        width:150px;
        height:150px;
        border: 50px solid #6592CF;
    }
  p[i]{
        width:50px;
        height:50px;
        background:#EEB850;
    }
</style>