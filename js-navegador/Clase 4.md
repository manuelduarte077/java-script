-   Objeto window
-   Objetos
    -   console
    -   navigator
    -   location
    -   history
-   Métodos
    -   alert(message)
    -   confirm(message)
    -   prompt(message)
    -   open()
        "https://developer.mozilla.org/es/docs/Web/API/Window/open"
    -   close()
-   Objeto location
-   Propiedades
    -   href "url actual, se puede cambiar para cambiar la pagina
        actual"
    -   host "dominio:puerto"
    -   hostname "dominio"
    -   port "puerto"
    -   protocol "protocolo (http, https)"
    -   origin "protocolo + dominio"
    -   hash "\#"
    -   pathname "ruta interna luego del dominio"
-   Métodos
    -   reload()
    -   assign(url)
    -   replace(url) "cambia la página actual sin guardar en history"
-   Objeto history
-   Propiedades
    -   length "Cantidad de elementos, incluye la página actual"
-   Métodos
    -   back()
    -   forward()
    -   go(position) "-1 back, 1 forward"
-   Objeto navigator
-   Detectar navegador "No es buena idea, es 90's - 2000's style"
-   Detectar características
    -   CSS "@supports
        https://ed.team/blog/css-si-tiene-condicionales-y-deberias-estar-usandolas"
    -   JavaScript "operador in"
    -   Modernizr "https://modernizr.com/"
-   Timers
-   setTimeout(callback,ms)
-   setInterval(callback,ms)
    -   clearInterval(interval)
-   Date
-   Instanciar
    -   new Date()
    -   new Date(year,month,day) "meses de 0 a 11"
    -   new Date(year,month,day,hours,minutes,seconds)
    -   new Date(string)
-   Métodos
    -   getFullYear()
    -   getMinutes()
    -   getSeconds()
    -   getDate()
    -   getDay()
    -   getMonth()
    -   getTime() "milisegundos desde el 1 de enero de 1970"
    -   getTimezoneOffset()
-   Ejercicio cuenta regresiva
    "https://www.youtube.com/watch?v=ZbF5qomB8XM"

