# Plano de Estudos Intensivo - 90 Dias
## De Leigo a Programador No-Code Profissional

**Aluno:** Anderson Ferreira Santos
**Data de Início:** 05 / 01 / 2025
**Compromisso Diário:** 1-2 horas
**Meta Final:** Criar projetos funcionais e profissionais

---

## Regras do Jogo

```
┌─────────────────────────────────────────────────────────────┐
│                    COMPROMISSOS                             │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  1. Estudar TODOS os dias (mesmo que 30min no mínimo)      │
│  2. Praticar > Assistir (70% prática, 30% teoria)          │
│  3. Não pular etapas - fundamentos são sagrados            │
│  4. Anotar dúvidas e perguntar ao Claude                   │
│  5. Comitar código no GitHub diariamente                   │
│  6. Marcar checkbox ao completar cada item                 │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

# MÊS 1: FUNDAMENTOS ABSOLUTOS
## "Sem fundamento, não há edifício"

---

## SEMANA 1: Lógica de Programação + Ambiente
**Meta:** Pensar como programador e configurar ferramentas

### DIA 1 (2h) - Configuração do Ambiente
**Objetivo:** Ter todas as ferramentas prontas

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 30min | Instalar/Configurar Cursor IDE | [cursor.sh](https://cursor.sh) |
| 30min | Criar conta GitHub | [github.com](https://github.com) |
| 30min | Instalar Git | [git-scm.com](https://git-scm.com) |
| 30min | Configurar terminal + extensões | Prática guiada |

**Checklist do dia:**
- [x] Cursor instalado e funcionando
- [x] Conta GitHub criada
- [x] Git instalado (verificar com `git --version`)
- [x] Primeira pasta de projeto criada

**Tarefa prática:**
```bash
# Execute no terminal:
mkdir ~/projetos
cd ~/projetos
mkdir estudos-programacao
cd estudos-programacao
git init
echo "# Minha Jornada de Programação" > README.md
git add .
git commit -m "Primeiro commit - início da jornada"
```

---

### DIA 2 (1.5h) - Introdução à Lógica
**Objetivo:** Entender o que é algoritmo

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 20min | Vídeo: O que é lógica de programação | [Curso em Vídeo - Gustavo Guanabara](https://www.youtube.com/watch?v=8mei6uVttho) |
| 20min | Vídeo: O que é algoritmo | [Curso em Vídeo - Algoritmo](https://www.youtube.com/watch?v=iEVLDKOLgQk) |
| 50min | Prática: Escrever 5 algoritmos do dia-a-dia | Exercício abaixo |

**Exercício Prático - Escreva algoritmos para:**
```
1. Fazer um café
2. Trocar uma lâmpada
3. Sacar dinheiro no caixa eletrônico
4. Atravessar a rua com segurança
5. Fazer login no Instagram

Modelo de resposta:
ALGORITMO: Fazer um café
INÍCIO
  1. Pegar a cafeteira
  2. Colocar água no reservatório
  3. Adicionar pó de café no filtro
  4. Ligar a cafeteira
  5. Aguardar o café ficar pronto
  6. Servir na xícara
FIM
```

**Checklist do dia:**
- [ ] Assisti aos 2 vídeos
- [ ] Escrevi os 5 algoritmos
- [ ] Salvei os algoritmos em um arquivo .txt no projeto

---

### DIA 3 (1.5h) - Variáveis e Tipos de Dados
**Objetivo:** Entender como o computador armazena informações

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 25min | Vídeo: Variáveis | [Curso em Vídeo - Variáveis](https://www.youtube.com/watch?v=RDrfZ-7WE8c) |
| 25min | Leitura: Tipos de dados | [MDN - Tipos de Dados](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Data_structures) |
| 40min | Prática no Claude Code | Exercícios interativos |

**Conceitos para dominar hoje:**
```javascript
// TIPOS DE DADOS PRINCIPAIS

// String (texto) - sempre entre aspas
let nome = "Maria";
let cidade = 'São Paulo';

// Number (números) - sem aspas
let idade = 25;
let preco = 99.90;
let temperatura = -5;

// Boolean (verdadeiro/falso)
let maiorDeIdade = true;
let temCarteira = false;

// Array (lista)
let frutas = ["maçã", "banana", "laranja"];

// Object (objeto)
let pessoa = {
    nome: "João",
    idade: 30,
    cidade: "Rio"
};
```

**Exercício - Criar variáveis para:**
```
1. Seu nome completo
2. Sua idade
3. Se você está estudando (true/false)
4. Lista das 3 linguagens que quer aprender
5. Objeto com seus dados (nome, idade, cidade, profissao)
```

**Checklist do dia:**
- [ ] Sei a diferença entre String, Number e Boolean
- [ ] Entendo o que é um Array
- [ ] Entendo o que é um Objeto
- [ ] Completei os exercícios

---

### DIA 4 (1.5h) - Operadores
**Objetivo:** Fazer cálculos e comparações

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 20min | Vídeo: Operadores | [Curso em Vídeo - Operadores](https://www.youtube.com/watch?v=BP63NhITvao) |
| 30min | Leitura + prática: Operadores JS | [JavaScript.info - Operadores](https://javascript.info/operators) |
| 40min | Exercícios práticos | Lista abaixo |

**Operadores para memorizar:**
```javascript
// ARITMÉTICOS
+   // soma
-   // subtração
*   // multiplicação
/   // divisão
%   // resto da divisão (módulo)
**  // potência

// COMPARAÇÃO
==  // igual (valor)
=== // igual (valor E tipo) ← PREFERIR ESTE
!=  // diferente
>   // maior que
<   // menor que
>=  // maior ou igual
<=  // menor ou igual

// LÓGICOS
&&  // E (AND) - ambos verdadeiros
||  // OU (OR) - pelo menos um verdadeiro
!   // NÃO (NOT) - inverte

// ATRIBUIÇÃO
=   // atribui valor
+=  // soma e atribui (x += 5 é igual a x = x + 5)
-=  // subtrai e atribui
```

**Exercícios - Calcule mentalmente, depois verifique:**
```javascript
// Qual o resultado?
10 + 5 * 2        // ?
(10 + 5) * 2      // ?
10 % 3            // ?
2 ** 3            // ?
10 > 5 && 3 < 1   // ?
10 > 5 || 3 < 1   // ?
!(5 > 3)          // ?
"5" === 5         // ?
"5" == 5          // ?
```

**Checklist do dia:**
- [ ] Sei todos os operadores aritméticos
- [ ] Entendo operadores de comparação
- [ ] Entendo operadores lógicos (&&, ||, !)
- [ ] Sei a diferença entre == e ===

---

### DIA 5 (2h) - Condicionais (if/else)
**Objetivo:** Ensinar o programa a tomar decisões

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 25min | Vídeo: Condicionais | [Curso em Vídeo - Condições](https://www.youtube.com/watch?v=_PqFiRm2DHc) |
| 35min | Leitura interativa | [JavaScript.info - Condicionais](https://javascript.info/ifelse) |
| 60min | Projeto: Verificador de idade | Prática guiada |

**Estrutura do IF/ELSE:**
```javascript
// ESTRUTURA BÁSICA
if (condicao) {
    // código se verdadeiro
}

