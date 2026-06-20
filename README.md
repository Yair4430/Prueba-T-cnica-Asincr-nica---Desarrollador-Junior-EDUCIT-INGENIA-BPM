# Prueba-T-cnica-Asincr-nica---Desarrollador-Junior-EDUCIT-INGENIA-BPM

1. El error numero uno era que la clase entre el boton en el html y el css estban mal nombrados, por eso no se tomaban los estilos.

    - en el css estaba nombrada la clase como " .btn-primery "
    - y en el componente button del HTML la clase esta nombrada como class="btn-primary" 

como solucion cambie la "e" por la "a" del css para dejarlo como en la clase del html 

2. El consumo de la API era correcto, pero las propiedades utilizadas para renderizar los datos no coincidían con la estructura real del JSON. 

    - Se reemplazo "user.full_name" por "user.name"
    - Se remplazo "user.email_address" por "user.email"
    
Ya con esa solucion logro  mostrar correctamente la información de los usuarios.

3. 
    - Había un error porque se intentaba insertar 2 columnas con 1 valor.
    - Se corrigió usando dos parámetros, uno para los nombres y otro para los correos.
    - Se utilizaron parámetros diferentes para evitar vulnerabilidades de SQL.

4. Se implementó una funcionalidad de búsqueda en tiempo real para filtrar usuarios por nombre sin necesidad de recargar la página.
