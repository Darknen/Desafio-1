# 🔐 SOS Security — Landing Page


> 🚀 **DESAFIO 01 — Tire sua Ideia do Papel**

O projeto apresenta a empresa SOS Security, seus principais serviços de segurança eletrônica, galeria de imagens e formas de contato.

A página foi desenvolvida utilizando **HTML5 e CSS3**, sem JavaScript, com foco em semântica, organização visual, acessibilidade e responsividade.

---

# 📌 Sobre o desafio

O objetivo do desafio é transformar uma ideia em uma Landing Page funcional e publicá-la utilizando o **GitHub Pages**.

Para o desenvolvimento deste projeto foi escolhida a **SOS Security**, uma empresa da área de segurança eletrônica.

A escolha de um negócio real permitiu criar uma página com aplicação prática, utilizando informações e serviços relacionados à atividade da empresa.

## Principais requisitos do desafio

O projeto deve possuir:

- HTML5;
- CSS3;
- CSS em arquivo externo;
- HTML semântico;
- layout responsivo;
- acessibilidade;
- Header;
- menu de navegação;
- Hero;
- seção Sobre;
- seção de Produtos ou Serviços;
- pelo menos 3 cards;
- galeria de imagens;
- seção de Contato;
- Footer;
- controle de versão com Git;
- repositório no GitHub;
- pelo menos 3 commits significativos;
- publicação utilizando GitHub Pages;
- README documentando o projeto;
- documentação do uso de Inteligência Artificial.

## Restrições do desafio

O desenvolvimento foi realizado respeitando as seguintes restrições:

- ❌ Sem JavaScript;
- ❌ Sem CSS inline;
- ❌ Sem `<style>` dentro do HTML;
- ✅ CSS armazenado em arquivo externo;
- ✅ HTML5 semântico.

---

# 🎯 Objetivo do projeto

O objetivo da Landing Page é apresentar a **SOS Security** de maneira clara, moderna e responsiva.

A página foi organizada para que o visitante consiga:

1. identificar rapidamente a empresa;
2. conhecer sua área de atuação;
3. visualizar os principais serviços;
4. visualizar exemplos relacionados à segurança eletrônica;
5. encontrar informações de contato;
6. solicitar atendimento.

---

# 🛠️ Tecnologias utilizadas

O projeto utiliza:

- **HTML5** — estrutura e conteúdo;
- **CSS3** — estilização, animações e responsividade;
- **Git** — controle de versão;
- **GitHub** — armazenamento do repositório;
- **GitHub Pages** — publicação da Landing Page;
- **Google Fonts** — tipografia utilizada no projeto.

Nenhum framework CSS ou biblioteca JavaScript foi utilizado.

---

# 🧱 HTML5 semântico

A estrutura foi desenvolvida utilizando elementos semânticos do HTML5.

Entre os elementos utilizados estão:

```html
<header>
<nav>
<main>
<section>
<article>
<figure>
<footer>
```

Esses elementos ajudam a organizar o documento e tornam sua estrutura mais compreensível tanto para desenvolvedores quanto para tecnologias assistivas.

## Organização geral

A página possui:

```text
HEADER
│
├── Logo
├── Menu de navegação
└── Botão de contato
│
MAIN
│
├── Hero
├── Sobre
├── Serviços
├── Galeria
├── Contato
└── Privacidade
│
FOOTER
```

---

# 🏠 Hero

O Hero é a primeira área visual da Landing Page.

Ele possui:

- imagem de fundo;
- camada escura para melhorar a leitura;
- frase de destaque;
- título principal;
- descrição;
- botões de ação.

O título recebeu um efeito de iluminação utilizando exclusivamente CSS.

O efeito cria uma faixa luminosa que atravessa as letras horizontalmente.

Exemplo da técnica utilizada:

```css
background: linear-gradient(
    90deg,
    #ffffff,
    #78d7ff,
    #ffffff
);

background-clip: text;
animation: brilhoHero 5s linear infinite;
```

