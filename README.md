# Desafio: Gerador de PDF Dinâmico
## Tarefa
- Crie uma aplicação React que permita ao usuário introduzir conteúdo textual e imagens, e ao final gerar um PDF e enviar o mesmo para uma API.

## Requisitos
### Formulário de entrada de dados:
- Crie um formulário dinâmico em que o usuário possa introduzir qualquer número de parágrafos e/ou imagens.
- O conteúdo desses parágrafos e imagens será utilizado para gerar um arquivo PDF.

### Renderização do PDF:
- Use a biblioteca [@react-pdf/renderer](https://react-pdf.org) para criar um PDF com base no conteúdo do formulário preenchido pelo usuário.
- O PDF deve ter um cabeçalho (criado a seu critério) que aparece em todas as páginas.
- A renderização das imagens deve ser feita em páginas avulsas, ou seja, sempre que houver uma imagem, ela deve ser renderizada sozinha (incluindo o cabeçalho), em uma única página.
- Você deve utilizar uma fonte não usual para o texto.
- Deverá ser possível pré-visualizar o PDF gerado, sem necessidade de realizar o download do mesmo.
- Deverá ser possível fazer o download do PDF gerado.

### Envio do PDF para a API:
- Deverá ser possível enviar o PDF para alguma API (não precisa fazer isso de verdade, somente o mock da chamada HTTP já é o suficiente).

## Dicas
- Você pode utilizar um framework para criar a aplicação, como o [NextJS](https://nextjs.org).
- Consulte a documentação do [@react-pdf/renderer](https://react-pdf.org) para aprender como criar elementos de texto, imagens e estilos no PDF, bem como alterar a fonte.
- Utilize o [Google Fonts](https://fonts.google.com) para baixar os arquivos de alguma fonte gratuita.

## Critérios de avaliação

### Em ordem de importância: 
1. Atendimento aos requisitos;
2. Organização do código;
3. Complexidade do código/interface visual.

## Entrega
- Deverá ser criado um repositório público contendo o seu projeto e um README com instruções de como rodar e utilizar a aplicação.
