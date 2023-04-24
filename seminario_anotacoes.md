# Conceitos gerais de Xtreme Programming
### Vários pontos podem ser comentados brevemente, mas os em negrito são os que estão mais diretamente relacionados a *Pair Programming*
## Os quatro valores do Xtreme Programming:
- **Comunicação**: Comunicação entre a equipe, a equipe e os clientes e a equipe e a gerência. Código também é a uma forma de comunicação (nesse caso, sobre o sistema)
- Simplicidade: Evitar overengineering. Pensar nos requisitos de hoje e se adequar com as mudanças que vêm, "You aren't gonna need it" (YAGNI). Refatorar o código, simplificar e eliminar código inutilizado ou redundante.
- Feedback: Feedback constante do sistema, do cliente e entre a equipe. SEMPRE criar testes para toda funcionalidade criada, para que a representação do estado atual do sistema seja mais confiável
- Coragem: Mudar aspectos importantes do sistema. Se encontrar falhas graves na arquitetura ou em alguma funcionalidade, refatore. Se um código novo ainda não está bem feito ou ficou mais complexo do que deveria, ter coragem de jogar tudo fora e refazer do 0, as próximas iterações serão mais simples e elegantes.

## Todas as práticas em resumo do Xtreme Programming:
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


# Programação em Pares
## Por que é importante?
A programação em pares é uma forma de manter os desenvolvedores motivados, auxiliar na criação de sistemas mais robustos e de distribuição de conhecimento institucional.
## Como funciona?
Há duas responsabilidades em cada par. Um deles fica com o computador trabalhando diretamente com alguma tarefa, enquanto o outro está analisando se esta é a melhor forma de implementar o código, pensando de forma mais ampla. Ex: 
- Esta abordagem atende o que precisamos? 
- Que casos de teste ainda não cobrimos? 
- Há alguma forma de simplificar outras partes do sistema de forma que o problema desapareça?

Desta forma, programação em pares é uma forma de "code review integrada". É a filosofia da [depuração com pato de borracha](https://pt.wikipedia.org/wiki/Debug_com_Pato_de_Borracha) levada ao próximo nível.
Além disso, o pareamento é dinâmico. Os desenvolvedores podem alternar seus papéis ou um desenvolvedor pode, em outro horário ou dia se juntar a outro desenvolvedor.

O emparelhamento de dois desenvolvedores pode ter algumas variantes, como experiente-experiente, experiente-novato ou novato-novato. Cada tipo de emparelhamento fornece benefícios próprios. A escolha irá depender do objetivo de curto-médio prazo que a equipe se encontra no momento. Por exemplo, se há alguma tarefa que um desenvolvedor iniciante no domínio está encontrando dificuldade, ele pode pedir ajuda de alguém experiente para ajudar. Neste emparelhamento a idéia não é que a pessoa escreva o código trabalho para ele, mas que ambos se comuniquem até chegarem na solução.