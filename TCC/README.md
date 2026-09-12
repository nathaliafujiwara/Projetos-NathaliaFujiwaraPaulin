# TCC
  
  Para me formar como técnica em eletrônica, tive que desenvolver um projeto final para a matéria de Automação Industrial. Para isso, a turma foi dividida em três equipes, cada uma responsável por um módulo do projeto determinado pelo professor: o equilíbrio automático de um pêndulo invertido utilizando um motor com uma hélice acoplada. 
  
  A minha equipe ficou responsável pelo módulo de aquisição de dados, que deveria ler a angulação atual da estrutura e a velocidade com que o motor está girando e,  em seguida, repassar essas informações para o módulo responsável pelo controle da velocidade da hélice, para estabelecer o equilíbrio.

Para isso, utilizamos o microcontrolador PIC18F4550, que já era utilizado nas aulas de Microprocessadores e Microcontroladores. Recebíamos as leituras não processadas do módulo de atuadores, que utilizava um giroscópio para Arduino, através de comunicação serial entre o Arduino deles e nosso PIC. Para enviar as informações para o próximo módulo, convertemos os dados para corrente elétrica, além de exibi-los em um display de LCD. 

Além do desenvolvimento da parte física do projeto, também tivemos que escrever um relatório e apresentá-lo para uma banca de professores de matérias técnicas. Recebemos diversos feedbacks sobre nosso projeto, que nos ajudaram a enxergar os pontos fortes e fracos de nossa solução. 

Esse trabalho exigiu um trabalho em equipe muito intenso e comunicação eficiente, tanto dentro do grupo quanto com a sala, o que foi um grande desafio. No final, nosso módulo funcionou perfeitamente e nosso esforço e trabalho foi reconhecido pelos professores. Porém, ao juntarmos todos os módulos, o processo não funcionou, pois o motor utilizado pelo grupo de atuadores queimou durante os testes finais, pouco antes das apresentações.
