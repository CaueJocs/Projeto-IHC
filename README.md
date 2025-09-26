# Projeto de Interface Humano-Computador

Projeto apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Interface Humano-Computador (CC8122) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://buscatextual.cnpq.br/buscatextual/visualizacv.do?metodo=apresentar&id=K4276893H6) e Prof. Dr. [Plinio Thomaz Aquino Junior](https://buscatextual.cnpq.br/buscatextual/visualizacv.do?metodo=apresentar&id=K4760819P7).

Este projeto se baseia no Trabalho de Conclusão de Curso (TCC) entitulado Sistema de Correção de Exercícios Físicos com MediaPipe: Uma Solução Multiplataforma Acessível sob orientação do Professor Victor Perrone de Lima Varela e desenvolvido pelos seguintes alunos:

- Caue Jacomini Zanatti
- Vinicius Henrique
- Luan Petroucic Moreno 
- Pedro Leite
- Giulliano Mazzaro

## Resumo

O projeto consiste em uma aplicação voltada à avaliação da execução de exercícios físicos a partir de vídeos. Utilizando a biblioteca MediaPipe para extração de poses corporais, o sistema realiza o processamento e análise dos movimentos gravados, gerando resultados matemáticos e métricas de desempenho sobre a execução dos exercícios.

O objetivo é oferecer uma solução acessível e multiplataforma que auxilie na correção de práticas físicas, contribuindo para a melhoria técnica dos usuários e possibilitando aplicações em contextos de treinamento, reabilitação e educação física.

## Introdução

2) Título Original do TCC: Comparação em tempo real de protocolo de exercícios fisioterápicos 
3) Nome do orientador: Victor Perrone de Lima Varela
4) Previsto desenvolver Interface? (  X ) Sim     (   ) Não
5) Objetivo do trabalho? Utilizar Pose Estimation para comparação de exercícios fisicos 
6) Qual o produto final?  O produto final do projeto é um sistema multiplataforma de análise de vídeos de exercícios físicos, que utiliza o MediaPipe para extrair poses corporais e aplicar cálculos matemáticos sobre os movimentos. A ferramenta gera relatórios e métricas quantitativas da execução dos exercícios, permitindo avaliar aspectos como postura, ângulos e repetições, oferecendo uma solução acessível para acompanhamento e correção da prática física. 
7) Quem é o usuário final deste produto? praticantes de atividades físicas, profissionais de educação física, treinadores e fisioterapeutas.
8) O que o usuário recebe de benefício ao usar esse produto? O benefício do usuário seria a possibilidade de receber um feedback objetivo e quantitativo sobre a execução dos exercícios, baseado em métricas matemáticas extraídas dos vídeos.
9) Quais as funcionalidades da ferramenta (visão do usuário)?  O usuário teria a opção testar a aplicação sem realmente comparar a pose com o vídeo base, opção de iniciar a gravação com comparação de pose, opção de verificar resultados e de escolher qual vídeo base deseja utilizar.
10) Quais tecnologias e ferramentas computacionais que pretendem usar neste projeto (TCC)? No projeto como linguagem principal será utilizado python no código fonte, mediapipe para extração da pose do usuário e do vídeo base, matplotlib para gráficos e analise das mídias e tkinter para criar a interface do usuário. 
11) Qual é o contexto de uso dessa aplicação? (esse já é um conceito de IHC que professor explicou na sala) ? o contexto de uso vai se consistir na execução do programa em ambientes fechados e controlados como consultórios ou triagens médicas. 

## Publico Alvo

