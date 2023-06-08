# Minha primeira biblioteca com NodeJS #
## Validador de links

## 📝 Descrição do projeto

Minha primeira biblioteca criada com o NodeJS, feita para automatizar o processo de verificação e checagem de status de links de um texto. Feito com o curso da Alura sobre [NodeJS](https://cursos.alura.com.br/course/nodejs-criando-primeira-biblioteca).

### COMO USAR
Essa biblioteca analisa os links do seu texto, podendo apenas listar todos eles ou também validá-los para ver se estão funcionando, informando o código do status (404 - not found, 200 - OK, por exemplo), para que você verifique se há a necessidade de atualizar algum link do seu projeto.

Para listar os links apenas, informe o caminho no terminal da seguinte maneira:

```
npm run cli caminho/arquivo.md
```

ou para validar os links:

```
npm run cli caminho/arquivo.md valida
```


## 🔧 Ferramentas e tecnologias ##

* Node JS
* NPM
* JavaScript


## 📌 Funcionalidades ##

Pra facilitar a vida do usuário, a biblioteca traz o código do erro seguido pela descrição. 

Por exemplo, para links que funcionam, ele exibe a mensagem "200 - OK". Se não for encontrado, exibe "404 - not found". Portanto, não é necessário saber o que cada código significa: a biblioteca traz essa descrição pra você.

Caso o site não exista mais, um erro personalizado aparecerá, informando que não foi possível encontrar o site.

## 👩🏻‍💻 Feito por ##

Desenvolvido com ♥ por [Bruna Soncini](www.linkedin.com/in/brunasoncini/).

