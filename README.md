# 🦇 Protocolo Gotham — Cruzadinha de Arquitetura Computacional

Jogo web interativo desenvolvido para a **Atividade Avaliativa III (Sprint 3)** da disciplina de **Arquitetura Computacional**, inspirado na estética noir investigativa de *The Batman* (2022). Além da cruzadinha principal sobre arquitetura de hardware, o projeto inclui módulos interativos sobre **Portas Lógicas** (guia teórico completo, quiz investigativo de 12 questões e laboratório simulador de circuitos digitais com 7 exercícios práticos).

---

## 🔗 Link do Site Publicado

👉 **[Acesse o jogo online aqui: https://guibenat.github.io/cruzadinha-protocolo-gotham/](https://guibenat.github.io/cruzadinha-protocolo-gotham/)**

---

## 🎮 Como Jogar

1. Na tela inicial (**Dossiê Central**), selecione **CRUZADINHA HARDWARE** para abrir o tabuleiro principal (ou navegue entre **PORTAS LÓGICAS** e **CIRCUITOS & EXERCÍCIOS** pelo menu superior).
2. Clique em qualquer casa ativa da grade ou escolha uma pista numerada nas listas de **Horizontais** e **Verticais**.
3. Digite as letras diretamente no teclado — o jogo converte automaticamente para maiúsculas, remove acentos e avança o cursor para a próxima casa da palavra.
4. Em casas de cruzamento, clique novamente na mesma célula (ou use o botão **Direção ⇄**) para alternar entre **Horizontal** e **Vertical**, ou navegue usando as setas do teclado.
5. Clique em **Conferir** para validar o tabuleiro: palavras corretas são destacadas em **verde** e palavras incorretas ou incompletas em **vermelho**, atualizando o contador de acertos (`X de 14 palavras`).
6. Clique em **Reiniciar** a qualquer momento para limpar o tabuleiro e iniciar uma nova tentativa.

---

## 🧩 Lista de Palavras e Pistas

O tabuleiro reúne **14 termos** da disciplina cruzados entre si:

| Posição | Palavra no Tabuleiro | Pista |
| :--: | :--- | :--- |
| **03 · H** | `MICROCONTROLADOR` | Chip único que integra processador, memória e periféricos para sistemas embarcados. |
| **09 · H** | `QUADCORE` | Processador com quatro núcleos físicos trabalhando em paralelo. |
| **10 · H** | `ADDRESSBUS` | Via unidirecional que transporta a localização física de onde ler ou gravar. |
| **12 · H** | `DATABUS` | Via bidirecional por onde trafegam as informações entre processador e memória. |
| **13 · H** | `ROM` | Memória não volátil gravada de fábrica, usada na inicialização do sistema. |
| **14 · H** | `RAM` | Memória principal volátil de leitura e escrita que perde dados sem energia. |
| **01 · V** | `EEPROM` | Memória não volátil que pode ser apagada e regravada eletricamente byte a byte. |
| **02 · V** | `ULA` | Parte da CPU que faz as contas e as operações lógicas. |
| **03 · V** | `MEMORIADEMASSA` | Armazenamento permanente de grande capacidade para arquivos e sistemas, como HD e SSD. |
| **04 · V** | `CPU` | Cérebro do computador responsável por buscar, decodificar e executar instruções. |
| **05 · V** | `REGISTRADORES` | Memórias ultrarrápidas internas ao processador que guardam dados em execução imediata. |
| **06 · V** | `CACHE` | Memória intermediária de altíssima velocidade entre o processador e a memória principal. |
| **07 · V** | `DUALCORE` | Arquitetura de processador equipada com dois núcleos de processamento independentes. |
| **11 · V** | `UC` | Componente do processador que coordena o fluxo de dados e decodifica instruções. |

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura semântica das telas, matriz da cruzadinha, quiz e bancada de circuitos.
- **CSS3** — Layout responsivo com estética noir, paleta carmesim/grafite e animações de interface.
- **JavaScript (ES6+)** — Lógica do tabuleiro, validação automática, efeitos sonoros via Web Audio API, chuva em Canvas e simulação de portas lógicas em tempo real.