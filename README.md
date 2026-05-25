# MAELIS: GUARDIÃ DA NÉVOA 

> *"Aqui, onde os pilares caíram... os protetores se ajoelharam diante da Névoa. Você ousa seguir onde eles ruíram?"*

**Maelis: Guardiã da Névoa** é um *arcade shooter* de fantasia sombria ambientado em um universo corrompido. O jogo resgata a nostalgia dos fliperamas clássicos (com fortes inspirações em *Galaga*), combinando combate dinâmico em ondas com uma narrativa onírica e melancólica.

---

## ⚙️ Arquitetura e Tecnologias
O projeto foi construído "do zero" para a Web, dispensando o uso de motores gráficos ou frameworks externos. Toda a mecânica de jogo foi desenvolvida utilizando:

- **JavaScript (Vanilla):** Controle de hordas, sistema de colisões, física de movimentação e lógica de gerenciamento de magias.
- **HTML5:** Estrutura do Canvas e renderização dos elementos do jogo.
- **CSS3:** Estilização de menus, tipografia e organização do HUD.

## 🕹️ Destaques da Gameplay

* **Sistema Tático de Magias:** O combate vai além do disparo simples. Ao longo da jornada, Maelis desbloqueia feitiços para controle de grupo:
  * 🔴 **Fogo:** Causa dano em área, explodindo inimigos próximos.
  * 🔵 **Gelo:** Paralisa alvos e freia o avanço das hordas.
  * ⚫ **Sombra:** Dispara um feixe perfurante que atravessa múltiplos inimigos.
* **HUD Emocional e Reativo:** O rosto da protagonista é exibido na interface e suas expressões faciais mudam em tempo real de acordo com a sua barra de vida (neutra, ferida, assustada).
* **Modo Infinito:** Após limpar a Clareira da Névoa, as Ruínas e o Jardim Corrompido na campanha principal, os jogadores podem testar seus limites de sobrevivência no modo *endless*.

## ⌨️ Controles do Jogo

Para garantir respostas rápidas, os controles foram otimizados para o teclado:

- `←` e `→` : Movimentação lateral da personagem
- `Espaço` : Disparo contínuo (Magia Básica)
- `Shift` / `Z` / `X` : Ativação dos ataques mágicos especiais
- `Esc` : Pausar jogo / Menu

## 🚀 Como Jogar

Como o projeto é nativo da Web, a execução é imediata. 

1. Faça o clone deste repositório para a sua máquina:
   ```bash
   https://maelis.roboticminds.com.br/