Não foi utilizado JavaScript para produzir a animação.

---

# 🏢 Sobre a empresa

A seção **Sobre** apresenta informações resumidas da empresa através de cards.

Os cards destacam pontos relacionados à empresa, como:

- experiência;
- atendimento;
- suporte técnico.

O objetivo dessa área é apresentar rapidamente características importantes da empresa sem utilizar grandes blocos de texto.

---

# 🔧 Serviços

A seção **Nossos Serviços** utiliza elementos `<article>` para representar cada serviço em um card independente.

Os serviços apresentados são:

### 01 — CFTV

Soluções de monitoramento por câmeras para residências, empresas e condomínios.

### 02 — Controle de Acesso

Soluções destinadas ao gerenciamento e organização da entrada de pessoas.

### 03 — Sistema de Incêndio

Soluções relacionadas a sistemas de detecção e alerta.

### 04 — Cerca Elétrica

Soluções de proteção perimetral.

### 05 — Cabeamento Estruturado

Organização e implantação de infraestrutura de cabeamento.

### 06 — Portões Automáticos

Soluções relacionadas à automação de portões.

## Comportamento dos cards

No desktop:

```text
[ Serviço 01 ] [ Serviço 02 ] [ Serviço 03 ]

[ Serviço 04 ] [ Serviço 05 ] [ Serviço 06 ]
```

No tablet:

```text
[ Serviço 01 ] [ Serviço 02 ]

[ Serviço 03 ] [ Serviço 04 ]

[ Serviço 05 ] [ Serviço 06 ]
```

No smartphone:

```text
[ Serviço 01 ]

[ Serviço 02 ]

[ Serviço 03 ]

[ Serviço 04 ]

[ Serviço 05 ]

[ Serviço 06 ]
```

---

# 🖼️ Galeria

A Landing Page possui uma galeria com imagens relacionadas ao segmento de segurança eletrônica.

Foram utilizadas três categorias:

1. Sistema de CFTV;
2. Controle de Acesso;
3. Equipamentos de Segurança Eletrônica.

As imagens da galeria são apresentadas utilizando elementos semânticos como:

```html
<figure>
    <img>
    <figcaption>
</figure>
```

## Arquivos da galeria

```text
galeria-01.png
galeria-02.jpg
galeria-03.png
```



# 📞 Contato

A Landing Page possui uma seção com um formulario para ao contato com a empresa.


## Campos do formulário

O formulário possui campos para:

- nome;
- e-mail;
- telefone;
- serviço;
- mensagem.

O formulário foi centralizado através de CSS para manter melhor equilíbrio visual na página.

---

# 📱 Responsividade

Um dos objetivos principais do projeto foi permitir que a Landing Page funcione em diferentes tamanhos de tela.

Foram criadas adaptações para:

### 🖥️ Desktop

Layout completo, com cards distribuídos em múltiplas colunas.

### 💻 Tablet

Elementos reorganizados em menos colunas para melhorar o aproveitamento da tela.

### 📱 Smartphone

Elementos apresentados principalmente em uma coluna, facilitando leitura e interação.

Foram utilizadas **Media Queries**.

Exemplo:

```css
@media (max-width: 950px) {
    /* ajustes para telas intermediárias */
}

@media (max-width: 700px) {
    /* ajustes para smartphones */
}

@media (max-width: 420px) {
    /* ajustes para telas pequenas */
}
```

O layout também utiliza:

```css
overflow-x: hidden;
```

para auxiliar na prevenção de rolagem horizontal indesejada.

---

# ♿ Acessibilidade

A acessibilidade foi considerada durante o desenvolvimento.

Foram aplicadas práticas como:

- HTML semântico;
- atributo `lang="pt-BR"`;
- hierarquia de títulos;
- utilização de `<h1>`, `<h2>` e `<h3>`;
- textos alternativos (`alt`) nas imagens;
- contraste entre texto e fundo;
- indicação visual de foco;
- tamanho adequado dos elementos interativos;
- labels associados aos campos do formulário;
- suporte à redução de movimentos.

