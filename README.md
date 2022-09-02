# Simulado de entrevista técnica

Desenvolva uma função chamada **aumentaSalario** que recebe como parâmetro uma lista de funcionários. Está lista já estará criada no script.js.

Sua função deve percorrer está lista e verificar o departamento de cada funcionário, caso o departamento seja **financeiro** você deve dar um aumento de **500** ao seu salário. Ao final deve ser retornada a lista com os salários atualizados.

Exemplo de retorno:

```javascript
[
    {
        nome: "Jose",
        email: "jose@gmail.com",
        departamento: "Financeiro",
        salario: 1700,
        tempoEmpresa: 2,
    },
    {
        nome: "João",
        email: "joao@gmail.com",
        departamento: "TI",
        salario: 1200,
        tempoEmpresa: 2,
    },
    {
        nome: "Andre",
        email: "andre@gmail.com",
        departamento: "Infra",
        salario: 1200,
        tempoEmpresa: 8,
    },
];
```

Repare que o salário de Jose era **1200** e foi atualizado para  **1700**, pois ele pertence ao departamento **Financeiro**.
