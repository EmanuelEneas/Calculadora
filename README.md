# 🔢 Calculadora – React App

Esta es una calculadora interactiva desarrollada en **React**, capaz de realizar operaciones básicas utilizando la librería **mathjs** para evaluar expresiones matemáticas.  
La aplicación cuenta con componentes reutilizables, manejo de estado y una interfaz sencilla con botones dinámicos.

---

## ✨ Características principales

- Operaciones básicas: suma, resta, multiplicación y división.
- Evaluación de expresiones con **mathjs**.
- Componente `Pantalla` para mostrar la operación actual.
- Botones reutilizables para números y operadores.
- Botón **Clear** para reiniciar la operación.
- Manejo de estado mediante `useState`.
- Validación simple antes de calcular resultados.
- Diseño organizado en filas para simular una calculadora física.

---

## 🧠 Funcionamiento

- Los números y operadores se van agregando al `input` mediante:

```jsx
const agregarInput = valor => setInput(input + valor);

