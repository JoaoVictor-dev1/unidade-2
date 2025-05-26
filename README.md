# 🚀 Sistema BitDogLab e IoT - Unidade 2
Este projeto explora o uso da placa BitDogLab para construção de um sistema de telemetria com foco em Internet das Coisas (IoT). Através da coleta e transmissão de dados via rede Wi-Fi, é possível monitorar em tempo real diversos sensores e apresentar essas informações de maneira visual e acessível.

# ⚙️ O que o Sistema Faz?

### ✅ Captura o acionamento do botão físico.
### ✅ Monitora a temperatura interna do processador.
### ✅ Mapeia a movimentação do joystick em dois eixos.
### ✅ Calcula a direção correspondente do joystick e exibe numa bússola visual.
### ✅ Envia os dados automaticamente ao servidor via HTTP.
### ✅ Exibe todas as informações em uma página web intuitiva e responsiva.

# 🖥️ Arquitetura da Solução
Coleta: A placa lê os sensores periodicamente.

Transmissão: Envio dos dados para o servidor através de requisições HTTP.

Armazenamento e distribuição: O backend processa e oferece as informações via uma rota pública.

Visualização: A interface web busca os dados e os apresenta em gráficos e indicadores.

# 🛠️ Tecnologias Envolvidas
BitDogLab com microcontrolador RP2040 e módulo Wi-Fi.

Firmware em C/C++ com suporte para protocolos de rede.

Node.js e Express no backend.

HTML, CSS e JavaScript puro no frontend.