## Foco de teclado

Elementos interativos recebem indicação visual quando selecionados pelo teclado:

```css
:focus-visible {
    outline: 3px solid var(--blue-accent);
    outline-offset: 3px;
}
```

## Redução de movimento

Foi implementada a preferência:

```css
@media (prefers-reduced-motion: reduce)
```

Quando o sistema do usuário está configurado para reduzir animações, os movimentos da página são minimizados.

---

# 🎨 Identidade visual

A identidade visual foi baseada principalmente na cor **azul**, relacionada à identidade da SOS Security.

A paleta utiliza:

```css
--blue-accent: #4cc9f0;
--blue-accent-dark: #219ebc;
--blue-light: #78d7ff;

--dark: #0a1929;
--dark-2: #203a43;

--white: #ffffff;
--soft: #f4f7fb;
```

A combinação utiliza:

- azul escuro;
- azul petróleo;
- azul ciano;
- branco;
- cinza claro.

A primeira versão do layout utilizava detalhes verdes.

Durante o desenvolvimento foi decidido substituir os elementos verdes por tons de azul/ciano para deixar a página mais coerente com a identidade visual da empresa e com a imagem utilizada no Hero.

---

# ✨ Recursos visuais criados somente com CSS

Mesmo sem utilizar JavaScript, foram adicionados alguns recursos visuais.

Entre eles:

- gradientes;
- animação do título;
- efeitos de hover;
- transições;
- sombras;
- cards;
- mudanças de cor;
- ampliação suave das imagens da galeria;
- adaptação responsiva.

Exemplo:

```css
.service-card:hover {
    transform: translateY(-8px);
}
```

---

# 📂 Estrutura de arquivos

A organização final do projeto segue esta estrutura:

```text
Projeto-SOS-Security/
│
├── index.html
├── README.md
│
├── css/
│   └── style.css
│
└── images/
    ├── logo.png
    ├── hero-bg.png
    ├── galeria-01.png
    ├── galeria-02.jpg
    └── galeria-03.png
```

## Função dos principais arquivos

### `index.html`

Responsável pela estrutura e conteúdo da Landing Page.

### `css/style.css`

Responsável por:

- identidade visual;
- layout;
- responsividade;
- animações;
- cards;
- formulário;
- Hero;
- galeria;
- Footer.

### `images/`

Diretório destinado aos recursos gráficos utilizados pela página.

---

# 🤖 Utilização de Inteligência Artificial

A Inteligência Artificial foi utilizada como **ferramenta de apoio durante o desenvolvimento do projeto**.

Seu uso fez parte do processo de:

- Planejamento;
- desenvolvimento;
- revisão;
- correção;
- design;
- documentação.

A IA não substituiu as tecnologias exigidas pelo desafio.

O projeto continua utilizando HTML5 e CSS3 como tecnologias responsáveis pela construção da página.

## Onde a IA foi utilizada

A IA auxiliou em:

- planejamento da Landing Page;
- estrutura semântica do HTML;
- organização das seções;
- criação dos cards;
- revisão de HTML;
- revisão de CSS;
- criação da responsividade;
- escolha da paleta;
- criação de efeitos visuais;
- análise de acessibilidade;
- centralização do formulário;
- criação de textos;
- criação das imagens da galeria;
- identificação de erros;
- documentação do projeto;
- preparação do README.

---

# 🧠 Prompt completo para criação da Landing Page

Abaixo está um prompt que representa, de forma consolidada, os requisitos utilizados para desenvolver o projeto desde o início.

