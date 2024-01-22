
## Ejemplo de estructura API en PHP - MVC con Firebase Database para implementación en Vercel </p>

 

## Ejemplo de estructura JSON en la base de datos Firebase

    name-your-database
    ├── public              
    ├── private                 

- ```[public]``` -> Aquí cree carpetas/claves que contendrán datos que pueden ser públicos y a los que puede acceder cualquier usuario de Api.
- ```[private]``` -> Aquí cree las carpetas/claves que contendrán los datos privados.

### Example:

    name-your-database
    ├── public    
    │   └── posts  
    │   └── products  
    ├── private                
    │   └── users              
     

## Dependencias/Requerir
>Para producción, es necesario conectarse a Firebase
- [Firebase Admin SDK for PHP](https://firebase-php.readthedocs.io/en/5.x/)

   └── ```composer require kreait/firebase-php```

> Para el entorno de desarrollo, se requiere utilizar variables de entorno (.env)
- [PHP dotenv](https://github.com/EzeAlarcon/api-web-mvc.git)

   └── ```composer require vlucas/phpdotenv```