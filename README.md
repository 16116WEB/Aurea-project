# Áurea Relógios

Catálogo demonstrativo de relógios desenvolvido como projeto escolar em HTML e CSS.

## Identificação

- **Integrantes:**
  - João Augusto dos Anjos Nolasco
  - Daniel Heitor Silva Cortes
  - Davi Jelinuir Neves
- **Curso:** Informática para Internet
- **Turma:** IFTP
- **Unidade curricular:** Versionamento e colaboração
- **Professor:** Josué Rodrigo Evangelista Figueirêdo
- **Data:** 13/11/2026

## Sobre o projeto

A Áurea é uma proposta de loja de relógios apresentada em um site de página única. O catálogo reúne os modelos Atlantic, Verona e Eclipse, com imagens, descrições e preços.

O projeto foi desenvolvido para praticar a estruturação de páginas com HTML, a estilização com CSS e a criação de layouts responsivos, além da organização e documentação de código.

> Este é um projeto escolar. A loja, os valores e os dados de contato são demonstrativos. Não são realizadas vendas pelo site.

## Objetivos

- Organizar fotos, nomes, descrições e preços em um único catálogo.
- Facilitar a consulta e a comparação dos modelos apresentados.
- Oferecer navegação simples entre as seções da página.
- Adaptar a apresentação do conteúdo a computadores e celulares.
- Aplicar os conhecimentos adquiridos no projeto de front-end.

## Funcionalidades

- **Catálogo:** apresentação de três relógios com fotos, descrições e preços.
- **Navegação interna:** menu com acesso às seções Produtos, Sobre e Contato.
- **Consulta de disponibilidade:** botões que levam à seção de contato, sem consultar estoque ou enviar mensagens.
- **Apresentação da loja:** seção que explica a proposta da Áurea.
- **Contato demonstrativo:** informações ilustrativas com e-mail fictício.
- **Perguntas frequentes:** respostas que podem ser abertas e fechadas.
- **Retorno ao início:** link disponível no rodapé.
- **Responsividade:** reorganização dos cartões e ajustes de estilo conforme o tamanho da tela.

O site não possui cadastro, login, carrinho de compras, pagamentos ou banco de dados.

## Tecnologias utilizadas

| Tecnologia ou ferramenta | Finalidade |
| --- | --- |
| HTML5 | Estrutura e conteúdo da página |
| CSS3 | Estilização, Flexbox e responsividade |
| Visual Studio Code | Edição dos arquivos |
| Git | Versionamento local do projeto |
| JPEG | Formato das imagens dos produtos |

As perguntas frequentes utilizam os elementos nativos `<details>` e `<summary>` do HTML. A aplicação não utiliza JavaScript ou bibliotecas externas.

## Estrutura do projeto

```text
Aurea_Projeto/
├── index.html
├── aurea.css
├── imagens/
│   ├── atlantic.jpg
│   ├── verona.jpg
│   └── eclipse.jpg
├── .vscode/
│   └── launch.json
├── README.md
└── documentacao/
    ├── Documentacao_Aurea_Projeto.docx
    ├── 01_catalogo.png
    ├── 02_sobre_contato.png
    ├── 03_celular.png
    └── gerar_documentacao.py
```

- **`index.html`:** contém o cabeçalho, o catálogo, as seções informativas e o rodapé.
- **`aurea.css`:** define cores, fontes, espaçamentos, cartões e ajustes para diferentes telas.
- **`imagens/`:** armazena as fotografias dos relógios.
- **`.vscode/launch.json`:** configura a depuração no editor para o endereço `http://localhost:8080`. Não inicia um servidor automaticamente.
- **`README.md`:** apresenta a documentação do projeto.
- **`documentacao/`:** reúne o documento da atividade, as capturas de tela e o script auxiliar de geração da documentação. Esse script não é necessário para executar o site.

## Como executar

### Abertura direta

1. Tenha a pasta completa do projeto no computador.
2. Mantenha os arquivos e as pastas na estrutura apresentada acima.
3. Abra o arquivo `index.html` em um navegador.
4. Utilize o menu para navegar pelas seções e clique nas perguntas frequentes para visualizar as respostas.

Não é necessário instalar dependências ou configurar banco de dados.

### Servidor local opcional

Se você já tiver o Python instalado, abra um terminal na pasta principal do projeto e execute:

```bash
python -m http.server 8080
```

Depois, acesse:

```text
http://localhost:8080
```

Para encerrar o servidor, pressione `Ctrl+C`.

## Demonstração

### Catálogo em computador

![Cabeçalho e catálogo com os três modelos de relógios](documentacao/01_catalogo.png)

Apresentação dos modelos Atlantic, Verona e Eclipse, com imagens, descrições, preços e botões de consulta.

### Sobre, contato e perguntas frequentes

![Seções Sobre e Contato com uma pergunta frequente expandida](documentacao/02_sobre_contato.png)

Informações sobre o projeto, contato demonstrativo e resposta de uma pergunta frequente.

### Visualização em celular

![Catálogo adaptado a uma tela de celular](documentacao/03_celular.png)

Apresentação do menu e dos produtos em uma tela com largura de 390 pixels.

## Melhorias futuras

- Implementar busca por nome e filtros por faixa de preço.
- Criar páginas com especificações detalhadas de cada relógio.
- Adicionar um formulário de contato com validação e envio de mensagens.
- Aprimorar a acessibilidade com testes de contraste e navegação por teclado.
- Otimizar as imagens para reduzir o tempo de carregamento.

Essas melhorias são propostas e ainda não estão implementadas.
