# PROJETO-1-BIMESTRE-SISTEMA-DE-JOGOS
🎮 MINI JOGOS EM C
Projeto desenvolvido para a disciplina de Programação 1, com o objetivo de aplicar conceitos de lógica, estruturas de controle, funções, vetores e interação com o usuário através do console em linguagem C.
O sistema funciona como um mini arcade, contendo três minijogos que podem ser acessados através de um menu principal.


🧠 OBJETIVO DO PROJETO:

Este projeto tem como finalidade desenvolver habilidades em:
- lógica de programação
- estruturas condicionais e de repetição
- uso de funções
- manipulação de vetores
- interação com o usuário via console
- Além disso, o trabalho estimula o raciocínio algorítmico e a resolução de problemas, aplicando conceitos vistos em sala de aula.


🕹 ESTRUTURA DO SISTEMA

Ao executar o programa, o usuário visualiza o menu principal:
1 - Perguntas e Respostas
2 - Cobra na Caixa
3 - Gousmas War
4 - Sair

Cada opção leva a um minijogo diferente.
Após o término de cada partida, o jogador pode:

- jogar novamente
- voltar ao menu principal

❓JOGO 1- PERGUNTAS E RESPOSTAS
Este jogo apresenta ao usuário cinco perguntas de múltipla escolha sobre a série Lupin, da Netflix.
A série acompanha Assane Diop, um homem que se inspira nas histórias do famoso ladrão fictício Arsène Lupin.

Cada pergunta possui quatro alternativas (A, B, C ou D).

FUNCIONAMENTO:
- O programa mostra uma pergunta sobre a série.
- O jogador escolhe uma alternativa.
- O sistema verifica se a resposta está correta.
- Ao final, o programa mostra a pontuação total.

EXEMPLO DE PERGUNTA:
1) Qual é o nome do protagonista da série Lupin?

a) Assane Diop
b) Arsène Lupin
c) Hubert Pellegrini
d) Benjamin Ferel

Se o jogador errar, o sistema mostra qual era a resposta correta.



🐍 JOGO 2- COBRA NA CAIXA

Este jogo se passa dentro de uma tumba egípcia.
No centro da sala existem cinco caixas.

Entre elas estão escondidos:

🟢 um botão que abre a porta (vitória)

🐍 uma cobra (derrota)

📦 caixas vazias

Regras do jogo:

- Dois jogadores participam da partida.
- Cada jogador escolhe um nome da lista disponível.
- O sistema sorteia quem começa.
- Os jogadores escolhem caixas alternadamente.

Uma caixa não pode ser escolhida novamente após ser aberta.

⚔️ JOGO 3- GOUSMAS WAR

Este é um jogo estratégico de turnos entre dois jogadores.
Cada jogador controla duas criaturas chamadas Gousmas.
Cada Gousma possui um atributo chamado fúria.

Ações possíveis: Durante o turno, o jogador pode escolher entre duas ações:

⚔️ Atacar

A Gousma atacante soma sua fúria à Gousma inimiga.


Se a fúria ultrapassar 5, a Gousma é destruída.

🔀 Dividir

Uma Gousma pode transferir parte de sua fúria para outra Gousma do mesmo jogador.

Regras:

deve transferir pelo menos 1 ponto

-a Gousma doadora não pode ficar com 0

-uma Gousma destruída pode voltar ao jogo

Condição de vitória:

-O jogador vence quando o adversário perde todas as suas Gousmas.



💻TECNOLOGIAS USADAS:
-Linguagem C
-Compilador Falcon C++
-Execução em console


🤖USO DE INTELIGENCIA ARTIFICIAL:

Durante o desenvolvimento do projeto, a ferramenta ChatGPT foi utilizada como apoio para:

-revisar lógica de algumas funções
-corrigir erros de compilação
-melhorar organização do código
-Alguns trechos tiveram auxílio direto da IA.



EXEMPLOS DO MEU USO COM A IA:
Exemplo 1 — Validação de caixa repetida


if(caixasAbertas[caixa]){
    printf("Essa caixa ja foi aberta\n");
    continue;
}
-Esse trecho impede que o jogador escolha uma caixa que já foi aberta anteriormente.


Exemplo 2 — Verificação de destruição de Gousma

if(jogadores[1-turno][d].furia > MAX_FURIA)
    jogadores[1-turno][d].ativa = 0;

-Esse código verifica se a fúria ultrapassou o limite permitido.


Exemplo 3 — Alternância automática de turnos
turno = 1 - turno;


-Esse comando alterna automaticamente o turno entre os jogadores.


👨‍💻AUTORA:Francinetti De Paula Abreu Pessoa


DISCIPLINA: Programação 1

📚 REFERENCIAS:
Além do material da disciplina, foram consultadas as seguintes fontes:

-Documentação da linguagem C(livro )
-ChatGPT (OpenAI)
    
