<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>ESP32 FreeRTOS Monitoring System</title>
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      max-width: 900px;
      margin: auto;
      line-height: 1.6;
      color: #222;
    }
    h1, h2 {
      color: #0b7285;
    }
    code {
      background: #f4f4f4;
      padding: 2px 6px;
      border-radius: 4px;
    }
    ul {
      margin-left: 20px;
    }
    .badge {
      display: inline-block;
      background: #0b7285;
      color: #fff;
      padding: 4px 10px;
      border-radius: 12px;
      font-size: 12px;
      margin-right: 5px;
    }
  </style>
</head>
<body>

<h1>ESP32 FreeRTOS Monitoring System</h1>

<p>
Sistema de monitoramento desenvolvido em <strong>ESP32</strong> utilizando
<strong>FreeRTOS</strong>, com foco em demonstrar conhecimentos práticos de
<strong>sistemas embarcados</strong>, multitarefa e comunicação entre processos.
</p>

<div>
  <span class="badge">ESP32</span>
  <span class="badge">FreeRTOS</span>
  <span class="badge">Wokwi</span>
  <span class="badge">Embedded Systems</span>
</div>

<hr>

<h2>📌 Objetivo</h2>
<p>
Demonstrar o uso de multitarefa em tempo real, separação de responsabilidades
e comunicação segura entre tarefas em um ambiente simulado.
</p>

<h2>🧠 Arquitetura</h2>
<ul>
  <li><strong>Task Sensor:</strong> Simula a leitura de temperatura e umidade.</li>
  <li><strong>Task Processamento:</strong> Valida e filtra os dados.</li>
  <li><strong>Task Logger:</strong> Exibe as informações no monitor serial.</li>
</ul>

<p>As tarefas se comunicam por meio de <strong>Queues do FreeRTOS</strong>.</p>

<h2>⚙️ Tecnologias Utilizadas</h2>
<ul>
  <li>ESP32 (dual-core)</li>
  <li>FreeRTOS</li>
  <li>Arduino Framework</li>
  <li>Wokwi Simulator</li>
</ul>

<h2>🚀 Funcionalidades</h2>
<ul>
  <li>Execução concorrente de tarefas</li>
  <li>Comunicação segura entre tasks</li>
  <li>Simulação de sensores</li>
  <li>Logger via Serial Monitor</li>
</ul>

<h2>🧪 Execução</h2>
<p>
O projeto foi desenvolvido e testado no
<a href="https://wokwi.com" target="_blank">Wokwi Simulator</a>,
não sendo necessário hardware físico.
</p>

<h2>📈 Possíveis Evoluções</h2>
<ul>
  <li>Adição de Watchdog</li>
  <li>Servidor Web embarcado</li>
  <li>MQTT para IoT</li>
  <li>Arquitetura modular (HAL / Services)</li>
</ul>

<h2>📄 Licença</h2>
<p>Projeto de caráter educacional e demonstrativo.</p>

</body>
</html>