```text
Crie uma Landing Page completa e responsiva para a empresa SOS Security,
especializada em soluções de segurança eletrônica.

O projeto será desenvolvido como atividade acadêmica e deverá utilizar
somente HTML5 e CSS3.

REGRAS:

1. Não utilizar JavaScript.
2. Não utilizar CSS inline.
3. Não utilizar a tag <style> dentro do HTML.
4. Todo o CSS deverá ficar em um arquivo externo.
5. Utilizar HTML5 semântico.
6. O projeto deverá funcionar em desktop, tablet e smartphone.
7. Não deverá existir rolagem horizontal.
8. Aplicar boas práticas de acessibilidade.
9. Utilizar textos alternativos descritivos nas imagens.
10. Utilizar uma hierarquia correta de títulos.

ESTRUTURA HTML OBRIGATÓRIA:

Utilizar:

<header>
<nav>
<main>
<section>
<article>
<footer>

A LANDING PAGE DEVERÁ POSSUIR:

1. HEADER

Criar um cabeçalho contendo:

- logotipo da SOS Security;
- menu de navegação;
- links para as principais seções;
- botão de contato.

Itens do menu:

Início
Sobre
Serviços
Galeria
Contato

2. HERO

Criar uma seção Hero de grande impacto visual.

Utilizar uma imagem relacionada à segurança eletrônica como background.

Adicionar uma camada escura sobre a imagem para melhorar a leitura.

Adicionar:

Texto:
"Segurança • Tecnologia • Confiança"

Título:
"Soluções completas em Segurança Eletrônica"

Descrição curta apresentando a empresa.

Adicionar dois botões de chamada para ação.

Criar no título um efeito de brilho ou faixa luminosa atravessando
as letras horizontalmente.

O efeito deverá ser desenvolvido exclusivamente com CSS.

3. SOBRE

Criar uma seção apresentando a SOS Security.

Adicionar cards destacando:

- Experiência;
- Atendimento;
- Suporte Técnico.

4. SERVIÇOS

Criar uma seção chamada "Nossos Serviços".

Cada serviço deverá ser representado utilizando <article>.

Criar seis cards:

01 - CFTV
02 - Controle de Acesso
03 - Sistema de Incêndio
04 - Cerca Elétrica
05 - Cabeamento Estruturado
06 - Portões Automáticos

Os cards deverão possuir:

- número;
- título;
- descrição;
- bordas arredondadas;
- sombra suave;
- efeito hover;
- detalhe visual em azul.

No desktop apresentar 3 cards por linha.

No tablet apresentar 2 cards por linha.

No smartphone apresentar 1 card por linha.

5. GALERIA

Criar uma galeria responsiva utilizando <figure>, <img> e <figcaption>.

Utilizar três imagens:

- CFTV;
- Controle de Acesso;
- Equipamentos de Segurança Eletrônica.

As imagens deverão possuir textos alternativos descritivos.

6. CONTATO

Criar uma seção de contato.


Criar um formulário contendo:

- Nome;
- E-mail;
- Telefone;
- Serviço;
- Mensagem.

Centralizar o formulário na página.

7. FOOTER

Criar um Footer contendo:

- nome da empresa;
- links de navegação;
- informações de contato;
- identificação do projeto.

8. IDENTIDADE VISUAL

Utilizar uma identidade baseada na cor azul.

Paleta principal:

Azul ciano: #4CC9F0
Azul ciano escuro: #219EBC
Azul claro: #78D7FF
Azul escuro: #0A1929
Azul petróleo: #203A43
Branco: #FFFFFF
Cinza claro: #F4F7FB

9. RESPONSIVIDADE

Criar Media Queries para:

- desktop;
- tablet;
- smartphone;
- telas muito pequenas.

Garantir que:

- os cards sejam reorganizados;
- o menu se adapte;
- o formulário permaneça dentro da tela;
- as imagens sejam responsivas;
- não exista rolagem horizontal.

10. ACESSIBILIDADE

Implementar:

- alt nas imagens;
- labels nos formulários;
- hierarquia correta de headings;
- contraste adequado;
- :focus-visible;
- prefers-reduced-motion.

11. ORGANIZAÇÃO DO CÓDIGO

Comentar o CSS por blocos, por exemplo:

RESET
HEADER
MENU
HERO
SOBRE
SERVIÇOS
GALERIA
CONTATO
FOOTER
RESPONSIVIDADE
ACESSIBILIDADE

Os comentários devem facilitar a leitura, manutenção e explicação
do código durante a apresentação acadêmica.

12. ESTRUTURA DO PROJETO

Organizar da seguinte maneira:

Projeto-SOS-Security/
│
├── index.html
├── README.md
│
├── css/
│   └── style.css
│
└── images/
    ├── logo.png
    ├── hero-bg.png
    ├── galeria-01.jpg
    ├── galeria-02.jpg
    └── galeria-03.jpg

O resultado deverá ser uma Landing Page moderna, profissional,
responsiva, acessível e adequada à identidade visual da SOS Security,
utilizando somente HTML5 e CSS3.
```

