Algoritmo promedioDeNotas
	Escribir "El promedio de notas tiene un peso porcentual asi: nota uno 25%, nota dos 25%; nota tres 20% y nota cuatro 30%; debe obtener un promedio superior a tres para aprobar"
	
	//definir nuestras variables
	Escribir "Para conocer su promedio ingrese sus notas a continuacion"
	Definir notauno, notados, notatres,notacuatro, resultado Como real;
	Definir promedio Como REAL
	Escribir "ingrese su primera nota";
	leer notauno
	Escribir "ingrese su segunda nota";
	leer notados
	Escribir "ingrese su tercera nota";
	leer notatres
	Escribir "ingrese su cuarta nota";
	leer notacuatro
	promedio= (notauno*0.25+notados*0.25+notatres*0.20+notacuatro*0.30)
	escribir "el resultado del promedio es",  notauno*0.25+notados*0.25+notatres*0.20+notacuatro*0.30
	Si promedio> 3 Entonces
		Escribir "FELICITACIONES USTED APROBO"
	SiNo
		Escribir "USTED REPROBO, DEBE PRESENTAR NUEVAMENTE EXAMEN"
	Fin Si

