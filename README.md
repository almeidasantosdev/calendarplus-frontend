# Calendar Plus — painel

Painel em que o profissional conecta a conta Google e o WhatsApp para o Calendar Plus marcar horários. Depois do login, a tela gera o QR Code da sessão, deixa definir o intervalo em que a IA pode agendar e permite ligar ou desligar essa automação.

Feito em React, TypeScript e Vite, com Socket.IO para o QR Code e o status da sessão. A API vem da variável `VITE_API_URL`.

Versão publicada: https://calendarplus-frontend.vercel.app

## Como rodar

```bash
npm install
npm run dev
```

Crie um `.env` com:

```
VITE_API_URL=https://sua-api
```