---

# 💬 Outros prompts utilizados durante o desenvolvimento

Além do prompt principal, foram utilizadas solicitações específicas para aprimorar partes da página.

### Serviços

```text
Transforme a seção Nossos Serviços em cards responsivos utilizando
elementos <article>.
```

### Hero

```text
Crie uma animação somente com CSS com um efeito de brilho ou
degradê passando pelo título do Hero da esquerda para a direita.
```

### Identidade visual

```text
Troque tudo que estiver verde na página por uma cor que combine
com o Hero e com a identidade azul da empresa.
```

### Formulário

```text
Centralize o formulário da seção de contato mantendo o layout
responsivo.
```

### Responsividade

```text
Revise o CSS para garantir funcionamento em desktop, tablet
e smartphone sem rolagem horizontal.
```

### Galeria

```text
Crie imagens individuais para a galeria de uma Landing Page
de uma empresa de segurança eletrônica.
```

---

# 🧩 Decisões tomadas durante o desenvolvimento

Durante a construção da Landing Page algumas decisões foram tomadas para adequar o projeto às regras do desafio.

## Menu mobile sem JavaScript

Como JavaScript não é permitido, foi evitada a dependência de um menu hamburger controlado por script.

Em telas pequenas o menu é reorganizado através de CSS.

## Efeito do Hero

A animação do título foi criada exclusivamente com:

```css
@keyframes
```

e propriedades de background do CSS.

## Formulário

O formulário inicialmente fazia parte de uma composição em colunas.

Posteriormente foi centralizado para melhorar o equilíbrio visual da seção de contato.

## Paleta

Os elementos verdes existentes durante uma etapa do desenvolvimento foram substituídos por azul/ciano para manter a identidade visual da empresa.

## Cards

Os serviços foram transformados em elementos `<article>` para melhorar a semântica do documento e atender às exigências acadêmicas.

---

# 🔄 Controle de versão com Git

O projeto utiliza Git para registrar as principais etapas do desenvolvimento.

Para atender ao desafio, os commits devem representar alterações significativas.

## Estratégia de commits

Os commits planejados para a versão final são:

```text
feat: cria estrutura semantica da landing page
```

Responsável pela estrutura inicial em HTML5.

---

```text
style: adiciona layout responsivo e identidade visual
```

Responsável pela estilização, paleta, Hero e responsividade.

---

```text
feat: adiciona servicos galeria e formulario de contato
```

Responsável pelas principais áreas de conteúdo da Landing Page.

---

```text
docs: adiciona documentacao e uso de IA no README
```

Responsável pela documentação final do projeto.

> Os commits acima devem ser registrados no histórico real do Git. Esta seção documenta a estratégia utilizada; ela não substitui o histórico do repositório.

---

# 💻 Comandos Git utilizados

Após finalizar os arquivos, o fluxo de versionamento pode ser realizado utilizando:

```bash
git status
```

Verifica os arquivos modificados.

```bash
git add .
```

Adiciona os arquivos ao próximo commit.

```bash
git commit -m "mensagem do commit"
```

Registra uma etapa do desenvolvimento.

