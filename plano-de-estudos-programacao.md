# Plano de Estudos de Programação (100% gratuito, em português)

> Feito para ser usado em grupo. O índice original cobre praticamente toda a
> computação (mobile, web, dados, DevOps, sistemas embarcados etc.), então este plano
> organiza tudo em **fases** e **trilhas**, para o grupo progredir com foco em vez de
> tentar tudo ao mesmo tempo — e ainda assim conseguir estudar coisas diferentes e trocar
> conhecimento entre si.

---

## Como o grupo pode usar este plano

1. Todo mundo começa pela **Fase 0 (Fundamentos)**, juntos — não pulem, mesmo quem já
   acha que sabe. É a base comum que garante que todos conseguem se ajudar depois.
2. Depois da Fase 0, cada pessoa (ou dupla) escolhe **uma trilha principal** (Web,
   Mobile, Dados/IA, DevOps/Infra ou Sistemas). Não precisa todo mundo escolher a mesma —
   pelo contrário, ter gente em trilhas diferentes é bom: quando alguém trava, alguém do
   grupo especializado naquilo pode ajudar.
3. Dentro de cada trilha, sigam a ordem sugerida — cada curso prepara para o próximo.
4. Ferramentas transversais (Git, Linux, Segurança básica) valem pra qualquer trilha —
   estudem em paralelo, não precisa dominar antes de seguir em frente.

---

## Organização em grupo

Ideias simples pra manter todo mundo engajado e evitar que o grupo se perca no meio do
caminho:

### Papéis e trilhas

Façam uma tabela como essa (pode ser num arquivo `progresso-do-grupo.md`, numa aba de
planilha, ou num quadro do GitHub Projects) pra saber quem está em quê:

| Pessoa | Trilha principal | Fase atual | Última atualização |
|---|---|---|---|
| Ex: Mauro | Web | Trilha 1.2 (framework front-end) | 05/08 |
| | | | |

### Encontros de sincronização

- Um encontro curto (15–20 min) por semana, presencial ou por chamada, só pra cada um
  contar o que concluiu e onde travou.
- Quem terminar uma trilha inteira pode fazer uma "mini-aula" de 10 minutos pro resto do
  grupo — ensinar é uma das formas mais rápidas de fixar o que se aprendeu.

### Duplas de estudo

Sempre que possível, formem duplas na mesma trilha nas primeiras semanas — ajuda a manter
o ritmo e criar o hábito de revisar código um do outro.

### Usando o GitHub para acompanhar

Se o repositório for compartilhado entre o grupo:

- Usem **Issues** para cada pessoa abrir uma "issue de progresso" (ex: `Progresso -
  Mauro`) e ir comentando semanalmente o que concluiu.
- Usem **Discussions** (se ativado no repositório) pra tirar dúvidas entre vocês antes de
  procurar em fóruns externos.
- Cada pessoa pode ter sua própria cópia local do `trilha-estudos.html` — o progresso é
  salvo por navegador/dispositivo, então cada um marca o seu.

### Regra de ouro do grupo

Ninguém fica pra trás sozinho. Se alguém sumir ou travar por mais de uma semana numa
etapa, é sinal pro grupo puxar aquela pessoa de volta — manda mensagem, oferece ajuda,
ou revisa junto o que está travando.

---

## Fase 0 — Fundamentos (todo mundo começa aqui)

| Ordem | Curso | Professor/Fonte |
|---|---|---|
| 1 | Programação para Iniciantes | Fabio Akita |
| 2 | Curso Lógica de Programação Completo 2023 | Jonathan de Souza |
| 3 | Como Computadores Funcionam? | Fabio Akita |
| 4 | Curso Grátis de Introdução ao Linux — Primeiros Passos | Gustavo Guanabara |
| 5 | Terminal Linux | Diego Mariano |
| 6 | Curso de Git e GitHub: grátis, prático e sem usar comandos no terminal | Gustavo Guanabara |
| 7 | Curso de Git e GitHub 2024 | Carlos Uchoa |

**Objetivo da fase:** entender lógica de programação, saber usar o terminal Linux
básico, e versionar código com Git/GitHub. Isso é pré-requisito para qualquer trilha —
e também o que permite ao grupo colaborar no mesmo repositório sem bagunçar o código
uns dos outros.

---

## Trilha 1 — Desenvolvimento Web (a mais recomendada para começar)

