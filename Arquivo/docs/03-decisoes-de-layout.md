# Decisões de Layout

## Introdução

Este documento registra as principais decisões de layout adotadas no desenvolvimento da landing page do projeto "Conecta Respeito".

A intenção é justificar as escolhas visuais, estruturais e técnicas da interface, mantendo uma apresentação clara, educativa e respeitosa.

## Organização visual

A página foi organizada em formato de landing page com seções verticais e navegação por âncoras.

Essa estrutura favorece a leitura sequencial do conteúdo e permite que o usuário entenda rapidamente:

- a proposta do projeto;
- o conceito de bullying;
- os tipos de violência e exclusão;
- os sinais de alerta;
- as formas seguras de agir;
- os canais de apoio;
- o compromisso da comunidade escolar.

## Uso de Bootstrap

O Bootstrap foi utilizado para garantir uma base responsiva e consistente na construção da interface.

Foram aplicados componentes como:

- `container`;
- `row` e `col`;
- `navbar`;
- `card`;
- `badge`;
- `button`;
- classes de espaçamento e alinhamento;
- responsividade para mobile.

A adoção do Bootstrap permite maior rapidez no desenvolvimento e mantém a arquitetura visual próxima aos padrões de um projeto acadêmico moderno.

## Estrutura por seções

O conteúdo foi dividido em seções com a tag `section`.

Cada uma possui uma função específica:

| Seção | Finalidade |
| ----- | --------- |
| Header | Exibir logo e menu de navegação |
| Hero | Apresentar a proposta e a mensagem de conscientização |
| O que é bullying? | Definir o tema e contextualizar o problema |
| Tipos de bullying | Apresentar as formas de agressão e exclusão |
| Sinais de alerta | Identificar comportamentos e mudanças que merecem atenção |
| Como agir de forma segura? | Orientar ações adequadas e responsáveis |
| Canais de apoio | Apresentar redes de acolhimento e orientação |
| Compromisso da comunidade | Destacar a responsabilidade coletiva |
| Footer | Exibir identificação acadêmica |

Essa divisão ajuda na organização do código e facilita futuras manutenções ou evoluções da página.

## Paleta visual

A identidade visual foi pensada para transmitir acolhimento, seriedade e confiança.

A predominância de verdes e tons suaves foi escolhida para sugerir equilíbrio, cuidado e prevenção, sem banalizar o tema ou gerar uma sensação inadequada diante da gravidade do assunto.

## Cabeçalho

O cabeçalho utiliza uma `navbar` fixa no topo da página.

A decisão por um menu fixo foi adotada para facilitar a navegação entre as seções, especialmente em páginas longas e com conteúdo educativo.

A logo do projeto foi carregada a partir do caminho:

```text
assets/images/logo.png
```

## Acessibilidade e clareza

O layout foi estruturado para manter boa legibilidade, contraste adequado e organização visual. Os textos foram elaborados para serem claros, diretos e adequados ao público escolar.

Além disso, a navegação por âncoras favorece a experiência de uso e melhora a acessibilidade da página.
