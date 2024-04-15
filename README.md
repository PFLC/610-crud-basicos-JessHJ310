# Qué es el CRUD
En informática, CRUD es el acrónimo de "Crear, Leer, Actualizar y Borrar" (del original en inglés: Create, Read, Update and Delete), que se usa para referirse a las funciones básicas en bases de datos o la capa de persistencia en un software.

# Ejemplos de aplicaciones del CRUD

- **Aplicaciones de gestión de contenido**
- **Aplicaciones de comercio electrónico**
- **Sistemas de reservas**
- **Aplicaciones de redes sociales**
- **Aplicaciones de gestión de proyectos**

# Significado de las siglas CRUD

- **Create**
Esta fase se utiliza para crear un nuevo registro en la base. Para implementar la operación «Crear», es necesario proporcionar un formulario o una interfaz donde el usuario pueda ingresar los datos para el nuevo registro. Después de que el usuario envía los datos, se debe realizar una validación de los mismos y luego insertarlos en la base o en el sistema de almacenamiento.

- **Read**
Esta fase se utiliza para leer los datos de la base y mostrarlos al usuario. Para implementar la operación «Leer», se debe proporcionar una interfaz que permita al usuario buscar y recuperar los registros existentes. Esto puede lograrse mediante el uso de filtros de búsqueda y una lista de resultados. Cuando el usuario hace clic en un registro, se debe mostrar su información completa.

- **Update**
Esta fase se utiliza para actualizar los datos existentes en la base de datos. Para implementar la operación «Actualizar», es necesario proporcionar una interfaz para que el usuario pueda modificar los datos de un registro existente. Una vez que el usuario envía los datos actualizados, debe realizarse una validación de los mismos y luego actualizar el registro correspondiente en la base o en el sistema de almacenamiento.

- **Delete**
Esta fase se utiliza para eliminar un registro existente. Para implementar la operación «Eliminar», se debe proporcionar una interfaz que permita al usuario seleccionar un registro existente y confirmar su eliminación.
Después de la confirmación, se debe borrar el registro correspondiente de la base o sistema.

![image](https://github.com/PFLC/610-crud-basicos-JessHJ310/assets/113735007/7efedd5d-7704-4c3a-8628-c8c14c39eca3)


# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

# Conclusión
En resumen, el CRUD es una herramienta invaluable en el desarrollo de software para la gestión de datos, pero su eficacia depende de cómo se integre con otras prácticas de desarrollo y cómo se adapte a las necesidades específicas de cada proyecto.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

