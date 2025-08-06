# 📘 Guía de Estándares de Código - VibeSphere

Guía de buenas prácticas y convenciones para el desarrollo del proyecto usando React.js, Node.js y MongoDB.

---

## 🔤 A. Reglas de nombres

### 🧠 General (JavaScript / JSX)
- **Variables y funciones**: `camelCase`
- **Clases y componentes React**: `PascalCase`
- **Constantes**: `UPPER_CASE`
- **Nombres de archivos**: `kebab-case` para archivos comunes, `PascalCase.jsx` para componentes

**Ejemplos válidos:**
```js
const userName = "Ana";

function getUserData() { ... }

class UserProfile extends Component { ... }

const API_URL = "https://api.vibesphere.com";
