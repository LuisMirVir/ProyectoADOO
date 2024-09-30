# Gestión de Biblioteca
## Descripción
Este sistema tiene como objetivo gestionar de manera eficiente los libros y usuarios de una biblioteca.
Se diseñará en torno a 3 clases principales: Usuario (Ej, Estudiante y bibliotecario), Libro, y Préstamo.
# Primer propuesta de clases y atributos

## Clases y Atributos:

### 1. Usuario
#### 1.1 Atributos:
- **nombre**: Nombre completo del usuario.
- **edad**: Edad del usuario.
- **contacto**: Información de contacto (teléfono, correo electrónico).
- **idUsuario**: Número identificador único del usuario.

#### 1.2 Métodos:
- **CRUD usuario**

---

### 2. Libro
#### 2.1 Atributos:
- **titulo**: Título del libro.
- **autor**: Autor del libro.
- **edicion**: Edición del libro.
- **año**: Año de publicación.
- **ISBN**: ISBN del libro.
- **cantidad**: Cantidad de ejemplares disponibles.
- **disponibilidad**: Booleano que indica si hay ejemplares disponibles para préstamo.
- **estado**: Fecha límite de devolución.

#### 2.2 Métodos:
- **CRUD libros**
- **buscarLibroPorISBN()**: Buscar un libro específico utilizando su identificador.

---

### 3. Préstamo
#### 3.1 Atributos:
- **idPrestamo**: Identificador único del préstamo.
- **usuario**: Referencia al usuario que realiza el préstamo.
- **libro**: Referencia al libro prestado.
- **fechaPrestamo**: Fecha en que se realizó el préstamo.
- **fechaDevolucion**: Fecha límite para la devolución.

#### 3.2 Métodos:
- **realizarPrestamo()**: Procesar un préstamo de un libro a un usuario.
- **devolverLibro()**: Gestionar la devolución de un libro.

# PENDIENTE CONFIRMACIÓN DE APROBADO
#### Luis Miranda Viramontes