```bash
git push
```

Envia os commits para o GitHub.

Para consultar o histórico:

```bash
git log --oneline
```

---

# 🌐 Publicação com GitHub Pages

O projeto será publicado utilizando **GitHub Pages**.

Após a publicação, a Landing Page poderá ser acessada diretamente pelo navegador.

## Site

🔗 **GitHub Pages:**

```text
LINK_DO_GITHUB_PAGES
```

> Este endereço será atualizado após a publicação definitiva.

---

# 💻 Repositório

O código-fonte do projeto está disponível em:

**GitHub**

```text
https://github.com/Darknen/Projeto-SOS-Security
```

---

# ✅ Checklist do desafio

## HTML semântico

- [x] Header
- [x] Nav
- [x] Main
- [x] Section
- [x] Article
- [x] Footer
- [x] Hierarquia de títulos

## Conteúdo

- [x] Hero
- [x] Sobre
- [x] Serviços
- [x] Pelo menos 3 cards
- [x] Galeria
- [x] Contato
- [x] Footer

## CSS

- [x] CSS externo
- [x] Identidade visual
- [x] Cards
- [x] Efeitos de hover
- [x] Animações em CSS
- [x] Media Queries

## Responsividade

- [x] Desktop
- [x] Tablet
- [x] Smartphone

## Acessibilidade

- [x] HTML semântico
- [x] Alt nas imagens
- [x] Hierarquia de títulos
- [x] Focus visible
- [x] Redução de movimento

## JavaScript

- [x] Projeto desenvolvido sem JavaScript

## Git e GitHub

- [x ] Confirmar pelo menos 3 commits significativos
- [ x] Enviar versão final para o GitHub
- [ x] Confirmar repositório atualizado

## GitHub Pages

- [ ] Publicar a versão final
- [ ] Testar o endereço público
- [ ] Adicionar o endereço neste README

## Inteligência Artificial

- [x] Uso da IA documentado
- [x] Prompt principal documentado
- [x] Exemplos de prompts documentados
- [x] Finalidade do uso da IA explicada

---

# 📊 Critérios do desafio

O projeto foi desenvolvido considerando os critérios de avaliação:

| Critério | Valor |
|---|---:|
| HTML semântico | 2,0 |
| CSS e organização visual | 2,0 |
| Responsividade | 1,5 |
| Acessibilidade | 1,5 |
| Git e GitHub | 1,0 |
| GitHub Pages | 1,0 |
| Uso consciente de IA | 0,5 |
| Pitch / apresentação | 0,5 |
| **Total** | **10,0** |

---

# 🎤 Resumo para apresentação

A Landing Page foi desenvolvida para apresentar a SOS Security, empresa da área de segurança eletrônica.

O projeto utiliza HTML5 semântico e CSS3 externo, sem JavaScript.

A página possui Hero, informações sobre a empresa, cards de serviços, galeria, área de contato e Footer.

O layout foi desenvolvido para funcionar em desktop, tablet e smartphone e também foram aplicadas práticas de acessibilidade.

A identidade visual utiliza principalmente tons de azul relacionados à identidade da empresa.

O projeto utiliza Git e GitHub para controle de versão e será publicado através do GitHub Pages.

A Inteligência Artificial foi utilizada como ferramenta de apoio para planejamento, revisão de código, responsividade, design, geração de imagens e documentação.

---

# 👨‍💻 Autor

**Carlos**

Projeto desenvolvido como atividade acadêmica de desenvolvimento web.

---

# 📚 Informações acadêmicas

**Projeto:** Desafio 01 — Tire sua Ideia do Papel  
**Tipo:** Landing Page  
**Tecnologias principais:** HTML5 e CSS3  
**Controle de versão:** Git e GitHub  
**Publicação:** GitHub Pages  
**Uso de IA:** Documentado neste README  

---

# 📄 Finalidade

Este projeto foi desenvolvido para fins acadêmicos e educacionais.