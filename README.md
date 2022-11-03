# Blog API

- Front: 
    - Obtener todas las publicaciónes
    - Obtener una en especifico
    - Obtener todas las categorias
    - Obtener todos los post de una categoria en especifico
    - Obtener todos los posts que he creado
    - Obtener todos los posts de un usuario en especifico
    - Podemos paginar los posts
    - Acciones de CRUD sobre Posts
    - Crear categorias 


```json
    {
        "total": 68,
        "prev": "localhost:9000/api/v1/posts?start=51&limit=60",
        "next": "localhost:9000/api/v1/posts?start=61&limit=68",
        "data": [
            {
                "id" : "f56cdc36-1323-4bc7-a9e0-5f4549510f33",
                "title" : "ejemplo",
                "content" : "lorem ipsum",
                "createdBy": {
                    "id" : "ba28075e-be58-4d69-b484-624c785748e0",
                    "name" : "Name",
                    "email" : "email@email.com"
                },
                    "category" :{
                    "id" :4,
                    "name" : "Tecnologia"
                }
            }
        ]
    }

``` 









