# 🕹️ Jogo da Forca

## 📄 Descrição

Este é um jogo simples do tipo **forca**, desenvolvido com HTML, CSS e JavaScript , tudo contido em **um único arquivo index.html`.

O objetivo é adivinhar 6 palavras relacionadas a processos de desenvolvimento, com base em dicas fornecidas. O jogador pode utilizar o teclado físico ou o teclado virtual na tela.

---

## 👥 Integrantes

- Monica Karol
- Mikaelle Martins 
- Bernardo dos Santos
- Alice Malaquias
- Priscila Gomes
- Pedro Augusto

---

## 🛠️ Tecnologias Utilizadas

- **HTML** – Estrutura da aplicação
- **CSS** – Estilização com layout responsivo
- **JavaScript** – Lógica do jogo (sorteio de palavras, controle de erros, teclado virtual)

## Requisitos do jogo

* Linguagens: HTML, CSS e JavaScript puro.
* Layout minimalista com fundo azul marinho.
* Fonte: `system-ui`, `Segoe UI`, `Roboto`.
* Bordas arredondadas, letras brancas.
* Layout:

  * Título e botões no topo.
  * Corpo dividido em duas colunas (forca à esquerda, palavra e teclado à direita).
  * Responsivo: em telas pequenas, coluna única.
  * Rodapé com dicas de uso.
    
## Regras do jogo:

O jogo sorteia uma palavra secreta dentre 6 termos com suas respectivas dicas.
O jogador pode usar o teclado virtual ou físico.
Acertos: letra aparece na palavra.
Erros: parte do boneco aparece.
Máximo de 6 erros por palavra.
Vence a rodada se descobrir todas as letras.
Vence o jogo se descobrir todas as 6 palavras.
Perde a rodada se completar o boneco.

## 📚 Palavras e Dicas

| Palavra      | Dica                                  |
|--------------|----------------------------------------|
| FASE         | Estágios ou etapas                    |
| DISCIPLINA   | Áreas de processo                     |
| WORKFLOW     | Mostram a sequência                   |
| ARTEFATOS    | Resultados intermediários             |
| PAPEIS       | Perfis profissionais participantes    |
| INTERACAO    | Cada ciclo de execução                |



## Prompt Criado

"Crie um jogo simples tipo forca em HTML/CSS e JavaScript;
Com fundo azul marinho, estilo minimalista, com fonte System-ui, Segoe UI, Roboto;
Com bordas arredondadas, letras brancas;
Com layout com título e botões no topo, corpo dividido em duas colunas (respondo em coluna única em telas pequenas), rodapé com dicas de uso;
Regras: sorteia palavra entre 6, com dicas de significado; o jogador escolhe letras (teclado virtual ou físico), acerto mostra letra, erro mostra boneco (até 6 partes), vence a rodada se descobrir todas letras da palavra e vence o jogo se descobrir todas as 6 palavras, perde se completar boneco;
Palavras: FASE, DISCIPLINA, WORKFLOW, ARTEFATOS, PAPEIS, INTERACAO, com significados indicados acima."

## Registro de Testes e Correções

Caso de Teste 1

Descrição: Caso o jogador não consiga acertar a palavra.
Resultado: 0 erros encontrados.

Caso de Teste 2

Descrição: Caso o jogador acerte a palavra.
Resultado: 0 erros encontrados.
