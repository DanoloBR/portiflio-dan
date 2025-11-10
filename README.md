# 🎨 Fluxogramas dos Programas em C

### 🔶 Legenda de Formas

* **Oval** → Início / Fim
* **Paralelogramo** → Entrada / Saída de dados
* **Retângulo** → Processamento (cálculos ou atribuições)
* **Losango** → Decisão (condicionais `if`)

---

## 🧮 1. Soma de dois números inteiros

```mermaid
flowchart TD
  A([Início]) --> B[/Digite o primeiro número inteiro/]
  B --> C[/Digite o segundo número inteiro/]
  C --> D[Calcular soma = num1 + num2]
  D --> E[/Mostrar num1, num2 e soma/]
  E --> F([Fim])
```

---

## 📊 2. Média de dois valores

```mermaid
flowchart TD
  A([Início]) --> B[/Digite o primeiro valor/]
  B --> C[/Digite o segundo valor/]
  C --> D[Calcular média = valor1 + valor2 dividido por 2]
  D --> E[/Mostrar valores e média/]
  E --> F([Fim])
```

---

## ⚪ 3. Área do círculo

```mermaid
flowchart TD
  A([Início]) --> B[/Digite o raio/]
  B --> C[Calcular área = pi * raio²]
  C --> D[/Mostrar pi, raio e área/]
  D --> E([Fim])
```

---

## 🌡️ 4. Conversão Celsius → Fahrenheit

```mermaid
flowchart TD
  A([Início]) --> B[/Digite temperatura em Celsius/]
  B --> C[Calcular fahrenheit = 9 * celsius + 160 dividido por 5]
  C --> D[/Mostrar Celsius e Fahrenheit/]
  D --> E([Fim])
```

---

## ⚖️ 5. Cálculo de IMC

```mermaid
flowchart TD
  A([Início]) --> B[/Digite peso/]
  B --> C[/Digite altura/]
  C --> D[Calcular imc = peso dividido por altura vezes altura]
  D --> E[/Mostrar peso, altura e imc/]
  E --> F([Fim])
```

---

## 🔠 6. Leitura de uma letra

```mermaid
flowchart TD
  A([Início]) --> B[/Digite uma letra/]
  B --> C[/Mostrar letra digitada/]
  C --> D([Fim])
```

---

## 🔢 7. Verificação de número par ou ímpar

```mermaid
flowchart TD
  A([Início]) --> B[/Digite um número inteiro/]
  B --> C[par = num1 % 2]
  C --> D{par == 0?}
  D -->|Sim| E[/Mostrar "Número par"/]
  D -->|Não| F[/Mostrar "Número ímpar"/]
  E --> G([Fim])
  F --> G
```

---

## 💰 8. Novo salário com aumento

```mermaid
flowchart TD
  A([Início]) --> B[/Digite salário base/]
  B --> C[/Digite percentual de aumento/]
  C --> D[novosalario = salario + salario * percentual dividido por 100]
  D --> E[/Mostrar novo salário/]
  E --> F([Fim])
```

---

## 😀 9. Leitura e exibição do nome

```mermaid
flowchart TD
  A([Início]) --> B[/Digite seu nome/]
  B --> C[/Mostrar mensagem com o nome/]
  C --> D([Fim])
```

---

## ⏳ 10. Cálculo de dias de vida

```mermaid
flowchart TD
  A([Início]) --> B[/Digite sua idade/]
  B --> C[AnosDeVida = idade * 365]
  C --> D[/Mostrar idade e dias de vida/]
  D --> E([Fim])
```
