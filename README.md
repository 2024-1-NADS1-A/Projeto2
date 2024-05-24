# FECAP - Fundação de Comércio Álvares Penteado

<p align="center">
<a href= "https://www.fecap.br/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" alt="FECAP - Fundação de Comércio Álvares Penteado" border="0"></a>
</p>

# Sensor de Presença

## Tropa do Urso

## Integrantes: <a href="https://www.linkedin.com/in/caua-william-967295247/?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app/">Caua William</a>, <a href=https://www.linkedin.com/in/gabriel-orlandi-4b5ab22ab">Gabriel Orlandi Portes</a>, <a href="https://www.linkedin.com/in/guilherme-mendes-albuquerque-6a50b330a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">Guilherme Mendes Albuquerque</a> e <a href="https://www.linkedin.com/in/rafaela-coelho-bastos-7b8ba61b4/">Rafaela Coelho Bastos</a>

## Professores Orientadores: <a href="https://www.linkedin.com/in/victorbarq/">Victor Bruno Alexander Rosetti de Quiroz</a> e <a href="https://www.linkedin.com/in/adriano-valente-534576135/">Adriano Valente</a>
## Descrição

<p align="center">
<img src="imagens/WhatsApp Image 2024-05-24 at 09.32.27.jpeg" border="0">
  Projeto feito por: Cauã William Barbieri Brandão, Gabriel Orlandi Portes, Guilherme Mendes Albuquerque e Rafaela Coelho Bastos
 
</p>
<br><br>
Descrição do Projeto
<br><br>
<br><br>
Nosso projeto utiliza um sensor PIR (Passive Infrared) em conjunto com um ESP32 para detectar a presença de pessoas em uma residência e enviar notificações automáticas através do Telegram. Quando o sensor PIR detecta movimento, o ESP32 processa essa informação e envia uma mensagem instantânea via Telegram para um grupo ou contato específico, alertando sobre a presença de alguém no local. Este sistema é ideal para aumentar a segurança residencial, permitindo que os moradores sejam avisados em tempo real sobre qualquer movimentação suspeita ou entrada não autorizada, independentemente de onde estejam.
<br><br>
May the force be with you!
<br><br>

## 🛠 Estrutura de pastas

-Raiz<br>
|<br>
|-->documentos<br>
  &emsp;|-->antigos<br>
  &emsp;|Documentação.docx<br>
|-->executáveis<br>
  &emsp;|-->windows<br>
  &emsp;|-->android<br>
  &emsp;|-->HTML<br>
|-->imagens<br>
|-->src<br>
  &emsp;|-->Backend<br>
  &emsp;|-->Frontend<br>
|readme.md<br>

A pasta raiz contem dois arquivos que devem ser alterados:

<b>README.MD</b>: Arquivo que serve como guia e explicação geral sobre seu projeto. O mesmo que você está lendo agora.

Há também 4 pastas que seguem da seguinte forma:

<b>documentos</b>: Toda a documentação estará nesta pasta.

<b>executáveis</b>: Binários e executáveis do projeto devem estar nesta pasta.

<b>imagens</b>: Imagens do sistema

<b>src</b>: Pasta que contém o código fonte.

## 🛠 Equipamentos e Componentes:

<p>1. ESP32: Um microcontrolador com Wi-Fi e Bluetooth integrados.</p>
<p>2. Sensor PIR: Sensor de movimento que detecta a presença de pessoas.</p>
<p>3. Jumpers e Protoboard: Para conectar os componentes.</p>
<p>4. Fonte de Alimentação: Pode ser uma bateria ou uma fonte de 5V.</p>
<p>5. Cabo USB: Para conectar o ESP32 ao computador para programação.</p>
<p>6. App Telegram: Para receber as notificações</p>

## 💻 Passos de Configuração:

<b>1. Instalar o Arduino IDE e Configurar ESP32:</b>
<p>• Baixe e instale o Arduino IDE a partir do site oficial.<p/>
<p>• Adicione a placa ESP32 ao Arduino IDE. Vá para File > Preferences e adicione o URL: https://dl.espressif.com/dl/package_esp32_index.json no campo "Additional Board Manager URLs".<p/>
<p>• Vá para -> <b>Tools</b> -> <b>Board</b> ->  <b>Boards Manager</b>, procure por "esp32" e instale a placa ESP32.<p/>
  
<br><br>
<b>2. Conectar o Sensor PIR ao ESP32:</b>
<p>• Conecte o VCC do sensor PIR ao pino 5V do ESP32.<p/>
<p>• Conecte o GND do sensor PIR ao GND do ESP32.<p/>
<p>• Conecte o pino de saída (OUT) do sensor PIR a um dos pinos digitais do ESP32, por exemplo, GPIO 12.<p/>
<br><br>
<b>3. Criar um Bot no Telegram:</b>
<p>• Abra o Telegram e procure pelo BotFather.<p/>
<p>• Use o comando /newbot e siga as instruções para criar um novo bot.<p/>
<p>• Anote o Token do bot fornecido pelo BotFather.<p/>
<br><br>
<b>4. Instalar Bibliotecas Necessárias:</b>
<p>• No Arduino IDE, instale a biblioteca UniversalTelegramBot e a biblioteca WiFi para ESP32.<p/>

## 🗃 Histórico de lançamentos

A cada atualização os detalhes devem ser lançados aqui.
* 0.3.0 - 22/05/2024
    * Teste na camera.
* 0.2.1 - 20/05/2024
    * Ultimo teste do sistema.
* 0.2.0 - 06/05/2024
    * Montando o sistema.
* 0.1.1 - 26/04/2024
    * Pesquisando os codigos.
* 0.1.0 - 08/04/2024
    * Compras dos materias necessario.
* 0.0.1 - 15/03/2024
    * Iniciação do projeto.

## 📋 Licença/License
<p xmlns:cc="http://creativecommons.org/ns#" >Este trabalho está licenciado sob <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom ;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical -align:texto inferior;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>

## 🎓 Referências

Aqui estão as referências usadas no projeto.

1. <https://github.com/iuricode/readme-template>
2. <https://github.com/gabrieldejesus/readme-model>
3. <https://creativecommons.org/share-your-work/>
4. <https://freesound.org/>
5. Músicas por: <a href="https://freesound.org/people/DaveJf/sounds/616544/"> DaveJf </a> e <a href="https://freesound.org/people/DRFX/sounds/338986/"> DRFX </a> ambas com Licença CC 0.
