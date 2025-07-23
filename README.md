# 📄 get_next_line

> Proyecto de la escuela 42 cuyo objetivo es implementar una función capaz de leer líneas completas desde un descriptor de archivo, una por llamada, de forma eficiente y controlada.

---

## 📌 Descripción

`get_next_line` es un proyecto diseñado para desarrollar una función que **devuelva una línea completa de un archivo** cada vez que es llamada, manteniendo su estado entre llamadas consecutivas. La línea se considera terminada cuando se encuentra un salto de línea (`\n`) o se alcanza el final del archivo.

Este ejercicio entrena el manejo de:

- Lectura controlada con `read()`
- Manipulación dinámica de memoria
- Manejo de buffers
- Gestión de múltiples descriptores de archivo
- Control de memoria y fugas

---

## 📚 Función principal

```c
char *get_next_line(int fd);
