# Roadmap Completo: Programador No-Code/Low-Code

## Sobre Este Guia
Este documento foi criado para te guiar do zero até a profissionalização em desenvolvimento no-code/low-code, utilizando ferramentas de IA como Claude Code e Cursor.

---

## O Que é Programação No-Code/Low-Code?

**No-Code**: Criar aplicações sem escrever código, usando interfaces visuais.
**Low-Code**: Escrever código mínimo, com assistência de IA e ferramentas visuais.

### Sua Vantagem Competitiva
Com Claude Code + Cursor, você opera no modelo **"AI-Assisted Development"**:
- A IA escreve o código
- Você entende a lógica e direciona
- Foco em resolver problemas, não em sintaxe

---

## FASE 1: Fundamentos Essenciais (Semanas 1-4)

### 1.1 Lógica de Programação (A BASE DE TUDO)

Antes de qualquer ferramenta, você precisa pensar como programador.

#### Conceitos Cruciais:

```
┌─────────────────────────────────────────────────────────────┐
│  VARIÁVEIS                                                  │
│  "Caixas" que guardam informações                          │
│                                                             │
│  nome = "João"        ← guarda texto                       │
│  idade = 25           ← guarda número                      │
│  ativo = true         ← guarda verdadeiro/falso            │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│  CONDICIONAIS                                               │
│  Tomada de decisões                                         │
│                                                             │
│  SE idade >= 18 ENTÃO                                      │
│      mostrar "Maior de idade"                              │
│  SENÃO                                                      │
│      mostrar "Menor de idade"                              │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│  LOOPS (Repetições)                                         │
│  Fazer algo várias vezes                                    │
│                                                             │
│  PARA cada cliente NA lista_clientes:                      │
│      enviar email de boas-vindas                           │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│  FUNÇÕES                                                    │
│  Blocos de código reutilizáveis                            │
│                                                             │
│  função calcularDesconto(preco, percentual):               │
│      retornar preco - (preco * percentual / 100)           │
└─────────────────────────────────────────────────────────────┘
```

#### Exercício Prático 1:
Descreva em português o passo a passo de:
1. Fazer login em um site
2. Calcular o troco de uma compra
3. Verificar se uma senha é forte

### 1.2 Estrutura de Dados

```
┌─────────────────────────────────────────────────────────────┐
│  ARRAYS/LISTAS                                              │
│  Coleção ordenada de itens                                  │
│                                                             │
│  frutas = ["maçã", "banana", "laranja"]                    │
│  frutas[0] = "maçã"  (primeiro item)                       │
│  frutas[2] = "laranja" (terceiro item)                     │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│  OBJETOS/DICIONÁRIOS                                        │
│  Dados com nome e valor                                     │
│                                                             │
│  usuario = {                                                │
│      nome: "Maria",                                         │
│      email: "maria@email.com",                             │
│      idade: 30                                              │
│  }                                                          │
│                                                             │
│  usuario.nome = "Maria"                                     │
│  usuario.email = "maria@email.com"                         │
└─────────────────────────────────────────────────────────────┘
```

### 1.3 Fluxo de Dados

```
ENTRADA → PROCESSAMENTO → SAÍDA

Exemplo: Calculadora de IMC
┌──────────────┐    ┌───────────────────┐    ┌──────────────┐
│   ENTRADA    │    │   PROCESSAMENTO   │    │    SAÍDA     │
│              │    │                   │    │              │
│ peso: 70kg   │ →  │ imc = peso /      │ →  │ IMC: 24.2    │
│ altura: 1.70 │    │ (altura * altura) │    │ Status:Normal│
└──────────────┘    └───────────────────┘    └──────────────┘
```

---

## FASE 2: Ferramentas do Desenvolvedor (Semanas 5-8)

### 2.1 Terminal/Linha de Comando

O terminal é sua base de operações. Comandos essenciais:

