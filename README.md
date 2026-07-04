**🇧🇷 Português** · [🇺🇸 English](README.en.md)

# 🎮 Oficina: Meu Primeiro Jogo em GDevelop

> Roteiro completo de oficina para crianças criarem seu primeiro jogo digital — do zero ao jogável em 2 horas, sem escrever código.

**Autora:** [Paula Peclat](https://github.com/paulapeclat) · [APedê Digital](https://paulapeclat.com.br)
**Faixa etária:** 8 a 12 anos · **Duração:** 2h (ou 2 encontros de 1h) · **Ferramenta:** [GDevelop](https://gdevelop.io) (gratuito, roda no navegador)

---

## Por que esta oficina existe

Na perspectiva da educação midiática, jogar não basta: queremos que as crianças **produzam** mídia e, ao produzir, entendam as escolhas que todo designer faz. Quando uma criança decide a velocidade do personagem, o que vale ponto e o que faz perder, ela descobre na prática que **todo jogo é feito de decisões de alguém** — e passa a olhar os jogos que consome com outros olhos.

Este material segue a progressão **do concreto ao abstrato**: manipulação direta de objetos → eventos (se/então) → variáveis (pontuação).

## Objetivos de aprendizagem

Ao final, cada criança terá:

- [ ] Criado um jogo funcional do gênero "colete os itens"
- [ ] Usado a lógica **evento → condição → ação** (base do pensamento computacional)
- [ ] Criado e modificado uma **variável** (pontuação)
- [ ] Tomado ao menos **3 decisões de design próprias** (personagem, velocidade, regra)
- [ ] Refletido sobre quem toma essas decisões nos jogos que joga

**Alinhamento BNCC:** Competência Geral 5 (cultura digital) — compreender, utilizar e **criar** tecnologias digitais de forma crítica, significativa e ética.

## Materiais

- Computadores com navegador (o [editor web do GDevelop](https://editor.gdevelop.io) não exige instalação)
- Opcional: conta gratuita GDevelop para salvar na nuvem (menores de 13 precisam de consentimento — alternativa: salvar o arquivo `.json` localmente)
- Projetor para demonstração

## Roteiro

### Etapa 0 — Conversa de abertura (10 min)

Pergunte: *"Quem aqui já jogou um jogo hoje? Quem foi que DECIDIU como esse jogo funciona?"*
Anote as hipóteses no quadro — vamos voltar a elas no fechamento.

### Etapa 1 — Conhecendo o palco (15 min)

1. Abrir [editor.gdevelop.io](https://editor.gdevelop.io) → **Novo projeto** → projeto vazio
2. Explorar juntos: **cena** (o palco), **objetos** (os atores), **eventos** (as regras)
3. Criar o primeiro objeto: sprite do jogador (usar a biblioteca de assets gratuita do GDevelop — deixe as crianças escolherem o personagem: **decisão de design nº 1**)

### Etapa 2 — Dando vida ao personagem (20 min)

1. Selecionar o objeto do jogador → **Comportamentos** → adicionar **"Movimento top-down"**
2. Testar com as setas do teclado (▶️ Preview)
3. Deixar cada criança ajustar a **velocidade** (decisão de design nº 2). Pergunta-gatilho: *"Um jogo muito fácil é divertido? E um impossível?"*

### Etapa 3 — O que cai do céu (20 min)

1. Criar o segundo objeto: o item a coletar (fruta, estrela, moeda — escolha livre)
2. Primeiro **evento**: `A cada 1 segundo → Criar objeto item em posição aleatória no topo`
3. Adicionar comportamento **"Força de gravidade"** ou evento de movimento para o item cair

*Intervalo natural aqui se a oficina for em 2 encontros.*

### Etapa 4 — A regra do jogo (20 min)

1. Criar a **variável de cena** `pontos = 0`
2. Evento: `Se jogador colide com item → apagar item E somar 1 em pontos`
3. Adicionar objeto de **texto** que mostra a pontuação
4. Cada criança define **o que acontece quando o item toca o chão** (decisão de design nº 3): perde ponto? acaba o jogo? nada?

### Etapa 5 — Tornando o jogo SEU (20 min)

Escolha livre entre: trocar o cenário de fundo, adicionar som ao coletar, criar um segundo tipo de item que vale mais pontos, ou adicionar um item "ruim" que tira pontos.

### Etapa 6 — Festival de jogos + fechamento (15 min)

1. Rodízio: cada criança joga o jogo de outra
2. Roda de conversa, voltando ao quadro da Etapa 0:
   - *"O que você decidiu no seu jogo que ficou diferente do jogo do colega?"*
   - *"Se todo jogo tem um designer decidindo as regras... o que os designers dos SEUS jogos favoritos decidiram para você jogar mais tempo?"*

Essa última pergunta é a ponte da criação para a **leitura crítica de mídia** — não pule o fechamento.

## Avaliação

Observação processual, não prova: a criança usou evento/condição/ação? Tomou decisões próprias e soube justificá-las? Participou da reflexão final? Um checklist por aluno resolve.

## Variações

- **6-8 anos:** professor projeta e dirige; crianças decidem coletivamente cada parâmetro (versão desplugada da agência de design)
- **12+ anos:** adicionar tela de game over, fases, ou migrar o mesmo jogo para [microStudio](https://microstudio.dev) e comparar blocos × código
- **Sem internet estável:** GDevelop tem versão desktop offline

## Licença

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.pt-br) — use, adapte e redistribua, com atribuição e mesma licença. Se usar em sua escola, [me conte como foi](https://github.com/paulapeclat/primeiro-jogo-gdevelop/issues)! 💛
