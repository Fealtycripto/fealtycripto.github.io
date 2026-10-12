# CriptoZion — fonte do site estático

Repositório **público** da apresentação estática do CriptoZion, projeto fundado por **Rony Costa (Zion)**, empreendedor, criador de conteúdo e criador da **Zion Smart DCA**, metodologia e projeto de software em evolução. Referência editorial BIO-1.0.

O conteúdo aborda Bitcoin, DeFi e planejamento de aportes. Este código HTML é uma frente histórica separada da aplicação atual: não reúne o backend, autenticação, dados de usuários ou serviços da plataforma.

## Destinos atuais

- [Site público do CriptoZion](https://criptozion.xyz).
- [Estratégias e conteúdos](https://criptozion.xyz/estrategias).
- [Acesso à plataforma](https://app.criptozion.xyz/login?next=%2F), que exige conta; alguns recursos dependem do Zion Pass.
- [Skill pública e experimentos](https://github.com/Fealtycripto/zion-smart-dca-skill).

A configuração GitHub Pages deste repositório contém CNAME `criptozion.xyz`. A presença dessa associação no GitHub não prova que estes arquivos sejam o código atualmente servido pelo domínio. Antes de uma mudança de hospedagem, conferir o destino efetivo e evitar substituir a aplicação por uma versão histórica.

## Conteúdo e tecnologias

HTML, CSS e JavaScript; páginas `index.html`, `academy.html`, `blog.html`, `calculadora.html` e artigos/assets locais. Links e integrações internas das páginas históricas podem exigir atualização; não tratá-los como serviços atuais validados.

Para inspecionar os arquivos localmente, na pasta deste repositório:

```sh
python -m http.server 8766 --bind 127.0.0.1
```

Abra `http://127.0.0.1:8766/`. As páginas podem consultar CDNs/APIs externas; não envie formulários ou teste pagamentos para uma simples revisão visual.

## Estágio, identidade e licença

Fonte estática com revisão editorial de identidade; não representa comprovação de performance financeira ou implantação da plataforma. Simulações não garantem retorno. DoubleDyn é iniciativa independente e Rony Costa (Zion) é sócio; Vila Pet Banho e Tosa é outra frente independente.

CriptoZion © 2026. Não há arquivo `LICENSE` versionado neste repositório; seu acesso público não concede automaticamente licença de reutilização. Nenhuma licença foi adicionada ou alterada nesta revisão.