// COM ELSE
if (condicao) {
    // código se verdadeiro
} else {
    // código se falso
}

// COM ELSE IF
if (condicao1) {
    // código se condição1 verdadeira
} else if (condicao2) {
    // código se condição2 verdadeira
} else {
    // código se nenhuma verdadeira
}

// EXEMPLO PRÁTICO
let idade = 18;

if (idade < 12) {
    console.log("Criança");
} else if (idade < 18) {
    console.log("Adolescente");
} else if (idade < 60) {
    console.log("Adulto");
} else {
    console.log("Idoso");
}
```

**Projeto do dia - Verificador de Situação do Aluno:**
```javascript
// Crie um programa que:
// 1. Recebe a nota do aluno (0-10)
// 2. Verifica a situação:
//    - nota >= 7: "Aprovado"
//    - nota >= 5 e < 7: "Recuperação"
//    - nota < 5: "Reprovado"
// 3. Se aprovado, mostrar mensagem de parabéns
// 4. Se reprovado, mostrar mensagem de incentivo
```

**Checklist do dia:**
- [ ] Entendo a estrutura if/else
- [ ] Sei usar else if para múltiplas condições
- [ ] Completei o projeto do verificador
- [ ] Commitei o código no GitHub

---

### DIA 6 (2h) - Loops (Repetições)
**Objetivo:** Automatizar tarefas repetitivas

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 30min | Vídeo: Estruturas de repetição | [Curso em Vídeo - Repetições](https://www.youtube.com/watch?v=WJaJcD7gFkk) |
| 30min | Leitura: Loops em JS | [JavaScript.info - Loops](https://javascript.info/while-for) |
| 60min | Exercícios práticos | Lista abaixo |

**Tipos de Loop:**
```javascript
// FOR - quando sabe quantas vezes repetir
for (let i = 0; i < 10; i++) {
    console.log(i); // 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
}

// FOR...OF - percorrer arrays
let frutas = ["maçã", "banana", "laranja"];
for (let fruta of frutas) {
    console.log(fruta);
}

// WHILE - enquanto condição for verdadeira
let contador = 0;
while (contador < 5) {
    console.log(contador);
    contador++;
}

// DO...WHILE - executa pelo menos uma vez
let num = 0;
do {
    console.log(num);
    num++;
} while (num < 3);
```

**Exercícios:**
```javascript
// 1. Imprimir números de 1 a 100

// 2. Imprimir apenas números pares de 0 a 50

// 3. Somar todos os números de 1 a 100

// 4. Tabuada do 7

// 5. Percorrer array e mostrar cada item com índice
let nomes = ["Ana", "Bruno", "Carlos", "Diana"];
// Resultado esperado:
// 0: Ana
// 1: Bruno
// 2: Carlos
// 3: Diana
```

**Checklist do dia:**
- [ ] Sei usar for tradicional
- [ ] Sei usar for...of para arrays
- [ ] Sei usar while
- [ ] Completei os 5 exercícios
- [ ] Commitei no GitHub

---

### DIA 7 (1.5h) - Revisão + Projeto da Semana
**Objetivo:** Consolidar conhecimento com projeto prático

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 30min | Revisão dos conceitos | Releitura das anotações |
| 60min | Projeto: Jogo de Adivinhação | Construir do zero |

**Projeto da Semana 1 - Jogo de Adivinhação:**
```javascript
/*
REQUISITOS DO JOGO:
1. O programa escolhe um número aleatório de 1 a 100
2. O jogador tem 7 tentativas para acertar
3. A cada tentativa, informar se o número é maior ou menor
4. Mostrar quantas tentativas restam
5. Se acertar, mostrar "Parabéns! Você acertou em X tentativas"
6. Se perder, mostrar "Game Over! O número era X"

CONCEITOS USADOS:
- Variáveis
- Condicionais
- Loops
- Operadores
*/

// Dica para número aleatório:
let numeroSecreto = Math.floor(Math.random() * 100) + 1;
```

**Checklist da Semana 1:**
- [ ] Ambiente configurado (Cursor, Git, GitHub)
- [ ] Sei escrever algoritmos em português
- [ ] Domino variáveis e tipos de dados
- [ ] Sei usar operadores
- [ ] Domino condicionais (if/else)
- [ ] Domino loops (for, while)
- [ ] Projeto da semana completo e no GitHub

---

## SEMANA 2: Funções + Arrays + Objetos
**Meta:** Organizar código e manipular dados

### DIA 8 (1.5h) - Funções Básicas
**Objetivo:** Criar blocos de código reutilizáveis

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 25min | Vídeo: Funções em JavaScript | [Curso em Vídeo - Funções](https://www.youtube.com/watch?v=aQQnJ_I-phE) |
| 25min | Leitura | [JavaScript.info - Funções](https://javascript.info/function-basics) |
| 40min | Exercícios práticos | Lista abaixo |

**Anatomia de uma Função:**
```javascript
// DECLARAÇÃO DE FUNÇÃO
function saudacao(nome) {
    return `Olá, ${nome}!`;
}

// CHAMADA DA FUNÇÃO
let mensagem = saudacao("Maria");
console.log(mensagem); // "Olá, Maria!"

// FUNÇÃO COM MÚLTIPLOS PARÂMETROS
function calcularMedia(nota1, nota2, nota3) {
    let soma = nota1 + nota2 + nota3;
    let media = soma / 3;
    return media;
}

let resultado = calcularMedia(7, 8, 9);
console.log(resultado); // 8

// ARROW FUNCTION (forma moderna)
const dobrar = (numero) => numero * 2;
const somar = (a, b) => a + b;
```

**Exercícios - Criar funções para:**
```javascript
// 1. Verificar se número é par ou ímpar
function ehPar(numero) {
    // retornar true se par, false se ímpar
}

// 2. Calcular área do retângulo
function areaRetangulo(base, altura) {
    // retornar base * altura
}

// 3. Converter Celsius para Fahrenheit
function celsiusParaFahrenheit(celsius) {
    // F = C * 9/5 + 32
}

// 4. Verificar se pessoa pode votar
function podeVotar(idade) {
    // retornar true se >= 16
}

