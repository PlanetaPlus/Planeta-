
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Link do Padlet: https://padlet.com/marianagp294/requisitos-de-software-planeta-2lc5dzeb944hrf6r

## 1. Introdução

***1.1.  Camille, Júlia, Mariana e Maurício***

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


[Requisitos/Persona_usuário.jpg
Requisitos/Persona_antiUsuario.jpg](https://github.com/PlanetaPlus/Planeta-/tree/ea2831072f0cfedeaed2076bb452d5b7a4a8f1ad/Requisitos)

Link de visualização:
https://www.canva.com/design/DAGmoQCb_dg/W44EIjLkdV5gtUJZcJ-gLA/edit?utm_content=DAGmoQCb_dg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

***Análise da situação atual: antes da introdução de sua solução***

1 O que as pessoas fazem? Não têm o costume de se preocuparem com os danos que causam ao meio-ambiente. 

2 Quais os artefatos envolvidos? Não são utilizados artefatos.

3 O que elas precisam saber? Que devem ser usados mecanismos para controlar nossos danos ao meio-ambiente.



***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***
1 O que as pessoas fazem? Preocupam-se com os danos que causam ao meio-ambiente.


2 Quais os artefatos envolvidos? 
-Aplicativo mobile Planeta+
-Quizzes e jogos interativos
-Sistema de recompensas (como medalhas, conquistas virtuais, árvore virtual etc.)
-Relatórios de progresso do usuário
-Notificações e lembretes ecológicos
-Recursos visuais e gamificados para educação ambiental


3 O que elas precisam saber? Que devem continuar usando plataformas como a Planeta+ para serem conscientes sobre suas ações.


***Cenário: Antes***

Antes da aplicação do sistema Planeta+, a maioria das pessoas, especialmente crianças e jovens, não possui o hábito de refletir sobre os impactos ambientais de suas ações diárias. O tema da sustentabilidade é frequentemente percebido como distante ou irrelevante, e os conteúdos educativos sobre o assunto são pouco atrativos ou acessíveis. Os usuários não utilizam ferramentas ou aplicativos que incentivem a mudança de comportamento ambiental, o que contribui para a manutenção de hábitos poluentes e pouco sustentáveis no cotidiano.

***Cenário: Depois***

Após a implementação do sistema Planeta+, os usuários passam a interagir com um aplicativo envolvente e educativo que os estimula a refletir e agir de forma mais consciente em relação ao meio ambiente. Por meio de quizzes, desafios e recompensas virtuais, eles aprendem conceitos importantes de sustentabilidade e são incentivados a adotar hábitos mais ecológicos, como economizar água, reduzir o uso de plástico e plantar árvores virtuais (com incentivo para ações reais). O aplicativo se torna um aliado no processo de conscientização ambiental, promovendo mudanças positivas de comportamento de forma lúdica e acessível.

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

[(https://github.com/PlanetaPlus/Planeta-/blob/bd49b3b31ae5dffe47099905447b66cd3b7b42f6/REQUISITOS%20FUNCIONAIS.png)](https://docs.google.com/spreadsheets/d/1Du95BnGc2OFL156DzZyPDY-ckGwqj1C-JvwXgmwB0TQ/edit?gid=0#gid=0)

***2.2. Requisitos Não Funcionais***
[
(https://github.com/PlanetaPlus/Planeta-/blob/bd49b3b31ae5dffe47099905447b66cd3b7b42f6/REQUISITOS%20NAO%20FUNCIONAIS.png)](https://docs.google.com/spreadsheets/d/1Du95BnGc2OFL156DzZyPDY-ckGwqj1C-JvwXgmwB0TQ/edit?gid=2116779670#gid=2116779670)

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

Link do relatorio da entrevista: https://docs.google.com/document/d/1Tw5XRnbTb_OfrOyhIM2K6PDbE4Kc7J0-x5EuW6OCw0s/edit?tab=t.0#heading=h.36razy1tyhc8


Link da entrevista gravada: https://drive.google.com/file/d/1t-S6nX85S-O8yJ5jRY0g4vWy4syTwThJ/view?usp=drivesdk


***2.5. Histórias do Usuário***
https://docs.google.com/document/d/1qBNQfn0DROuD8HnEY6sMnPDoZCfbK-cOM_jJlqpf2W4/edit?tab=t.0

***2.6. Diagramas de Caso de Uso e Especificações***
https://github.com/PlanetaPlus/Planeta-/blob/main/DiagramaDeCasoDeUso.png

Especificação dos Casos de Uso: 

https://1drv.ms/w/c/f5d7142c7b2a3228/EahW5mEswX1Ki50JcFF40KIBTlPeZXphGAp-4_WPnD-PWw?e=2EMJgc


(https://github.com/PlanetaPlus/Planeta-/blob/main/DiagramaDeCasoDeUso.mdj)

***2.7. Diagramas de Atividades***

(https://github.com/PlanetaPlus/Planeta-/blob/main/DiagramaDeAtividade_Requisitos.png)

***2.8. Matrizes de Rastreabilidade***

*<Imagem, arquivo (PDF), link com Matriz de Rastreabilidade.>*

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
