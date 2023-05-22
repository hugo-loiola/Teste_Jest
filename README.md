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

### Exemplo de teste unitário

- Criar um arquivo calculadora.js

```js
// calculadora.js
function soma(a, b) {
  return a + b;
}
exports.soma = soma;
```

- Criar um arquivo calculadora.test.js

```js
// calculadora.test.js
const calculo = require("./calculadora");

describe("funcões matemáticas", () => {
  test("Soma dois numeros", () => {
    expect(calculo.soma(10, 20)).toBe(30);
    expect(calculo.soma(20, 20)).toBe(40);
  });
});
```
