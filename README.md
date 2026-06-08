# Modbus TCP Scan v1.6 🚀

### 🌐 Language / Idioma
* 🇺🇸 [English Version](#-english-version)
* 🇧🇷 [Versão em Português](#-versão-em-português)

---

## 🇺🇸 English Version

### 📦 Download
* Direct Link: [**Download ModbusScan_v1.6.exe**](https://github.com/luizcromanelli/Modbus-TCP-Scan/releases/download/1.6/ModbusScan_v1.6.zip)

A lightweight, fast, and industrial-grade graphical tool (GUI) designed for real-time scanning, diagnostics, and monitoring of Modbus TCP networks.
Modbus Scan v1.6 is a completely free tool (Free), developed in Python using pyModbusTCP. The software was severely optimized and structured with data validation masks and an intelligent state machine for fault handling, ensuring absolute stability in harsh and unpredictable industrial environments.

### 💻 System Compatibility

* **Operating Systems:** Fully compatible with Windows 7, 8, 10, and 11.
* **Architectures:** Native support for 32-bit (x86) and 64-bit (x64) systems.
* **Portability:** Portable software (Standalone) — works directly from a flash drive, with no installation, administrator privileges, or Python dependencies required.

### 💎 Why choose Modbus TCP Scan v1.6?

Unlike generic scanners that crash, freeze ("Not Responding"), or close by themselves due to network fluctuations or typing errors, this version was engineered with field-tested prevention mechanics:
* 📊 **Dynamic and Clean Statistics:** A complete diagnostic panel featuring a synchronized Uptime Clock and an Error Rate Tracker (%) that automatically reset at each new scan cycle to ensure accurate reports.
* ⚡ **Fixed Timeout Shield:** Network socket communication is fixed at a secure 5.0-second window upon initialization, eliminating unstable socket renegotiations at the operating system level in the middle of a scan.
* 🧩 **Deep Data Decoding:** Full support for 16-bit registers (Uint16, Int16) and 32-bit registers (Udint32, Dint32, Float 32-bit) with visual and educational handling of Byte Order (Endianness) (ABCD, DCBA, BADC, CDAB).
* 🔍 **High-Readability Grid:** Displays converted values in readable formats, alongside Hexadecimal and Binary strings structured with visual underscores (_) to facilitate bit mask analysis.

### 🛠️ Main Operational Features

* **Supported Modbus Functions:**
  * FC 01 - Read Coils (0X)
  * FC 02 - Read Discrete Inputs (1X)
  * FC 03 - Read Holding Registers (4X)
  * FC 04 - Read Input Registers (3X)
* **Bandwidth Metrics:** Exact calculation of the physical packet size, showing precisely how many Bytes (TX/RX) are traveling through the infrastructure.
* **Fault-Tolerant Retry Mechanism:** Up to 10 consecutive connection attempts with visual status feedback (flashing indicator LED) before performing a safe automatic disconnection.

### 🚀 How to Run (Pre-Compiled Executable)

Python installation, dependency management, or terminal commands are not required for field work.
1. Click here for [**Direct Download of ModbusScan_v1.6.exe**](https://github.com/luizcromanelli/Modbus-TCP-Scan/releases/download/1.6/ModbusScan_v1.6.zip).
2. Save the file to your computer.
3. Double-click and run natively on any Windows machine.

⚠️ **Important Execution Instructions (Windows SmartScreen):** As it is a free, un-signed portable utility, Windows Defender may display the screen "Windows protected your PC". The file is 100% safe. To allow execution, follow one of the two methods below:
* **Method 1 (On the alert screen):** In the SmartScreen warning window, click on the **"More info"** text link, and then click on the button that appears called **"Run anyway"**.
* **Method 2 (In the file properties):** Before opening, right-click on the downloaded `ModbusScan_v1.6.exe` file, go to **Properties**, check the **"Unblock"** checkbox located at the bottom of the General tab, and click Apply/OK.

### 📄 License and Contact

* **Developer:** Luiz Cláudio Romanelli
* **Contact:** luizcromanelli@gmail.com
Distributed under the MIT license. Feel free to clone, open issues, or submit pull requests with improvement suggestions!

---

## 🇧🇷 Versão em Português

### 📦 Download
* Link Direto: [**Baixar ModbusScan_v1.6.exe**](https://github.com/luizcromanelli/Modbus-TCP-Scan/releases/download/1.6/ModbusScan_v1.6.zip)

Uma ferramenta gráfica (GUI) leve, rápida e de classe industrial projetada para varredura, diagnóstico e monitoramento em tempo real de redes Modbus TCP.
O Modbus Scan v1.6 é uma ferramenta totalmente gratuita (Free), desenvolvida em Python utilizando pyModbusTCP. O software foi severamente otimizado e estruturado com máscaras de validação de dados e uma máquina de estados inteligente para tratamento de falhas, garantindo estabilidade absoluta em ambientes industriais hostis e imprevisíveis.

### 💻 Compatibilidade do Sistema

* **Sistemas Operacionais:** Totalmente compatível com Windows 7, 8, 10 e 11.
* **Arquiteturas:** Suporte nativo para sistemas de 32 bits (x86) e 64 bits (x64).
* **Portabilidade:** Software portátil (Standalone) funciona diretamente do pendrive, sem necessidade de instalação, privilégios de administrador ou dependências do Python.

### 💎 Por que escolher o Modbus TCP Scan v1.6?

Diferente de escaneadores genéricos que travam, congelam ("Não Respondendo") ou fecham sozinhos devido a oscilações de rede ou erros de digitação, esta versão foi engenheirada com mecânicas de prevenção testadas em campo:
* 📊 **Estatísticas Dinâmicas e Limpas:** Painel de diagnóstico completo apresentando um Relógio de Uptime sincronizado e um Rastreador de Taxa de Erro (%) que se reiniciam automaticamente a cada novo ciclo de varredura para garantir relatórios precisos.
* ⚡ **Escudo de Timeout Fixo:** A comunicação do socket de rede é fixada em uma janela segura de 5,0 segundos na inicialização, eliminando renegociações instáveis de socket a nível de sistema operacional no meio do scan.
* 🧩 **Deep Data Decoding:** Suporte completo para registradores de 16 bits (Uint16, Int16) e 32 bits (Udint32, Dint32, Float 32-bit) com manipulação visual e didática de Byte Order (Endianness) (ABCD, DCBA, BADC, CDAB).
* 🔍 **Grid de Alta Legibilidade:** Exibe os valores convertidos para formatos legíveis, além das strings em Hexadecimal e Binário estruturadas com sublinhados visuais (_) para facilitar a análise de máscaras de bits.

### 🛠️ Principais Recursos Operacionais

* **Funções Modbus Suportadas:**
  * FC 01 - Read Coils (0X)
  * FC 02 - Read Discrete Inputs (1X)
  * FC 03 - Read Holding Registers (4X)
  * FC 04 - Read Input Registers (3X)
* **Métricas de Largura de Banda:** Cálculo exato do tamanho físico dos pacotes, mostrando precisamente quantos Bytes (TX/RX) estão trafegando pela infraestrutura.
* **Mecanismo de Retentativa Tolerante a Falhas:** Até 10 tentativas de conexão consecutivas com feedback visual de status (LED indicador piscante) antes de realizar a desconexão automática segura.

### 🚀 Como Executar (Executável Pré-Compilado)

Não é necessário instalar Python, gerenciar dependências ou digitar comandos no terminal para o trabalho de campo.
1. Clique aqui para fazer o [**Download Direto do ModbusScan_v1.6.exe**](https://github.com/luizcromanelli/Modbus-TCP-Scan/releases/download/1.6/ModbusScan_v1.6.zip).
2. Salve o arquivo em seu computador.
3. Dê um duplo clique e execute nativamente em qualquer máquina Windows.

⚠️ **Instruções Importantes de Execução (Windows SmartScreen):** Por ser um utilitário portátil gratuito e não assinado digitalmente com certificados corporativos, o Windows Defender exibirá a tela "O Windows protegeu o computador". O arquivo é 100% seguro. Para liberar a execução, siga um dos dois métodos abaixo:
* **Método 1 (Na tela do alerta):** Na janela do aviso do SmartScreen, clique no link de texto "Mais informações" (More info) e, em seguida, clique no botão que aparecerá chamado "Executar assim mesmo" (Run anyway).
* **Método 2 (Nas propriedades do arquivo):** Antes de abrir, clique com o botão direito sobre o arquivo ModbusScan_v1.6.exe baixado, vá em Propriedades, marque a caixa de seleção "Desbloquear" (Unblock) localizada na parte inferior da aba Geral e clique em Aplicar/OK.

### 📄 Licença e Contato

* **Desenvolvedor:** Luiz Cláudio Romanelli
* **Contato:** luizcromanelli@gmail.com
Distribuído sob a licença MIT. Sinta-se à vontade para clonar, abrir issues ou enviar pull requests com sugestões de melhorias!
