# Testes

### Instalação

```bash
# 1-Crie um projeto Node.js
npm init
# 2-Instale o pacote do Jest.
npm install --save-dev jest
# Veja se o script test foi incluído no package.json.
# "scripts": {
# "test": "jest",
# }
# Execute o Jest pelo Node.js.
npm run test
npm t
Npm test
```

### Modelo de Especificação do Jest

```js
describe("contexto do teste", () => {
  test("o que será testado", () => {
    expect(); // resultado esperado
  });
});
```
