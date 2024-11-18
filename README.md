# Taller-de-Pseint
14 Ejercicio realizados con Pseudocodigo

Algoritmo Taller
	Definir s Como Cadena
	Definir b_t, a_t, calcular1, d1_2, d2_2, sumar, d1_3, d2_3,d3_2, d3_3, d4_3, d1_4, d2_4, d3_4, d4_4, d5_4, sumar_4, restar1_4_4, restar2_4, multiplicar_4, division_4, gc,   gf, ac, ac_6, ar, ba, ar_7, dm, dmr, r_8, bm, bmr, ar_9, r_9, ac_10, pi_10, r_10, dn1_11, pdn_11, r_11, precio, vendedor, impuesto, r_14 Como Real
	Escribir '1. Encontrar el area de un triangulo'
	Escribir '2. Sumar 3 valores'
	Escribir '3. Leer 4 valores y sumarlos'
	Escribir '4. Leer 5 valores '
	Escribir '5. leer un valor correspodiente a la temperatura en grados centigrados'
	Escribir '6. Encontrar el area de un cuadrado: '
	Escribir '7. Encontrar el area rectangulada'
	Escribir '8. Encontrar el area del rombo'
	Escribir '9. Encontrar el area de un trapecio'
	Escribir '10. Encontrar el area de un circulo'
	Escribir '11. Encontrar el 10% de un valor'
	Escribir '12. Imprimir todas las converiones'
	Escribir '13. Pesos colombianos a Dolares'
	Escribir '14. Resolver texto'
	Escribir 'Selecciona un ejercicio '
	Leer s;
	Si s="1" Entonces
		Escribir 'Ingresa la base del triangulo: '
		Leer b_t
		Escribir 'Ingresa la altura del triangulo: '
		Leer a_t
		calcular1 <- (b_t*a_t)/2
		Escribir 'los datos ingresados son: '
		Escribir 'Base: ', b_t
		Escribir 'Altura: ', a_t
		Escribir 'El area seria ', calcular1, ' Unidades'
	SiNo
		Si s='2' Entonces
			Escribir 'Ingresa los datos que quieras sumar'
			Escribir 'Dato 1: '
			Leer d1_2
			Escribir 'Dato 2: '
			Leer d2_2
			Escribir "Dato 3: "
			Leer d3_2;
			sumar <- d1_2+d2_2+d3_2
			Escribir 'Datos ingresados: '
			Escribir d1_2
			Escribir d2_2
			Escribir d3_3
			Escribir 'El resultado es ', sumar
		SiNo
			Si s='3' Entonces
				Escribir 'Ingresa 4 Datos para sumarlos'
				Escribir 'Dato1: '
				Leer d1_3
				Escribir 'Dato2: '
				Leer d2_3
				Escribir 'Dato3: '
				Leer d3_3
				Escribir 'Dato4: '
				Leer d4_3
				sumar_3 <- d1_3+d2_3+d3_3+d4_3
				Escribir 'datos ingresados: ', d1_3, ' ', d2_3, ' ', d3_3, ' ', d4_3
				Escribir 'El resultado es: ', sumar_3
			SiNo
				Si s='4' Entonces
					Escribir 'Dato1: '
					Leer d1_4
					Escribir 'Dato2: '
					Leer d2_4
					Escribir 'Dato3: '
					Leer d3_4
					Escribir 'Dato4: '
					Leer d4_4
					Escribir 'Dato5: '
					Leer d5_4
					sumar_4 <- d1_4+d2_4+d3_4+d4_4+d5_4
					restar1_4 <- sumar_4-(d1_4+d2_4+d3_4)
					restar2_4 <- sumar_4-(d4_4+d5_4)
					multiplicar_4 <- restar1_4*restar2_4
					division_4 <- sumar_4/multiplicar_4
					Escribir 'El resultado de la suma: ', sumar_4
					Escribir 'Resta de los 3 primeros datos: ', restar1_4
					Escribir 'Resta de los 2 ultimos datos: ', restar2_4
					Escribir 'Multiplicacion de la restas: ', multiplicar_4
					Escribir 'Division entre la suma y multiplicacion: ', division_4
				SiNo
					Si s='5' Entonces
						Leer gc
						gf <- (gc*9/5)+32
						Escribir 'Cuantos grados centigrados desea convertir a fahrenheit: '
						Escribir 'Resultado a Fahrenheit: ', gf
						Escribir 'Grados Centigrados: ', gc
					SiNo
						Si s='6' Entonces
							Escribir 'Medida del cuadrado: (Lado)'
							Leer ac
							ac_6 <- ac*ac
							Escribir 'El area del cuadrado es: ', ac_6
						SiNo
							Si s='7' Entonces
								Escribir 'Medida del rectangulo (Area): '
								Leer ar
								Escribir 'Medida del rectangulo (Base): '
								Leer ba
								ar_7 <- ba*ar
								Escribir 'El area del rectangulo es: ', ar_7
							SiNo
								Si s='8' Entonces
									Escribir 'Medida del rombo (Diagonal Menor): '			
									Leer dm
									Escribir 'Medida del rombo (Diagonal Mayor): '
									Leer dmr
									r_8 <- (dm*dmr)/2
									Escribir 'El area del rombo es: ', r_8
								SiNo
									Si s='9' Entonces
										Escribir 'Medida del trapecio (Base Menor): '
										Leer bm
										Escribir 'Medida del rombo (Base Mayor): '
										Leer bmr
										Escribir 'Medida del rombo (Altura): '
										Leer ar_9
										r_9 <- (((bm+bmr)/2)*ar_9)
										Escribir 'El area del rombo es: ', r_9
									SiNo
										Si s='10' Entonces
											Escribir 'Area del circulo: '			
											Leer ac_10
											pi_10 <- 3.1416
											r_10 <- pi_10*ac_10^2
											Escribir 'El area del circulo es: ', r_10
										SiNo
											si s="11" Entonces			
												Escribir "Escribe un dato numerico: ";
												leer dn1_11;
												Escribir "Cuanto porcentaje deseas obtener del dato numerico?: ";
												Leer pdn_11;
												r_11 = (pdn_11/dn1_11)*100
												Escribir "El porcentaje de ",dn1_11, " es ",r_11,"%";
											SiNo
												si s="12" Entonces
													Escribir "Ingresa los metros que desas convertir: ";
													Leer m1_12;
													k = m1_12/1000
													h = m1_12/100
													d = m1_12/10
													de2 = m1_12*10
													c = m1_12*100
													m = m1_12*1000
													Escribir "Aqui esta el resultado en 6 converciones";
													Escribir k
													Escribir h
													Escribir d
													Escribir de2
													Escribir c
													Escribir m
												SiNo
													si s= "13" Entonces
														Escribir "Cuantos pesos colombianos desea convertir a dolares?: ";
														leer pd;
														r_13 = pd*0.00022
														Escribir "La convercion es: ",r_13," Dolares";
													SiNo
														si s="14" Entonces		
															precio = 35000000
															vendedor = precio*0.12
															impuesto = precio*0.06
															r_14 = precio+vendedor+impuesto
															Escribir "En total seria: ",r_14," Pesos" ;
														FinSi
													FinSi
												FinSi
											FinSi
										FinSi
									FinSi
								FinSi
							FinSi
						FinSi
					FinSi
				FinSi
			FinSi
		FinSi
	FinSi
FinAlgoritmo
