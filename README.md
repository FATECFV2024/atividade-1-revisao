# Atividade 1 - Revisão de Conceitos

## Sumário 
- [Como Utilizar Esse Projteto](#como-utilizar-esse-projeto-)
- [Escopo da Atividade](#escopo-da-atividade-%EF%B8%8F) 
- [No Google ClassRoom](#no-google-clasroom--)
- [Regras](#regras-)
- [Feedback](#feedback-)

## Como Utilizar Esse Projeto 📁

- Nesse projeto há pasta:
    - src:Exclusiva para incluir os códigos esperados

- Na sua máquina tem que ter instalado o <a href="https://www.oracle.com/br/java/technologies/downloads/" target="_blank">Java Development Kit (JDK) </a> 
- Caso utilize o VisualStudio Code é necessário que instale a <a href="https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack" target="_blank">Extension Pack for Java</a>


## Escopo da Atividade 🛠️
Implementar uma classe que seja capaz de simular todos os cenários abaixo: 

### Contrato para autocorreção no GitHub Classroom

Para que a correção automática funcione, implemente os métodos estáticos abaixo na classe `App`:

```java
public static double[] operacoesBasicas(double a, double b)
public static double calcularINSS(double salario)
public static double calcularIRPF(double salario)
public static int[] converterIdadeEmDias(int totalDias)
```

Regras esperadas pelo corretor:
- `operacoesBasicas`: deve retornar `{soma, subtracao, multiplicacao, divisao}`
- `calcularINSS`: aplica a alíquota sobre o salário inteiro, conforme faixa
- `calcularIRPF`: aplica a alíquota sobre o salário inteiro, conforme faixa
- `converterIdadeEmDias`: retorna `{anos, meses, dias}` considerando ano=365 e mês=30

### 🧮 Exercício 01: Operações Básicas
Escreva um programa JAVA que solicite dois números e exiba a soma, subtração, multiplicação e divisão desses números.

---

### 💸 Exercício 02: Cálculo de INSS
Escreva um programa JAVA que leia o **Nome do Funcionário** e o seu **Salário Fixo**. Através do seu salário, faça o cálculo de desconto do **INSS**:
* **7,5%** para aqueles que ganham até R$ 1.412,00
* **9%** para quem ganha entre R$ 1.412,01 até R$ 2.666,68
* **12%** para os que ganham entre R$ 2.666,69 até R$ 4.000,03
* **14%** para quem ganha de R$ 4.000,04 até R$ 7.786,02

---

### 📑 Exercício 03: Cálculo de IRPF
Escreva um programa JAVA que leia o **Nome do Funcionário** e o seu **Salário Fixo**. Através do seu salário, faça o cálculo de desconto do **IRPF**:
* **Isento** para aqueles que ganham até R$ 2.259,20
* **7,5%** para quem ganha entre R$ 2.259,21 até R$ 2.826,65
* **15%** para os que ganham entre R$ 2.826,66 até R$ 3.751,05
* **22,55%** para quem ganha de R$ 3.751,06 até R$ 4.664,68
* **27,5%** para quem ganhar mais de R$ 4.664,68

---

### 📅 Exercício 04: Conversor de Idade
Escreva um programa JAVA que leia a **Idade de um aluno em dias** e informe em anos, meses e dias.
* **Observação:** Considere que todo ano tem 365 dias (descartando anos bissextos) e todos os meses têm 30 dias.


## No Google ClassRoom  👥

- Não há necessidade fazer o upload do projeto 
- Enviar o Link do Repositório 

## Regras 📄

- Utilize as boas práticas de programação que são sempre mencionadas em aula e nos materiais; 
- Observe sempre os modificadores de acesso em atributos e métodos;
- Observe os nomes de classes e atributos;
- Utilize comentários para elucidar o cenário elaborado;

## Feedback 📨
-  Sua atividade receberá uma pontuação de 0 a 10, que compõe os 30% da Nota da ATV1;
-  A nota será atribuída no Google ClassRoom

## GitHub Classroom - Correção Automática 🤖

Este repositório já possui configuração de autocorreção em:
- `.github/classroom/autograding.json`
- `autograde/Autograder.java`
- `scripts/grade.sh`

Pontuação automática:
- Compilação: 2 pontos
- Exercício 01: 2 pontos
- Exercício 02: 2 pontos
- Exercício 03: 2 pontos
- Exercício 04: 2 pontos

### Como usar
1. Crie a atividade no GitHub Classroom usando este repositório como template.
2. Na atividade, habilite `Autograding`.
3. Importe os testes a partir do arquivo `.github/classroom/autograding.json` (ou configure os mesmos comandos manualmente).
4. Ao receber `push` do aluno, execute os testes de autograding.





