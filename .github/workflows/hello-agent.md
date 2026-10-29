---
name: hello-agent

on:
  workflow_dispatch:

safe-outputs:
  create-issue:
---

# Agente Hello

Leer el Readme.md del repositorio
Creara una issue con el titulo
"Ejemplo de Issue generada por Agente"

En el cuerpo de la Issue poner:
- Un resumen del repositorio
- Una lista de bullets describiendo el reposiorio
- Finalizar con la oracion "Generado por Github Agentic Worflow"