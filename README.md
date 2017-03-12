# VeroBlck_Marlin

Setting parameter to Mechanics Parts built by Team MakerWelt.

## Reference

Firmware [Marlin](https://github.com/MarlinFirmware/Marlin) - release 
Software [mUVe 3D Printer](http://www.muve3d.net/press/supportsources/muve-1-software/)
Hardware [Arduino Mega 2560](https://www.arduino.cc/en/Main/arduinoBoardMega2560) 

### Features 

- LCD 16x2 working..
- Display Full Graphics working...
- Stepper Motor, Servo Motor and End Stop working...
- AutoLeveling working...

### Aditional Reference

- Support Generator [STL](https://www.nanodlp.com/forum/viewtopic.php?id=419)

- New Profile

Enjoy!!

## Primeros Pasos

### Verificar Comunicacion Arduino Mega con Raspberry 

1. Primero el LCD 16x2 debe mostrar la IP del modulo, luego ingresar en algun buscador (Chrome, Safari,etc).
2. Ahora debemos realizar la prueba de "Z calibration", para verificar si el motor de paso a paso esta activo para realizar el proceso de curado.
3. La pestana "Z calibration" --> primero hacer clic en "Motor OFF" luego "Motor ON", aqui observamos si el motor de paso se bloquea (Si el motor se "Bloquea" --> clic en "Auto_Home")(Si el motor no se "Bloquea" --> clic en "Setup" ir al recuadro "USB/Serial Port Path" dice "/dev/ttyACM0" aqui se debe probar con "/dev/ttyACM0" - "/dev/ttyACM1", el arduino cambia de port "Submit" o "teclado enter"). finalmente probar con el paso faltante de de "Auto_Home"
4. Ahora realizar la prueba con el Projector y el servo.

### Edit Profile

1. Primero ir a la pestana "profile", aqui utilizaremos el perfil de "XY 50" clic en "Edit"
2. Ahora vemos 2 posibles configuraciones "Burn-in Layers" y "Normal Layers", por la prueba estamos homogenizando las configuraciones.
3. "Layer Thickness" --> 20 micras    "Cure Time" --> 20 seconds
4. Nota: estos cambios en  "Burn-in Layers" y "Normal Layers" los mismos valores.








