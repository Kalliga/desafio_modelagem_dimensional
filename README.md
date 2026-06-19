# Modelagem Dimensional - DIO
## Objetivo

Criar um modelo dimensional (Star Schema) com foco na análise dos dados dos professores.

## Tabela Fato

- F_Professor

## Tabelas Dimensão

- D_Professor
- D_Departamento
- D_Curso
- D_Disciplina
- D_Data
- D_Aluno

## Observações

Foi criada uma dimensão de datas para permitir análises temporais relacionadas à oferta de disciplinas e cursos, conforme solicitado no desafio.

O modelo foi estruturado em formato Star Schema, tendo o Professor como objeto principal de análise.
