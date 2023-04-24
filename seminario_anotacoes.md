Os quatro valores do Xtreme Programming:
Comunicação
Simplicidade
Feedback
Coragem

Todas as práticas em resumo do Xtreme Programming (citar, mas não se alongar. Em negrito os tópicos que nos interessa):
- O jogo do planejamento: Rapidamente determine o escopo do próximo lançamento, combinando prioridades do negócio e estimativas técnicas. Assim que a realidade se sobrepor ao plano, atualize o plano.
- Lançamentos pequenos: Coloque um sistema simples em produção rapidamente, então lançar novas versões em ciclos curtos.
- Metáfora: Guie todo o desenvolvimento com uma simples história compartilhada de como o sistema funciona.
- Design simples: O sistema deve ser arquitetado da forma mais simples possível a cada dado momento. Complexidade extra deve ser removida assim que descoberta.
- Testes: Programadores continuamente escrevem testes de unidade, que devem executar sem falhas para que o desenvolvimento continue. Clientes escrevem testes demonstrando que os recursos estão concluídos.
- Refatorando: Programadores reestruturam o sistema sem alterar o seu comportamento, para remover duplicação, melhorar a comunicação, simplificar e adicionar flexibilidade.
- **Programação em Pares: Todo código de produção é escrito com dois programadores em um computador.**
- **Propriedade Coletiva: Qualquer um, a qualquer momento, em qualquer ponto, pode alterar qualquer código do sistema.**
- Integração Contínua: Integrar e compilar o sistema diversas vezes a cada vez que uma tarefa é concluída.
- Semana de 40 horas: A princípio não trabalhe mais que 40 horas por semana. Nunca faça hora extra por duas semanas consecutivas.
- Cliente no local: Inclua um usuário real no time, disponível tempo integral para responder perguntas.
- Padrões (*standards*) de código: Os programadores escrevem todo código de acordo com regras que enfatizam comunicação através do código.

Programação em pares é uma forma de code review integrada. É a filosofia do [depuração com pato de borracha](https://pt.wikipedia.org/wiki/Debug_com_Pato_de_Borracha) levada ao próximo nível.


There are two roles in each pair. One partner, the one with the keyboard and the mouse, is
thinking about the best way to implement this method right here. The other partner is thinking more
strategically:
- Is this whole approach going to work?
- What are some other test cases that might not work yet?
- Is there some way to simplify the whole system so the current problem just disappears?
Pairing is dynamic. If two people pair in the morning, in the afternoon they might easily be paired
with other folks. If you have responsibility for a task in an area that is unfamiliar to you, you might
ask someone with recent experience to pair with you. More often, anyone on the team will do as a
partner.