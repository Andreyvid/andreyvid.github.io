# Andrey.dev

Portfólio e cartão de visitas de **Andrey Dutra**, desenvolvedor Full Stack.
Sites, landing pages e sistemas sob medida.

🔗 **Site:** https://andreyvid.github.io

## O que tem na página

- Título e frases digitadas em loop (efeito de terminal)
- Vitrine de projetos com cards animados
- Faixa de tecnologias em loop
- Botão de orçamento direto no WhatsApp
- Links para GitHub e LinkedIn
- Respeita a configuração "reduzir movimento" do sistema (os efeitos mais fortes são desligados)

## Tecnologias

- HTML, CSS e JavaScript puro, em um único arquivo (`index.html`)
- [Motion](https://motion.dev) para as animações, carregado por CDN
- Hospedagem no GitHub Pages

## Como editar

Tudo está no `index.html`, com comentários `EDITE AQUI`:

| O que mudar | Onde |
|---|---|
| Frases que digitam | `const items`, no final do arquivo |
| Número do WhatsApp | links `wa.me/55...` (botão de orçamento e card de contato) |
| LinkedIn e GitHub | seção `contato` |
| Projetos | blocos `<a class="card">` na seção `projetos` |
| Tecnologias da faixa | `<div class="ticker-track">` |

## Rodando localmente

Não precisa instalar nada. Abra o `index.html` no navegador.
(As animações do Motion precisam de internet, por causa do CDN. Sem ela, a página aparece normal, só sem esses efeitos.)

## Projetos em destaque

- **Serra Imóveis**: site para imobiliária com painel administrativo para cadastrar imóveis com fotos.
- **MaxProgress**: diário de treino com registro de carga e repetições, recorde pessoal e evolução por exercício. [Ver site](https://andreyvid.github.io/maxprogress-site/)

## Contato

- LinkedIn: https://www.linkedin.com/in/andreyvid-dutra
- GitHub: https://github.com/Andreyvid
- WhatsApp: (11) 95292-4981
