## SENAI-SP

### UC12 - SA2 - Atividade online1

### Modelagem do diagrama UML, conforme o que foi solicitado na atividade.

Consiste na modelagem de um sistema de clientes por meio de um diagrama de classes UML _simplificado_, de forma a criar relacionamentos entre as entidades vinculadas. 

As entidades envolvidas, os atributos , métodos e a lógica dos relacionamentos entre as classes, são criados de acordo com o levantamento de requisitos, em que é definido, junto ao cliente, o que o sistema se propõe a fazer.

Nesta atividade, para fins de simplificação, apenas foi solicitada a criação do método "pagar imposto" dentro da classe Pessoa, não sendo levando em conta, até então, questões sobre cardinalidade entre as classes. Por meio desta atividade, foi possível estudar os conceitos de relacionamento, contendo herança e composição, abordados em aula. Observe ainda que no diagrama da classe pai (Pessoa), foi  criado um atributo e um método com modificadores de acesso protegido, onde somente as classes filhas (Pessoa Física e Pessoa Jurídica) poderão obter informações da classe pai. Desta forma, esse relacionamento de herança exclusivo entre as entidades, permite o seu isolamento em relação ao meio externo que , se contivessem outras classes,  não conseguiriam acessar as classes pai e filhas mencionadas.  Isto reforça o conceito do encapsulamento.   

Também foram criados atributos privados em algumas classes, com o intuito de preservar a integridade dos dados, impedindo o seu acesso não autorizado. Desta forma, apenas os métodos públicos que irão permitir a (inserção/recuperação) de dados (no/do objeto), onde novamente o conceito de encapsulamento entra em cena. Para fins de simplificação, não foram criados outros métodos.


![diagrama](https://user-images.githubusercontent.com/88597534/150710321-e39b0da2-c01d-4dde-b5d6-436d12df88d4.jpg)


