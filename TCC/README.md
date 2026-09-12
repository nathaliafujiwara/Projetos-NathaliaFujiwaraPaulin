# TCC
  
  Para me formar como técnica em eletrônica, eu tive que fazer um projeto final, para a matéria de Automação Industrial. Para isso, a turma 
foi dividida em três equipes, cada uma responsável por um módulo do projeto determinado pelo professor: o equilíbrio automático de um 
pêndulo invertido utilizando um motor com uma hélice acoplada. A minha equipe desenvolveu o módulo de aquisição de dados, para ler a 
angulação atual da estrutura e a velocidade com que o motor está girando e, logo em seguida, repassar essas informações para o módulo
responsável pelo controle da velocidade da hélice, para estabelecer o equilíbrio.

Para isso, utilizamos o microcontrolador PIC18F4550, que era utilizado nas aulas de Microprocessadores e Microcontroladores, e 
recebíamos as leituras não processadas do módulo de atuadores, que estavam usando um giroscópio para Arduíno, através de comunicação serial 
entre o Arduíno deles e nosso PIC. Para enviar as informações para o próximo módulo, convertemos os dados para corrente elétrica, além de 
imprimí-los em um display de LCD. 

Além do desenvolvimento da parte física do projeto, também tivémos que escrever um relatório e apresentá-lo para uma banca de 
professores de matérias técnicas, todos extremamente experientes e com excelentes feedbacks sobre nosso projeto. 

Esse trabalho necessitou de um trabalho em equipe impecável com a turma e muita comunicação eficiente, o que foi um grande desafio. 
Porém, no final, mesmo com nosso módulo funcionando perfeitamente e nosso esforço e trabalho reconhecido pelos professores, ao juntar 
todos os módulos o processo não funcionou, como o motor utilizado pelo grupo de atuadores queimou durante os testes finais logo antes
das apresentações.
