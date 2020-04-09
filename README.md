# Dudas Covid-19

DudasCovid es una iniciativa con la misión de combatir la falta de información que presenta la población respecto al COVID-19. Contar con una fuente de información evita graves problemas, que van desde el pánico, hasta la falta de medidas sanitarias adecuadas. #dudascovid

La información presentada en la base de conocimientos es verificada y alimentada por personas voluntarias, quienes cuentan con conocimiento y experiencia en el área de la salud, y que amablemente donan su tiempo para mantener a la población correctamente informada.

Si tienes un área de especialidad afín y deseas sumarte a ésta iniciativa, puedes ingresar al siguiente link: https://dudascovid.com/expert/all.

# Pagina web

Puedes visitar https://dudascovid.com para más detalle del proyecto.

# Publicación de la información *Dataset*

### Reportes diarios (covid_19_daily_reports)
Esta carpeta contiene las dudas y respuestas de los expertos que son recolectados por día.

### Nombre de archivos

MM-DD-YYYY.json

Ejemplo del esquema de información

    {  
    "question": {  
        "text": "¿Qué es el coronavirus?",  
        "info": {  
            "age": null,  
            "gender": "Male",  
            "country": "MX",  
            "city": "MEX",  
            "poll": [  
                {  
                    "question": "Después de leer esta información ¿Qué tan nervioso, ansioso, o abrumado te sientes?",  
                    "answer": "quite a bit",  
                    "id": "overwhelmedFeeling"  
                }  
            ]  
        },  
        "answer": [  
            {  
                "text": "Ejemplo de respuesta",  
                "authorInfo": {},  
                "isPublic": false,  
                "createdAt": "2020-04-07T22:32:21.263+00:00",  
                "likes": 0  
            },  
            {  
                "text": "Ejemplo de respuesta 2",  
                "authorInfo": {  
                    "institute": "UNAM",  
                    "experience": 20,  
                    "specialty": "Medicina del deporte"  
                },  
                "isPublic": true,  
                "createdAt": "2020-04-07T22:32:21.263+00:00",  
                "likes": 5 
            },
            ...
        ]  
    }  
}

### Frecuencia de actualización
Archivos a partir del 13 de abril de 2020 estarán expuestos en **covid_19_daily_report** y se actualizara una vez al día al rededor de las 23:59 (UTC).
Archivos con una semana de haber estado expuesto, pasarán a la carpeta **archived_data**

### API publica para obtener en tiempo real los últimos resultados (proximamente)

https://dudascovid.com/api/all
