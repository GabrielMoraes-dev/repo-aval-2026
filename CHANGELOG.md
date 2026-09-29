# Changelog

Todas as mudanças relevantes deste projeto são documentadas neste arquivo.

O formato segue o [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/)
e o projeto adota o [Versionamento Semântico](https://semver.org/lang/pt-BR/).

## [1.1.0] - 2026-09-28

### Adicionado

- Formatação da média com uma casa decimal e vírgula.
- Situação "Aprovado com distinção" para médias a partir de 9,0.
- Testes para notas inválidas.

### Alterado

- Cálculo da média simplificado utilizando métodos de array.

### Corrigido

- Média exatamente 7,0 passa a ser classificada como "Aprovado".

## [1.0.0] - 2026-09-14

### Adicionado

- Cálculo da média aritmética das notas.
- Classificação da situação do aluno: Aprovado, Recuperação ou Reprovado.
- Execução pela linha de comando (`npm start -- <notas>`).
- Integração contínua com testes e verificação de Conventional Commits.