// 5. Calcular desconto
function aplicarDesconto(preco, percentualDesconto) {
    // retornar preço com desconto aplicado
}
```

**Checklist do dia:**
- [ ] Sei criar funções com function
- [ ] Sei usar parâmetros e return
- [ ] Sei criar arrow functions
- [ ] Completei os 5 exercícios

---

### DIA 9 (1.5h) - Arrays (Listas)
**Objetivo:** Trabalhar com coleções de dados

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 20min | Vídeo: Arrays | [Curso em Vídeo - Arrays](https://www.youtube.com/watch?v=L06WPHkdxQk) |
| 30min | Leitura: Métodos de Array | [JavaScript.info - Arrays](https://javascript.info/array) |
| 40min | Prática com métodos | Exercícios |

**Métodos Essenciais de Array:**
```javascript
let frutas = ["maçã", "banana", "laranja"];

// ADICIONAR
frutas.push("uva");        // adiciona no final
frutas.unshift("morango"); // adiciona no início

// REMOVER
frutas.pop();              // remove do final
frutas.shift();            // remove do início

// ENCONTRAR
frutas.indexOf("banana");  // retorna posição (1)
frutas.includes("maçã");   // retorna true/false

// TAMANHO
frutas.length;             // quantidade de itens

// FATIAR
frutas.slice(1, 3);        // retorna parte do array

// JUNTAR
frutas.join(", ");         // "maçã, banana, laranja"

// ORDENAR
frutas.sort();             // ordem alfabética
frutas.reverse();          // inverte ordem
```

**Métodos Modernos (MUITO IMPORTANTES):**
```javascript
let numeros = [1, 2, 3, 4, 5];

// MAP - transforma cada item
let dobrados = numeros.map(n => n * 2);
// [2, 4, 6, 8, 10]

// FILTER - filtra itens
let pares = numeros.filter(n => n % 2 === 0);
// [2, 4]

// FIND - encontra primeiro item
let maiorQue3 = numeros.find(n => n > 3);
// 4

// REDUCE - reduz a um valor
let soma = numeros.reduce((acc, n) => acc + n, 0);
// 15

// FOREACH - executa para cada item
numeros.forEach(n => console.log(n));
```

**Exercícios:**
```javascript
let alunos = [
    { nome: "Ana", nota: 8 },
    { nome: "Bruno", nota: 6 },
    { nome: "Carlos", nota: 9 },
    { nome: "Diana", nota: 5 }
];

// 1. Pegar apenas os nomes (usar map)

// 2. Filtrar aprovados (nota >= 7)

// 3. Encontrar quem tirou 9

// 4. Calcular média da turma (usar reduce)

// 5. Verificar se alguém reprovou (nota < 5)
```

**Checklist do dia:**
- [ ] Sei adicionar/remover itens de arrays
- [ ] Sei usar map, filter, find
- [ ] Sei usar reduce
- [ ] Completei os exercícios

---

### DIA 10 (1.5h) - Objetos
**Objetivo:** Estruturar dados complexos

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 25min | Vídeo: Objetos | [Curso em Vídeo - Objetos](https://www.youtube.com/watch?v=6_zk0gPHWgM) |
| 25min | Leitura | [JavaScript.info - Objetos](https://javascript.info/object) |
| 40min | Prática | Exercícios |

**Trabalhando com Objetos:**
```javascript
// CRIANDO OBJETOS
let usuario = {
    nome: "João Silva",
    idade: 28,
    email: "joao@email.com",
    ativo: true,
    enderecos: [
        { cidade: "São Paulo", cep: "01234-000" },
        { cidade: "Rio de Janeiro", cep: "20000-000" }
    ],
    apresentar: function() {
        return `Olá, sou ${this.nome}`;
    }
};

// ACESSANDO PROPRIEDADES
console.log(usuario.nome);           // "João Silva"
console.log(usuario["email"]);       // "joao@email.com"
console.log(usuario.enderecos[0].cidade); // "São Paulo"

// MODIFICANDO
usuario.idade = 29;
usuario.telefone = "11999999999"; // adiciona nova propriedade

// DELETANDO
delete usuario.ativo;

// VERIFICANDO
"nome" in usuario;                   // true
usuario.hasOwnProperty("email");     // true

// ITERANDO
Object.keys(usuario);    // ["nome", "idade", "email", ...]
Object.values(usuario);  // ["João Silva", 28, ...]
Object.entries(usuario); // [["nome", "João Silva"], ...]

// DESTRUCTURING (muito usado!)
const { nome, idade } = usuario;
console.log(nome);  // "João Silva"
```

**Exercícios:**
```javascript
// 1. Criar objeto "produto" com: nome, preco, estoque, categoria

// 2. Criar array de 3 produtos

// 3. Função que recebe produto e aplica 10% de desconto

// 4. Filtrar produtos com estoque > 0

// 5. Calcular valor total do estoque (preco * estoque de cada)
```

**Checklist do dia:**
- [ ] Sei criar objetos
- [ ] Sei acessar e modificar propriedades
- [ ] Sei usar destructuring
- [ ] Sei iterar sobre objetos
- [ ] Completei os exercícios

---

### DIA 11 (1.5h) - Manipulação de Strings
**Objetivo:** Processar textos como um profissional

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 20min | Leitura: Métodos de String | [JavaScript.info - Strings](https://javascript.info/string) |
| 30min | Prática com métodos | Exercícios guiados |
| 40min | Mini-projeto: Validador | Construir |

**Métodos Essenciais de String:**
```javascript
let texto = "  Olá, Mundo!  ";

// LIMPEZA
texto.trim();           // "Olá, Mundo!" (remove espaços)
texto.trimStart();      // "Olá, Mundo!  "
texto.trimEnd();        // "  Olá, Mundo!"

// TRANSFORMAÇÃO
texto.toUpperCase();    // "  OLÁ, MUNDO!  "
texto.toLowerCase();    // "  olá, mundo!  "

// BUSCA
texto.includes("Mundo"); // true
texto.startsWith("  O"); // true
texto.endsWith("!  ");   // true
texto.indexOf("Mundo");  // 7

// EXTRAÇÃO
texto.slice(2, 5);       // "Olá"
texto.substring(2, 5);   // "Olá"
texto.charAt(2);         // "O"

// SUBSTITUIÇÃO
texto.replace("Mundo", "Brasil"); // "  Olá, Brasil!  "
texto.replaceAll("o", "0");       // substitui todos

// DIVISÃO
"a,b,c".split(",");      // ["a", "b", "c"]
"olá".split("");         // ["o", "l", "á"]

// TEMPLATE LITERALS (muito importante!)
let nome = "Maria";
let idade = 25;
let frase = `Meu nome é ${nome} e tenho ${idade} anos.`;
```

**Mini-projeto: Validador de Formulário**
```javascript
// Criar funções para validar:

// 1. Email (deve conter @ e .)
function validarEmail(email) {
    // implementar
}

