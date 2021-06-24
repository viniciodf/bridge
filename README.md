Padroes de Projeto

1) Criacionais -> Os padrões criacionais fornecem vários mecanismos de criação de objetos, que aumentam a flexibilidade e reutilização de código já existente.
2) Estruturais -> Os padrões estruturais explicam como montar objetos e classes em estruturas maiores mas ainda mantendo essas estruturas flexíveis e eficientes.
3) Comportamentais -> Padrões comportamentais são voltados aos algoritmos e a designação de responsabilidades entre objetos.

* Estruturais

2.Bridge

O que é:
O Bridge é um padrão de projeto estrutural que divide a lógica de negócio ou uma enorme classe em hierarquias de classe separadas que podem ser desenvolvidas independentemente.

Aplicabilidade:
Utilize o padrão Bridge quando você quer dividir e organizar uma classe monolítica que tem diversas variantes da mesma funcionalidade (por exemplo, se a classe pode trabalhar com diversos servidores de base de dados).
Utilize o padrão quando você precisa estender uma classe em diversas dimensões ortogonais (independentes).
Utilize o Bridge se você precisar ser capaz de trocar implementações durante o momento de execução.

Identificação:
O Bridge pode ser reconhecido por uma distinção clara entre alguma entidade controladora e várias plataformas diferentes nas quais ela se baseia.

Exempos de utilizacao:
O padrão Bridge é especialmente útil ao lidar com aplicações de multi plataforma, oferecer suporte a vários tipos de servidores de banco de dados, ou ao trabalhar com vários provedores de API de um determinado tipo (por exemplo, plataformas em nuvem, redes sociais etc.)