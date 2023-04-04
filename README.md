# Ênfases 

**Teste de negrito com asteriscos**
__Teste de negrito com underline__

*Teste de itálico com asteriscos*
_Teste de itálico com underline_

***Todo em negrito e itálico***

~~Tachado~~

**Negrito e _itálico_ aninhado**

Teste de subscrito <sub>Subscrito</sub>

Teste de sobrescrito<sup>Sobrescrito</sup>


## Listas

* Item 1
* Item 2
* Item 3


1. Item 1
   1. SubItem um
   1. SubItem dois
2. Item 2
3. Item 3

## Links

[Github](https://www.github.com)

[https://www.google.com](https://www.google.com)

Perfil: https://github.com/marcelookasaki

### 3 Link com imagem

[![Link do perfil na imagem do octo](https://myoctocat.com/assets/images/base-octocat.svg)](https://github.com/marcelookasaki)


#### 4 Teste de Markdown 


## Teste de Markdown Imagem com url

![Octo](https://myoctocat.com/assets/images/base-octocat.svg)

###### 5 Teste de Markdown
###### 6 Imagem local

![Profe](img/profe.png)

## Inserindo um código

```js
const http = require('http')

const server = http.createServer((req, res) => {
  console.log(`${req.method} - ${req.url}`)
  res.statuscode = 200
  res.setHeader('Content-Type', 'text/html')
  res.end('<h1>Hello World from IEC!</h1>')
})

let port = process.env.PORT || 3000
server.listen(port, () => {
  console.log(`servidor server rodando em http://localhost:${port}`)
})
  ```
## Inserindo lista de tarefas

- [x] fazer compras
- [ ] montar cardápio
- [x] estudar
- [ ] praticar atividade física
- [ ] meditar