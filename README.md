<div align="center">
  <img src="https://img.shields.io/badge/Status-Desenvolvimento-green?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Plataforma-ESP32-blue?style=for-the-badge&logo=espressif" alt="ESP32">
  <img src="https://img.shields.io/badge/Linguagem-C++-00599C?style=for-the-badge&logo=c%2B%2B" alt="C++">
</div>

<br />

<div align="center">
  <h1>🚗 AutoSense: Monitorização Veicular OBD-II</h1>
  <p><i>Sistema inteligente de telemetria em tempo real desenvolvido como TCC para Engenharia da Computação.</i></p>
</div>

---

## 📝 Sobre o Projeto
O **AutoSense** é um sistema embarcado projetado para democratizar o acesso aos dados da ECU (Engine Control Unit). Através do protocolo **OBD-II**, o sistema extrai métricas vitais, processa-as em um **ESP32** e as apresenta em uma interface touch via display **Nextion**.

> **Diferencial:** Une a robustez do hardware industrial com uma interface moderna e intuitiva, permitindo diagnóstico de falhas (DTC) sem a necessidade de scanners profissionais caros.

---

## 🛠️ Stack Tecnológica
<table>
  <tr>
    <td><b>Hardware</b></td>
    <td>ESP32 DevKit V1, Display Nextion 3.5", Adaptador OBD-II (ELM327/STN)</td>
  </tr>
  <tr>
    <td><b>Firmware</b></td>
    <td>C++ (Arduino IDE / ESP-IDF)</td>
  </tr>
  <tr>
    <td><b>Protocolos</b></td>
    <td>CAN Bus, UART, OBD-II (ISO 15765-4)</td>
  </tr>
</table>

---

## 🚀 Principais Funcionalidades
* ✅ **Dashboard Real-time:** Visualização de RPM, Temperatura, Carga do Motor e Velocidade.
* ✅ **Diagnóstico DTC:** Leitura e limpeza de códigos de erro da injeção eletrônica.
* ✅ **Interface Touch:** Navegação entre telas e configurações diretamente no display.
* ✅ **Low Latency:** Otimização de polling para garantir fluidez nos dados.

---

---

## 📸 Demonstração
<div align="center">
  <video src="videonextion.mp4" width="600" controls>
    O seu navegador não suporta a visualização de vídeos.
  </video>
  <p><i>Demonstração do AutoSense: Interface Nextion e telemetria via ESP32</i></p>
</div>

---

---

## 👨‍🔬 Autor
**João Vitor Fernandes Euzebio** - *Estudante de Engenharia da Computação*
<br />
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jo%C3%A3o-vitor-fernandes-euzebio/) 
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/JoaoVitoreuzebio)
