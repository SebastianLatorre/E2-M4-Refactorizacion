# 🛠️ E2-M4 Ejercicio
## Refactorización a ES6+ 🚀

### Objetivo:
Tomar un bloque de código JavaScript funcional pero escrito con sintaxis "antigua" (pre-ES6) y modernizarlo aplicando las mejoras introducidas en ES6 y versiones posteriores. El objetivo es practicar la reescritura de código para que sea más legible, conciso y robusto.

### Actividad:
A continuación, se presenta un script que define un objeto de usuario y una función para crear un mensaje de presentación. Tu tarea es refactorizar (reescribir) este código para que utilice las características modernas de JavaScript.

### Código Antiguo (para refactorizar):

```javascript
// Objeto que representa a un usuario
var usuario = {
  nombre: 'Ana',
  edad: 24,
  ciudad: 'Barcelona'
};

// Función tradicional para crear el mensaje de presentación
function crearMensajePresentacion(user) {
  var nombre = user.nombre;
  var edad = user.edad;
  var ciudad = user.ciudad;

  var mensaje = 'Hola, mi nombre es ' + nombre + ', tengo ' + edad + ' años y vivo en la ciudad de ' + ciudad + '.';
  
  return mensaje;
}

// Se llama a la función y se muestra el resultado en consola
var mensajeDeBienvenida = crearMensajePresentacion(usuario);
console.log(mensajeDeBienvenida);
```

### Requisitos de la Refactorización:
Debes modificar el código aplicando las siguientes mejoras:

- **Declaración de Variables:** Reemplaza todas las declaraciones con var por let o const, según corresponda. Piensa cuál es más adecuado para cada caso.
- **Funciones:** Convierte la function tradicional en una arrow function.
- **Strings:** Sustituye la concatenación con el operador + por el uso de template literals (plantillas de texto con comillas invertidas `).
- **Desestructuración (Destructuring):** En lugar de acceder a las propiedades del objeto una por una (ej: user.nombre), utiliza la desestructuración para extraer nombre, edad y ciudad directamente en los parámetros de la función o al inicio de la misma.

### Resultado Esperado en Consola (debe ser idéntico al original):

> Hola, mi nombre es Ana, tengo 24 años y vivo en la ciudad de Barcelona.

### Conceptos a Aplicar:

- **Variables de Bloque:** let y const.
- **Arrow Functions:** Sintaxis `() => {}`.
- **Template Literals:** `` `Mi string es ${miVariable}` ``.
- **Destructuring:** `const { propiedad1, propiedad2 } = miObjeto;`.

### Entrega:
El trabajo deberá ser entregado a través de un repositorio público en GitHub. En el repositorio, incluye tanto el archivo con el código original como el archivo con tu código refactorizado para poder compararlos. Por favor, comparte únicamente el enlace a dicho repositorio. 📤