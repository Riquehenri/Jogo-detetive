# 🕵️‍♂️ Caso Vovô Coxa

Um jogo de investigação em Python onde você assume o papel de um detetive tentando resolver o misterioso assassinato do Vovô Coxa. Utilize pistas lógicas, elimine suspeitos e acerte o local e o autor do crime antes que o tempo acabe!

## 🔍 Como jogar

- Você tem **até as 06:00** para resolver o caso.
- Em cada rodada, escolha:
  - `0` para receber uma **dica**
  - `1` para fazer um **palpite** (apenas 1 tentativa)
  - `2` para visualizar o **mapa do local**
- Você perde se errar o palpite ou se o tempo acabar.

## 🧠 Lógica Dedutiva

O jogo gera pistas com base no local do assassinato. Algumas são verdadeiras, outras contraditórias — use seu raciocínio lógico!

Além disso, o jogo pode ser complementado com a biblioteca `ttg` (Tabela Verdade Python) para testar a validade de proposições lógicas baseadas nas pistas do jogo.

## 📜 Recursos

- 🎭 Seis suspeitos com **motivações reais**
- 🧩 Geração aleatória do **assassino** e do **local do crime**
- 🕰️ Sistema de **tempo dinâmico**
- 💡 Dicas variadas, algumas enganosas!
- 🗺️ Mapa ASCII para auxiliar na investigação
- 📚 Análise lógica com a biblioteca [`ttg`](https://pypi.org/project/ttg/)

## 📦 Requisitos

- Python 3
- `pygame`
- `ttg` (opcional, para análises lógicas)

Instale com:

```bash
pip install pygame ttg