### 1.1 Front-end (HTML, CSS, JS)

| Ordem | Curso |
|---|---|
| 1 | Curso completo e atual de HTML5 e CSS3 — Módulos 1 a 4 (Gustavo Guanabara) |
| 2 | Frontend para Iniciantes (LuizTools) |
| 3 | Curso Grátis de JavaScript e ECMAScript para Iniciantes (Gustavo Guanabara) |
| 4 | Curso Javascript Completo 2023 + 14 Mini-Projetos (Jhonatan de Souza) |
| 5 | Curso de Sass (Vida FullStack) |

### 1.2 Um framework front-end (escolha um para começar)

- **React** → ReactJS Fundamentos (Dev Samurai) → Curso de React (Matheus Battisti) → ReactJS API GitHub (Dev Samurai)
- **Vue.js** → Curso completo e gratuito de Vue.js 3 (Igor Halfeld) → Curso de Vue 3 (Matheus Battisti)

### 1.3 Back-end (escolha uma linguagem)

- **Node.js** → Curso de Node.js (Celke) → Serie API NodeJS (Rocketseat) → Testes no NodeJS com Jest (Rocketseat)
- **Python** → ver Trilha 3 (Python) → depois Django ou FastAPI
- **PHP** → Curso de PHP para Iniciantes (Gustavo Guanabara) → Introdução ao PHP orientado a objetos (Diego Mariano) → Curso Introdução ao Laravel 8
- **Java** → ver seção Java abaixo → Spring Boot (Giuliana Bezerra ou Fernanda Kipper)
- **C#** → Fundamentos do C# (André Baltieri) → Iniciando com ASP.NET Core (Eduardo Pires)

### 1.4 Banco de dados

| Ordem | Curso |
|---|---|
| 1 | Curso de Banco de Dados MySQL (Gustavo Guanabara) |
| 2 | Curso de Modelagem de Dados (Bóson Treinamentos) |
| 3 | Dominando o Postgres (Dev Samurai) |

### 1.5 TypeScript (depois de já saber JS)

| Ordem | Curso |
|---|---|
| 1 | Curso completo de Typescript (Rincko Dev) |
| 2 | TypeScript — Aprendendo Junto (DevDojo) |
| 3 | Angular (Loiane Groner) *— opcional, se quiser esse framework* |

> **Ideia de projeto em grupo:** depois da Fase 1.1–1.3, montem juntos um projeto real
> (ex: um site de eventos, um clone simples de alguma rede social, um sistema de lista de
> tarefas) — cada um cuida de uma parte (front, back, banco de dados) e usam Git/GitHub
> pra colaborar de verdade.

---

## Trilha 2 — Mobile

Escolha uma via:

**Nativo Android/Kotlin**
1. Desenvolvedor Android Iniciante (Gabriel Ferrari)
2. Aprenda Kotlin do zero — Módulo Básico (Pedro Massango)
3. Curso de Kotlin — Básico (Rapadura Dev)

**Multiplataforma (Flutter)**
1. Criando seu primeiro App com Flutter (André Baltieri)
2. Curso Flutter Básico [NV1] (Deivid Willyan)
3. Curso COMPLETO de Flutter (Flutterando)
4. Curso Arquitetura no Flutter (Deivid Willyan) — depois de já ter base

**React Native** (se já souber React)
1. Aprenda React Native (Canal Geek Dev)
2. Curso base de React Native 2025 (Lucas Souza Dev)

---

## Trilha 3 — Dados / Inteligência Artificial

### 3.1 Base: Python

| Ordem | Curso |
|---|---|
| 1 | Curso de Python 3 — Mundo 1: Fundamentos (Gustavo Guanabara) |
| 2 | Curso de Python 3 — Mundo 2: Estruturas de Controle (Gustavo Guanabara) |
| 3 | Curso de Python 3 — Mundo 3: Estruturas Compostas (Gustavo Guanabara) |
| 4 | Orientação a Objetos (Otávio Miranda) |

### 3.2 Ciência de dados e Machine Learning

| Ordem | Curso |
|---|---|
| 1 | Introdução à Ciência da Computação com Python — Parte 1 e 2 (USP/Coursera) |
| 2 | Python Fundamentos para Análise de Dados (Data Science Academy) |
| 3 | Data Science: Visualização de Dados com Python (Diego Mariano) |
| 4 | Curso Data Science e Machine Learning (Data ICMC) |
| 5 | Machine Learning e Data Science: O Guia para Iniciantes (Jones Granatyr) |
| 6 | Curso Deep Learning (Deep Learning Brasil) |

