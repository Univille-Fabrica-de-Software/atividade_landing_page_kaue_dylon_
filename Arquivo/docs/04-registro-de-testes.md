# Registro de Testes

## Introdução

Este documento registra os testes manuais previstos para a landing page do projeto "Conecta Respeito".

O objetivo é verificar se a página abre corretamente, se os recursos visuais são carregados, se a navegação funciona e se o layout responde adequadamente em diferentes tamanhos de tela.

## Ambiente de teste

| Item | Informação |
| ---- | ---------- |
| Sistema operacional | Windows |
| Navegador utilizado | Microsoft Edge / Google Chrome |
| Editor de código | VS Code |
| Forma de execução | Arquivo local / Live Server |
| Data do teste | Registrar data |
| Responsável pelo teste | Nome do acadêmico |

## Teste 1 - Abertura da página

| Verificação | Resultado esperado | Status |
| ----------- | ------------------ | ------ |
| Abrir o arquivo `index.html` | A página deve abrir no navegador sem erros | Pendente |
| Carregar o título da aba | A aba deve exibir "Conecta Respeito" | Pendente |
| Carregar o conteúdo principal | O hero e as seções devem aparecer corretamente | Pendente |
| Carregar o Bootstrap | O layout deve responder corretamente com grid e cards | Pendente |
| Carregar o CSS próprio | O estilo visual da página deve ser aplicado | Pendente |

## Teste 2 - Logo e favicon

| Verificação | Resultado esperado | Status |
| ----------- | ------------------ | ------ |
| Exibir a logo no cabeçalho | A imagem `logo.png` deve aparecer no navbar | Pendente |
| Verificar texto alternativo da logo | A imagem deve possuir atributo `alt` | Pendente |
| Exibir favicon na aba | O ícone deve aparecer na aba do navegador | Pendente |
| Conferir caminhos dos ícones | Os caminhos devem apontar para `assets/icons/favicon_io/` | Pendente |

## Teste 3 - Navegação interna

| Link do menu | Destino esperado | Status |
| ------------ | ---------------- | ------ |
| Início | Deve levar para a seção inicial | Pendente |
| Bullying | Deve levar para a seção "O que é bullying?" | Pendente |
| Tipos | Deve levar para a seção "Tipos de bullying" | Pendente |
| Sinais | Deve levar para a seção "Sinais de alerta" | Pendente |
| Como agir | Deve levar para a seção "Como agir de forma segura?" | Pendente |
| Apoio | Deve levar para a seção "Canais de apoio ou orientação" | Pendente |
| Compromisso | Deve levar para a seção "Compromisso da comunidade" | Pendente |

## Teste 4 - Conteúdo obrigatório

| Conteúdo | Resultado esperado | Status |
| -------- | ------------------ | ------ |
| Cabeçalho | Deve conter logo e menu de navegação | Pendente |
| Seção hero | Deve conter o `h1` principal e chamada de conscientização | Pendente |
| Bullying | Deve explicar o conceito do tema e sua relação com exclusão e agressão | Pendente |
| Tipos de bullying | Deve apresentar os principais tipos como físico, verbal, psicológico, social e digital | Pendente |
| Sinais de alerta | Deve mostrar indicadores de atenção | Pendente |
| Como agir | Deve orientar ações seguras e acolhedoras | Pendente |
| Canais de apoio | Deve indicar redes de apoio e orientação | Pendente |
| Compromisso da comunidade | Deve reforçar a responsabilidade coletiva | Pendente |
| Rodapé | Deve apresentar disciplina, nome do acadêmico e ano | Pendente |

## Teste 5 - Responsividade

| Dispositivo/tamanho | Resultado esperado | Status |
| ------------------- | ------------------ | ------ |
| Desktop | Layout deve aparecer organizado em colunas | Pendente |
| Notebook | Conteúdo deve permanecer legível e equilibrado | Pendente |
| Tablet | Cards e blocos devem se adaptar ao espaço | Pendente |
| Celular | Conteúdo deve aparecer em sequência vertical e legível | Pendente |
| Menu mobile | Navbar deve abrir e fechar corretamente | Pendente |

## Teste 6 - Acessibilidade básica

| Verificação | Resultado esperado | Status |
| ----------- | ------------------ | ------ |
| Idioma da página | A tag `html` deve conter `lang="pt-BR"` | Pendente |
| Hierarquia de títulos | Deve existir um único `h1` principal | Pendente |
| Texto alternativo | Imagens devem possuir atributo `alt` | Pendente |
| Links compreensíveis | Os links devem indicar claramente seu destino | Pendente |
| Navegação por teclado | Menu e links devem ser acessíveis por teclado | Pendente |
| Contraste visual | Textos devem permanecer legíveis sobre o fundo | Pendente |

## Teste 7 - Publicação no GitHub Pages

| Verificação | Resultado esperado | Status |
| ----------- | ------------------ | ------ |
| Repositório criado | Projeto deve estar disponível no GitHub | Pendente |
| GitHub Pages configurado | Página deve estar publicada pela branch principal | Pendente |
| Página publicada abre corretamente | URL pública deve abrir a landing page | Pendente |
| Arquivos estáticos carregam | CSS, logo e favicon devem funcionar na versão pública | Pendente |
| Links internos funcionam | Menu deve navegar corretamente na versão publicada | Pendente |

## Problemas encontrados

Registre abaixo os problemas identificados durante os testes.

```text
Exemplo:
O favicon não apareceu na aba do navegador.
Causa provável: caminho incorreto no atributo href.
Correção: ajuste do caminho para assets/icons/favicon_io/favicon-32x32.png.
```

