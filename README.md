# 🌡️ Classificador de Temperatura em Python

Este repositório contém um script simples e interativo em Python que classifica a temperatura digitada pelo usuário com mensagens divertidas e emojis. Ele serve como um exemplo básico de uso de condicionais (`if`, `elif`, `else`) em Python.

## 📋 Descrição

O programa solicita ao usuário uma temperatura em graus Celsius e, com base no valor inserido, classifica a sensação térmica em uma das seguintes categorias:

- **Gelada** 🥶🧊 (abaixo de 11°C)
- **Normal** 😁😄 (entre 11°C e 19.9°C)
- **Quente** 🔥🥵 (entre 20°C e 30°C — *ver observação abaixo*)
- **Outro valor**: Mensagem de despedida

### ⚠️ Observação importante

O seguinte trecho do código contém um erro lógico:

```python
elif 20 <= Temperatura > 30:
