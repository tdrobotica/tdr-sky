# tdr-sky

	LIBRERIA SKYBOTS V0.1
	Desarrollado por Skybots y tdrobotica para controlar los circuitos y robots de forma simple
	y didactica, contiene una serie de funciones que facilitan el funcionamiento de los circuitos
	la librería va conbinada con los ejemplos de Arduino.
	FUNCIONES
	-----------------
		* Control del Dirver de Motores.
		* Lectura del botón.
		* Lectura del estado de la bateria (En los que esta disponible).
		* Lectura del sensor de linea (En los que esta disponible).
	-----------------

Wizard es una tarjeta electronica diseñada para robotica general
contiene las siguientes conexiones:
  *Entradas
    -Boton D14
    -Sensor Bateria A1
    - 7 pines digitales (A11,D16,A0,A9,A6,D7,A8), los A puenden ser analogos
    -Receptor D1 TX
  *Salidas
    -Motor MA(D5-D6)
    -Motor MB(D10-D11)
    -Parlante D0 RX

Linebot es un robot Seguidor de lineas educativo.
contiene las siguientes conexiones:
  *Entradas
    -1 Boton D12
    -8 sensores de linea Digitales D4, D7, D8, D16, D15, D19,D18
    -1 Led-On habilitador de los sensores D14
  *Salidas
    -1 Motor MA(D5-D6)
    -1 Motor MB(D10-D11)
    -1 LED D13
  *Comunicacion
    -1 Serial Rx D0, Tx D1
    -1 I2C SDA D2, SCL D3