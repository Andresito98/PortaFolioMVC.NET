# ProjectWebMVC


POSIBLES PROBLEMAS O PROBLEMAS QUE YA SABEMOS:

- PROBLEMA CON LOS ICONOS:
Tengo que investigar acerca de los iconos porque no aparecen.
Docu Bootstrap: https://getbootstrap.com/docs/5.0/extend/icons/
El enlace oficial es: https://icons8.com/icons/set/linkedin
Como opcional tambiene tiene FontAwesome: https://fontawesome.com/ que habría que ponerle el Nuget y a correr

- PROBLEMA CON RESPONSIVES:
    Si hay algun problema de dimensiones pueden ser los responsives:
     Pueden ser los container o container2 o sino buscar:
     @media (max-width: 575.98px) {
        .table-responsive-sm {
            overflow-x: auto;
            -webkit-overflow-scrolling: touch;
        }
    }
