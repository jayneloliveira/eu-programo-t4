# Conteúdo das aulas do curso Eu ProgrAmo

## Aula 1 - Conceitos básicos e HMTL
### Conceitos básicos
- Internet;
- Front vs. back;
- Introdução Projeto;
- Navegadores, website;
- Editores de texto.

#### Editores de texto
Para se modificar um arquivo .html e .css, precisamos de editor de texto. Apesar de que um simples bloco de notas pode ser a ferramenta para criação desses arquivos, vários softwares foram lançados no mercado para gostos dos programado res, oferecendo facilidades e plugins para facilitar o desenvolvimento. Alguns famosos e notáveis são:
- [Sublime Text](https://www.sublimetext.com/);
- [Notepad++](https://notepad-plus-plus.org/);
- [Atom](https://atom.io/);
- O que vamos usar durante as aulas é o [Visual Studio Code](https://code.visualstudio.com/);


#### Estrutura de pastas
A estrutura de pastas básicas é:
```
css
   style.css
img
   imagem.jpg

index.html
```
Ou seja, uma pasta com um arquivo **index.html na raiz** e duas pastas:
- Pasta *css* para inserção de nossos estilos .css 
- Pasta *img* para inserção de nossas imagens.

-----

### HTML
HTML é uma abreviação de **Hyper Text Markup Language** (linguagem de marcação em hipertexto). Ou seja, não se trata de uma linguagem de programação, pois não tem lógica (algoritmos, processos etc). Ele cria a **estrutura** de uma página ou aplicação web, determinando a separação de layout e seu conteúdo.

Documentos .html possuem tags de estruturação básica:
```html
<!doctype html>
<html>
    <head></head>
    <body></body>
</html>
```

Internamente, as tags html possuem uma anatomia básica também:
```html
<nome-da-tag atributo="valor do atributo">
    conteúdo
</nome-da-tag>
```