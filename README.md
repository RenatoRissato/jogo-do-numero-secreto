# Jogo do Número Secreto

Este é um jogo simples desenvolvido em HTML, CSS e JavaScript, onde o jogador deve adivinhar um número secreto gerado aleatoriamente.

## 🔗 Link do Projeto
Você pode jogar o Jogo do Número Secreto acessando este link:
👉 [jogo-do-numero-secreto](https://jogo-do-numero-secreto-omega-pearl-42.vercel.app/)

## 🛠 Tecnologias Utilizadas
- HTML
- CSS
- JavaScript

## 🚀 Como Jogar
1. O jogo escolherá um número secreto aleatório.
2. Digite um número e tente adivinhar.
3. O jogo informará se o número inserido é maior ou menor que o número secreto.
4. Continue tentando até acertar!

## 📂 Estrutura do Projeto
```
📂 jogo-do-numero-secreto
├── 📂 img            # Imagens do projeto
├── 📄 index.html     # Página principal do jogo
├── 📄 style.css      # Estilização da interface
├── 📄 app.js         # Lógica do jogo
```
## 💻 Lógica de Programação
- **Geração do Número:**  
  Utilizei a função `Math.random()` para gerar um número aleatório entre 1 e 10. Esse número é convertido para inteiro com `parseInt()`.
  
- **Controle de Repetição:**  
  O número gerado é armazenado em um array para garantir que, ao iniciar um novo jogo, o JavaScript selecione um número diferente daquele escolhido anteriormente. Assim, cada clique no botão de "Novo Jogo" resulta na geração de um novo número, sem repetições até que       todos os números de 1 a 10 tenham sido utilizados. Quando o array acumula os 10 números, ele é automaticamente resetado, permitindo que a contagem comece do zero novamente.
  
- **Feedback de Voz:**  
  Utilizei o método `responsiveVoice.speak` para dar feedback auditivo, fazendo com que o texto exibido na tela seja falado em voz alta com uma voz configurada para "Brazilian Portuguese Female" em velocidade de 1.2.

- **Fluxo do Jogo:**  
  Ao acertar o número, o jogo exibe uma mensagem de sucesso e informa a quantidade de tentativas utilizadas. Se o palpite estiver incorreto, o jogo indica se o número secreto é maior ou menor e solicita um novo palpite.
  
## 📌 Como Executar Localmente
Caso queira rodar o projeto localmente:
1. Clone este repositório:
   ```bash
   git clone https://github.com/RenatoRissato/jogo-do-numero-secreto.git
   ```
2. Abra o arquivo `index.html` em um navegador.

## 📜 Licença
Este projeto é de código aberto e está disponível sob a licença MIT.

---

Feito com ❤️ por [Renato Rissato](https://github.com/RenatoRissato) 🚀
