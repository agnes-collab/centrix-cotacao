# Freitas Centrix — Landing Page de Campanha

Protótipo de validação da landing page e materiais de campanha para geração de leads em Comércio Exterior.

## Estrutura

```
freitas-centrix/
├── index.html    # Arquivo único com LP completa, LP compacta, criativos e Google Ads
└── README.md
```

## Conteúdo

O `index.html` contém quatro seções navegáveis:

- **Landing Page** — hero com formulário RD Station, dor, proposta de valor, diferenciais, Centrix e depoimentos
- **Landing Page Compacta** — versão enxuta com hero, dor, diferenciais e CTA
- **Criativos** — 3 copies × 2 versões × 2 formatos (Feed 1080×1350 e Stories 1080×1920)
- **Google Ads** — 15 headlines, 4 descrições e listas de palavras-chave

## Formulário

Integração via **RD Station** — embed carregado via `onload` para evitar erros de inicialização. Cada LP tem um container próprio com ID único.

## Criativos

Imagens hospedadas em `freitascomex.com.br`. Cada copy tem duas versões de arte para Feed e Stories.

## Status

Protótipo de validação. Formulário integrado ao RD Station.

## Próximos passos

- [ ] Substituir embed RD Station quando houver atualização de formulário
- [ ] Adicionar Google Tag Manager
- [ ] Testar responsividade mobile
- [ ] Configurar domínio / subdomínio