// 2. Senha (mínimo 8 caracteres, uma maiúscula, um número)
function validarSenha(senha) {
    // implementar
}

// 3. Nome (mínimo 3 caracteres, sem números)
function validarNome(nome) {
    // implementar
}

// 4. CPF (11 dígitos, apenas números)
function validarCPF(cpf) {
    // implementar
}
```

**Checklist do dia:**
- [ ] Sei limpar e transformar strings
- [ ] Sei buscar dentro de strings
- [ ] Sei usar template literals
- [ ] Completei o validador de formulário

---

### DIA 12 (2h) - Projeto Prático: Lista de Tarefas (Console)
**Objetivo:** Aplicar tudo que aprendeu em um projeto real

| Tempo | Atividade |
|-------|-----------|
| 30min | Planejar o projeto |
| 90min | Implementar |

**Requisitos do Projeto:**
```javascript
/*
LISTA DE TAREFAS (TODO LIST) - Versão Console

FUNCIONALIDADES:
1. Adicionar tarefa (com título e prioridade: alta/média/baixa)
2. Listar todas as tarefas
3. Marcar tarefa como concluída
4. Remover tarefa
5. Filtrar por prioridade
6. Filtrar por status (pendente/concluída)
7. Buscar tarefa por texto
8. Mostrar estatísticas (total, concluídas, pendentes)

ESTRUTURA DE UMA TAREFA:
{
    id: 1,
    titulo: "Estudar JavaScript",
    prioridade: "alta",
    concluida: false,
    criadaEm: "2025-01-05"
}

CONCEITOS APLICADOS:
- Arrays e métodos (push, filter, find, map)
- Objetos
- Funções
- Condicionais
- Loops
- Strings
*/
```

**Checklist do dia:**
- [ ] Projeto planejado
- [ ] Todas as 8 funcionalidades implementadas
- [ ] Código organizado em funções
- [ ] Testei todas as funcionalidades
- [ ] Commitei no GitHub

---

### DIA 13 (1.5h) - Escopo e Closures
**Objetivo:** Entender onde variáveis existem

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 30min | Vídeo/Leitura | [JavaScript.info - Escopo](https://javascript.info/closure) |
| 60min | Prática e exemplos | Exercícios |

**Conceitos:**
```javascript
// ESCOPO GLOBAL
let global = "Sou global";

function exemplo() {
    // ESCOPO LOCAL
    let local = "Sou local";
    console.log(global); // funciona
    console.log(local);  // funciona
}

console.log(global); // funciona
console.log(local);  // ERRO! local não existe aqui

// VAR vs LET vs CONST
var x = 1;    // escopo de função, pode redeclarar (evitar!)
let y = 2;    // escopo de bloco, não pode redeclarar
const z = 3;  // escopo de bloco, não pode mudar

// CLOSURE (função que "lembra" variáveis externas)
function contador() {
    let count = 0;
    return function() {
        count++;
        return count;
    };
}

const contar = contador();
console.log(contar()); // 1
console.log(contar()); // 2
console.log(contar()); // 3
```

**Checklist do dia:**
- [ ] Entendo escopo global vs local
- [ ] Sei a diferença entre var, let e const
- [ ] Entendo o conceito de closure
- [ ] Sempre uso const/let (nunca var)

---

### DIA 14 (1.5h) - Revisão Semana 2 + Desafio
**Objetivo:** Consolidar e testar conhecimento

| Tempo | Atividade |
|-------|-----------|
| 30min | Revisão dos conceitos |
| 60min | Desafio da semana |

**Desafio da Semana 2 - Sistema de Biblioteca:**
```javascript
/*
Criar um sistema de gerenciamento de biblioteca:

FUNCIONALIDADES:
1. Cadastrar livro (titulo, autor, ano, disponivel)
2. Cadastrar usuário (nome, email, livrosEmprestados[])
3. Emprestar livro (verificar disponibilidade)
4. Devolver livro
5. Listar livros disponíveis
6. Listar livros emprestados por usuário
7. Buscar livro por título ou autor
8. Relatório: livros mais emprestados

Dica: Use arrays de objetos para livros e usuários
*/
```

**Checklist da Semana 2:**
- [ ] Domino funções e arrow functions
- [ ] Sei manipular arrays com map, filter, reduce
- [ ] Sei trabalhar com objetos
- [ ] Sei manipular strings
- [ ] Entendo escopo e closures
- [ ] Completei o projeto de Lista de Tarefas
- [ ] Completei o desafio da Biblioteca

---

## SEMANA 3: HTML + CSS Fundamentos
**Meta:** Criar interfaces visuais

### DIA 15 (2h) - Introdução ao HTML
**Objetivo:** Entender a estrutura de páginas web

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 30min | Vídeo: HTML Básico | [Curso em Vídeo - HTML5](https://www.youtube.com/watch?v=epDCjksKMok) |
| 30min | Leitura: Tags HTML | [MDN - HTML Básico](https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/HTML_basics) |
| 60min | Prática: Criar página pessoal | Exercício |

**Estrutura HTML:**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página</title>
</head>
<body>
    <!-- Conteúdo visível aqui -->
</body>
</html>
```

**Tags Essenciais:**
```html
<!-- ESTRUTURA -->
<header></header>    <!-- cabeçalho -->
<nav></nav>          <!-- navegação -->
<main></main>        <!-- conteúdo principal -->
<section></section>  <!-- seção -->
<article></article>  <!-- artigo -->
<aside></aside>      <!-- conteúdo lateral -->
<footer></footer>    <!-- rodapé -->
<div></div>          <!-- divisão genérica -->

<!-- TEXTO -->
<h1> a <h6>          <!-- títulos -->
<p></p>              <!-- parágrafo -->
<span></span>        <!-- texto inline -->
<strong></strong>    <!-- negrito semântico -->
<em></em>            <!-- itálico semântico -->
<br>                 <!-- quebra de linha -->

<!-- LISTAS -->
<ul><li></li></ul>   <!-- lista não ordenada -->
<ol><li></li></ol>   <!-- lista ordenada -->

<!-- LINKS E MÍDIA -->
<a href=""></a>      <!-- link -->
<img src="" alt="">  <!-- imagem -->
<video></video>      <!-- vídeo -->

<!-- FORMULÁRIOS -->
<form></form>        <!-- formulário -->
<input type="">      <!-- campo de entrada -->
<button></button>    <!-- botão -->
<select></select>    <!-- dropdown -->
<textarea></textarea><!-- área de texto -->
```

**Projeto do dia - Página Pessoal HTML:**
```html
<!-- Criar página com:
1. Header com seu nome
2. Navegação com 3 links
3. Seção "Sobre mim"
4. Seção "Habilidades" (lista)
5. Seção "Projetos" (3 cards)
6. Formulário de contato
7. Footer com redes sociais
-->
```