```bash
# Navegação
pwd                 # Mostra onde você está
ls                  # Lista arquivos da pasta
cd pasta            # Entra na pasta
cd ..               # Volta uma pasta

# Manipulação de Arquivos
mkdir nova-pasta    # Cria pasta
touch arquivo.txt   # Cria arquivo
rm arquivo.txt      # Remove arquivo
cp origem destino   # Copia arquivo
mv origem destino   # Move/renomeia arquivo

# Visualização
cat arquivo.txt     # Mostra conteúdo
code .              # Abre VS Code/Cursor na pasta atual
```

### 2.2 Git e GitHub (Controle de Versão)

```
┌─────────────────────────────────────────────────────────────┐
│                    POR QUE USAR GIT?                        │
├─────────────────────────────────────────────────────────────┤
│ ✓ Salva histórico de todas as alterações                   │
│ ✓ Permite voltar a versões anteriores                      │
│ ✓ Colaboração em equipe                                     │
│ ✓ Backup do seu código na nuvem (GitHub)                   │
│ ✓ Portfólio profissional                                    │
└─────────────────────────────────────────────────────────────┘
```

Comandos essenciais:
```bash
git init                    # Inicia repositório
git add .                   # Prepara arquivos para commit
git commit -m "mensagem"    # Salva alterações
git push                    # Envia para GitHub
git pull                    # Baixa atualizações
git status                  # Verifica estado atual
git log                     # Histórico de commits
```

### 2.3 Cursor IDE - Seu Ambiente de Trabalho

```
┌─────────────────────────────────────────────────────────────┐
│                    CURSOR IDE                               │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  ┌──────────┐  ┌────────────────────────┐  ┌──────────┐   │
│  │ Explorer │  │                        │  │   AI     │   │
│  │          │  │    Editor de Código    │  │  Chat    │   │
│  │ Arquivos │  │                        │  │          │   │
│  │ do       │  │                        │  │ Claude/  │   │
│  │ Projeto  │  │                        │  │ GPT      │   │
│  │          │  │                        │  │          │   │
│  └──────────┘  └────────────────────────┘  └──────────┘   │
│                                                             │
│  ┌──────────────────────────────────────────────────────┐  │
│  │                    Terminal                          │  │
│  └──────────────────────────────────────────────────────┘  │
└─────────────────────────────────────────────────────────────┘
```

#### Atalhos Essenciais:
```
Ctrl + `          → Abre/fecha terminal
Ctrl + P          → Busca rápida de arquivos
Ctrl + Shift + P  → Paleta de comandos
Ctrl + B          → Mostra/esconde barra lateral
Ctrl + S          → Salvar arquivo
Ctrl + Z          → Desfazer
Ctrl + Shift + Z  → Refazer
Ctrl + D          → Seleciona próxima ocorrência
Ctrl + /          → Comenta linha
```

### 2.4 Claude Code - Seu Assistente de Programação

Como usar efetivamente:

```
┌─────────────────────────────────────────────────────────────┐
│               PROMPTS EFETIVOS PARA CLAUDE                  │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│ ❌ RUIM: "Faz um site pra mim"                             │
│                                                             │
│ ✅ BOM: "Crie uma landing page com:                        │
│         - Header com logo e menu                            │
│         - Seção hero com título e botão CTA                │
│         - 3 cards de benefícios                            │
│         - Formulário de contato                            │
│         - Footer com redes sociais                         │
│         Use HTML, CSS e JavaScript vanilla"                │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│ ❌ RUIM: "Tá dando erro"                                   │
│                                                             │
│ ✅ BOM: "Ao clicar no botão de enviar, aparece o erro:    │
│         'TypeError: Cannot read property of undefined'     │
│         no console. O botão deveria enviar os dados        │
│         do formulário para a API"                          │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## FASE 3: Tecnologias Web (Semanas 9-16)

### 3.1 HTML - Estrutura

```html
<!-- HTML = Esqueleto da página -->
<!DOCTYPE html>
<html>
<head>
    <title>Minha Página</title>
</head>
<body>
    <header>Cabeçalho</header>
    <main>
        <h1>Título Principal</h1>
        <p>Parágrafo de texto</p>
        <button>Clique aqui</button>
    </main>
    <footer>Rodapé</footer>
</body>
</html>
```

