# jQuery-Commons

```javascript
if (isAwesome){
  return true
}
```
**Obtener texto seleccionado**
```javascript
$(".selectedProvider").on("change", function(e){	
  var _text = $(".selectedProvider option:selected").text();
});
```
