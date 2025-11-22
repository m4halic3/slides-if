# Modelo Base de Slides em Marp

Este repositório contém um modelo de slides desenvolvido em Markdown utilizando o Marp. O objetivo é oferecer uma estrutura padrão para apresentações acadêmicas, permitindo reutilização e consistência visual em futuros trabalhos.

## Sobre o Template

O modelo inclui:

- Imagem de fundo aplicada em todos os slides  
- Logo fixa no canto superior esquerdo  
- Tipografia padronizada (Inter e Playfair Display)  
- Slide de capa com título, subtítulo, nome do aluno, disciplina e professor  
- Paginação automática iniciando após o sumário  
- Slide de agradecimento centralizado  
- Estilização consistente para títulos, tópicos e texto  
- Suporte a HTML e CSS no arquivo Markdown

## Tecnologias Utilizadas

- Marp (VS Code extension ou Marp CLI)  
- Markdown  
- HTML e CSS  
- Fontes do Google Fonts  

## Estrutura do Projeto
```
│
├── assets/
│ └── img/
│ ├── fundo-slide.png
│ └── logo-if.png
│
├── slides.md
└── README.md
```
## Como Usar

1. Instalar a extensão “Marp for VS Code”.
2. Abrir o arquivo `slides.md` no VS Code.
3. Usar a visualização do Marp para acompanhar o slide durante a edição.
4. Exportar o arquivo através do comando:
   - Exportar para PDF, HTML ou PPTX pelo menu de comando do Marp.

## Como Editar

Para alterar título, subtítulo ou nome do aluno, basta localizar no arquivo:

```md
<h1>TÍTULO DO TRABALHO</h1>
<h2>Subtítulo Opcional</h2>
<p class="nome">Nome do Aluno</p>
```

Para alterar disciplina e professor:

```md
<p class="disciplina">
  Disciplina: Nome da Disciplina  
  Professor(a): Nome do Professor
</p>
```

Para substituir a logo ou a imagem de fundo, basta trocar os arquivos dentro de assets/img/.

## Objetivo do Repositório
Manter um modelo estável, simples e reutilizável para apresentações futuras, garantindo padronização visual, clareza e facilidade de edição apenas com Markdown.

### Licença
Uso livre para fins acadêmicos e institucionais.
