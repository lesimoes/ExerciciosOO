# Exercicios de Fixação e Revisão sobre Orientação a Objetos


Ex01: Winglerson é funcionário em uma empresa de construção civíl e gosta de praticar ioga, 
é umbandista, tem o CPF 100.200.300-45, gosta de músicas dos anos 90, sua matrícula é 10030, 
não usa o Facebook desde 2018 e tem o cargo de marceneiro pleno. 
Objetivo: Criar classes, objetos e usar abstração para modelagem.

(a) Crie duas classes para representar Winglerson em dois domínios diferentes: 
  Domínio 01: Empresa de construção civíl
  Domínio 02: Uma rede social
  
  
 Dica: Use de abstração para separar o que faz ou não sentido em cada domínio.
 
 
(b) Crie uma classe principal que irá executar a aplicação. 
 Essa classe deve apenas gerenciar a entrada e saída de dados (leitura do teclado e informações em tela) 
 e criar um objeto para representar Winglerson como funcionário.
 

Ex02: Considerando a classe criada para representar Winglerson no domínio de uma empresa de construção civil 
responda as perguntas e se necessário mude o seu código para atender as expectativas.

Objetivo: Criar objetos consistentes.

(a) O objeto da classe são criados de modo consistente?

(b) Em OO podemos usar uma função especial invocada sempre ao criar objetos. Que tipo de função é essa?

(c) Implemente uma função que faça a validação de CPF.

(d) Podemos obrigar que todo objeto da classe que Winglerson faz parte tenho como obrigação validar o CPF e, 
apenas em quando for um CPF válido, criar um objeto?



Ex03: Agora vamos estender as capacidades da nossa classe, que iremos chamar de Funcionário.

Objetivo: Herança e Polimorfismo.

(a) Imagine que precisamos representar outro tipo de funcionário na nossa aplicação, 
esse novo tipo de funcionário tem as mesmas ações (funções e métodos) e propriedades (atributos) 
que já tínhamos implementado, porém ele deve ter, necessariamente, um curso superior. 
Como podemos alterar nossa classe para atender a nova demanda? Será necessário criar uma nova classe.

(b) Uma abordagem possível, porém não recomendada, é criar um nova classe e "copiar e colar" o código da classe anterior. 
Pense em quais o problemas dessa abordagem? Pense em manutenção de software. 
Essa abordagem melhora ou piora? Justifique sua resposta.

(c) Cria uma classe "pai" que irá conter as regras gerais para todos os funcionários e 
classes específicas que irão herdar regras da classe pai e implementar apenas as ações
ou propriedades que são diferentes.

(d) Imagine agora que a classe do objeto Winglerson deve ter outro atributo, 
esse atributo é "gerente" é um tipo de funcionário. Como seria a implementação?
