# Jogo do Número Secreto

## Sobre o Projeto
O **Jogo do Número Secreto** é um jogo interativo desenvolvido com HTML, CSS e JavaScript, onde o jogador deve adivinhar um número gerado aleatoriamente entre 1 e 10. O jogo fornece dicas visuais e auditivas para orientar o jogador até a resposta correta.

## Funcionalidades
- Geração de um número aleatório secreto.
- Exibição de mensagens na tela e por voz (usando a API `responsiveVoice`).
- Feedback interativo indicando se o número secreto é maior ou menor.
- Contador de tentativas para incentivar a precisão.
- Botão de reinício do jogo ao acertar o número.

## Tecnologias Utilizadas
- **HTML**: Estrutura da página.
- **CSS**: Estilização visual (arquivo `style.css`).
- **JavaScript**: Lógica do jogo e interatividade (arquivo `app.js`).
- **ResponsiveVoice.js**: Biblioteca para leitura de texto em voz alta.

## Como Jogar
1. O jogo exibe uma mensagem inicial com as instruções.
2. Digite um número entre 1 e 10 no campo de entrada.
3. Clique no botão **Chutar** para verificar se acertou.
4. O jogo fornecerá uma dica se o número for maior ou menor que o número secreto.
5. Continue tentando até acertar!
6. Ao acertar, o jogo mostrará a quantidade de tentativas e ativará o botão **Novo jogo**.

## Estrutura do Projeto
```
📂 JogoNumeroSecreto
│── 📄 index.html       # Página principal do jogo
│── 📄 style.css        # Estilos visuais do jogo
│── 📄 app.js           # Lógica do jogo
│── 📂 img             # Pasta para imagens do projeto
│── 📄 README.md        # Documentação do projeto
```

## Captura de Tela
Adicione aqui um print do projeto para melhor visualização.

![Print do Jogo](https://github.com/Matheusisa/Jogo-Numero-Secreto/blob/main/img/numero_secreto.jpg)

## Como Executar o Projeto
1. Faça o download ou clone este repositório:
   ```sh
   git clone https://github.com/Matheusisa/Jogo-Numero-Secreto.git
   ```
2. Abra o arquivo `index.html` em um navegador.
3. Divirta-se jogando!

## Melhorias Futuras
- Adicionar um contador de pontuação.
- Expandir a faixa de números para um desafio maior.
- Criar um design mais dinâmico e responsivo.

---
Feito com ❤️ e JavaScript!
