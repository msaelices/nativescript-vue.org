---
title: ConfirmDialog
apiRef: https://docs.nativescript.org/api-reference/modules/_ui_dialogs_#confirm
contributors: [ianaya89]
---

El método `confirm()` muestra un mensaje de confirmación con un botón de OK y otro de cancelación.

Este método forma parte del [módulo de `dialogs`](https://docs.nativescript.org/api-reference/modules/_ui_dialogs_).

---

## Uso básico

El método `confirm()`, esta disponible de forma global. Puedes llamarlo en cualquier lugar dentro de tu aplicacioón.

```javascript
confirm('Your message')
  .then(result => {
    console.log(result);
  });
```

## Configurar las opciones del diálogo

```javascript
confirm({
  title: 'Your title',
  message: 'Your message',
  okButtonText: 'Your OK button text',
  cancelButtonText: 'Your Cancel text'
}).then(result => {
  console.log(result);
});
```

[> screenshots for=ConfirmDialog <]