- O produto é direcionado a praticantes de atividades físicas e profissionais da área de saúde e esporte, como educadores físicos, personal trainers e fisioterapeutas, além de instituições acadêmicas voltadas a estudos de movimento humano.
- Demográficas: jovens e adultos (18–45 anos) com interesse em atividades físicas regulares, bem como profissionais formados ou em formação em Educação Física, Fisioterapia e áreas afins.
- Comportamentais: pessoas que buscam melhorar sua performance nos treinos, monitorar resultados de forma precisa ou corrigir posturas para evitar lesões; profissionais que necessitam de ferramentas de análise para auxiliar alunos e pacientes.
- Psicográficas: indivíduos motivados por autodesenvolvimento, saúde, bem-estar e desempenho físico, que valorizam tecnologia acessível e métodos inovadores para otimizar resultados.
- Geográficas: aplicável em qualquer região, mas com maior potencial em centros urbanos, onde há maior concentração de academias, estúdios de treinamento, clínicas de fisioterapia e universidades com cursos de saúde e esporte.

## Análise de concorrência

1. Identifique os principais concorrentes ou softwares mais utilizados pelo seu público-alvo.
2. Colete informações sobre os concorrentes selecionados.
3. Analise as características e funcionalidades dos concorrentes.
4. Avalie a experiência do usuário (UX).
5. Examine os preços e modelos de negócio.
6. Pesquisa de satisfação do cliente e opiniões.
7. Identifique padrões e tendências no mercado.
8. Elabore relatórios e sumarize os resultados.
9. Extraia pontos positivos e faça recomendações.

### Personas

- Descreva as personas que irão interagir com a aplicação ou produto. Deixe claro suas principais caracteristicas e contextos sociais, econômicos e culturais.
- Quais informações sobre o usuário o serviço ou poduto deve guardar?

  - Persona primaira ...
  - Persona secundária ...
  - Outras personas ...

### Mapa de empatia

![Mapa de empatia](empatia.png)

- Determine o mapa de empatia[^1] de pelo menos uma persona primária e uma sercundária.
  - O que o usuário vê: aqui estamos falando do ambiente visual em que o usuário se encontra. Ou seja, o que ele efetivamente enxerga, as pessoas e objetos que estão ao seu redor. Isso ajuda a entender o contexto em que o usuário está inserido e as influências visuais que está recebendo.
  - O que o usuário ouve: neste quadrante, buscamos entender o que o usuário está ouvindo, os sons que o cercam e como eles influenciam suas ações.
  - O que o usuário diz e faz: aqui consideramos ações e comportamentos que o usuário apresenta durante sua interação com serviço ou poduto.
  - O que o usuário pensa e sente: neste quadrante, buscamos entender os pensamentos, sentimentos, emoções e percepções que o usuário tem em relação ao serviço ou poduto. Quais expectativas o usuário cria sobre o serviço ou poduto?
  Que tipo de serviço ou poduto mais agrada essa persona?
  - Dores: quando falamos sobre dores do usuário, estamos fazendo referência a quaisquer obstáculos, necessidades ou frustrações que o usuário possa experimentar ao tentar realizar uma tarefa ou alcançar um objetivo. Isso inclui, por exemplo, problemas de usabilidade, dificuldades de acesso ou outros desafios que podem afetar a experiência do usuário.
  - Ganhos: nesse caso estamos falando de quaisquer benefícios ou recompensas que o usuário possa experimentar ao utilizar o serviço ou poduto. Isso pode incluir economia de tempo ou facilidade de uso, por exemplo. Que desejos do usuário o serviço ou poduto satisfaz?

## Contexto de uso

- Descreva o ambiente em que o serviço ou poduto deve ser utilizado.
- Qual/quais o(s) contexto(s) sociais, econômicos e culturais existentes neste ambiente?
- Quais informações sobre o ambiente, o serviço ou poduto deve guardar antes de iniciar a interação?
- O que normalmente deve estar acontecendo com o ambiente quando o usuário interagir com o serviço ou poduto?

## Jornada do usuário

- Criar uma narrativa para o o seu serviço ou poduto com o usuário.
- Determine o que o usuário realiza desde a primeira até o última interação com o serviço ou poduto.
  - Descreva o que acontece ou pode acontecer passo a passo
  - Como a tarefa começa? Como a tarefa se desenvolve? Como a tarefa termina?


<!--
## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?
 -->
 
## Coleta de dados

## Modelo de tarefas

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

### Prototipação em baixo nível (papel)
#### Avaliação heurística

### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->
