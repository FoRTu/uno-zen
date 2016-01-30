# Mi version de **Uno Zen** para Ghost
[<img src="http://i.imgur.com/561YaMH.png">](http://fortu.io)

---

## Introducción

Este tema para [Ghost](https://ghost.org) es un fork de [Uno-Zen](https://github.com/Kikobeats/uno-zen) que he personalizado a mi gusto.


## Instalacíon

Simplemente hay que clonar el repositorio con **git clone** dentro de la carpeta **content/themes** the **ghost**.

Se hace uso de jQuery, por lo que es necesario poner el siguiente texto en el apartado **Blog Footer** en **Code injection** que encontraras en la página de administración de **ghost**:

```html
<script type="text/javascript" src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
```

Se debería ver tal que así:

![](https://camo.githubusercontent.com/f600498109f9b8e7d15fadd28b51c75b1f585d0f/687474703a2f2f692e696d6775722e636f6d2f4b365a595933752e706e67)

### Google Analytics

 Para monitorizar la pagina con **Google Analytics** entrar en la página de administración de Ghost `Code Injection` → `Blog Header` y poner el siguiente texto con vuestro ID:

```html
<script>
var ga_id = 'ID_GOOGLE_ANALYTICS';
</script>
```

### Comentarios ([Disqus](https://disqus.com/))

Para agregar la opción de comentarios con **Disqus**, entra en la página de administración `Code Injection` → `Blog Header` y pegáis el siguiente texto con el ID de **Disqus**:

```html
<script>
var disqus_shortname = 'ID_DISQUS';
</script>
```

Estos son los ajustes mínimos para que funcione, pero si estas pensando en personalizarlo mas aun, pasate por la [documentación](https://github.com/Kikobeats/uno-zen/blob/master/DOCUMENTATION.md) del autor original.
