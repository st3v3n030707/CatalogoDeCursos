Como ejecutar la APP( Pasos y Comandos ) 
1. Clonar el Repositorio
Descarga el código fuente de la aplicación usando git clone y navega hasta el directorio del proyecto.
git clone [URL_DE_TU_REPOSITORIO]
cd [NOMBRE_DEL_DIRECTORIO]
2.Instalar Dependencias
Instalar todas las bibliotecas y paquetes necesarios.
npm install
3.Ejecutar la Aplicación
Inicia la aplicación en modo de desarrollo.
npm run dev
4.Acceder a la Aplicación
Una vez que el proceso anterior finalice, la aplicación estará disponible en tu navegador. Abre la siguiente URL:

http://localhost:[PUERTO]

estructura, lista, filtro, paginacion
Esta aplicación ha logrado implementar las siguientes funcionalidades clave:

Estructura de la Interfaz: Se ha definido una estructura modular y organizada que separa los componentes de la interfaz de usuario (UI), la lógica de negocio y la gestión de datos, facilitando el mantenimiento y la escalabilidad.

Visualización de Lista: Muestra una lista de elementos de manera clara y organizada.

Funcionalidad de Filtro: Permite a los usuarios filtrar la lista de elementos en función de múltiples criterios (ej: por nombre, estado, categoría, etc.), mejorando la experiencia de búsqueda de información específica.

Paginación: Implementa paginación para manejar grandes volúmenes de datos de forma eficiente, limitando la cantidad de elementos mostrados por página y ofreciendo navegación entre ellas.
