

# Projeto Disciplina: IHC


Olá! Este repositório faz parte do projeto da disciplina de Interação Homem Computador da UTFPR - Campus Cornélio Procópio. 

## 1. Introdução

***1.1.  Nome do Grupo***

- Teacher Connect

***1.2.  Problema***

- Descrição do problema: Queremos melhorar a interação professor, com um app mobile que traz funcionalidades para o professor.
  Por exemplo: Registro de diário de frequência, capacitações, entre outras...

***1.3.  Análise dos sistemas concorrentes***

- Documentos Físicos: Muitos professores ainda realizam tarefas de forma manual, como por exemplo, a chamada por meio de papel. Tal fato pode se tornar um problema pelo acúmulo de papelada, gasto desnecessário de material ou financeiro ou uma complicação na organização de documentos. 

- Office 365: A biblioteca da Microsoft é um dos principais softwares utilizados entre os professores para a realização de simples tarefas, desde criação de documentos, anotação de faltas ou realização de arquivos para a aula.

***1.4.  Público Alvo***
- Professores do ensino fundamental e médio do ensino público, que possuem pouca familiaridade com informática.

## 2. Perfil do usuário

***2.1. Descrição dos Usuários: Personas***

### [Professora Clara](./Personas/Professora%20Clara.md)
![image](https://raw.githubusercontent.com/yuriGY/disciplina-ihc/main/images/persona%201.png)

### [Professor Carlos](./Personas/Professor%20Carlos.md)
![image](https://raw.githubusercontent.com/yuriGY/disciplina-ihc/main/images/persona%202.png)

***2.2. Análise de Tarefas: ANTES***

![image](https://raw.githubusercontent.com/yuriGY/disciplina-ihc/main/images/analise-tarefas-antes.png)

***2.3. Análise de Tarefas: DEPOIS***
![image](https://raw.githubusercontent.com/yuriGY/disciplina-ihc/main/images/analise-de-tarefas-depois.png)


## 3. Design

***3.1. Requisitos Funcionais***

Apresente os requisitos funcionais do sistema (listagem de tudo o que o sistema deveria fazer).  No mínimo 15 requisitos. 

**Requisitos Funcionais**
| ID   | Requisito Funcional                                                                                                                                                             | Prioridade |
|------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| RF01 | O sistema deve permitir que professores façam login utilizando um nome de usuário e senha.                                                                                      | Alta       |
| RF02 | O sistema deve permitir o cadastro e atualização de novos professores, incluindo informações como nome, e-mail, cpf.                                                            | Alta       |
| RF03 | O sistema deve permitir o cadastro e atualização de novas turmas, incluindo informações como nome da turma e professor responsável.                                             | Alta       |
| RF04 | O sistema deve incluir um menu acessível a partir da interface principal, permitindo aos usuários acessar diferentes opções e funcionalidades oferecidas pelo sistema.          | Média      |
| RF05 | O sistema deve permitir o cadastro e atualização de novos alunos, incluindo informações como nome, data de nascimento, e-mail, telefone e turma à qual pertencem.               | Alta       |
| RF06 | O sistema deve ter um sistema de avaliação e feedback dos alunos.                                                                                                               | Baixa      |
| RF07 | O sistema deve permitir o registro e acompanhamento de presença dos alunos.                                                                                                     | Média      |
| RF08 | O sistema deve permitir que professores editem registros de frequência dos alunos para corrigir erros ou atualizar informações.                                                 | Média      |
| RF09 | O sistema deve possuir um modulo de capacitação para professores.                                                                                                               | Média      |
| RF10 | O sistema deve permitir que os professores consultem seus certificados.                                                                                                         | Baixa      |
| RF11 | O sistema deve permitir que professores entrem na área de turmas para visualizar e gerenciar as turmas que estão lecionando.                                                    | Média      |
    
***3.2. Descrição textual***    

Apresente uma descrição textual resumida do seu design.  Quais as funcionalidades, principais escolhas de design, dentre outros. 

- O design proposto para o aplicativo visa otimizar a interação dos professores com as suas respectivas atividades diárias. Entre as principais funcionalidades, o aplicativo oferecerá um sistema de registro de frequência diário, permitindo que os professores acompanhem a presença e a participação dos alunos de forma eficiente. Além disso, o aplicativo terá uma seção dedicada a cursos de capacitação, onde os professores poderão se atualizar e aprimorar suas habilidades pedagógicas. As principais escolhas de design foram feitas pensando na usabilidade e na praticidade para o usuário, com uma interface amigável e intuitiva.

***3.3. Design preliminar***      

Apresente uma ilustrações do design: incluir os desenhos (sketches) das telas relativas à interface do seu sistema. 
- [Clique aqui para acessar as sketches](https://github.com/yuriGY/disciplina-ihc/blob/main/ninjamock-project.pdf)

## 4. Protótipo

Apresentar o protótipo "em uso". Seu protótipo deve ser construído utilizando o Figma. 
- [Link para acessar o protótipo do Figma](https://www.figma.com/design/V6ERk0hssqPSuDTTxODIJY/Untitled?node-id=0%3A1&t=Og03IPeV5BFO8RbF-1)

## 5. Avaliação e Re-Design

***5.1. Avaliação com usuários*** 

Esta avaliação consiste na aplicação do método Think  Aloud com dois usuários. Vocês devem gravar o áudio do usuário e a tela do protótipo durante o teste.

-   Apresentar um vídeo de 3 minutos que resume os principais problemas encontrados.    
[Link para acessar o vídeo sobre os principais problemas](https://youtu.be/UYVEbVJkGns)

ANTES de conduzir o teste, defina as seguintes questões:

-   O que se deseja obter?
<br>R: Queremos definir possíveis dificuldades do uso do protótipo, a interação do usuário com ele para analisarmos a melhoria de seu design.    
-   Quando e onde vai acontecer?
<br>R: O teste será realizado de forma online após a conclusão inicial do protótipo do Figma.  
-   Qual a duração prevista de cada sessão?
<br>R: Cada sessão tem a estimativa de 5 minutos para o usuário se interar com as páginas.   
-   Qual o estado do sistema no início do teste?
<br>R: O sistema no início está em estado de prontidão aguardando a ação do usuário.   
-   Quem serão os usuários?
<br>R: Pessoas relacionadas a área da educação.       
-   Quais tarefas serão solicitadas aos usuários?
<br>R: Entrada de páginas e comunicação com as interações da tela para a visualização das suas expectativas nas entradas e saídas das informações.      
-   Qual critério será utilizado para decidir que os usuários terminaram cada tarefa corretamente?    
R: Pelo feedback final do usuário com a orientação de entrar em todas as telas.  
<br><br>Por fim, os resultados devem ser analisados e apresentados da seguinte forma:

-   Descrever  a avaliação e os resultados obtidos (quais problemas foram identificados no seu design?).
<br>R: O sistema foi relatado como uma interface fácil, agradável e intuitiva de se utilizar, porém com algumas limitações em relação ao uso do Figma e também com a possibilidade de melhoria para a interação.  
-   Resumir os resultados das avaliações com análise crítica referente e se os princípios e metas de usabilidade considerados importantes para o seu sistema foram satisfeitos ou não.
<br>R: Acreditamos que o protótipo aparenta estar com um feedback positivo devido aos relatos dos testes e que a usabilidade está clara e simples segundo a fácil navegação entre as páginas pelos relatos, contudo, acreditamos que há sim espaço para melhorias, porém, as nossas metas foram batidas pelas nossas definições prévias.
- Apresentar uma análise crítica da avaliação realizada, com identificação de problemas e sugestões de melhorias (quais modificações devem ser realizadas na próxima versão do protótipo?).
<br>R: O grupo decidiu que o design poderia ter uma melhoria em relação aos elementos de navegação, como em relação ao tamanho dos botões de menu para o acesso entre as telas e pop-ups e num maior destaque de cor ou tamanho de textos de maior importância com o intuito de situar melhor o cenário em que o cliente se encontra.
## Referências


***Relato - Usuário 1***

![image](https://raw.githubusercontent.com/yuriGY/disciplina-ihc/main/images/Usu%C3%A1rio%201.png)

***Relato - Usuário 2***
![image](https://raw.githubusercontent.com/yuriGY/disciplina-ihc/main/images/Usu%C3%A1rio%202.png)

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.

[2] Stackedit.io <edição de texto para o GitHub>
