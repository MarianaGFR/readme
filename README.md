
# Big Game Survey 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE) 

# Sobre o projeto

Nesta iniciativa, criei uma estação meteorológica com arduino que permite monitorar as variáveis de temperatura e umidade de um ambiente, exibir estes dados em um display LCD e também em seu smartphone via Bluetooth.

A estação meteorológica com Arduino não apenas monitora as variáveis essenciais de temperatura e umidade de um ambiente, mas também proporciona uma experiência moderna e prática de visualização de dados via Bluetooth para celulares android.  

Meu projeto oferece uma solução acessível e eficaz para manter um olho constante nas condições climáticas locais. Ao exibir esses dados em um display LCD, tornamos a informação instantaneamente acessível para qualquer pessoa em seu ambiente. 

## Layout app mobile
![app mobile](https://github.com/MarianaGFR/readme/assets/132612810/1cfc9a05-ec8e-499d-8222-18b81d94c225)

# Tecnologias utilizadas
## Linguagem de Programação
- C++
  
## Blibiotecas
- LiquidCrystal.h
- DHT.h
- SoftwareSerial.h

# Como executar o projeto

## Preparação dos Componentes
Certifique-se de ter os componentes necessários, incluindo:

- Um Arduino (ou placa compatível).
- Um sensor de temperatura e umidade DHT11.
- Um display de LCD compatível com o controlador HD44780.
- Uma placa Bluetooth (se desejar transmitir os dados para um dispositivo externo via Bluetooth).

## Montagem do Circuito
- Conecte o sensor DHT11 ao Arduino de acordo com as especificações do código. Geralmente, o sensor é conectado ao pino analógico A5.
- Conecte o display de LCD ao Arduino conforme especificado no código, conectando os pinos RS, EN, D4, D5, D6 e D7.
- Se estiver usando uma placa Bluetooth, conecte-a ao Arduino conforme necessário.

## Montagem e conexão
![montagem e conexao estacao](https://github.com/MarianaGFR/readme/assets/132612810/cb8c09d3-97f5-48b4-b54a-f17b5196bba7)

## Configuração do Ambiente de Desenvolvimento
- Certifique-se de ter o Arduino IDE instalado em seu computador.
- Instale as bibliotecas necessárias para o sensor DHT11 e o display de LCD. Você pode fazer isso através do Arduino IDE, acessando o menu "Sketch" > "Include Library" > "Manage Libraries..." e procurando pelas bibliotecas necessárias.

## Upload do Código
- Abra o código no Arduino IDE.
- Selecione a placa Arduino correta e a porta serial adequada nas configurações do Arduino IDE.
- Faça o upload do código para o Arduino.

## Teste e Monitoramento
- Após o upload do código, abra o monitor serial no Arduino IDE para visualizar os dados de temperatura e umidade sendo lidos pelo sensor DHT11.
- Você também pode verificar se o display de LCD está exibindo corretamente as informações de temperatura e umidade.

## Opcional: Transmissão de Dados via Bluetooth
- Se você conectou uma placa Bluetooth, você pode utilizar um aplicativo compatível em seu dispositivo móvel para receber os dados transmitidos pelo Arduino via Bluetooth.

```

# Autor

Mariana Gonçalves de Freitas Ribeiro

marianagfreitasr@gmail.com
