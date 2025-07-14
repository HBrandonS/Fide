# Proyecto Fidecompro - Avance 2  
**Curso:** Programación Cliente Servidor Concurrente  
**Estudiante:** [Brandon Hernandez]  
**Profesor:** [VARGAS MONTES MARIO ALBERTO]  
**Entrega:** Avance 2 (10%)  

---

## 🧾 Descripción general

Este proyecto simula el sistema de facturación de la cadena Fidecompro. Se desarrolló en Java utilizando programación orientada a objetos y una interfaz gráfica con `Swing`.  

En este avance 2 se implementa el 40% de las funcionalidades, cumpliendo con los requerimientos de la rúbrica, incluyendo clases, herencia, polimorfismo, manejo de excepciones, colecciones e interfaz gráfica.

---

## ✅ Funcionalidades implementadas

| Historia de Usuario | Estado |
|----------------------|--------|
| Login de usuario con contraseña | ✅ Implementado |
| Registro de nuevos productos | ✅ Implementado |
| Registro de nuevos clientes | ✅ Implementado |
| Visualización del sistema en GUI | ✅ Implementado |
| Generación de factura (en progreso) | 🔄 Pendiente para avance 3 |

---

## 🔧 Tecnologías usadas

- Java SE 17
- Swing (GUI)
- ArrayList
- Clases y objetos
- Herencia (`Persona` → `Usuario`, `Cliente`)
- Polimorfismo (`obtenerInformacion()`)
- Excepciones (`try-catch` en validaciones)

---

## 🗂️ Estructura del código

Todo el código está contenido en una sola carpeta para cumplir con los lineamientos del curso.  
Archivos principales:

- `Main.java` – Punto de entrada
- `Usuario.java`, `Cliente.java`, `Producto.java`, `Factura.java` – Clases principales
- `SistemaFacturacion.java` – Lógica de negocio
- `VentanaLogin.java`, `VentanaPrincipal.java`, `VentanaCliente.java`, `VentanaProducto.java` – GUI

---

## 🖼️ Capturas de pantalla (opcional)

> Puedes insertar aquí capturas como:
- Login exitoso
- Registro de cliente
- Registro de producto
- Menú principal

---

## 💬 Notas adicionales

- El login usa un usuario por defecto:  
  - Usuario: `admin`  
  - Contraseña: `1234`  
- El proyecto está preparado para expandirse en el Avance 3 con:
  - Facturación completa
  - Archivo físico
  - Persistencia o serialización
  - Hilos o tareas en paralelo

---

## 📁 Cómo ejecutar

1. Clona o descarga el repositorio.
2. Abre el proyecto en NetBeans (o cualquier IDE Java).
3. Ejecuta `Main.java`.
4. Ingresa las credenciales `admin` / `1234` para iniciar.

---

## 🧑‍💻 Autor

**[Brandon Hernandez Serrano]**  
[HBrandonS]

