# Ejercicio de Laboratorio: Sistema de Gestión de Inventario (SGI) - InkaRetail S.A.C.

Este módulo se centró en ejecutar y completar la documentación de pruebas para el sistema SGI de InkaRetail, abarcando los módulos de Autenticación (Login) y Registro de usuarios.

## Herramientas Utilizadas
* **Navegador Web:** Google Chrome / Mozilla Firefox (para pruebas manuales)
* **Gestión de Datos:** Google Sheets (para la matriz resumen)
* **Documentación Técnica:** Google Docs (para el detalle de casos paso a paso)
* **Control de Versiones:** Git y GitHub

## Matriz de Resumen del Entregable
A continuación se presenta la consolidación de los casos de prueba ejecutados (incluyendo los casos TC-003 al TC-008 completados en su totalidad):

| ID | Funcionalidad | Nombre del Caso | Técnica | Prioridad | Resultado Esperado (Resumen) | Estado | Enlace Documento Detallado |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **TC-001** | Login | Login exitoso | PE-Válida | Alta | Popup bienvenida + redirige a home | PASS | [Ver en Google Docs](LINK_AQUÍ) |
| **TC-002** | Login | Contraseña incorrecta | PE-Invalida | Alta | Error rojo, no accede | PASS | [Ver en Google Docs](LINK_AQUÍ) |
| **TC-003** | Login | Usuario no registrado | PE-Invalida | Alta | Mensaje 'usuario no encontrado' | PASS | [Ver en Google Docs](LINK_AQUÍ) |
| **TC-004** | Login | Campos vacíos | Edge Case | Media | Mensaje 'completa todos los campos' | PASS | [Ver en Google Docs](LINK_AQUÍ) |
| **TC-005** | Login | Email sin formato | Edge Case | Media | Mensaje 'formato inválido' | PASS | [Ver en Google Docs](LINK_AQUÍ) |
| **TC-006** | Registro | Registro exitoso | PE-Válida | Alta | Cuenta creada + popup bienvenida | PASS | [Ver en Google Docs](LINK_AQUÍ) |
| **TC-007** | Registro | Passwords distintos | PE-Invalida | Alta | Mensaje 'no coinciden' | PASS | [Ver en Google Docs](LINK_AQUÍ) |
| **TC-008** | Registro | Email duplicado | PE-Invalida | Alta | Mensaje 'ya registrado' | PASS | [Ver en Google Docs](LINK_AQUÍ) |

> **Nota de Entrega:** Las especificaciones extendidas de precondiciones, datos exactos de entrada y flujos de pasos secuenciales se encuentran centralizados en el documento de Google Docs accesible desde la última columna de la matriz.