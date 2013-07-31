actas_votaciones
================

Este repositorio contiene las Actas de Votaciones Nominales de la HCDN organizadas por períodos.

PDF
===

En el directorio 'pdf' se encuentran las siguientes actas:

* Actas en PDF de texto desde el año 2001 (Período 119) en adelante.
* Actas en PDF de imágen (necesitan OCR) de los años 1999 y 2000.

JSON
====
En el directorio 'json' se encuentran los datos extraidos de las actas y almacenados en archivos JSON con la siguiente estructura:

    {
    "periodo": 131,
    "tipo_periodo": "Período Ordinario",
    "sesion": 1,
    "tipo_sesion": "Sesión de Tablas",
    "reunion": 1,
    "tipo_reunion": "Reunión"

    "titulo": "Pedido de Licencia del Sr. Diputado SABBATELLA, Martín.-",

    "acta": 1,
    "version": "Ult.Mod.Ver 2",
    "fecha": "13/03/2013",
    "hora": "14:50",

    "base_mayoria": "Votos Emitidos",
    "tipo_mayoria": "Más de la mitad",
    "quorum": "Más de la mitad",

    "miembros": 257,

    "resultado": "AFIRMATIVO",

    "presidente": "DOMINGUEZ, Julián Andrés",

    "observaciones": "Pedido de Licencia del Sr. Diputado SABBATELLA, Martín desde el 01 de Marzo de 2013 hasta el 09 de Diciembre de 2013.-\n",

    "votos": [
        ["ABDALA de MATARAZZO, Norma Amanda", "Frente Cívico por Santiago", "Santiago del Estero", "AFIRMATIVO"],
        ["ALBRIEU, Oscar Edmundo Nicolas", "Frente para la Victoria - PJ", "Rio Negro", "AFIRMATIVO"],
        ...
        ["YOMA, Jorge Raul", "Frente para la Victoria - PJ", "La Rioja", "AUSENTE"]
    ],
    }


Aclaración
==========

Las actas fueron descargadas del [sitio oficial de la HCDN](http://www.diputados.gov.ar/secadmin/ds_electronicos/actas_votacion-portada.html).

Según se informa dicho sitio, la información es de dominio público y puede ser utilizada libremente citando la fuente.