**Checklist do dia:**
- [ ] Entendo a estrutura HTML básica
- [ ] Conheço as tags semânticas
- [ ] Sei criar formulários
- [ ] Criei minha página pessoal em HTML

---

### DIA 16 (2h) - CSS Básico
**Objetivo:** Estilizar elementos

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 30min | Vídeo: CSS Básico | [Curso em Vídeo - CSS3](https://www.youtube.com/watch?v=FRhM6sMOTfg) |
| 30min | Leitura | [MDN - CSS Básico](https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/CSS_basics) |
| 60min | Estilizar página do dia anterior | Prática |

**Formas de adicionar CSS:**
```html
<!-- 1. Inline (evitar) -->
<p style="color: red;">Texto</p>

<!-- 2. Internal -->
<style>
    p { color: red; }
</style>

<!-- 3. External (recomendado) -->
<link rel="stylesheet" href="style.css">
```

**Seletores CSS:**
```css
/* Por tag */
p { color: blue; }

/* Por classe */
.destaque { background: yellow; }

/* Por ID */
#header { height: 80px; }

/* Combinações */
header nav a { color: white; }     /* descendente */
.card > h2 { font-size: 24px; }    /* filho direto */
.btn:hover { background: blue; }   /* pseudo-classe */
.input:focus { border: 2px solid blue; }
```

**Propriedades Essenciais:**
```css
/* TEXTO */
color: #333;
font-size: 16px;
font-family: Arial, sans-serif;
font-weight: bold;
text-align: center;
line-height: 1.5;
text-decoration: none;

/* CAIXA (Box Model) */
width: 100%;
height: 200px;
padding: 20px;          /* espaço interno */
margin: 10px;           /* espaço externo */
border: 1px solid #ccc;
border-radius: 8px;

/* FUNDO */
background-color: #f5f5f5;
background-image: url('imagem.jpg');
background-size: cover;

/* DISPLAY */
display: block;
display: inline;
display: inline-block;
display: none;
```

**Checklist do dia:**
- [ ] Sei as 3 formas de adicionar CSS
- [ ] Entendo seletores (tag, classe, id)
- [ ] Conheço o Box Model
- [ ] Estilizei minha página pessoal

---

### DIA 17 (2h) - Flexbox
**Objetivo:** Criar layouts flexíveis

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 30min | Vídeo: Flexbox | [Origamid - Flexbox](https://www.youtube.com/watch?v=hTl1xfbGiUo) |
| 30min | Jogo interativo | [Flexbox Froggy](https://flexboxfroggy.com/#pt-br) |
| 60min | Prática: Layout completo | Exercício |

**Flexbox Essencial:**
```css
.container {
    display: flex;

    /* Direção */
    flex-direction: row;        /* horizontal (padrão) */
    flex-direction: column;     /* vertical */

    /* Alinhamento horizontal */
    justify-content: flex-start;   /* início */
    justify-content: center;       /* centro */
    justify-content: flex-end;     /* fim */
    justify-content: space-between;/* espaço entre */
    justify-content: space-around; /* espaço ao redor */

    /* Alinhamento vertical */
    align-items: flex-start;
    align-items: center;
    align-items: flex-end;
    align-items: stretch;       /* estica (padrão) */

    /* Quebra de linha */
    flex-wrap: wrap;

    /* Espaçamento */
    gap: 20px;
}

.item {
    flex: 1;           /* cresce igualmente */
    flex-grow: 1;      /* pode crescer */
    flex-shrink: 0;    /* não encolhe */
    flex-basis: 200px; /* tamanho base */
}
```

**Exercício - Criar:**
1. Header com logo à esquerda e menu à direita
2. Grid de 3 cards centralizados
3. Footer com 3 colunas

**Checklist do dia:**
- [ ] Completei o Flexbox Froggy
- [ ] Sei centralizar elementos
- [ ] Sei criar layouts com flex
- [ ] Criei os 3 componentes do exercício

---

### DIA 18 (2h) - CSS Grid
**Objetivo:** Criar layouts em grade

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 30min | Vídeo: CSS Grid | [Origamid - Grid](https://www.youtube.com/watch?v=elcEyHFSoQo) |
| 30min | Jogo interativo | [Grid Garden](https://cssgridgarden.com/#pt-br) |
| 60min | Prática: Dashboard layout | Exercício |

**CSS Grid Essencial:**
```css
.container {
    display: grid;

    /* Definir colunas */
    grid-template-columns: 200px 1fr 200px;      /* fixo, flexível, fixo */
    grid-template-columns: repeat(3, 1fr);       /* 3 colunas iguais */
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); /* responsivo */

    /* Definir linhas */
    grid-template-rows: 80px 1fr 60px;

    /* Espaçamento */
    gap: 20px;

    /* Áreas nomeadas */
    grid-template-areas:
        "header header header"
        "sidebar main aside"
        "footer footer footer";
}

.header { grid-area: header; }
.sidebar { grid-area: sidebar; }
.main { grid-area: main; }
.footer { grid-area: footer; }
```

**Exercício - Layout de Dashboard:**
```
┌─────────────────────────────────────┐
│              HEADER                 │
├──────────┬──────────────────────────┤
│          │                          │
│ SIDEBAR  │         MAIN             │
│          │                          │
│          │                          │
├──────────┴──────────────────────────┤
│              FOOTER                 │
└─────────────────────────────────────┘
```

**Checklist do dia:**
- [ ] Completei o Grid Garden
- [ ] Sei criar grids com colunas/linhas
- [ ] Sei usar grid-template-areas
- [ ] Criei o layout de dashboard

---

### DIA 19 (2h) - Responsividade
**Objetivo:** Sites que funcionam em qualquer tela

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 30min | Vídeo: Media Queries | [Origamid - Responsivo](https://www.youtube.com/watch?v=H91DhKPjhPk) |
| 30min | Leitura | [MDN - Media Queries](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_media_queries/Using_media_queries) |
| 60min | Tornar página responsiva | Prática |

**Media Queries:**
```css
/* Mobile First - começa pelo mobile */

/* Base (mobile) */
.container {
    padding: 10px;
}

.card {
    width: 100%;
}

/* Tablet (768px+) */
@media (min-width: 768px) {
    .container {
        padding: 20px;
    }

    .cards {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
    }
}

/* Desktop (1024px+) */
@media (min-width: 1024px) {
    .container {
        max-width: 1200px;
        margin: 0 auto;
    }

    .cards {
        grid-template-columns: repeat(3, 1fr);
    }
}

/* Breakpoints comuns */
/* Mobile: até 767px */
/* Tablet: 768px - 1023px */
/* Desktop: 1024px+ */
/* Large Desktop: 1440px+ */
```

**Unidades Relativas:**
```css
/* RECOMENDADAS */
rem    /* relativo ao font-size do html (padrão 16px) */
em     /* relativo ao font-size do elemento pai */
%      /* porcentagem do elemento pai */
vw     /* 1% da largura da viewport */
vh     /* 1% da altura da viewport */

/* EVITAR para responsividade */
px     /* pixels fixos */
```

**Checklist do dia:**
- [ ] Sei usar media queries
- [ ] Entendo mobile-first
- [ ] Sei usar unidades relativas
- [ ] Minha página está responsiva

---

### DIA 20 (2h) - Projeto: Landing Page Completa
**Objetivo:** Criar página profissional HTML/CSS

| Tempo | Atividade |
|-------|-----------|
| 30min | Escolher design de referência |
| 90min | Implementar |

**Requisitos da Landing Page:**
```
1. Header fixo com logo + menu hamburguer (mobile)
2. Hero section com título, subtítulo e CTA
3. Seção de benefícios (3-4 cards)
4. Seção de depoimentos
5. Seção de preços (3 planos)
6. FAQ (perguntas frequentes)
7. Formulário de contato
8. Footer completo

REQUISITOS TÉCNICOS:
- HTML semântico
- CSS organizado
- Flexbox e/ou Grid
- 100% responsivo
- Transições suaves (hover)
```

**Referências de design:**
- [Dribbble](https://dribbble.com/search/landing-page)
- [Awwwards](https://www.awwwards.com/)

**Checklist do dia:**
- [ ] Design escolhido
- [ ] Todas as seções implementadas
- [ ] Responsivo em mobile/tablet/desktop
- [ ] Código limpo e organizado
- [ ] Commitado no GitHub

---

### DIA 21 (1.5h) - Revisão Semana 3
**Objetivo:** Consolidar HTML/CSS

| Tempo | Atividade |
|-------|-----------|
| 30min | Revisão dos conceitos |
| 60min | Melhorar projeto da landing page |

**Checklist da Semana 3:**
- [ ] Domino HTML semântico
- [ ] Sei estilizar com CSS
- [ ] Domino Flexbox
- [ ] Domino CSS Grid
- [ ] Sei criar layouts responsivos
- [ ] Landing page completa e responsiva

---

## SEMANA 4: JavaScript no Navegador
**Meta:** Tornar páginas interativas

### DIA 22 (2h) - DOM Manipulation
**Objetivo:** JavaScript controlando HTML

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 30min | Vídeo: DOM | [Curso em Vídeo - DOM](https://www.youtube.com/watch?v=WWZX8RWLxIk) |
| 30min | Leitura | [JavaScript.info - DOM](https://javascript.info/document) |
| 60min | Prática | Exercícios |

**Selecionando Elementos:**
```javascript
// Por ID
const titulo = document.getElementById('titulo');

// Por classe
const cards = document.getElementsByClassName('card');

// Por tag
const paragrafos = document.getElementsByTagName('p');

// SELETORES MODERNOS (preferir estes!)
const header = document.querySelector('header');        // primeiro
const botoes = document.querySelectorAll('.btn');      // todos
const input = document.querySelector('#email');
const link = document.querySelector('nav a:first-child');
```

**Manipulando Elementos:**
```javascript
const elemento = document.querySelector('.card');

// CONTEÚDO
elemento.textContent = 'Novo texto';           // apenas texto
elemento.innerHTML = '<strong>HTML</strong>';  // pode ter HTML

// ATRIBUTOS
elemento.setAttribute('id', 'card-1');
elemento.getAttribute('id');
elemento.removeAttribute('id');

// CLASSES
elemento.classList.add('ativo');
elemento.classList.remove('ativo');
elemento.classList.toggle('ativo');
elemento.classList.contains('ativo');

// ESTILOS
elemento.style.color = 'red';
elemento.style.backgroundColor = 'blue';
elemento.style.display = 'none';
```

**Criando e Removendo:**
```javascript
// CRIAR
const novoDiv = document.createElement('div');
novoDiv.textContent = 'Novo elemento';
novoDiv.classList.add('card');

// ADICIONAR
document.body.appendChild(novoDiv);            // no final
pai.insertBefore(novoDiv, referencia);         // antes de
pai.insertAdjacentHTML('beforeend', '<p>Novo</p>');

// REMOVER
elemento.remove();
pai.removeChild(filho);
```

**Exercícios:**
1. Mudar texto de todos os títulos h2
2. Adicionar classe "destaque" ao clicar em cards
3. Criar lista de itens dinamicamente
4. Remover item ao clicar nele

**Checklist do dia:**
- [ ] Sei selecionar elementos (querySelector)
- [ ] Sei modificar texto e HTML
- [ ] Sei manipular classes
- [ ] Sei criar e remover elementos

---

### DIA 23 (2h) - Eventos
**Objetivo:** Responder a ações do usuário

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 30min | Vídeo: Eventos | [Curso em Vídeo - Eventos](https://www.youtube.com/watch?v=wWnBB-mZIvY) |
| 30min | Leitura | [JavaScript.info - Eventos](https://javascript.info/events) |
| 60min | Prática | Exercícios |

**Tipos de Eventos:**
```javascript
// MOUSE
click        // clique
dblclick     // duplo clique
mouseenter   // mouse entrou
mouseleave   // mouse saiu
mousemove    // mouse movendo

// TECLADO
keydown      // tecla pressionada
keyup        // tecla solta
keypress     // tecla pressionada (deprecated)

// FORMULÁRIO
submit       // formulário enviado
change       // valor mudou
input        // digitando
focus        // elemento focado
blur         // elemento perdeu foco

// DOCUMENTO
DOMContentLoaded  // DOM carregado
load              // página toda carregada
scroll            // rolagem
resize            // redimensionamento
```

**Adicionando Eventos:**
```javascript
// FORMA MODERNA (recomendada)
const botao = document.querySelector('#btn');

botao.addEventListener('click', function(event) {
    console.log('Clicou!');
    console.log(event.target);  // elemento clicado
});

// COM ARROW FUNCTION
botao.addEventListener('click', (e) => {
    e.preventDefault();  // previne comportamento padrão
    console.log('Clicou!');
});

// REMOVENDO EVENTO
function handleClick() {
    console.log('Clicou!');
}
botao.addEventListener('click', handleClick);
botao.removeEventListener('click', handleClick);
```

**Event Delegation:**
```javascript
// Em vez de adicionar evento em cada item...
// Adiciona no pai e verifica qual filho foi clicado

document.querySelector('ul').addEventListener('click', (e) => {
    if (e.target.tagName === 'LI') {
        console.log('Clicou no item:', e.target.textContent);
    }
});
```

**Exercícios:**
1. Botão que muda cor do fundo
2. Input que mostra quantidade de caracteres
3. Formulário que valida antes de enviar
4. Lista onde clicar no item remove ele

**Checklist do dia:**
- [ ] Sei adicionar eventos com addEventListener
- [ ] Conheço os principais tipos de eventos
- [ ] Sei usar event.target
- [ ] Sei usar preventDefault()

---

### DIA 24 (2h) - Projeto: Todo List Visual
**Objetivo:** Aplicar DOM + Eventos em projeto real

| Tempo | Atividade |
|-------|-----------|
| 30min | Estruturar HTML/CSS |
| 90min | Implementar JavaScript |

**Requisitos:**
```
FUNCIONALIDADES:
1. Adicionar tarefa (input + botão ou Enter)
2. Marcar como concluída (checkbox ou clique)
3. Remover tarefa (botão X)
4. Filtros: Todas / Ativas / Concluídas
5. Contador de tarefas pendentes
6. Limpar todas concluídas
7. Animações suaves

INTERFACE:
- Design limpo e moderno
- Responsivo
- Feedback visual nas ações
```

**Checklist do dia:**
- [ ] HTML estruturado
- [ ] CSS estilizado
- [ ] Todas funcionalidades implementadas
- [ ] Animações funcionando
- [ ] Commitado no GitHub

---

### DIA 25 (2h) - LocalStorage
**Objetivo:** Salvar dados no navegador

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 30min | Leitura | [JavaScript.info - LocalStorage](https://javascript.info/localstorage) |
| 30min | Prática básica | Exercícios |
| 60min | Adicionar ao Todo List | Implementação |

**LocalStorage:**
```javascript
// SALVAR
localStorage.setItem('nome', 'João');

// RECUPERAR
const nome = localStorage.getItem('nome');

// REMOVER
localStorage.removeItem('nome');

// LIMPAR TUDO
localStorage.clear();

// SALVANDO OBJETOS/ARRAYS (precisa converter)
const tarefas = [
    { id: 1, texto: 'Estudar', concluida: false },
    { id: 2, texto: 'Exercitar', concluida: true }
];

// Salvar
localStorage.setItem('tarefas', JSON.stringify(tarefas));

// Recuperar
const tarefasSalvas = JSON.parse(localStorage.getItem('tarefas'));
```

**Implementar no Todo List:**
```javascript
// Carregar tarefas ao iniciar
function carregarTarefas() {
    const salvas = localStorage.getItem('tarefas');
    return salvas ? JSON.parse(salvas) : [];
}

// Salvar sempre que modificar
function salvarTarefas(tarefas) {
    localStorage.setItem('tarefas', JSON.stringify(tarefas));
}

// Chamar salvarTarefas após cada ação (adicionar, remover, completar)
```

**Checklist do dia:**
- [ ] Sei usar localStorage
- [ ] Sei converter objetos com JSON
- [ ] Todo List salva e carrega dados
- [ ] Dados persistem ao recarregar página

---

### DIA 26 (2h) - Fetch API / Consumindo APIs
**Objetivo:** Buscar dados externos

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 30min | Vídeo: Fetch API | [YouTube - Fetch](https://www.youtube.com/watch?v=Oive66jrwBs) |
| 30min | Leitura | [JavaScript.info - Fetch](https://javascript.info/fetch) |
| 60min | Projeto: App de Clima | Implementação |

**Fetch Básico:**
```javascript
// GET - Buscar dados
fetch('https://api.exemplo.com/dados')
    .then(response => response.json())
    .then(data => {
        console.log(data);
    })
    .catch(error => {
        console.error('Erro:', error);
    });

// COM ASYNC/AWAIT (mais moderno)
async function buscarDados() {
    try {
        const response = await fetch('https://api.exemplo.com/dados');
        const data = await response.json();
        console.log(data);
    } catch (error) {
        console.error('Erro:', error);
    }
}

// POST - Enviar dados
async function enviarDados(dados) {
    const response = await fetch('https://api.exemplo.com/dados', {
        method: 'POST',
        headers: {
            'Content-Type': 'application/json'
        },
        body: JSON.stringify(dados)
    });
    return response.json();
}
```

**Projeto: App de Clima**
```javascript
// API gratuita: OpenWeatherMap
// Cadastre em: https://openweathermap.org/api

const API_KEY = 'sua_api_key';

async function buscarClima(cidade) {
    const url = `https://api.openweathermap.org/data/2.5/weather?q=${cidade}&appid=${API_KEY}&units=metric&lang=pt_br`;

    const response = await fetch(url);
    const data = await response.json();

    return {
        cidade: data.name,
        temperatura: data.main.temp,
        descricao: data.weather[0].description,
        icone: data.weather[0].icon
    };
}
```

**Checklist do dia:**
- [ ] Sei usar fetch com .then()
- [ ] Sei usar async/await
- [ ] Sei tratar erros com try/catch
- [ ] App de clima funcionando

---

### DIA 27 (2h) - Async/Await Aprofundado
**Objetivo:** Dominar código assíncrono

| Tempo | Atividade | Recurso |
|-------|-----------|---------|
| 40min | Leitura | [JavaScript.info - Async](https://javascript.info/async-await) |
| 80min | Exercícios práticos | Lista abaixo |

**Conceitos:**
```javascript
// PROMISE - representa valor futuro
const minhaPromise = new Promise((resolve, reject) => {
    setTimeout(() => {
        resolve('Sucesso!');
        // ou reject('Erro!');
    }, 1000);
});

// CONSUMINDO PROMISE
minhaPromise
    .then(resultado => console.log(resultado))
    .catch(erro => console.error(erro));

// ASYNC/AWAIT - forma mais legível
async function exemplo() {
    const resultado = await minhaPromise;
    console.log(resultado);
}

// MÚLTIPLAS PROMISES EM PARALELO
async function buscarTudo() {
    const [usuarios, posts] = await Promise.all([
        fetch('/api/usuarios').then(r => r.json()),
        fetch('/api/posts').then(r => r.json())
    ]);

    console.log(usuarios, posts);
}

// PROMISE.RACE - primeira que resolver
const rapida = await Promise.race([promise1, promise2]);
```

**Exercícios:**
1. Criar função que espera X segundos
2. Buscar dados de 3 APIs diferentes em paralelo
3. Implementar retry (tentar 3 vezes se falhar)
4. Criar loading spinner enquanto busca dados

**Checklist do dia:**
- [ ] Entendo Promises
- [ ] Sei criar minhas próprias Promises
- [ ] Sei usar Promise.all()
- [ ] Completei os exercícios

---

### DIA 28 (2h) - Revisão + Projeto Final Mês 1
**Objetivo:** Consolidar todo o mês

| Tempo | Atividade |
|-------|-----------|
| 30min | Revisão geral |
| 90min | Projeto integrador |

**Projeto Final Mês 1 - Pokédex:**
```
REQUISITOS:
1. Consumir PokéAPI (https://pokeapi.co/)
2. Listar pokémons com paginação
3. Buscar por nome
4. Ver detalhes ao clicar (modal ou página)
5. Favoritar pokémons (salvar no localStorage)
6. Filtrar por tipo
7. Design responsivo e atraente

CONCEITOS APLICADOS:
- HTML semântico
- CSS (Flexbox/Grid, responsivo)
- JavaScript (DOM, eventos, fetch, localStorage)
- Async/await
```

**Checklist do Mês 1:**
- [ ] Domino lógica de programação
- [ ] Domino JavaScript (variáveis, funções, arrays, objetos)
- [ ] Domino HTML/CSS
- [ ] Sei criar layouts responsivos
- [ ] Sei manipular o DOM
- [ ] Sei consumir APIs
- [ ] Tenho 3+ projetos no GitHub
- [ ] Pokédex completa e funcionando

---

# MÊS 2: DESENVOLVIMENTO MODERNO
## "Frameworks e ferramentas profissionais"

---

## SEMANA 5: Git Avançado + Node.js

### DIA 29-30: Git Workflow Profissional
### DIA 31-32: Node.js Básico
### DIA 33-34: NPM e Módulos
### DIA 35: Projeto com Node.js

---

## SEMANA 6: React Fundamentos

### DIA 36-37: Introdução ao React
### DIA 38-39: Componentes e Props
### DIA 40-41: Estado e Eventos
### DIA 42: Mini-projeto React

---

## SEMANA 7: React Avançado

### DIA 43-44: Hooks (useState, useEffect)
### DIA 45-46: Roteamento (React Router)
### DIA 47-48: Estilização (Tailwind CSS)
### DIA 49: Projeto: Dashboard

---

## SEMANA 8: Next.js + Deploy

### DIA 50-51: Introdução ao Next.js
### DIA 52-53: Rotas e Páginas
### DIA 54-55: Deploy na Vercel
### DIA 56: Projeto completo deployado

---

# MÊS 3: PROJETOS PROFISSIONAIS
## "Construindo portfólio de verdade"

---

## SEMANA 9-10: Backend com Supabase
- Autenticação
- Banco de dados
- Storage
- Funções serverless

## SEMANA 11-12: Projeto SaaS Completo
- Landing page
- Sistema de auth
- Dashboard
- Pagamentos (Stripe)
- Deploy profissional

---

# RECURSOS COMPLETOS

## Canais YouTube (Português)
1. **Curso em Vídeo** - Fundamentos, gratuito e completo
2. **Rocketseat** - Conteúdo moderno
3. **Origamid** - CSS e design
4. **Filipe Deschamps** - Conceitos e carreira
5. **Dev Soutinho** - JavaScript avançado

## Canais YouTube (Inglês)
1. **Traversy Media** - Projetos práticos
2. **Fireship** - Vídeos curtos e densos
3. **Web Dev Simplified** - Explicações claras
4. **The Net Ninja** - Tutoriais completos

## Documentação Oficial
- [MDN Web Docs](https://developer.mozilla.org/pt-BR/)
- [JavaScript.info](https://javascript.info/)
- [React Docs](https://react.dev/)
- [Next.js Docs](https://nextjs.org/docs)

## Prática
- [freeCodeCamp](https://www.freecodecamp.org/)
- [Exercism](https://exercism.org/)
- [CodeWars](https://www.codewars.com/)
- [Frontend Mentor](https://www.frontendmentor.io/)

## Jogos de Aprendizado
- [Flexbox Froggy](https://flexboxfroggy.com/)
- [Grid Garden](https://cssgridgarden.com/)
- [CSS Diner](https://flukeout.github.io/)
- [Coding Fantasy](https://codingfantasy.com/)

---

# ACOMPANHAMENTO DE PROGRESSO

## Semana 1: ___/___/___ a ___/___/___
| Dia | Tópico | Tempo | Concluído |
|-----|--------|-------|-----------|
| 1 | Ambiente | 2h | [ ] |
| 2 | Lógica | 1.5h | [ ] |
| 3 | Variáveis | 1.5h | [ ] |
| 4 | Operadores | 1.5h | [ ] |
| 5 | Condicionais | 2h | [ ] |
| 6 | Loops | 2h | [ ] |
| 7 | Revisão + Projeto | 1.5h | [ ] |

**Projeto da semana entregue:** [ ]
**Commits no GitHub:** ___

## Semana 2: ___/___/___ a ___/___/___
| Dia | Tópico | Tempo | Concluído |
|-----|--------|-------|-----------|
| 8 | Funções | 1.5h | [ ] |
| 9 | Arrays | 1.5h | [ ] |
| 10 | Objetos | 1.5h | [ ] |
| 11 | Strings | 1.5h | [ ] |
| 12 | Projeto Todo | 2h | [ ] |
| 13 | Escopo | 1.5h | [ ] |
| 14 | Revisão + Desafio | 1.5h | [ ] |

**Projeto da semana entregue:** [ ]
**Commits no GitHub:** ___

## Semana 3: ___/___/___ a ___/___/___
| Dia | Tópico | Tempo | Concluído |
|-----|--------|-------|-----------|
| 15 | HTML | 2h | [ ] |
| 16 | CSS | 2h | [ ] |
| 17 | Flexbox | 2h | [ ] |
| 18 | Grid | 2h | [ ] |
| 19 | Responsividade | 2h | [ ] |
| 20 | Projeto Landing | 2h | [ ] |
| 21 | Revisão | 1.5h | [ ] |

**Projeto da semana entregue:** [ ]
**Commits no GitHub:** ___

## Semana 4: ___/___/___ a ___/___/___
| Dia | Tópico | Tempo | Concluído |
|-----|--------|-------|-----------|
| 22 | DOM | 2h | [ ] |
| 23 | Eventos | 2h | [ ] |
| 24 | Todo Visual | 2h | [ ] |
| 25 | LocalStorage | 2h | [ ] |
| 26 | Fetch/API | 2h | [ ] |
| 27 | Async/Await | 2h | [ ] |
| 28 | Pokédex | 2h | [ ] |

**Projeto da semana entregue:** [ ]
**Commits no GitHub:** ___

---

# CONTRATO DE COMPROMISSO

Eu, _________________________________, me comprometo a:

1. Dedicar 1-2 horas diárias aos estudos de programação
2. Não pular etapas do plano
3. Praticar mais do que assistir
4. Fazer commits diários no GitHub
5. Pedir ajuda quando travar
6. Não desistir nos momentos difíceis

**Assinatura:** _________________________
**Data de início:** ___/___/2025
**Meta de conclusão:** ___/___/2025

---

*Criado com Claude Code - Seu professor de programação*
