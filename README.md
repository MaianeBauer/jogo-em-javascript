# jogo-em-javascript
 Este Redmi te guiará passo a passo pelo código, desvendando seus segredos e te ensinando conceitos importantes de forma intuitiva, lúdica e educativa.
 Detalhe especial este jogo possui acessibilidade inclusa de voz pelo navegador, essa funcionalidade torna o jogo mais inclusivo e democrático, permitindo que todos possam desfrutar da experiência de jogar, independentemente de suas habilidades físicas.
 Acesse o link e texte o jogo:
 https://jogo-lake-phi.vercel.app/

 #listaNumerosSorteados: Uma lista que guarda os números aleatórios já sorteados, evitando repetições.
 #numeroLimite: Define o limite superior (até 10) para os números que podem ser sorteados.
 #numeroSecreto: O número secreto que o jogador precisa adivinhar.
 #tentativas: Contador de tentativas do jogador.

 
 A Jornada Começa:

exibirMensagemInicial: Apresenta o título do jogo e as instruções para o jogador.
verificarChute:
Obtém o valor do chute do jogador.
Compara o chute com o numeroSecreto:
Se acertar:
Exibe mensagem de vitória e o número de tentativas.
Habilita o botão para reiniciar o jogo.
Se errar:
Indica se o chute foi maior ou menor que o numeroSecreto.
Aumenta o contador de tentativas.
Limpa o campo de chute.
gerarNumeroAleatorio:
Gera um número aleatório entre 1 e numeroLimite.
Verifica se o número já foi sorteado (evitando repetições).
Retorna o número aleatório sorteado.
limparCampo: Limpa o campo de chute do jogador.
reiniciarJogo:
Reinicia o jogo:
Gera um novo numeroSecreto.
Limpa o campo de chute.
Zera o contador de tentativas.
Exibe a mensagem inicial.
Desabilita o botão para reiniciar.


Aprendendo com a Diversão:
Ao desenvolver  o código, utilizei:

Variáveis: Armazenar e manipular informações.
Funções: Organizar o código em blocos reutilizáveis.
Condicionais: Tomar decisões com base em comparações.
Laços: Repetir ações um número determinado de vezes.
Interação com o usuário: Obter e exibir informações.

Dicas para Jogadores:
Comece com um número limite menor: Isso facilita o aprendizado e aumenta suas chances de adivinhar o número secreto.
Preste atenção às pistas: O jogo te informa se o seu chute foi maior ou menor que o número secreto.


![Captura de tela 2024-06-25 225336](https://github.com/MaianeBauer/jogo-em-javascript/assets/142107409/e016c751-2849-46ee-a7c5-faa781cc9818)![Captura de tela 2024-06-25 225424](https://github.com/MaianeBauer/jogo-em-javascript/assets/142107409/83ddcfe7-e964-45f9-a89e-ae6b4ac121ba)



Divirta-se e fique a vontande para me chamar sobre alguma duvida ou implementação de melhorias!




