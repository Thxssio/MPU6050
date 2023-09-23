<h1 align="center">MPU6050</h1>


***WebServer MPU6050 and ESP32***

- [x] Adafruit Unified Sensor
- [x] Adafruit Bus IO
- [x] Adafruit MPU6050
- [x] [ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer/archive/master.zip)
- [x] [AsyncTCP](https://github.com/me-no-dev/AsyncTCP/archive/master.zip)

***PlatiformIO:***
```
lib_deps =   adafruit/Adafruit MPU6050 @ ^2.0.3
    adafruit/Adafruit Unified Sensor @ ^1.1.4
    me-no-dev/ESP Async WebServer @ ^1.2.3
    arduino-libraries/Arduino_JSON @ 0.1.0
```

`
Clique no ícone PIO na barra lateral esquerda. As tarefas do projeto devem ser abertas.`
`Selecione env:esp32doit-devkit-v1 (pode ser um pouco diferente dependendo da placa que você está usando).`
`Expanda o menu Plataforma .`
`Selecione Construir imagem do sistema de arquivos.`
`Por fim, clique em Carregar imagem do sistema de arquivos .`
##
 ***ESP32 Filesystem Uploader [Download](https://github.com/me-no-dev/arduino-esp32fs-plugin/releases/)***

 `Encontre a localização do seu Sketchbook. No seu Arduino IDE, vá em Arquivo > Preferências e verifique a localização do seu Sketchbook. No meu caso, está no seguinte caminho:C:\Usuários\thxssio\Documentos\Arduino`
 
 `Vá para o local e crie uma pasta de ferramentas`
 `Descompacte a pasta .zip baixada . Abra-o e copie a pasta ESP32FS para a pasta de ferramentas que você criou na etapa anterior. Você deve ter uma estrutura de pastas semelhante: /tools/ESP32FS/tool/esp32fs.jar`

 `Por fim, reinicie seu Arduino IDE.`
`Para verificar se o plugin foi instalado com sucesso, abra seu Arduino IDE. Selecione sua placa ESP32, vá em Ferramentas e verifique se você tem a opção “ ESP32 Sketch Data Upload “.`



 
