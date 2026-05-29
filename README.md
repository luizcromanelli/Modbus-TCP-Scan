# Modbus TCP Scan v1.6  🚀

Uma ferramenta gráfica (GUI) leve, rápida e de classe industrial projetada para varredura, diagnóstico e monitoramento em tempo real de redes **Modbus TCP**.

O **Modbus Scan v1.6** é uma **ferramenta totalmente gratuita (Free)**, desenvolvida em Python utilizando `tkinter`. O software foi severamente otimizado e estruturado com máscaras de validação de dados e uma máquina de estados inteligente para tratamento de falhas, garantindo estabilidade absoluta em ambientes industriais hostis e imprevisíveis.

---

## 💻 Compatibilidade do Sistema

* **Sistemas Operacionais:** Totalmente compatível com **Windows 7, 8, 10 e 11**.
* **Arquiteturas:** Suporte nativo para sistemas de **32 bits (x86)** e **64 bits (x64)**.
* **Portabilidade:** Software portátil (Standalone) funciona diretamente do pendrive, sem necessidade de instalação, privilégios de administrador ou dependências do Python.

---

## 💎 Por que escolher o Modbus TCP Scan v1.6?

Diferente de escaneadores genéricos que travam, congelam ("Não Respondendo") ou fecham sozinhos devido a oscilações de rede ou erros de digitação, esta versão foi engenheirada com mecânicas de prevenção testadas em campo:

* **📊 Estatísticas Dinâmicas e Limpas:** Painel de diagnóstico completo apresentando um **Relógio de Uptime** sincronizado e um **Rastreador de Taxa de Erro (%)** que se reiniciam automaticamente a cada novo ciclo de varredura para garantir relatórios precisos.
* **⚡ Escudo de Timeout Fixo:** A comunicação do socket de rede é fixada em uma janela segura de 5,0 segundos na inicialização, eliminando renegociações instáveis de socket a nível de sistema operacional no meio do scan.
* **🧩 Deep Data Decoding:** Suporte completo para registradores de 16 bits (`Uint16`, `Int16`) e 32 bits (`Udint32`, `Dint32`, `Float 32-bit`) com manipulação visual e didática de **Byte Order (Endianness)** (*ABCD, DCBA, BADC, CDAB*).
* **🔍 Grid de Alta Legibilidade:** Exibe os valores convertidos para formatos legíveis, além das strings em Hexadecimal e Binário estruturadas com sublinhados visuais (`_`) para facilitar a análise de máscaras de bits.

---

## 🛠️ Principais Recursos Operacionais

1. **Funções Modbus Suportadas:**
   * `FC 01 - Read Coils (0X)`
   * `FC 02 - Read Discrete Inputs (1X)`
   * `FC 03 - Read Holding Registers (4X)`
   * `FC 04 - Read Input Registers (3X)`
2. **Métricas de Largura de Banda:** Cálculo exato do tamanho físico dos pacotes, mostrando precisamente quantos **Bytes (TX/RX)** estão trafegando pela infraestrutura.
3. **Mecanismo de Retentativa Tolerante a Falhas:** Até 10 tentativas de conexão consecutivas com feedback visual de status (LED indicador piscante) antes de realizar a desconexão automática segura.

---

## 🚀 Como Executar (Executável Pré-Compilado)

Não é necessário instalar Python, gerenciar dependências ou digitar comandos no terminal para o trabalho de campo.

1. Acesse a seção [**Releases**](https://github.com/luizcromanelli/Modbus-TCP-Poll/releases) deste repositório.
2. Baixe o arquivo `ModbusScan_v1.6.exe`.
3. Dê um duplo clique e execute nativamente em qualquer máquina Windows.

---

## 📄 Licença e Contato

* **Desenvolvedor:** Luiz Cláudio Romanelli
* **Contato:** luizcromanelli@gmail.com

Distribuído sob a licença **MIT**. Sinta-se à vontade para clonar, abrir issues ou enviar pull requests com sugestões de melhorias!
