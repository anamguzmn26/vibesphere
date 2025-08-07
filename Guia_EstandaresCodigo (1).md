# Guía de Estándares de Código

## Reglas de nombres

- **Variables:** usar `camelCase` (ej. `userName`, `totalAmount`).
- **Clases:** usar `PascalCase` (ej. `UserController`, `PaymentService`).
- **Métodos:** usar `camelCase` (ej. `getUserData()`, `saveInvoice()`).
- **Constantes:** usar `SCREAMING_SNAKE_CASE` (ej. `MAX_USERS`, `API_KEY`).

## Comentarios y documentación interna

- Usar comentarios en inglés (o español si el equipo lo decide) para describir el propósito del código.
- Documentar funciones con JSDoc o formato similar.
- Evitar comentarios obvios; el código debe ser autoexplicativo.

## Identación y estilo de código

- Usar 2 espacios por nivel de indentación.
- Incluir punto y coma al final de cada línea.
- Mantener líneas de máximo 80-100 caracteres.
- Usar comillas simples `'` por defecto, dobles `"` solo si se necesitan.

## Ejemplos aceptados y no aceptados

### ✔ Aceptado

```js
function getUserData(userId) {
  return users.find(user => user.id === userId);
}
```

### ❌ No aceptado

```js
function Get_User_data(ID){
return users.find(function(u){return u.id==ID});
}
```