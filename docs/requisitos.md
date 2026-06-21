# Requisitos do Sistema

## Problema Identificado

As plataformas educacionais atuais apresentam algumas limitações que impactam a colaboração e o acompanhamento dos alunos, tais como:

* Dificuldade para criação de grupos diretamente na plataforma.
* Poucas atualizações e recursos colaborativos.
* Ausência de uma inteligência artificial voltada para explicações e resumos educacionais.
* Interface pouco organizada para gerenciamento de conteúdos.
* Falta de ferramentas para visualização de dados acadêmicos através de gráficos e tabelas.
* Pouca visibilidade para os professores sobre o engajamento dos alunos nos conteúdos disponibilizados.
* Limitações para avaliações em grupo.
* Ausência de papéis intermediários, como monitores.
* Falta de critérios personalizados para avaliação de trabalhos em grupo.

# Requisitos Funcionais

## RF01 - Autenticação

O sistema deve permitir login utilizando conta Google.

## RF02 - Gerenciamento de Turmas

O sistema deve permitir que usuários participem e gerenciem turmas.

## RF03 - Criação de Atividades

O sistema deve permitir que professores criem atividades para suas turmas.

## RF04 - Comunicação

O sistema deve permitir troca de mensagens entre alunos e professores.

## RF05 - Organização de Conteúdo

O sistema deve permitir a classificação e organização de conteúdos e documentos.

## RF06 - Grupos de Estudo

O sistema deve permitir a criação de grupos de estudo e conversa pelos alunos.

## RF07 - Monitoramento de Acesso

O sistema deve permitir que professores visualizem quais alunos acessaram conteúdos e documentos.

## RF08 - Avaliações em Grupo

O sistema deve permitir avaliações realizadas em grupo.

## RF09 - Perfis de Usuário

O sistema deve possuir diferentes perfis de acesso:

* Administrador
* Professor
* Aluno
* Monitor

## RF10 - Inteligência Artificial

O sistema deve disponibilizar uma inteligência artificial capaz de gerar explicações e resumos sobre conteúdos educacionais.

## RF11 - Avaliação Colaborativa

O sistema deve permitir que alunos avaliem apresentações e trabalhos realizados por outros grupos através de notas e critérios definidos pelo professor.

Ao final da avaliação, o sistema deve calcular automaticamente a média das notas atribuídas pelos alunos e combiná-la com a nota do professor, utilizando pesos configuráveis para compor a nota final da atividade.

# Regras de Negócio

## RN01

Apenas professores podem publicar atividades acadêmicas.

## RN02

Alunos podem criar grupos de conversa e estudo.

## RN03

Toda publicação de conteúdo deve possuir uma classificação obrigatória.

## RN04

O sistema deve permitir comunicação entre alunos e professores por mensagens internas.

## RN05

Monitores possuem permissões limitadas definidas pelo professor ou administrador.

## RN06

Avaliações em grupo devem possuir critérios previamente definidos pelo professor.

## RN07

O professor poderá definir se uma atividade utilizará avaliação colaborativa, bem como os pesos aplicados às notas dos alunos e à nota do professor na composição da nota final.

# Requisitos Não Funcionais

## RNF01 - Segurança

O sistema deve garantir autenticação segura e proteção dos dados dos usuários.

## RNF02 - Escalabilidade

O sistema deve suportar crescimento gradual de usuários sem perda significativa de desempenho.

## RNF03 - Integração

O sistema deve permitir futuras integrações com sistemas acadêmicos de escolas e universidades.

## RNF04 - Usabilidade

O sistema deve apresentar interface intuitiva e organizada para alunos e professores.

## RNF05 - Disponibilidade

O sistema deve estar disponível para acesso contínuo durante os períodos letivos.

# Funcionalidades Futuras

* Integração completa com sistemas de escolas e universidades.
* Controle de presença automatizado.
* Integração com sistemas de notas institucionais.
* Relatórios avançados de desempenho.
* Dashboards com gráficos e indicadores acadêmicos.
* Evolução da Inteligência Artificial para suporte educacional avançado.
