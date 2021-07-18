# Resumo sobre a metodologia ágil SCRUM

Este repositório possui um breve resumo sobre **o que é o SCRUM**. Todo este conteúdo é o resultado da conclusão do curso **Projetos ágeis com SCRUM** do professor Thiago Sano, da [Digital Innovation One](digitalinnovation.one), pesquisas realizadas no youtube e posts de especialistas na área.

## Sumário

- [Introdução a gestão de projetos](#introducao-a-gestao-de-projetos)
  - [Cascata](#cascata)
  - [Agil](#agil)
  - [Comparativo Tradicional x Ágil](#comparativo-tradicional-x-agil)
- [Introdução ao SCRUM](#introducao-ao-scrum)
  - [Razões para adotar o SCRUM](#razoes-para-adotar-o-scrum)
  - [Características do time SCRUM](#caracteristicas-do-time-scrum)
  - [Papéis e responsabilidades de cada um do time](#papeis-e-responsabilidades)
  - [Cerimônias do Scrum](#cerimonias-do-scrum)
  - [Gestão de projetos tradicional x ágil](#gestao-de-projetos-tradicional-x-agil)
- [Fundamentos de um projeto ágil](#fundamentos-de-um-projeto-agil)
  - [Papéis e responsabilidades do Product Owner](#papeis-e-responsabilidades-do-product-owner)
  - [Analisando escopo de definindo prioridades](#analisando-escopo-e-definindo-prioridades)
  - [Papel do Product Owner na transformação digital](#papel-do-product-owner-na-transformacao-digital)
- [Conceitos e atividades essenciais para o sucesso de um projeto ágil](#conceitos-e-atividades-essenciais-para-o-sucesso-de-um-projeto-agil)
  - [Conceitos e planejamento de tarefas](#conceitos-e-planejamento-de-tarefas)
  - [Rotinas de um time ágil](#rotinas-de-um-time-agil)

## Introducao a gestao de projetos

### Cascata

Na engenharia de software tradicional um projeto de software segue uma metodologia que geralmente é a **cascata**, onde o software só avança quando uma fase é inteiramente completa, tradicionalmente, os softwares incrementais são planejados seguindo as seguintes etapas:

- Concepção - (Levantamento e análise de requisitos)
- Análise e Design - (Prototipação)
- Desenvolvimento - (Develop)
- Testes - (Homolog)
- Implantação - (Production)

Este tipo de metodologia, acaba gerando um prazo de entrega muito alto, e desperdicio de recursos financeiros e pessoais (funcionários) da empresa. Na maioria das vezes, quando o software é finalizado e entregue, o usuário final acaba utilizando somente 20% de todo o software construído. 

### Agil

Na metodologia ágil, o software é construído seguindo a idéia de software **incremental**, onde o software é construído por partes de no máximo 1 mês, e cada parte executa-se em um ciclo iterativo.

É importante lembrar, que **Ágil** é diferente de **Rápido**, ser Ágil significa as seguintes carecterísticas: 

- **Rapidez (mudança) e desembaraço**: Identificar problemas em menos tempo e quebrar funcionalidades complexas em diferentes partes.
- **Fazer coisas complexas de forma simples**
- **Equipe comprometida com os objetivos** - A equipe entrega novas funcionalidades constantemente
- **Maior valor para o cliente** - O cliente consegue acompanhar as entregas do software no início do desenvolvimento. 

### Comparativo Tradicional x Agil

| Tradicional | Ágil |
| ----------- | ----------- |
| Escopo definido na fase inicial do projeto - (**Preditivo**) | Escopo definido ao longo do Projeto - (**Adaptativo**) |
| Projeto é controlado por fases e marcos. | Projeto é controlado por funcionalidades entregues. |
| Cliente só vê o software funcionando na fase final do Projeto | Cliente pode ver parte do software funcionando na parte inicial do Projeto.
| Resistência a mudanças. | Mudanças constantes de acordo com feedbacks contínuos.

Em projetos tradicionais (**cascata**), você corre o risco de descobrir que estava errado depois de meses. Com o **SCRUM**, você descobre que estava errado em no máximo 30 dias.

## Introducao ao SCRUM

O **SCRUM** é um dos frameworks utilizados para aplicar as metodologias ágeis, existem varios outros como o XP, Kanban etc...

O **SCRUM** produz melhores resultados em equipes pequenas e multidisciplinares, e segue os 3 seguintes pilares:

- **Transparência**
  - Conversar mais e escrever menos
  - Demonstrar o software constantemente aos usuários e obter feedbacks constantes;
- **Adaptação**: 
  - Requisitos mudam ao longo do tempo
- **Inspeção**
  - Aprender progressivamente com o uso do software.

### Razoes para adotar o SCRUM

- Desenvolvido e entregue em partes menos (2 a 4 semanas), com constante feedback dos usuários;
- Melhor gerenciamento de riscos; (Redução de incertezas)
- Comprometimento, motivação e transparência da equipe. (Daily Meeting).
- Maior valor para o negócio; (Priorização do Backlog)
- Usuários envolvidos durante todo o ciclo.
- Aplicação das lições aprendidas. (melhoria contínua).

### Caracteristicas do time SCRUM

- Equipes capazes de se auto-organizarem.
- As tarefas são do time e todos são responsáveis.
- Forte comprometimento com os resultados.

### Papeis e responsabilidades

No total temos 3 papeis com suas respectivas responsabilides, são elas:

- **Product Owner (PO)**
  - Representante da área de negócios.
  - PO é uma pessoa  e não um comitê (Grupo)
  - Define as funcionalidades do software (Product Backlog)
  - Prioriza as funcionalidades de acordo com o valor do negócio.
  - Garante que o time de desenvolvimento entenda os itens do backlog no nível necessário.

- **Scrum Master (SM)**
  - Garantir o uso correto do SCRUM
  - Scrum Master não é Gerente de projetos.
  - Age como facilitador.
  - Auxilia o Product Owner no planejamento e estimativas do backlog.
  - Auxilia a equipe a remover impedimentos.
  - Treina o time em autogerenciamento e interdisciplinaridade.

- **Time de desenvolvimento**
  - Possui habilidades suficientes para desenvolver, testar, criar e desenhar, ou seja, tudo que for necessário para entregar o software funcionando.
  - Composto por 3 a 9 pessoas

### Cerimonias do SCRUM

#### Time Box

Tempo máximo definido para fazer uma cerimônia ou todo o desenvolvimento de uma sprint

#### Sprint

Sprint (Corrida, arrancada), é o principal evento do scrum, com duração máxima de 30 dias corridos.

#### Composicao de uma sprint

- **Planejamento da Sprint**
  - O planejamento de uma sprint é composto pelos seguintes participantes:
    - Product Owner
    - Scrum Master
    - Time de Desenvolvimento

Geralmente, no planejamento de uma sprint de 30 dias, as reuniões levam 8h, sendo que nas 4 primeiras horas:

- O Product Owner (PO) define **o quê fazer**, ou seja, quais funcionalidades deveram ser desenvolvidas, e é também onde o time de **Desenvolvimento** tira todas as suas dúvidas referentes ao negócio.

Nas outras 4 horas, o time de desenvolvimento define **como fazer** e quebram as funcionalidades e definem os prazos de entrega de cada atividade.

- **Reuniôes diárias (Daily Meeting)**
  - Depois de realizado o planejamento da sprint, o time de desenvolvimento realiza reuniôes diárias de 15 minutos, onde é discutido oque é para fazer, oque está sendo feito, e o que foi concluído e se possui algum impedimento.
  - Nessas reunioes, participam o Product Owner (PO), Time de desenvolvimento e o Scrum Master.    
- **Revisão da Sprint (Review)**
  - No último dia da sprint, ocorre uma reunião onde o time de desenvolvimento apresenta para o **Product Owner (PO)** o trabalho feito.

- **Retrospectiva da Sprint**
  - Esta reunião ocorre no ultimo dia da sprint, onde é discutido os erros, acertos e aprendizados que a equipe teve no decorrer do desenvolvimento desta spint.

### Gestao de projetos tradicional x agil

## Fundamentos de um projeto agil

### Papeis e responsabilidades do product owner

### Analisando escopo e definindo prioridades

### Papel do product owner na transformacao digital

## Conceitos e atividades essenciais para o sucesso de um projeto agil

### Conceitos e planejamento de tarefas

### Rotinas de um time agil