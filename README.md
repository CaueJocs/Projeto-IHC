# Projeto de Interface Humano-Computador

Projeto apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Interface Humano-Computador (CC8122) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://buscatextual.cnpq.br/buscatextual/visualizacv.do?metodo=apresentar&id=K4276893H6) e Prof. Dr. [Plinio Thomaz Aquino Junior](https://buscatextual.cnpq.br/buscatextual/visualizacv.do?metodo=apresentar&id=K4760819P7).

Este projeto se baseia no Trabalho de Conclusão de Curso (TCC) entitulado Sistema de Correção de Exercícios Físicos com MediaPipe sob orientação do Professor Victor Perrone de Lima Varela e desenvolvido pelos seguintes alunos:

- Luan Petroucic Moreno – RA: 22.122.076‑7
- Vinicius Henrique Silva – RA: 22.122.063‑5
- Cauê Jacomini Zanatti – RA: 22.122.024‑7
- Giulliano Mazzaro Camargo – RA: 22.121.024‑8
- Pedro Henrique Almeida Leite – RA: 22.221.003‑1


## Resumo

O projeto consiste em uma aplicação voltada à avaliação da execução de exercícios físicos a partir de vídeos. Utilizando a biblioteca MediaPipe para extração de poses corporais, o sistema realiza o processamento e análise dos movimentos gravados, gerando resultados matemáticos e métricas de desempenho sobre a execução dos exercícios.

O objetivo é oferecer uma solução acessível e multiplataforma que auxilie na correção de práticas físicas, contribuindo para a melhoria técnica dos usuários e possibilitando aplicações em contextos de treinamento, reabilitação e educação física.

## Introdução

2) Título Original do TCC: Sistema de Correção de Exercícios Físicos com MediaPipe
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

## Desenvolvimento
- [Análise de Concorência](https://github.com/CaueJocs/Projeto-IHC/wiki/02-%E2%80%90-An%C3%A1lise-De-Concorr%C3%AAncia)
- [Personas](https://github.com/CaueJocs/Projeto-IHC/wiki/03-%E2%80%90-Personas)
- [Cenário de Análise/Problema](https://github.com/CaueJocs/Projeto-IHC/wiki/04-%E2%80%90-Cen%C3%A1rio-de-An%C3%A1lise-Problema)
- [Análide de Tarefas](https://github.com/CaueJocs/Projeto-IHC/wiki/05-%E2%80%90-An%C3%A1lise-de-Tarefas)
- [Prototipação em Papel](https://github.com/CaueJocs/Projeto-IHC/wiki/06-%E2%80%90-Prototipa%C3%A7%C3%A3o-em-Papel)
- [Coleta de Dados](https://github.com/CaueJocs/Projeto-IHC/wiki/07-%E2%80%90-M%C3%A9todos-de-Coleta-de-Informa%C3%A7%C3%A3o)
- [Ciclo de vida da engenharia de usabilidade](https://github.com/CaueJocs/Projeto-IHC/wiki/08-%E2%80%90-Ciclo-de-vida-da-engenharia-de-usabilidade)
- [Modelo Conceitual](https://github.com/CaueJocs/Projeto-IHC/wiki/09-%E2%80%90-Modelo-Conceitual) 
- [MOLIC](https://github.com/CaueJocs/Projeto-IHC/wiki/10-%E2%80%90-MOLIC)
- [FIGMA](https://github.com/CaueJocs/Projeto-IHC/wiki/11-%E2%80%90-FIGMA)
- [Planejamento da Avaliação](https://github.com/CaueJocs/Projeto-IHC/wiki/12%E2%80%90-Planejamento-da-Avalia%C3%A7%C3%A3o)
- [Avaliação de IHC através de Inspeção Heurística](https://github.com/CaueJocs/Projeto-IHC/wiki/13-%E2%80%90-Avalia%C3%A7%C3%A3o-de-IHC-atrav%C3%A9s-de-Inspe%C3%A7%C3%A3o-Heur%C3%ADstica)
- [Avaliação de Usabilidade baseado em Observação do Usuário](https://github.com/CaueJocs/Projeto-IHC/wiki/14-%E2%80%90-Avalia%C3%A7%C3%A3o-de-Usabilidade-baseado-em-Observa%C3%A7%C3%A3o-do-Usu%C3%A1rio)
