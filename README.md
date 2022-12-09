# Mecatronica-2022-2023
Mecatrónica alcabmo URJC

## Comunicación con RemoteXY
Para la parte de comunicación del arduino con el telefono android encontré esta página https://remotexy.com/ que te dejaba con su aplicación
crearte una interfaz gráfica y te daba una blibioteca y un código de arduino para que pudiesemos integrarlo con la parte de los motores.

### Modulo HC-05
Teniamos que legir una forma de conectar el arduino UNO con el móvil asi que decidimos que lo mejor era el modulo HC-05 por que la comunicación iba
a ser complicada usando otra cosa que no sea bluetooht por el lugar donde ibamos a hacer la demonstración.

![image](https://user-images.githubusercontent.com/78978241/206696380-33818d58-fdee-473a-860b-28fe3d404cae.png)

Al principio pobre a hacer el setup en un arduino mega2560 pero por alguna razón no consegui hacer la conexion, luego probamos en el arduino UNO donde ibamos a hacer la práctica y parecia que daba el mismo resultado pero usando los pines digitales directamente en vez de los especificos de comunicación ya si que nos fue bien.

La interfaz que usaremos será una cosa como esta:

![image](https://user-images.githubusercontent.com/78978241/206697631-e23f1fa7-0f6d-4a10-987b-9390a1efcf95.png)

Asi podemos girar izquierdo, derecha, alante y atrás y nos abstraemos un pooc de los controles de tanque.

