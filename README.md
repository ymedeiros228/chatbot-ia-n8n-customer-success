# Chatbot CS + IA (n8n)

Desafio técnico de Customer Success: chatbot que responde com base de conhecimento via **n8n + Google Sheets + IA** (Groq/OpenAI).

**Autor:** [Yuri Medeiros](https://github.com/ymedeiros228) · CC · 6º período

## Como funciona

1. Usuário envia pergunta no chat  
2. n8n recebe a mensagem  
3. Google Sheets consulta a base Q&A  
4. IA escolhe / formula a resposta mais próxima  
5. Resposta automática no fluxo  

## Stack

- n8n (fluxo exportado em `workflow/`)
- Google Sheets / planilha (`base_de_dados/`)
- IA (Groq/OpenAI)
- Documentação e prints em pastas do repo

## Estrutura

```
documentacao/   # PDF técnico
video/          # Apresentação
prints/         # Capturas
workflow/       # Export n8n (.json)
base_de_dados/  # Planilha da base
```

## Status

Projeto funcional e validado no contexto do desafio (leitura da base, automação e integrações).

## Melhorias possíveis

- WhatsApp, busca vetorial, dashboard de métricas, atendimento hybrid.

---

Portfólio flagship: [SIGAPS](https://github.com/ymedeiros228/sigaps) · [Painel UBS](https://github.com/ymedeiros228/painel-ubs-planifica)
