# HTML5

É uma linguagem de marcação que tem as seguintes responsabilidades:

- Conteúdo;  
- Semântico (tags);
- Estrutura

* `<h1>` - heading 1 - 6. Normalmente só chega no máximo ao terceiro nível.
Usamos ele quando queremos definir títulos.  
  
- `<a>`  - Link (a - anchor)
Usamos ela para definir a navegação do usuário. Se você tem um texto que você quer que o usuário clique nele e ele va apara outro lugar, você pode usar essa tag junto com o atributo `href`. Exemplo de um `a` que o usuário é direcionado para o site da collabcode.training:

```
<a href="http://collabcode.training">CollabCode.Training</a>
```

> <https://github.com/CollabCodeTech/XDs>

Nota:

> Sessões: Header, Produto, Botões.  
- Charset:
```html
<meta charset="utf-8">
```
O texto que mostra para o usuário fica delimitadas pelas tag `<body>...</body>`, já as tags de configuração ficam delimitadas pela tag `<head>...</head>`.

- `DOCTYPE`
```html
<!DOCTYPE html>
```

- `<nav>` (nasceu no html5). Tags de estrutura.

- Tag `<header>`: cabeçalho do site.
- Tag `<title>`: Título do site. Dentro do `<head>` (sempre?!).

# CSS 

É uma linguagem de estilo, isso quer dizer que ela tem as seguintes responsabilidades:

- Visual;  

## Para passar o link do CSS: ##
Colocar entre as tags `<head> e </head>`:
```html
<link rel="stylesheet" href="header.css">
```
## background-color: ##

## color: ##

## text-decoration ##
- Tirar tracinho debaixo do link: `text-decoration: none;`

## Reset CSS - meyerweb.com ##
- Criar arquivo `reset.css` com o conteúdo de `http://meyerweb.com/eric/tools/css/reset/`.
- Colocar entre as tags `<head> e </head>`:
```html
<link rel="stylesheet" href="reset.css">
```
**antes** de outros arquivos CSS.