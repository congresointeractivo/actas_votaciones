actas_votaciones
================

Este repositorio contiene las Actas de las Votaciones Nominales y Numéricas de la HCDN organizadas por períodos. En los directorios 'csv' y 'json' se encuentra la información extraída de las actas: votación y encabezados.

PDF
===

En el directorio 'pdf' se encuentran las siguientes actas:

* Actas en PDF de texto desde el año 2001 (Período 119) en adelante.
* Actas en PDF de imágen (necesitan OCR) de los años 1999 y 2000.

CSV
====
En el directorio 'csv' se encuentran los datos de las VOTACIONES nominales extraidos de las actas y almacenados en archivos CSV con la siguiente estructura:

    APELLIDO, NOMBRE, PARTIDO, PROVINCIA, VOTO

Por ejemplo

    ACCAVALLO, Julio Cesar,FREPASO,Rio Negro,AFIRMATIVO

NOTA: El campo NOMBRE no fue separado del apellido durante el procesamiento por lo cual actualmente posee un espacio al inicio. En el ejemplo: " Julio Cesar".


ACLARACIÓN: En el directorio se encuentran los siguientes archivos con listados de actas:
 - VOTACIONES_ANULADAS.TXT se listan las actas que fueron posteriormente anuladas.
 - VOTACIONES_NUMERICAS.TXT se listan las actas que contienen votaciones numéricas (no nominales).
 - VOTACIONES_FALTANTES.TXT se listan las actas para las cuales todavía no se generaron los archivos CSV correspondientes. Por el momento no se han generado los CSV correspondientes a los períodos legislativos 117 y 118.


JSON
====
En el directorio 'json' se encuentran los datos de las VOTACIONES y de los ENCABEZADOS extraidos de las actas y almacenados en archivos JSON con la siguiente estructura:

    {
    "periodo": 131, "tipo_periodo": "Período Ordinario",
    "sesion": 1, "tipo_sesion": "Sesión de Tablas",
    "reunion": 1, "tipo_reunion": "Reunión"

    "titulo": "Pedido de Licencia del Sr. Diputado SABBATELLA, Martín.-",

    "acta": 1, "version": "Ult.Mod.Ver 2", "fecha": "13/03/2013", "hora": "14:50",

    "base_mayoria": "Votos Emitidos", "tipo_mayoria": "Más de la mitad", "quorum": "Más de la mitad",

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


NOTA: Actualmente sólo se cuentan con los datos de los períodos legislativos 129, 130 y 131.


Aclaración
==========

Las actas fueron descargadas del [sitio oficial de la HCDN](http://www.diputados.gov.ar/secadmin/ds_electronicos/actas_votacion-portada.html).

Según se informa dicho sitio, la información es de dominio público y puede ser utilizada libremente citando la fuente.