### 3.2 CSS - Estilo Visual

```css
/* CSS = Aparência da página */

/* Cores, fontes, tamanhos */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f5f5f5;
    color: #333;
}

/* Layout com Flexbox */
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
}

/* Responsividade */
@media (max-width: 768px) {
    .container {
        flex-direction: column;
    }
}
```

### 3.3 JavaScript - Interatividade

```javascript
// JavaScript = Comportamento da página

// Variáveis
const nome = "João";
let idade = 25;

// Funções
function saudar(nome) {
    return `Olá, ${nome}!`;
}

// Eventos
document.querySelector('button').addEventListener('click', () => {
    alert('Botão clicado!');
});

// Manipular DOM
document.getElementById('titulo').textContent = 'Novo Título';
```

### 3.4 Frameworks e Bibliotecas

```
┌─────────────────────────────────────────────────────────────┐
│                 ECOSSISTEMA MODERNO                         │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  FRONTEND (Interface)                                       │
│  ├── React        → Biblioteca mais popular                │
│  ├── Next.js      → React com superpoderes                 │
│  ├── Vue.js       → Alternativa mais simples               │
│  └── Tailwind CSS → Estilização rápida                     │
│                                                             │
│  BACKEND (Servidor)                                         │
│  ├── Node.js      → JavaScript no servidor                 │
│  ├── Express      → Framework web simples                  │
│  ├── Supabase     → Backend pronto (no-code)               │
│  └── Firebase     → Backend Google (no-code)               │
│                                                             │
│  BANCO DE DADOS                                             │
│  ├── PostgreSQL   → Relacional robusto                     │
│  ├── MongoDB      → Não-relacional flexível                │
│  └── Supabase     → PostgreSQL gerenciado                  │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## FASE 4: Desenvolvimento Prático (Semanas 17-24)

### 4.1 Projetos para Portfólio

#### Nível Iniciante:
1. **Landing Page Pessoal** - HTML/CSS/JS
2. **Calculadora** - Lógica + DOM
3. **Lista de Tarefas (Todo)** - CRUD básico
4. **Quiz Interativo** - Arrays + Condicionais

#### Nível Intermediário:
5. **Blog com CMS** - Next.js + Markdown
6. **Dashboard de Dados** - Gráficos + API
7. **E-commerce Simples** - Carrinho + Checkout
8. **App de Clima** - Consumo de API

#### Nível Avançado:
9. **SaaS Completo** - Auth + Pagamento + Dashboard
10. **App Mobile** - React Native/Flutter
11. **Automação com IA** - APIs + Integração
12. **Sistema de Agendamento** - Full-stack

### 4.2 Stack Recomendada para No-Code/Low-Code

```
┌─────────────────────────────────────────────────────────────┐
│              STACK MODERNA COM IA                           │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  DESENVOLVIMENTO                                            │
│  ├── Cursor IDE      → Editor com IA                       │
│  ├── Claude Code     → Assistente de código                │
│  └── v0.dev          → Gera UI com IA                      │
│                                                             │
│  FRONTEND                                                   │
│  ├── Next.js 14+     → Framework React                     │
│  ├── Tailwind CSS    → Estilização                         │
│  └── shadcn/ui       → Componentes prontos                 │
│                                                             │
│  BACKEND                                                    │
│  ├── Supabase        → Auth + Database + Storage           │
│  ├── Vercel          → Deploy automático                   │
│  └── Stripe          → Pagamentos                          │
│                                                             │
│  AUTOMAÇÃO                                                  │
│  ├── n8n             → Workflows visuais                   │
│  ├── Zapier          → Integrações prontas                 │
│  └── Make            → Automações complexas                │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## FASE 5: Profissionalização (Contínuo)

### 5.1 Habilidades Complementares

