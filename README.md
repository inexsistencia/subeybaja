subeybaja
=========

1. primer cambio: hecho por el usuario pablo-jimenez-olx 
seedito el archivo README.md y lo que se incorporo en el es esto que estas leyendo
(normal desde el editor sublime en en la compu del trabajo)

	#####comandos usados:

	1. git add README.md
	2. git commit -m "texto del mensaje"
	3. git push origin master

2. segundo paso crear un Branch:
en este paso voy a crear un branch llamado *rama_de_prueba*
y en el se comitearan estos cambios

	#####comandos usados:

	1. git branch rama_de_prueba (crea la nueba rama o branch)
	2. git branch (es para consultar cuales existen)
	3. git checkout *nombre del branch* (con esta orden podemos cambiar de un branch a otro en este caso la orden seria *git checkout rama_de_prueb*)
	> *Para crear una nueva rama y saltar a ella, en un solo paso, puedes utilizar el comando 'git checkout' con la opción '-b':*
	> git checkout -b iss53
	> [lik a help de branc en git](http://git-scm.com/book/es/Ramificaciones-en-Git-Procedimientos-b%C3%A1sicos-para-ramificar-y-fusionar)

3. paso para poder **mergear** no ya acia el fork original, sino entre ramas propias desde unarama propia hasta nuestro master (en este caso de nuestro branch rama_de_prueba, hacia nuestro master)