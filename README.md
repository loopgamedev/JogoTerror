# JogoTerror

# 🧠 Minha Mente a Cada Noite

**Gênero:** Terror psicológico / Puzzle / Aventura  
**Engine:** Godot 4.x  
**Desenvolvedor:** Loop Souza  
**Estado:** Em desenvolvimento  

---

## 🖤 Sinopse

Após uma tentativa de suicídio com remédios, o protagonista entra em coma e desperta em um labirinto sombrio — a manifestação da própria mente. Preso nesse espaço entre a vida e a morte, ele precisa enfrentar seus traumas, medos e memórias fragmentadas para encontrar uma saída... ou se perder de vez.

Cada noite representa uma camada mais profunda da psique, com desafios que refletem o estado emocional e espiritual do personagem. Escolhas moldam o desfecho — viver ou desistir.

---

## 🕹️ Mecânicas principais

- 🎮 **Exploração em labirinto:** mapas escuros com layout que muda a cada noite.
- 🔦 **Lanterna com toggle:** iluminação limitada, pilha acaba, exige cautela.
- 🎵 **Sons aleatórios:** ruídos repentinos (sussurros, batidas, choros).
- 🚪 **Portas automáticas:** algumas se abrem sozinhas, outras exigem resolver puzzles.
- 💓 **Batimentos cardíacos na HUD:** aceleram com sustos, sustos influenciam gameplay.
- 🎥 **Tremor de câmera:** indica presença de entidades.
- 👻 **Fantasma perseguidor:** IA que caça o jogador conforme ele explora.
- 💾 **Sistema de checkpoints:** salvar progresso ao alcançar certos marcos.

---

## 🌒 Estrutura das Fases

### **Prólogo: O Silêncio**
- Tutorial. Jogador acorda no labirinto e aprende a andar, interagir e usar a lanterna.
- Nenhum inimigo, só vozes e pistas fragmentadas sobre sua situação.

---

### **Noite 1: O Peso das Palavras**
- Primeiros sustos leves e puzzles simples (ativar interruptores, encontrar chaves).
- Introdução ao sistema de batimentos e lanterna com carga limitada.

---

### **Noite 2: Memórias que Gritam**
- Inimigos aparecem pela primeira vez.
- Mecânica de se esconder ou fugir.
- Fragmentos de lembranças espalhados (diálogos, objetos marcantes).

---

### **Noite 3: A Escolha**
- Labirinto mais complexo.
- Player confronta um trauma maior (evento da infância ou momento decisivo).
- Enigma que exige combinar memórias corretas.

---

### **Noite 4: O Espelho**
- Fantasma perseguidor ativo o tempo todo.
- Sala com múltiplos espelhos, apenas um mostra o caminho certo.
- Final se aproxima, tensão máxima.

---

### **Final: Viver ou Desistir**
- Baseado nas decisões anteriores, o jogador chega a um dos finais:
  - **Aceitação:** Ele decide lutar e acorda.
  - **Desistência:** Ele permanece em coma, e o jogo termina em fade escuro.
  - **Final secreto:** Se todas as memórias forem coletadas e puzzles resolvidos corretamente, há uma cena de reconciliação com um ente querido falecido.

---

## 📁 Estrutura do Projeto

```plaintext
├── Scenes/
│   ├── Player/
│   ├── Enemies/
│   ├── Fases/
│   ├── UI/
├── Scripts/
├── Assets/
│   ├── Sprites/
│   ├── Audio/
│   ├── Fonts/
├── SaveSystem/
├── README.md