### 3.3 Web com Python (opcional, se quiser back-end também)

- **Django** → Curso de Django Aprenda a Desenvolver Aplicações Web Do Zero (Jefferson Lobato)
- **FastAPI** → Curso de FastAPI 2025 (Eduardo Mendes)
- **Flask** → Curso de Flask (Filipe Morelli)

---

## Trilha 4 — DevOps / Infraestrutura

*Pré-requisito: já ter feito a Fase 0 (Linux + Git) e idealmente saber programar em algo.*

| Ordem | Curso |
|---|---|
| 1 | Curso de Docker para iniciantes — aprenda Docker em 1 hora (Matheus Battisti) |
| 2 | Descomplicando o Docker (LINUXtips) |
| 3 | Curso de Introdução ao Kubernetes (Insight Lab) |
| 4 | Descomplicando o Kubernetes (LinuxTips) |
| 5 | Kubernetes para Devs Javascript (Erick Wendel) *— se sua stack for JS/Node* |

---

## Trilha 5 — Linguagens de sistemas / performance

Para quem já tem base de programação e quer ir mais fundo:

| Ordem | Curso |
|---|---|
| 1 | Aprenda C e C++ — Fundamentos Para Lógica de Programação (One Day Code) |
| 2 | Curso de C (Cláudio Rogério Carvalho Filho) |
| 3 | Programação Moderna em C (Papo Binário) |
| 4 | Aprenda Rust (CodeShow) |
| 5 | Curso Rust Básico (Linguagem Rust) |
| 6 | Aprenda Go / Golang (NBK Mundo Tech) |
| 7 | Go — Aprenda a Programar (Ellen Körbes) |

---

## Java — trilha própria (grande o suficiente para ser separada)

| Ordem | Curso |
|---|---|
| 1 | Curso de Java para Iniciantes (Gustavo Guanabara) |
| 2 | Curso de Programação Orientada a Objetos em Java (Gustavo Guanabara) |
| 3 | Curso de Java Básico (Loiane Groner) |
| 4 | Estrutura de Dados com Java (Loiane Groner) |
| 5 | Fundamentos do Java para Iniciantes (Giuliana Bezerra) |
| 6 | Curso de Java, Spring COMPLETO e GRATUITO (Fernanda Kipper) |
| 7 | Aulões Spring Boot (Giuliana Bezerra) |

---

## Ferramentas e tópicos transversais (fazer aos poucos, em paralelo)

| Tema | Curso |
|---|---|
| Editor de código | Produtividade máxima com o VS Code (Diego Martins de Pinho) |
| Segurança básica | Curso de Segurança da Informação (Gustavo Guanabara) |
| Markdown (documentação) | Guia da Linguagem Markdown (Curso em Vídeo) |
| Redes | Curso Redes de Computadores (Gustavo Guanabara) |

---

## Sugestão de cronograma (estudando ~1h/dia)

| Semanas | Foco |
|---|---|
| 1–3 | Fase 0 completa, junto com o grupo (lógica, Linux, Git) |
| 4–6 | HTML/CSS + JavaScript básico |
| 7–9 | Framework front-end (React ou Vue) |
| 10–13 | Back-end + banco de dados (escolha uma linguagem) — bom momento pro projeto em grupo |
| 14+ | Projetos práticos combinando tudo, depois expandir para outra trilha (Mobile, Dados, DevOps) |

Isso é só um ritmo de referência — o importante é praticar escrevendo código todo dia,
mesmo que pouco, em vez de só assistir aula. Combinem entre vocês um ritmo que funcione
pra todo mundo; de nada adianta um cronograma que só uma pessoa consegue seguir.

---

## Observação importante

O grupo não precisa (e não deveria tentar) estudar todas as ~30 linguagens/áreas desse
índice ao mesmo tempo, nem cada pessoa sozinha. A maioria dos desenvolvedores
profissionais domina bem 1–2 linguagens e tem noção geral das outras. Cada um escolhe uma
trilha, vai até conseguir construir um projeto pequeno sozinho, e só depois expande — e o
grupo, coletivamente, acaba cobrindo muito mais terreno do que se cada um tentasse fazer
tudo sozinho.