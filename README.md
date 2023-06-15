# 42_Projects

Um resumo da minha formação e um compilado dos projetos que realizei na 42 São Paulo.

*******

## índice

1. [O que é a 42?](#1)
1. [Formação](#1.5)
	- [Fase 1](#2)
	- [Fase 2](#3)
	- [Fase 3](#4)
1. [Como clonar este repositório?](#5)

*******

<div id='1'/>

## O que é a 42?

A École 42 é uma renomada escola de programação fundada na França por [Xavier Niel](https://www.forbes.com/profile/xavier-niel/) em 2013. Ela adota uma metodologia de ensino disruptiva e inovadora, baseada no aprendizado prático e colaborativo.

Ao contrário das instituições de ensino tradicionais, a École 42 não possui professores ou aulas formais. Em vez disso, os alunos aprendem principalmente por meio de projetos práticos e trocas com a comunidade. Essa abordagem incentiva a autonomia, o pensamento crítico e a resolução de problemas.

<div id='1.5'/>

## Formação

O currículo é composto por uma série de projetos temáticos, individuais ou em grupo, nos quais os alunos devem progredir. Cada projeto possui seus próprios desafios e metas a serem alcançadas. Os alunos devem completar cada projeto com sucesso antes de passar para o próximo, garantindo assim um aprendizado progressivo e sólido.

Cada projeto tem como objetivo ensinar conceitos fundamentais e explorar tecnologias importantes utilizadas no desenvolvimento de software. O catálogo a seguir abrange uma variedade de temas de programação abordados de maneira prática.

<div id='2'/>

### Fase 1 - Entrando em Órbita

Primeiros passos na formação, em que a maioria dos projetos utiliza a linguagem C, nesta etapa todos os projetos são individuais.

| Projeto | Descrição |
| --- | ---|
| **[Libft](https://github.com/gsmereka/Libtf)** | A Libft é uma biblioteca de funções em C que pode ser facilmente utilizada em qualquer projeto. Ela contém replicas de funções já existentes na biblioteca padrão de C. Em muitos projetos subsequentes, devemos utilizar as versões da Libft em vez das originais. |
| **[get_next_line](https://github.com/gsmereka/get_next_line)** | Uma função extra inclusa na Libft, tem o objetivo de possibilitar a leitura de linhas em arquivos de forma eficiente. |
| **[ft_printf](https://github.com/gsmereka/ft_printf)** | Replica da função printf, também incluída na Libft. |
| **[Born2BeRoot](https://github.com/gsmereka/born2beroot)** | Uma introdução ao uso de máquinas virtuais. Configuramos um servidor SSH e entendemos regras gerais de administração de sistemas, segurança de senhas e mais. |
| **[So_Long](https://github.com/gsmereka/So_long)** | Um jogo simples no estilo top-down, utilizando uma biblioteca gráfica simples implementada para a 42. |
| **[Pipex](https://github.com/gsmereka/Pipex)** | O Pipex tem o objetivo de simular como o operador '\|' funciona em processos Linux. |

<div id='3'/>

### Fase 2 - Ampliando Horizontes

Nesta etapa, temos acesso aos primeiros projetos em grupo e o primeiro desafio extra proposto pela 42.

| Projeto | Descrição |
| --- | ---|
| **[push_swap](https://github.com/gsmereka/push_swap)** | Um projeto visando entender algoritmos de ordenação, devemos escolher os melhores métodos para ordenar uma pilha de números aleatórios utilizando operações pré-determinadas.
| **[Minishell](https://github.com/gsmereka/Minishell)** | Uma réplica simples e funcional do Bash utilizado em Linux, também meu primeiro projeto em dupla e o com maior duração até então. |
| **[Philosophers](https://github.com/gsmereka/Philosophers)** | Um projeto focado em aprender o funcionamento de threads e resolução de data-races e death_locks (preciso anotar referencias). |
| **[NetPractice](https://github.com/gsmereka/netpractice)** | Uma introdução a redes e protocolo IPv4, em que devemos solucionar problemas de conexões entre redes e intra redes. |
| **[Cub3d / MiniRT](https://github.com/gsmereka/minirt)** | Meu segundo projeto gráfico e segundo projeto em dupla. |

<div id='4'/>

### Fase 3 - Explorando o Espaço

Em produção...

<div id='5'/>

## Como clonar este repositório?

Ao escrever o comando git clone, adicione a flag "--recurse-submodules" da seguinte forma:<br>

`git clone --recurse-submodules https://github.com/gsmereka/42_Projects.git`
