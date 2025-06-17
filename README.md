
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Link do Padlet: [Padlet Planeta+](https://padlet.com/marianagp294/requisitos-de-software-planeta-2lc5dzeb944hrf6r)

## 1. Introdução

***1.1.  Camille DalLin de Oliveira - 2648784
Júlia Pivello Vila Real - 2565684
Mariana Gasparotto Palácios - 2648890
Maurício Albuquerque Christakis - 2649152***

***1.2.  Planeta+***

***1.3.  A ideia é um aplicativo mobile com quizzes e desafios para reduzir a pegada ambiental do usuário (ex: "Plante uma árvore virtual"). O problema a ser resolvido é a falta de conscientização sobre hábitos poluentes.***

Este documento apresenta os requisitos dos usuários a serem desenvolvidos pela Planeta+, fornecendo aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

O objetivo do sistema Planeta+ é conscientizar sobre a pegada ambiental e hábitos poluentes dos usuários, utilizando  jogos em forma de quizzes e outros recursos interativos que ensinam as atitudes adequadas com relação ao meio ambiente, simulando situações para verificar as atitudes do usuário. O sistema ajudará a resolver o problema da falta de conscientização sobre hábitos poluentes.

***1.2.  Público Alvo***

Este documento se destina aos arquitetos de software, engenheiros de software, testadores, clientes.

***1.3. Descrição dos usuários***
Os usuários finais do sistema serão indivíduos interessados em conscientizar-se quanto a questões sustentáveis e, por ter uma interface dinâmica e jogos educativos, o software tem potencial de ser utilizado principalmente por crianças e jovens.

***Personas:***

> **Persona Usuário**
<img src="https://github.com/PlanetaPlus/Planeta-/blob/main/Requisitos/Usuario_Persona.jpg" alt="Persona Usuário">

-------------------------------------------------------------

> **Persona Anti-Usuário**
<img src="https://github.com/PlanetaPlus/Planeta-/blob/main/Requisitos/AntiUsuario_Persona.jpg" alt= "Persona Anti-Usuário">

----------------------------------------------------------------------------------------------------

### ***Análise da situação atual: antes da introdução de sua solução***

1. **O que as pessoas fazem?**
     - Não têm o costume de se preocuparem com os danos que causam ao meio-ambiente. 

2. **Quais os artefatos envolvidos?**
     - Não são utilizados artefatos.

3. **O que elas precisam saber?**
     - Que devem ser usados mecanismos para controlar nossos danos ao meio-ambiente.

------------------------------------

### ***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***

1. **O que as pessoas fazem?** 

   - Preocupam-se com os danos que causam ao meio-ambiente.


2.  **Quais os artefatos envolvidos?**

    - Aplicativo mobile Planeta+

    - Quizzes e jogos interativos

    - Sistema de recompensas (como medalhas, conquistas virtuais, árvore virtual etc.)

    -  Relatórios de progresso do usuário

    - Notificações e lembretes ecológicos

    - Recursos visuais e gamificados para educação ambiental



3. **O que elas precisam saber?**

    - Que devem continuar usando plataformas como a Planeta+ para serem conscientes sobre suas ações.


***Cenário: Antes***

Antes da aplicação do sistema Planeta+, a maioria das pessoas, especialmente crianças e jovens, não possui o hábito de refletir sobre os impactos ambientais de suas ações diárias. O tema da sustentabilidade é frequentemente percebido como distante ou irrelevante, e os conteúdos educativos sobre o assunto são pouco atrativos ou acessíveis. Os usuários não utilizam ferramentas ou aplicativos que incentivem a mudança de comportamento ambiental, o que contribui para a manutenção de hábitos poluentes e pouco sustentáveis no cotidiano.

***Cenário: Depois***

Após a implementação do sistema Planeta+, os usuários passam a interagir com um aplicativo envolvente e educativo que os estimula a refletir e agir de forma mais consciente em relação ao meio ambiente. Por meio de quizzes, desafios e recompensas virtuais, eles aprendem conceitos importantes de sustentabilidade e são incentivados a adotar hábitos mais ecológicos, como economizar água, reduzir o uso de plástico e plantar árvores virtuais (com incentivo para ações reais). O aplicativo se torna um aliado no processo de conscientização ambiental, promovendo mudanças positivas de comportamento de forma lúdica e acessível.

-----------------------------------

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

| ID | REQUISITO FUNCIONAL | PRIORIDADE | DEPENDE DE |
| -- | ------------------- | --------- | ----------- |
| RF01  | O software deve permitir que o usuário crie/faça login em uma conta. |M|            |
| RF02  | O sistema deve permitir que o usuário compartilhe o seu progresso nas redes sociais. |C| RF01, RF06, RNF04 |
| RF03  | O software deve permitir que o usuário calcule a sua pegada de carbono com base em seus hábitos diários. |M| RF01, RNF02 |
| RF04  | O software deve permitir que o usuário visualize um ranking de pontuações sobre a diminuição de CO2. |S| RF01,RF03, RNF07 |
| RF05  | O sistema deve permitir que o usuário exporte os dados, como relatórios sobre o cálculo da pegada de carbono e resultado de quizzes em PDF para trabalhos escolares. |W| RF03, RF06, RNF09 |
| RF06  |  O software deve permitir que o usuário acompanhe seu progresso na diminuição da pegada de carbono, de acordo com o histórico de pegada de carbono e de resultado de quizzes. |M| RF01, RF03, RNF10 |
| RF07  | O sistema deve permitir que o usuário receba uma avaliação semanalmente da sua evolução. |M| RF01, RF06, RNF08 |
| RF08  | O sistema deve permitir que o usuário faça quizzes sobre o impacto dos seus hábitos. |M| RF01, RNF05 |
| RF09  | O sistema deve permitir que o usuário resgate pontos de lojas parceiras. |C| RF01, RF06, RNF04 |
| RF10  | O software deve permitir que o usuário veja gráficos coloridos sobre o quanto ele melhorou mês a mês. |S| RF01, RF06, RNF02, RNF06 |
| RF11  | O software deve emitir um selo “amigo do clima” para usuários e empresas com bom desempenho sustentável. |S| RF06, RF07 |
| RF12  | O sistema deve permitir que o usuário visualize suas árvores e conquistas em uma tela dedicada com interações visuais (focado exclusivamente na árvore virtual, já que é central no app) |C|RF06, RF10|
| RF13  | O sistema deve permitir a configuração personalizada de lembretes e notificações (relacionado à tela de configurações). |C|RF06, RNF08|
| RF14  | O sistema deve exibir na tela inicial um planeta cuja aparência muda dinamicamente conforme os hábitos sustentáveis do usuário, ficando saudável com bons hábitos e poluído com maus hábitos. |M|RF06, RF10|
| RF15 | O sistema deve conceder gotas de água virtuais ao usuário como recompensa por cada conquista, que poderão ser usadas para regar sua árvore virtual. |S|RF04, RF05|

--------------------------

***2.2. Requisitos Não Funcionais***
| ID | REQUISITO FUNCIONAL | PRIORIDADE | DEPENDE DE |
| -- | ------------------- | --------- | ----------- |
| RNF01  | O aplicativo deve ser compatível com as versões mais recentes do Android e iOS. |M|            |
| RNF02  | O tempo de resposta do aplicativo deve ser inferior a 2 segundos para qualquer ação do usuário. |M| RNF07 |
| RNF03  |O aplicativo deve consumir menos de 5% de bateria em uso contínuo por 1 hora. |S| RNF01, RNF09 |
| RNF04  | O armazenamento de dados do usuário deve ser criptografado para garantir segurança e privacidade. |M| RF01 |
| RNF05  | O aplicativo deve funcionar offline para visualização de quizzes já baixados. |C| RF08, RNF09 |
| RNF06  | A interface do usuário (UI) deve seguir princípios de acessibilidade WCAG 2.1 |M| RF10 |
| RNF07  | O aplicativo deve suportar até 10.000 usuários simultâneos sem degradação de desempenho. |S| RF01, RF04 |
| RNF08  | O sistema deve enviar notificações push apenas em horários pré-definidos (evitando spamming). |C| RF01, RF07 |
| RNF09  | O aplicativo deve ocupar menos de 50 MB de espaço no dispositivo do usuário. |C| RF05, RF10 |
| RNF10  | As atualizações do aplicativo devem ser lançadas trimestralmente com melhorias e correções, de segurança, usabilidade e desempenho |S| RF06, RF07 |
| RNF11  | O sistema deve estar em conformidade com a LGPD, incluindo termos de uso e consentimento do usuário para coleta de dados. |M| RF01 |
| RNF12  | A arquitetura do aplicativo deve ser flexível e escalável para permitir crescimento futuro e uso por instituições (como escolas). |S||


Link da planilha com os requisitos e tipos de dependência: https://docs.google.com/spreadsheets/d/1Du95BnGc2OFL156DzZyPDY-ckGwqj1C-JvwXgmwB0TQ/edit?gid=2116779670#gid=2116779670

***2.3. Perguntas***

**Roteiro de Perguntas para Entrevista**
> *Sobre o cálculo da pegada de carbono (RF03)*
- Que fatores você considera essenciais para que o cálculo da pegada de carbono de um indivíduo seja preciso?
- Existem metodologias ou bases de dados que você recomenda utilizar?
- Como podemos tornar esse cálculo simples o suficiente para usuários leigos, mas ainda confiável?
  
> *Sobre o progresso e comportamento do usuário (RF06)*
- Que tipo de feedback seria mais eficaz para incentivar mudanças de hábito sustentáveis?
- Acompanhar o progresso ambiental mês a mês é realista? Como você sugere que isso seja feito?
- Existe alguma métrica visual (ex: equivalente de árvores, água economizada) que funcione bem para engajar?

> *Sobre quizzes e educação ambiental (RF08)*
- O uso de quizzes sobre sustentabilidade pode de fato educar ou transformar comportamento?
- Que tipo de conteúdo você acredita ser mais eficaz nesses quizzes (mitos, estatísticas, comparações)?
- Você tem exemplos de campanhas bem-sucedidas usando gamificação ambiental?
  
> *Sobre a criação de conta e segurança (RF01 + RNF04)*
- A criação de conta deve exigir nome e e-mail, ou menos? Há riscos em termos de dados pessoais nesse contexto?
- Você considera essencial criptografar os dados de hábitos ambientais dos usuários? Por quê?
  
> *Sobre o desempenho e acesso (RNF01, RNF02, RNF07)*
- Para um app educacional de sustentabilidade, você acha importante que ele funcione em qualquer celular, mesmo mais antigo?
- Você vê algum impacto ambiental negativo em um app que exige internet constante ou alto consumo de energia?
- Suportar milhares de usuários simultâneos é importante ou pode ser resolvido com outros meios (ex: escalonamento)?


***2.4. Entrevista***

- **Relatorio da entrevista:** 
A entrevista abordou a criação de um aplicativo educacional gamificado com foco em sustentabilidade, motivado pela experiência de vida de Maurício em sua cidade natal, Paranaguá. A equipe planeja incluir quizzes teóricos e funcionalidades para calcular a pegada de carbono dos usuários, visando tornar as informações acessíveis e impactantes, com a possibilidade de um selo 'amigo do clima' para empresas. Durante a reunião, foram discutidos feedbacks eficazes para promover mudanças de comportamento, a importância da conformidade com a LGPD na coleta de dados e a necessidade de planejar a arquitetura do aplicativo para escalabilidade futura. A entrevistadora sugeriu várias consultorias e pesquisas adicionais para aprimorar o projeto, além de convidar a equipe a apresentar o protótipo final ao projeto de extensão dela.

**Notas:**


**Motivação e Origem do Projeto (00:00 - 06:00)**
1. Maurício (Integrante do grupo) explicou que sua motivação veio de sua cidade natal Paranaguá, com forte contato com questões ambientais.
2. O projeto surgiu de conversa com a avó, professora, que notou que crianças não entendem sustentabilidade.
3. A equipe decidiu aliar tecnologia e sustentabilidade, criando um aplicativo educacional.
4. A proposta foi aprovada pela professora apesar da complexidade inicial.
5. A entrevistadora destacou a importância de associar tecnologia com questões socioambientais.



**Conceito e Funcionalidades do Aplicativo (06:00 - 14:19)**
1. Equipe está desenvolvendo um protótipo gamificado semelhante ao Duolingo.
2. Aplicativo incluirá quizzes teóricos sobre sustentabilidade.
3. Funcionalidade para calcular pegada de carbono baseada nos hábitos do usuário.
4. Sugestão de tornar o cálculo da pegada de carbono mais acessível para leigos.
5. A entrevistadora mencionou a importância de exemplos comparativos para usuários entenderem seu impacto.
6. Equipe considera implementar um selo 'amigo do clima' para empresas.
7. A entrevistadora sugeriu consultar a norma ABNT PR 2030 para empresas ESG.



**Feedback e Relatórios (14:19 - 22:41)**
1. Discussão sobre tipos de feedback eficazes para mudança de comportamento.
2. Sugestão de mostrar dados de impacto a longo prazo (ex: uso de esponjas plásticas ao longo de um ano).
3. A equipe planeja implementar relatórios mensais e um relatório anual abrangente.
4. Sugestão de tornar relatórios visualmente atrativos, similar ao modelo do Spotify.
5. Proposta de elementos visuais que mostram os impactos ambientais (ex: floresta que melhora ou piora).
6. Confirmação de que quizzes podem efetivamente educar e conscientizar sobre sustentabilidade.
7. Importância de contextualizar os conteúdos para o dia-a-dia do público-alvo.



**Dados, Privacidade e Desempenho (22:41 - 39:08)**
1. Discussão sobre coleta de dados pessoais (nome, e-mail) e necessidade de termos de serviço.
2. Importância de conformidade com LGPD para dados dos usuários.
3. Criptografia considerada desejável mas não prioritária inicialmente.
4. Foco em desenvolver para dispositivos com poucos recursos computacionais, especialmente para escolas públicas.
5. Sugestão de considerar o impacto ambiental do próprio aplicativo e planejar compensações.
6. Recomendação de projetar arquitetura flexível para escalabilidade futura.
7. A entrevistadora sugeriu pesquisar sobre Sistema B para modelo de negócio.
8. Convite para apresentar o protótipo final ao projeto de extensão da entrevistadora.



**Atitudes a tomar após reunião**
1. Consultar a Fundação Ellen MacArthur e Instituto Lixo Zero para obter materiais sobre economia circular e pegada de carbono (09:06)
2 .Examinar a norma ABNT PR 2030 para recomendações para empresas ESG (14:19)
3. Pesquisar navegador Ecosia como exemplo de tecnologia com propósito socioambiental (24:32)
4. Implementar termos de serviço e conformidade com LGPD no aplicativo (26:23)
5. Projetar arquitetura flexível para permitir escalabilidade futura (33:31)
6. Pesquisar sobre empresas certificadas pelo Sistema B para possível modelo de negócio (37:40)




- **Entrevista gravada:**
  
[Arquivo com gravação da entrevista](https://drive.google.com/file/d/1t-S6nX85S-O8yJ5jRY0g4vWy4syTwThJ/view?usp=drivesdk)



***2.5. Histórias do Usuário***

| ID | OBJETIVO |
|--- | -------- | 
|RF01| Como usuário, quero criar uma conta e fazer login para que eu posso acessar e utilizar os recursos do app. |
|RF02| Como usuário, quero compartilhar meu progresso nas redes sociais, para mostrar minhas conquistas e inspirar outras pessoas. |
|RF03| Como usuário, quero calcular minha pegada de carbono com base em meus hábitos diários, para que eu entenda meu impacto ambiental e saiba onde posso melhorar. |
|RF04| Como usuário, quero visualizar um ranking de pontuações de diminuição de CO₂, para que eu possa comparar meu desempenho com o de outros usuários.  |
|RF05| Como estudante, quero exportar relatórios em PDF (incluindo cálculo da pegada e resultados de quizzes), para que eu possa usar esses documentos em trabalhos escolares ou apresentações. |
|RF06| Como usuário, eu quero acompanhar meu progresso na diminuição de pegada de carbono, para que eu possa verificar o quanto eu reduzi da minha pegada de carbono.  |
|RF07| Como usuário, eu quero poder receber uma avaliação semanal da minha evolução para que eu possa avaliar minha performance durante a semana. |
|RF08| Como usuário, eu quero poder fazer quizzes sobre o impacto ambiental, para que eu possa diminuir minha pegada de carbono de forma divertida. |
|RF09| Como usuário, eu quero poder resgatar pontos de lojas parceiras, para que eu possa ter recompensas. |
|RF10| Como usuário, eu quero poder observar gráficos coloridos sobre como melhorei de mês a mês, para que possa verificar de forma intuitiva meu progresso. |
|RF11| Como usuário engajado, quero receber um selo “amigo do clima” quando adotar hábitos sustentáveis no aplicativo, para que eu possa ser reconhecido pelo meu esforço e me sentir motivado a continuar melhorando. |
|RF12| Como usuário do aplicativo, quero ver um planeta que muda de aparência conforme meus hábitos sustentáveis, para que eu possa visualizar de forma clara e divertida o impacto das minhas ações no meio ambiente.  |
|RF13| Como usuário do aplicativo, quero acessar uma tela exclusiva para visualizar minhas árvores e conquistas virtuais, para que eu acompanhe meu progresso ambiental de forma gamificada e motivadora. |
|RF14| Como usuário do app, quero poder configurar os horários e tipos de lembretes que recebo, para que as notificações estejam alinhadas com minha rotina e preferências. |


----------------------

***2.6. Diagramas de Caso de Uso e Especificações***

> ***Diagrama de Caso de Uso***
<img src="https://github.com/PlanetaPlus/Planeta-/blob/main/DiagramaDeCasoDeUso.png" alt="Diagrama de Caso de Uso">

**Especificação dos Casos de Uso:**

ID: 001

Nome do caso de uso: Interação do Usuário com o Aplicativo Planeta+

Atores: Usuário, Sistema

Visão Geral: Este caso de uso abrange as principais interações do usuário com o aplicativo Planeta+, que visa promover a conscientização ambiental por meio de quizzes, recompensas e simulações gamificadas. O sistema também atua de forma automática em algumas funcionalidades, como notificações e atualização do estado do planeta virtual.


Cenário de Sucesso Principal:
1. O usuário acessa o aplicativo Planeta+.
2. Escolhe entre realizar o cadastro ou efetuar o login.
3. O sistema valida os dados de autenticação e redireciona o usuário para a tela principal.
4. O usuário seleciona a opção Responder Quizzes.
5. O sistema carrega um conjunto de perguntas e exibe a primeira.
6. O usuário responde às perguntas e o sistema registra as respostas.
7. Ao término do quiz, o sistema calcula o desempenho e mostra o resultado.
8. Se aplicável, o sistema entrega recompensas virtuais (medalhas ou pontos).
9. O usuário, com saldo suficiente, acessa a função Plantar Árvore Virtual.
10. O sistema registra a árvore plantada e atualiza o estado do planeta.
11. O usuário acessa a tela do Planeta Virtual, que reflete suas ações (mais verde ou mais degradado).
12. Periodicamente, o sistema envia notificações ecológicas automáticas, incentivando ações sustentáveis.
13. O usuário acompanha seu progresso por meio de relatórios e telas de status dentro do app.
14. O caso de uso termina quando o usuário decide sair ou encerrar a sessão.

Extensões:
· E.1 No Passo 3, os dados de login são inválidos. → O sistema exibe mensagem de erro e solicita nova tentativa.

· E.2 No Passo 5, o quiz não carrega. → O sistema mostra um erro de conexão e sugere tentar novamente mais tarde.

· E.3 No Passo 6, o tempo para responder uma pergunta se esgota. → A resposta é registrada como em branco ou incorreta.

· E.4 No Passo 9, o usuário tenta plantar árvore sem saldo ecológico. → O sistema informa que ele deve completar desafios antes de plantar.

-----------------------

***2.7. Diagramas de Atividades***
<img src="https://github.com/PlanetaPlus/Planeta-/blob/main/Requisitos/Diagrama%20de%20Atividade.jpg" alt="Diagrama de Atividades">


***2.8. Matrizes de Rastreabilidade***
| ID Requisito | História de Usuário                 | Caso de Uso                      | Tela / Protótipo                        | Artefatos Relacionados                |
| ------------ | ----------------------------------- | -------------------------------- | --------------------------------------- | ------------------------------------- |
| RF01         | HU01 – Criar conta e login          | CU01 – Autenticar Usuário        | Tela de Login / Cadastro                | Firebase Auth, BD de Usuários         |
| RF02         | HU02 – Compartilhar progresso       | CU07 – Compartilhar Resultados   | Tela de Progresso / Compartilhamento    | API Social (ex: WhatsApp / Instagram) |
| RF03         | HU03 – Calcular pegada de carbono   | CU02 – Calcular Pegada           | Tela de Pegada de Carbono               | Algoritmo de Cálculo, BD de Hábitos   |
| RF04         | HU04 – Ver ranking de CO₂           | CU03 – Visualizar Ranking        | Tela de Ranking                         | BD de Pontuação, Sistema de Ranking   |
| RF05         | HU05 – Exportar relatórios PDF      | CU08 – Gerar Relatório           | Tela de Relatórios                      | Geração de PDF, BD de Usuário         |
| RF06         | HU06 – Acompanhar progresso pessoal | CU04 – Visualizar Progresso      | Tela da Árvore Virtual / Tela Progresso | BD de Conquistas, Árvore Virtual      |
| RF07         | HU07 – Avaliação semanal            | CU09 – Receber Avaliação Semanal | Tela de Notificações                    | Sistema de Avaliação, Cron Scheduler  |
| RF08         | HU08 – Jogar quizzes                | CU05 – Responder Quiz            | Tela de Quiz                            | Banco de Perguntas, Gamificação       |
| RF09         | HU09 – Receber recompensas          | CU06 – Ver Recompensas           | Tela de Recompensas                     | Sistema de Recompensas, BD de Itens   |



***2.9. Protótipos***

https://ninjamock.com/Designer/Workplace/204683795/Page14)

## Referências

[1] “Diretrizes Curriculares Nacionais para a Educação Ambiental”, MEC/CONAMA, Versão 2002. Localização: https://www.mma.gov.br/estruturas/educamb/_arquivos/diretrizes.pdf

[2] “Games e Educação Ambiental: Perspectivas para o Desenvolvimento Sustentável”, R. S. Dias e C. J. Ferreira, Versão 2018. Localização: https://revistas.unifacs.br/index.php/redu/article/view/4168

[3] “Pegada Ecológica”, WWF Brasil, Versão 2023. Localização: https://www.wwf.org.br/natureza_brasileira/pegada_ecologica/

[4] “FlutterFlow Docs – Build mobile apps visually”, FlutterFlow Inc., Versão 2025. Localização: https://docs.flutterflow.io/

[5] “Supabase Documentation”, Supabase, Versão 2025. Localização: https://supabase.com/docs

[6] “Educação Ambiental: princípios e práticas”, Sato, M., Versão 2003. Localização: Acervo Biblioteca Virtual em Educação MEC (http://bd.camara.leg.br)

[7] “Diretrizes para Design de Aplicativos Educacionais Gamificados”, I. H. Cruz e D. C. Barbosa, Versão 2021. Localização: https://seer.ufrgs.br/rita/article/view/117381

[8] “Gamificação e Aprendizagem: Uma Revisão Sistemática”, M. F. Souza et al., Versão 2020. Localização: https://periodicos.unb.br/index.php/rbie/article/view/32342

[9] “WCAG 2.1: Diretrizes de Acessibilidade para Conteúdo Web”, W3C, Versão 2018. Localização: https://www.w3.org/TR/WCAG21/

[10] “Google Material Design Guidelines”, Google, Versão 2025. Localização: https://m3.material.io/
