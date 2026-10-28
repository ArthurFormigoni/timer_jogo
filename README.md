# Desafio do Cronômetro (Timer Jogo) ⏱️

Jogo de precisão mental inspirado no clássico desafio da rua. 
Feito para jogar no celular, tablet ou computador.

## 🎯 Como Funciona
1. Escolha o tempo alvo (**3.00s**, **5.00s**, **7.00s** ou **10.00s**).
2. Bata no **Buzzer** (`START`). A contagem começa em segredo (`--:--.--`).
3. Conte os segundos mentalmente e bata no **Buzzer** (`STOP`) no momento exato!
4. **Condição de Vitória**: O jogador vence se a diferença for de no máximo **±0.15 segundos**!

## 🚀 GitHub Pages
Este repositório está configurado para publicação direta via **GitHub Pages**:
1. No repositório no GitHub, vá em **Settings** > **Pages**.
2. Em **Build and deployment** > **Source**, selecione `Deploy from a branch`.
3. Escolha a branch `main` e a pasta `/ (root)`.
4. Clique em **Save**. O jogo estará disponível no link fornecido pelo GitHub!

## 🛠️ Tecnologias
- HTML5, CSS3 moderno (Design de Buzzer Arcade 3D e Display LED digital de 7 segmentos).
- Web Audio API (Efeitos sonoros de relé mecânico e buzzer sem arquivos externos).
- Mobile & Tablet First com suporte a vibração tátil (`navigator.vibrate`).
