# Jogo de Adivinhação de Número Secreto com Feedback de Voz

Este é um jogo simples de adivinhação onde o usuário tenta adivinhar um número secreto gerado aleatoriamente pelo programa. O jogo oferece feedback tanto em texto quanto em voz, utilizando a API `SpeechSynthesisUtterance` para tornar a experiência mais interativa e acessível.

## Funcionalidades

- **Jogo de Adivinhação:** O programa gera um número secreto aleatório entre 1 e 10. O usuário deve adivinhar esse número.
- **Feedback de Voz:** Utilizando a API `SpeechSynthesisUtterance`, o programa fornece feedback em voz, informando se o número adivinhado é maior, menor ou igual ao número secreto.
- **Tentativas e reinício:** O usuário pode tentar várias vezes até acertar o número. Após acertar, a opção de reiniciar o jogo é habilitada.
- **Design Responsivo:** O jogo é simples e pode ser jogado em qualquer dispositivo, seja desktop ou mobile.

## Como Jogar

1. **Abra o Jogo:** Após abrir o arquivo `index.html` em seu navegador, o jogo começará automaticamente.
2. **Adivinhação:** O programa gera um número secreto aleatório entre 1 e 10. O jogador deve digitar um número na caixa de entrada e clicar em "Chutar".
3. **Feedback:** O jogo informa se o número digitado é maior, menor ou igual ao número secreto, tanto no formato de texto quanto em voz.
4. **Novo Jogo:** Ao acertar o número, o botão "Novo jogo" fica habilitado, permitindo que o jogador inicie uma nova rodada.

## Tecnologias Usadas

- **HTML** e **JavaScript** para a lógica e interface do jogo.
- **SpeechSynthesisUtterance API** para síntese de fala e feedback de voz.
- **CSS** (via `style.css`): Estilo para a interface do jogo.

## Instruções de Uso

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/adivinhacao-numero-secreto.git
   cd adivinhacao-numero-secreto

2. Abra o arquivo HTML: O jogo é uma aplicação simples baseada em navegador. Abra o arquivo index.html no seu navegador preferido.

3. Inicie o Jogo:
- O número secreto será gerado automaticamente e você deve tentar adivinhar o número entre 1 e 10.
- Após cada tentativa, o jogo fornecerá um feedback em texto e em voz.
- Ao acertar, você poderá reiniciar o jogo clicando em "Novo jogo".

## Exemplo de Uso

   1. Abra o arquivo index.html em seu navegador.
   2. Digite um número de 1 a 10 e clique em "Chutar".
   3. O jogo vai informar se o número é maior ou menor que o número secreto. A resposta será dada em texto e voz.
   4. Continue tentando até acertar o número secreto.
   5. Quando você acertar, o botão "Novo jogo" será habilitado para reiniciar a partida.

## Contribuindo

Se você deseja contribuir para o projeto, siga as etapas abaixo:

   Faça um fork deste repositório.
  - Crie uma branch para suas modificações (git checkout -b feature/nome-da-feature).
  - Faça commit das suas alterações (git commit -m 'Adicionando nova feature').
  - Envie para o seu fork (git push origin feature/nome-da-feature).
  - Abra um pull request no repositório original.

##Licença

Este projeto está licenciado sob a MIT License.
