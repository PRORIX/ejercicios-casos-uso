# ejercicios-casos-uso

## Biblioteca

### Actores

|  Actor | Usuario |
|---|---|
| Descripción  | Usuario de la biblioteca  |
| Características  | _Características que describen al actor_ |
| Relaciones |   |
| Referencias | Buscar libro, pedir prestado un libro, devolver libro |   
|  Notas |  _Notas adicionales_ |
| Autor  | prorix |
|Fecha | 5.11.24 |

|  Actor | Bibliotecario |
|---|---|
| Descripción  | Bibliotecario que gestiona la biblioteca  |
| Características  | _Características que describen al actor_ |
| Relaciones |   |
| Referencias | Gestionar inventario de libros, registrar préstamos |   
|  Notas |  _Notas adicionales_ |
| Autor  | prorix |
|Fecha | 5.11.24 |


### Casos de uso

|  Caso de Uso	CU | Buscar libro  |
  |---|---|
  | Fuentes  | _Documento que sustenta el caso de uso_  |
  | Actor  | Usuario |
  | Descripción | Buscar un libro en la lista  |
  | Flujo básico | 1. Acceder a la barra de búsqueda, 2. Escribir el libro a buscar, 3. Hacer CLIC en "buscar. |
  | Pre-condiciones | Ser un usuario de la biblioteca  |  
  | Post-condiciones  | Aparecen los libros relacionados  |  
  |  Requerimientos | Estar registrado en la biblioteca  |
  |  Notas |  _Notas adicionales_ |
  | Autor  | prorix |
  |Fecha | 5.11.24 |

  |  Caso de Uso	CU | Pedir prestado un libro  |
  |---|---|
  | Fuentes  | _Documento que sustenta el caso de uso_  |
  | Actor  | Usuario |
  | Descripción | Pedir un libro que haya en la biblioteca  |
  | Flujo básico | 1. Buscar el libro, 2. Solicitar el préstamo. |
  | Pre-condiciones | Buscar y acceder al libro  |  
  | Post-condiciones  | Se realiza la solicitud  |  
  |  Requerimientos | Estar registrado en la biblioteca, que haya disponibilidad del libro  |
  |  Notas |  _Notas adicionales_ |
  | Autor  | prorix |
  |Fecha | 5.11.24 |

  |  Caso de Uso	CU | Devolver libro  |
  |---|---|
  | Fuentes  | _Documento que sustenta el caso de uso_  |
  | Actor  | Usuario |
  | Descripción | Devolver un libro de la biblioteca que se haya prestado  |
  | Flujo básico | 1. Llevar el libro a la biblioteca, 2. Devolverlo. |
  | Pre-condiciones | Llevar el libro  |  
  | Post-condiciones  | Se completa la devolución  |  
  |  Requerimientos | Estar registrado en la biblioteca, haber solicitado el libro previamente  |
  |  Notas |  _Notas adicionales_ |
  | Autor  | prorix |
  |Fecha | 5.11.24 |

  |  Caso de Uso	CU | Gestionar inventario de libros  |
  |---|---|
  | Fuentes  | _Documento que sustenta el caso de uso_  |
  | Actor  | Bibliotecario |
  | Descripción | Se gestiona el inventario de la biblioteca  |
  | Flujo básico | 1. Acceder al inventario, 2. Realizar la gestión. |
  | Pre-condiciones | Necesitar realizar una gestión  |  
  | Post-condiciones  | Se aplica la gestión |  
  |  Requerimientos | Ser un bibliotecario con permisos  |
  |  Notas |  _Notas adicionales_ |
  | Autor  | prorix |
  |Fecha | 5.11.24 |

  |  Caso de Uso	CU | Registrar préstamos  |
  |---|---|
  | Fuentes  | _Documento que sustenta el caso de uso_  |
  | Actor  | Bibliotecario |
  | Descripción | Registrar préstamos de libros  |
  | Flujo básico | 1. Iniciar préstamo, 2. Aportar los datos, 3. Aplicar. |
  | Pre-condiciones | Usuario solicita préstamo  |  
  | Post-condiciones  | Se realiza la solicitud  |  
  |  Requerimientos | Un usuario necesita un préstamo, hay disponibilidad del libro  |
  |  Notas |  _Notas adicionales_ |
  | Autor  | prorix |
  |Fecha | 5.11.24 |
