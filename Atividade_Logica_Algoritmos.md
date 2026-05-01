# Lógica e Algoritmos
📍 Atividade IV

📅 Aula 16/abril

## 🔹 Descrição da Atividade
Elaboração de um algoritmo em pseudocódico (linguagem neutra estruturada) para organizar o processo de entrada de alunos em uma sala de aula.

## 💻 Código
```
VARIÁVEIS
lista_oficial {lista dos alunos autorizados a entrar}
fila {lista de alunos esperando para entrar}
número_da_matrícula {identificador único de cada aluno}
nome_do_aluno {nome associado ao identificador}
aluno
-------------------

INÍCIO

LER lista_oficial

FAÇA aluno = PRIMEIRO EM fila
ESCREVA “Digite o número da sua matrícula:” FAÇA número_da_matrícula = ENTRADA

LER número_da_matrícula
  SE número_da_matrícula ESTÁ em lista_oficial ENTÃO
    ESCREVA: “Entrada permitida. Bem-vindo, (nome_do_aluno)!”
  SENÃO
    ESCREVA: “Entrada negada. (nome_do_aluno) não está na lista.”

REMOVER aluno DE fila
REPETIR ENQUANTO fila > 0

FIM SE
FIM

```
