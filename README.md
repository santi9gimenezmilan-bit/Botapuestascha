# Bot de Apuestas con Valor (+EV)

Este bott analiza cuotas de **fútbol, NFL y NBA** usando [The Odds API](https://the-odds-api.com/)  
y envía **alertas de apuestas con valor esperado positivo (+EV)** a Telegram.

## Configuración
- Token de Telegram ya integrado
- chat_id ya integrado
- API Key de The Odds API ya integrada

## Cómo funciona
- Corre cada 10 minutos en Railway
- Calcula el Valor Esperado (EV)
- Si EV > 3%, envía alerta con:
  - Evento
  - Selección
  - Cuota
  - Valor esperado
  - Stake sugerido

## Deploy en Railway
1. Sube estos archivos a un repositorio en GitHub.
2. Conecta el repositorio a Railway.
3. Railway instalará dependencias y correrá el bot.
4. Recibirás alertas directas en Telegram.
