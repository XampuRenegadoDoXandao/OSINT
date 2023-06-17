# Inteligência de Código Aberto (OSINT)

Esse repositório contém informações, recursos e ferramentas para performar o básico de [Inteligência de Código Aberto (OSINT)](https://en.wikipedia.org/wiki/Open-source_intelligence), ou seja, conseguir informações de fontes públicas.

## 📖 Conteúdos
- [Projeto](#-projeto)
- [Técnicas básicas](#técnicas-básicas)
   - [Google dorks](#-google-dorks)
     - [Ideia principal](#ideia-principal)
     - [Exemplos práticos](#exemplos-práticos)

## [↑](#-Conteúdos) Projeto

A ideia principal do projeto é conscientizar sobre o uso das redes e o excesso de informação, por meio de uma investigação conduzida pelo próprio usuário para encontrar informações sobre si próprio. O foco é ajudar pessoas com um tutorial fácil de seguir sem entrar em conteúdos extremamente complexos. Sinta-se a vontade para contribuir respeitando a [Licença](/LICENSE).

## Técnicas básicas

### [↑](#-Conteúdos) Google dorks

### Ideia principal

Google dorks é uma forma de pesquisar no google eficiência. A seguir será demonstrado o conceitos básicos.

**intitle:"Teste"** > só aparecerá itens em que "Teste" faça parte do título da página. <br/>
**inurl:"Teste"** > só aparecerá itens em que "Teste" faça parte da URL. <br/>
**intext:"Teste"** > só aparecerá itens em que "Teste" faça parte do texto na página. <br/>
**filetype:pdf** > só aparecerá itens em que tenha um arquivo PDF. <br/>
**OR** > deve ser usado em casos ambíguos, caso esteja procurando por duas coisas ao mesmo tempo. <br/>
**site:"github.com"** > só aparecerá resultados caso o site seja "github.com". <br/>
**-** > é um indicativo de que o item posterior é negativo, ou seja, não aparecerá resultados sobre. <br/>

### Exemplos práticos

A seguir será clarificado de uma forma mais prática como a pesquisa realmente funciona.

**"Nome Sobrenome"** > Só encontrará resultados em que "Nome Sobrenome" faça parte, sem as aspas o google retornaria coisas relacionadas. <br/>
**inurl:"nomedeusuário123"** > Só encontrará resultados em que "nomedeusuário123" faça parte da URL, pode ajudar a encontrar contas em redes sociais. <br/>
**"Nome Sobrenome" filetype:pdf OR filetype:doc** > Só encontrará resultados em que tenha o "Nome Sobrenome" em um arquivo de tipo PDF ou DOC. <br/>
**"Nome Sobrenome" -site:twitter.com -site:facebook.com** > Só aparecerá resultados em que "Nome Sobrenome" faça parte e não seja no site "twitter.com" e "facebook.com". <br/>
