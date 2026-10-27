# 🌟 Formulário de Matrícula | Estrelas do Amanhã

Projeto de estudo desenvolvido acompanhando as aulas da **Rocketseat**, com foco na construção e estilização de formulários utilizando **HTML e CSS**.

A proposta é criar a interface de matrícula de uma escola de educação infantil, reunindo informações da criança, endereço, dados do responsável e opções de matrícula.

## 📋 Sobre o projeto

O formulário está organizado em quatro seções:

- **Informações da criança:** nome completo, data de nascimento, sexo, informações médicas e seleção da certidão de nascimento.
- **Endereço residencial:** CEP, rua, número, cidade e estado.
- **Informações do responsável:** nome, telefone e e-mail.
- **Opções de matrícula:** escolha do turno e de uma modalidade esportiva.

A interface também inclui uma caixa de concordância com os termos, botões de ação e uma área lateral com a identidade visual da escola.

## 🛠️ Tecnologias e recursos utilizados

- **HTML5:** estrutura da página e controles do formulário.
- **CSS3:** layout, tipografia, cores e estados visuais dos componentes.
- **CSS Grid e Flexbox:** organização das colunas, campos e botões.
- **Google Fonts:** utilização da fonte Poppins.
- **SVG:** ícones, logotipo e ilustração.

O projeto foi construído sem JavaScript e sem frameworks.

## 📚 O que aprendi e pratiquei

### 1. Estrutura e organização de formulários

Pratiquei o uso de `form`, `fieldset` e `legend` para dividir o formulário em grupos com títulos e facilitar a compreensão das informações solicitadas.

Também utilizei `label` com os atributos `for` e `id` para associar os textos aos respectivos campos.

Trabalhei com diferentes controles:

- `input` dos tipos `text`, `date`, `number`, `tel` e `email`.
- `select` e `option` para listas de seleção.
- `textarea` para informações mais longas.
- `input type="file"` para escolher um arquivo.
- `radio` para escolher uma opção por grupo.
- `checkbox` para marcar a concordância com os termos.

### 2. Atributos e validação nativa

Pratiquei o uso de `placeholder`, `value`, `name`, `disabled` e `required`, entendendo suas funções nos campos do formulário.

No campo de e-mail, utilizei `type="email"` e `required` para aproveitar a validação do próprio navegador. Com CSS, personalizei a borda e a mensagem de erro conforme a validade desse campo.

Também estudei o uso de `method="post"` e `enctype="multipart/form-data"`, que preparam o formulário para um envio contendo arquivos. O processamento desses dados depende de um servidor.

### 3. Layout com Grid e Flexbox

Utilizei **CSS Grid** para dividir a página entre o formulário e a apresentação da escola, além de organizar os cartões de seleção de turno e esporte.

Com **Flexbox**, alinhei campos lado a lado, como rua e número, e defini proporções diferentes para o espaço ocupado por cada um.

Pratiquei ainda o controle de espaçamentos com `gap`, `padding` e `margin`, o uso de `max-width` e a rolagem independente da área do formulário.

### 4. Personalização dos campos

Trabalhei com `appearance: none` e `all: unset` para personalizar a aparência dos controles, além de bordas, fundos, ícones e indicadores de seleção.

Na área de seleção de arquivos, posicionei o campo sobre uma interface personalizada usando `position: absolute`, `inset` e `opacity`.

Também pratiquei estados e seletores como:

- `:hover`, `:focus` e `:focus-within` para destacar elementos durante a interação.
- `:checked` para representar opções selecionadas.
- `:valid` e `:invalid` para estilizar a validade dos campos.
- `:has()` para alterar o visual de um contêiner conforme o estado de um campo interno.
- Seletores de atributos, como `[disabled]` e `[required]`.

### 5. Organização e reutilização do CSS

Centralizei cores e configurações de tipografia em variáveis declaradas no `:root`, reutilizando esses valores com `var()`.

Dividi os estilos em arquivos por responsabilidade e utilizei `@import` para reuni-los. Também pratiquei o aninhamento de seletores CSS com `&`.

Essa organização facilita localizar os estilos de cada componente e manter a identidade visual da página.

## 📁 Estrutura do projeto

```text
Formulario-de-Matricula/
├── index.html
├── assets/
│   ├── Illustration.svg
│   ├── Logo.svg
│   └── icons/
└── styles/
    ├── styles.css
    ├── global.css
    ├── layout.css
    ├── forms.css
    └── fields/
        ├── index.css
        ├── input.css
        ├── droparea.css
        ├── radio.css
        ├── checkbox.css
        └── buttons.css
```

## 💻 Como visualizar

1. Baixe ou clone este repositório.
2. Abra a pasta do projeto no VS Code.
3. Abra o arquivo `index.html` no navegador ou utilize a extensão **Live Server**.

Não é necessário instalar dependências. A fonte Poppins é carregada pela internet através do Google Fonts.

## 🚧 Escopo desta versão

Esta versão é um exercício de interface com HTML e CSS:

- O botão **Salvar respostas** ainda não possui uma ação implementada.
- O formulário não está conectado a um serviço para receber e armazenar matrículas.
- O CEP não realiza consulta automática; rua, cidade e estado exibem valores de exemplo em campos desabilitados.
- O layout principal foi desenvolvido em duas colunas, sem uma adaptação específica para telas pequenas.

## 👨‍💻 Autor e créditos

Desenvolvido por [Carlos Leonello](https://github.com/carlosleonello), durante os estudos na [Rocketseat](https://www.rocketseat.com.br/).

Este repositório registra minha prática e meus aprendizados na construção de formulários com HTML e CSS.
