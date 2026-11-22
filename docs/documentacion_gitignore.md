
"DOCUMENTACIÓN DEL ARCHIVO .gitignore"
" El archivo .gitignore está configurado para ser utilizado por Git para especificar los archivos y directorios que deben ser excluidos de un seguimiento de versiones de un repositorio. En los proyectos desarrollados con python, nos ayuda a evitar agregar archivos temporales cachés entornos virtuales configuraciones locales y demás elementos que no sean necesarios para poder compartir el código fuente."

"2. OBJETIVO 
El objetivo es documentar la configuración del .gitignore qué utilizamos en el anterior proyecto, así poder identificar las principales reglas de exclusión de archivos y directorios manteniendo un propósito para organizar el repositorio y facilitarnos el trabajo colaborativo y pues obviamente también proteger la información que se debe publicar"

"3. DESCRIPCIÓN DEL ARCHIVO 
El archivo .gitignore nos muestra las reglas que permiten a Git ignorar diferentes archivos y carpetas. Pero estas reglas se organizan en diferentes categorías dependiendo las herramientas, los frameworks y todos los procesos utilizados para el desarrollo del proyecto python.!

"4. ARCHIVOS COMPILADOS DE PYTHON 
Aquí excluimos los archivos que se generan automáticamente durante la ejecución del programa y la compilación estos son _pycache/,*.pyc, *.pyc y y otros archivos compilados. Esto nos evita el almacenamiento de archivos que puedan generarse automáticamente."

"5. DISTRIBUCIÓN Y EMPAQUETADO 
Se evitan o se excluyen los directorios y archivos generados durante la construcción instalación y distribución de paquetes, como es build/,dist/,*.egg y *.egg-info/."

"6. PRUEBAS Y COBERTURAS DEL CÓDIGO 
También se evitan archivos y carpetas generados por herramientas de pruebas y análisis de cobertura cómo lo es: .pytest_cache/,.coversge,htmlcov/ y coversge.xml"

"7. FRAMEWORKS Y HERRAMIENTAS 
Este archivo incluye algunas reglas para excluir datos y configuraciones locales de herramientas y frameworks como Django, flaks, scrapy, celery, redis, rabbitMQ, activeMQ, Júpyter notebook, spyder, pycharm, visual studio Code, Ruff, marimo y streamlit."

"8. ENTORNOS VIRTUALES 
p evitamos directorios y archivos asociados con entornos virtuales, cómo .venv/, venv/, env/ y ENV/. LO QUE NOS PERMITE QUE CADA UNO DE LOS COLABORADORES PUEDA CONFIRMAR SU PROPIO ENTORNO DE DESARROLLO"

"9. ARCHIVOS DE CONFIGURACIÓN Y DATOS SENSIBLES 
Evitamos todos los archivos que puedan tener información privada o configuraciones locales, como  .env, .pypirc y .streamlit/secretos.toml. estas reglas nos ayudan a prevenir la publicación errónea o accidental de las credenciales contraseñas y los diferentes accesos directos que podamos tener."

"10. LOS CACHÉS Y ARCHIVOS TEMPORALES 
Evitamos todos los directorios de caché archivos de depuración los registros de ejecución y otros elementos temporales generados por la herramienta de desarrollo."

"11. LA IMPORTANCIA DEL ARCHIVO .gitignore
El archivo .gitignore nos permite mantener nuestro repositorio limpio organizado y con los archivos necesarios para desarrollar nuestro proyecto correctamente Además nos facilita demasiado nuestro trabajo colaborativo no reduce los archivos innecesarios y nos ayuda a contribuir a la protección de toda la información privada que tengamos."

"12. CONCLUSIONES 
El archivo .gitignore es una herramienta bastante importante para el desarrollo del software de python y también en la gestión de repositorios mediante Git. La utilización de este nos ayuda a incluir archivos temporales configuraciones locales entornos visuales y otros elementos que no deben formar parte de las versiones de nuestro archivo. De la misma manera esto favorece a tener una mejor organización la seguridad un mantenimiento y una colaboración en los diferentes proyectos de software."

Realizado por: 
Sergio Alejandro Cely Carrillo 

Joan Sebastian Martínez Atehortua

Laura Daniela Díaz Guerrero 

Código: 213023A_  2204







