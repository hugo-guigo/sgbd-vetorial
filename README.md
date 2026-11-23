# Estudo e avaliação de um SGBD vetorial

Atividade supervisionada de Sistemas Gerenciadores de Banco de Dados (Ciência da Computação, UFG, 2º semestre de 2026, Prof. Leonardo Andrade Ribeiro).

O grupo apresenta e demonstra um SGBD vetorial, sempre em contraste com o SGBD relacional visto em sala.

- **SGBD escolhido:** a definir (opções em [dbdb.io](https://dbdb.io/browse?data-model=vector&q); também vale um relacional com extensão, como o [pgvector](https://github.com/pgvector/pgvector)).
- **Grupo (3 a 5 pessoas):** a preencher.

## O que a apresentação precisa ter

| Seção | Conteúdo | Responsável |
|---|---|---|
| Breve histórico | lançamento, quem desenvolve, versão atual | |
| API | carga de dados, linguagem de consulta e modificação | |
| Funcionalidades | junções, consultas com múltiplos vetores, consultas híbridas (filtro em atributos não vetoriais), atualização de vetores | |
| Arquitetura | armazenamento, índices, processamento de consultas, transações; contraste com o relacional | |
| Metodologia | como o grupo se organizou: reuniões, divisão de tarefas, execução | |
| Demonstração | mostra a API, as funcionalidades e a arquitetura apresentadas | |
| Atividade extra (opcional) | integração do SGBD com um LLM, na apresentação e na demonstração | |

Avaliação: clareza, corretude e profundidade (destaque para o contraste com o relacional), qualidade da demonstração, presença e participação nas outras apresentações. A nota é individual e qualquer integrante pode ser perguntado sobre qualquer parte.

## Entrega

- Apresentação na data do Plano de Curso: a preencher.
- Slides em PDF na tarefa da Plataforma Turing.

## Estrutura do repositório

```text
demo/     código e dados da demonstração
docs/     anotações de estudo por seção (histórico, API, arquitetura...)
slides/   fonte e PDF final dos slides
```

## Como contribuir

1. Clone o repositório e crie uma branch para a sua parte: `git checkout -b nome/secao`.
2. Faça commits pequenos e abra um pull request para a `main`.
3. Não suba senhas, chaves de API nem arquivos `.env` (já estão no `.gitignore`).
