# Calendar Plus — base do frontend do Wagoo

Este repositório é a primeira versão do frontend do Wagoo. O painel conecta a conta Google e o WhatsApp para marcar horários. Depois do login, gera o QR Code da sessão, define o intervalo em que a IA pode agendar e liga ou desliga essa automação.

Feito em React, TypeScript e Vite, com Socket.IO para o QR Code e o status da sessão. A API vem da variável `VITE_API_URL`.

## Produto

O Wagoo em produção está em [https://wagoobot.com](https://wagoobot.com).

A página abre com o título "Muito mais que agendar. A gestão que o seu espaço precisa." O texto visível diz que o cliente marca no WhatsApp, que o horário fica firme com sinal e que a comissão fecha sem planilha. A navegação tem Como Funciona, Valor, Planos, FAQ e Login. A seção de agenda cita o Google Calendar.

## Como rodar

```bash
npm install
npm run dev
```

Crie um `.env` na raiz:

```
VITE_API_URL=https://sua-api
```