```
┌─────────────────────────────────────────────────────────────┐
│              SOFT SKILLS ESSENCIAIS                         │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  ✓ Resolução de Problemas                                  │
│    → Dividir problemas grandes em pequenos                 │
│                                                             │
│  ✓ Pesquisa Eficiente                                      │
│    → Saber buscar soluções (Google, StackOverflow, Docs)   │
│                                                             │
│  ✓ Comunicação                                              │
│    → Explicar soluções técnicas de forma simples           │
│                                                             │
│  ✓ Gestão de Tempo                                         │
│    → Estimar e cumprir prazos                              │
│                                                             │
│  ✓ Aprendizado Contínuo                                    │
│    → Tecnologia muda constantemente                        │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### 5.2 Fontes de Aprendizado

```
GRATUITOS:
├── freeCodeCamp.org      → Cursos completos
├── The Odin Project      → Fullstack gratuito
├── MDN Web Docs          → Documentação oficial
├── YouTube               → Traversy Media, Fireship
└── Dev.to                → Artigos da comunidade

PAGOS (Recomendados):
├── Rocketseat            → PT-BR, qualidade alta
├── Alura                 → PT-BR, variedade
├── Udemy                 → Esperar promoções
└── Frontend Masters      → Conteúdo avançado
```

### 5.3 Construindo Presença Profissional

```
┌─────────────────────────────────────────────────────────────┐
│               PORTFÓLIO PROFISSIONAL                        │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  1. GitHub Ativo                                            │
│     → Commits frequentes                                    │
│     → READMEs bem escritos                                  │
│     → Projetos organizados                                  │
│                                                             │
│  2. LinkedIn Otimizado                                      │
│     → Projetos destacados                                   │
│     → Certificações                                         │
│     → Recomendações                                         │
│                                                             │
│  3. Site Pessoal                                            │
│     → Portfólio visual                                      │
│     → Blog técnico (opcional)                               │
│     → Formulário de contato                                 │
│                                                             │
│  4. Contribuições Open Source                               │
│     → Mostra colaboração                                    │
│     → Visibilidade na comunidade                           │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## Checklist de Progresso

### FASE 1 - Fundamentos
- [ ] Entendo variáveis e tipos de dados
- [ ] Sei usar condicionais (if/else)
- [ ] Consigo criar loops (for/while)
- [ ] Sei criar e usar funções
- [ ] Entendo arrays e objetos
- [ ] Consigo descrever algoritmos em português

### FASE 2 - Ferramentas
- [ ] Navego no terminal com confiança
- [ ] Sei usar Git (add, commit, push, pull)
- [ ] Tenho conta no GitHub com repositórios
- [ ] Domino os atalhos do Cursor
- [ ] Sei fazer prompts efetivos para IA

### FASE 3 - Tecnologias Web
- [ ] Crio estruturas HTML semânticas
- [ ] Estilizo com CSS (incluindo Flexbox/Grid)
- [ ] Faço páginas responsivas
- [ ] Manipulo o DOM com JavaScript
- [ ] Consumo APIs externas
- [ ] Uso pelo menos um framework (React/Next.js)

### FASE 4 - Projetos
- [ ] Tenho 3+ projetos no portfólio
- [ ] Pelo menos 1 projeto fullstack
- [ ] Projetos deployados e funcionando
- [ ] READMEs profissionais

### FASE 5 - Profissional
- [ ] Perfil GitHub profissional
- [ ] LinkedIn atualizado
- [ ] Site/portfólio pessoal
- [ ] Primeira renda com programação

---

## Próximos Passos Imediatos

1. **AGORA**: Configure seu ambiente (Cursor + Terminal)
2. **SEMANA 1**: Pratique lógica de programação
3. **SEMANA 2**: Aprenda comandos do terminal e Git
4. **SEMANA 3-4**: Crie sua primeira página HTML/CSS
5. **MÊS 2**: Adicione JavaScript e interatividade
6. **MÊS 3+**: Escolha um framework e construa projetos

---

## Comandos Úteis para Começar

```bash
# Criar pasta do projeto
mkdir meu-primeiro-projeto
cd meu-primeiro-projeto

# Iniciar Git
git init

# Abrir no Cursor
cursor .

# Criar arquivos iniciais
touch index.html style.css script.js
```

---

*Documento criado com Claude Code*
*Última atualização: Janeiro 2025*
