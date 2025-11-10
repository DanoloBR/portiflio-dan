---

### 🧮 1. Soma de dois numeros inteiros

```mermaid
flowchart TD
    A([Inicio])
    B[Declarar num1, num2, soma]
    C[Solicitar: Digite o primeiro numero inteiro]
    D{Entrada valida?}
    E[Solicitar novamente num1]
    F[Solicitar: Digite o segundo numero inteiro]
    G{Entrada valida?}
    H[Solicitar novamente num2]
    I[soma = num1 + num2]
    J[Exibir num1, num2 e soma]
    K([Fim])

    A --> B --> C --> D
    D -->|Nao| E --> D
    D -->|Sim| F --> G
    G -->|Nao| H --> G
    G -->|Sim| I --> J --> K
```

---

### ⚪ 2. Area do circulo

```mermaid
flowchart TD
    A([Inicio])
    B[Declarar raio, area, pi = 3.14]
    C[Solicitar: Digite o valor do raio]
    D{Entrada valida e raio >= 0?}
    E[Solicitar novamente raio]
    F[area = pi * raio²]
    G[Exibir pi, raio e area]
    H([Fim])

    A --> B --> C --> D
    D -->|Nao| E --> D
    D -->|Sim| F --> G --> H
```

---

### ⚖️ 3. Calculo do IMC

```mermaid
flowchart TD
    A([Inicio])
    B[Declarar peso, altura, imc]
    C[Solicitar: Digite o peso em kg]
    D{Entrada valida e peso > 0?}
    E[Solicitar novamente peso]
    F[Solicitar: Digite a altura em metros]
    G{Entrada valida e altura > 0?}
    H[Solicitar novamente altura]
    I[imc = peso / altura²]
    J[Exibir peso, altura e imc]
    K([Fim])

    A --> B --> C --> D
    D -->|Nao| E --> D
    D -->|Sim| F --> G
    G -->|Nao| H --> G
    G -->|Sim| I --> J --> K
```

---

### 🔤 4. Letra e codigo ASCII

```mermaid
flowchart TD
    A([Inicio])
    B[Declarar letra]
    C[Solicitar: Digite uma letra]
    D{Entrada valida e eh letra?}
    E[Solicitar novamente letra]
    F[Exibir letra digitada]
    G[Exibir codigo ASCII da letra]
    H[Exibir letra maiuscula]
    I([Fim])

    A --> B --> C --> D
    D -->|Nao| E --> D
    D -->|Sim| F --> G --> H --> I
```

---

### 🔢 5. Numero par ou impar

```mermaid
flowchart TD
    A([Inicio])
    B[Declarar numero]
    C[Solicitar: Digite um numero inteiro]
    D{Entrada valida?}
    E[Solicitar novamente numero]
    F[resto = numero % 2]
    G{resto == 0?}
    H[Exibir: Numero eh par]
    I[Exibir: Numero eh impar]
    J[Exibir numero e resto]
    K([Fim])

    A --> B --> C --> D
    D -->|Nao| E --> D
    D -->|Sim| F --> G
    G -->|Sim| H --> J --> K
    G -->|Nao| I --> J --> K
```

---

### 👤 6. Leitura do nome

```mermaid
flowchart TD
    A([Inicio])
    B[Declarar nome]
    C[Solicitar: Digite seu primeiro nome]
    D{Entrada valida e nao vazia?}
    E[Solicitar novamente nome]
    F[Exibir: Ola, nome]
    G[Exibir: Prazer em conhece-lo, nome]
    H[Exibir: Comprimento do nome]
    I([Fim])

    A --> B --> C --> D
    D -->|Nao| E --> D
    D -->|Sim| F --> G --> H --> I
```

---

### ⏳ 7. Dias e horas de vida

```mermaid
flowchart TD
    A([Inicio])
    B[Declarar idade, diasDeVida, horasDeVida]
    C[Solicitar: Digite sua idade em anos]
    D{Entrada valida e idade >= 0?}
    E[Solicitar novamente idade]
    F[diasDeVida = idade * 365]
    G[horasDeVida = diasDeVida * 24]
    H[Exibir idade, dias e horas de vida]
    I([Fim])

    A --> B --> C --> D
    D -->|Nao| E --> D
    D -->|Sim| F --> G --> H --> I
```

---
Perfeito ✅
Abaixo estão **3 fluxogramas em formato Mermaid totalmente compatíveis com o GitHub**, correspondendo exatamente aos códigos C que você enviou.
Todos seguem o mesmo estilo dos anteriores: sem acentos, sem aspas, sem símbolos especiais e prontos para renderizar corretamente no `README.md`.

---

### 🧮 1. Media de dois valores reais

```mermaid
flowchart TD
    A([Inicio])
    B[Declarar valor1, valor2, media]
    C[Solicitar: Digite o primeiro valor]
    D{Entrada valida?}
    E[Solicitar novamente valor1]
    F[Solicitar: Digite o segundo valor]
    G{Entrada valida?}
    H[Solicitar novamente valor2]
    I[media =  'valor1 + valor2' / 2]
    J[Exibir valor1]
    K[Exibir valor2]
    L[Exibir media]
    M([Fim])

    A --> B --> C --> D
    D -->|Nao| E --> D
    D -->|Sim| F --> G
    G -->|Nao| H --> G
    G -->|Sim| I --> J --> K --> L --> M
```

---

### 🌡️ 2. Conversao de Celsius para Fahrenheit

```mermaid
flowchart TD
    A([Inicio])
    B[Declarar celsius, fahrenheit]
    C[Solicitar: Digite a temperatura em Celsius]
    D{Entrada valida?}
    E[Solicitar novamente celsius]
    F[fahrenheit = '9 * celsius + 160' / 5]
    G[Exibir temperatura em Celsius]
    H[Exibir temperatura em Fahrenheit]
    I[Exibir diferenca entre escalas]
    J([Fim])

    A --> B --> C --> D
    D -->|Nao| E --> D
    D -->|Sim| F --> G --> H --> I --> J
```

---

### 💰 3. Reajuste salarial

```mermaid
flowchart TD
    A([Inicio])
    B[Declarar salario, percentual, novoSalario]
    C[Solicitar: Digite o salario base]
    D{Entrada valida e salario >= 0?}
    E[Solicitar novamente salario]
    F[Solicitar: Informe o percentual de aumento]
    G{Entrada valida?}
    H[Solicitar novamente percentual]
    I[novoSalario = salario + 'salario * percentual / 100']
    J[Exibir salario base]
    K[Exibir percentual de aumento]
    L[Exibir novo salario]
    M([Fim])

    A --> B --> C --> D
    D -->|Nao| E --> D
    D -->|Sim| F --> G
    G -->|Nao| H --> G
    G -->|Sim| I --> J --> K --> L --> M
```

---
