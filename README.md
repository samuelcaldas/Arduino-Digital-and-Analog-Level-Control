# Sistema de Controle de Nível de Água

Este projeto implementa um sistema de controle de nível de água para um reservatório usando dois bombas e sensores digitais ou analógicos. O projeto usa um Arduino Uno e componentes eletrônicos simples. O sistema pode operar em dois modos: automático ou manual. No modo automático, o sistema controla o nível de água no reservatório ligando ou desligando as bombas de acordo com as leituras dos sensores. No modo manual, o usuário pode controlar as bombas diretamente pressionando botões.

![Esquemático do sistema](schematic.png)

*Esquemático do sistema*

![Projeto montado](project.jpg)

*Projeto montado*

## Como usar

Para usar este projeto, você precisa ter o Arduino IDE instalado no seu computador. Você também precisa ter os seguintes componentes:

- Arduino Uno
- Protoboard
- Fios jumper
- 2 bombas de água
- 2 LEDs vermelhos
- 2 LEDs verdes
- 2 resistores de 220 ohms
- 2 resistores de 10 kohms
- 1 chave seletora de modo
- 2 botões de controle
- 4 sensores de nível de água (digitais ou analógicos)

Siga os passos abaixo para montar o projeto:

1. Conecte os componentes eletrônicos de acordo com o esquemático.
2. Abra o arquivo `water_level_control.ino` no Arduino IDE.
3. Selecione a porta serial do seu Arduino e carregue o código.
4. Coloque o reservatório em um local seguro e encha-o com água até o nível desejado.
5. Ligue o Arduino e selecione o modo de operação do sistema usando a chave seletora.
6. Observe os LEDs e as bombas funcionando de acordo com o nível de água e os botões pressionados.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [License](LICENSE) para mais detalhes.
