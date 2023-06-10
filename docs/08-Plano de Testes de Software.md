# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Apresente os cenários de testes utilizados na realização dos testes da sua aplicação. Escolha cenários de testes que demonstrem os requisitos sendo satisfeitos.

Enumere quais cenários de testes foram selecionados para teste. Neste tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo de usuários que foi escolhido para participar do teste e as ferramentas utilizadas.
 
## Ferramentas de Testes (Opcional)

Comente sobre as ferramentas de testes utilizadas.
 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)
> - [Criação e Geração de Planos de Teste de Software](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

8. Plano de Teste de Software
Requisitos para testes de software:
•	A aplicação deve possuir um tópico de dicas de como montar um CV.
•	A aplicação deve possuir layouts predefinidos e a opção de personalizar.
•	A aplicação deve ter página de fácil navegação, para facilitar correções, caso seja necessário.

Os testes funcionais a serem praticados no site são descritos a seguir.

Caso de Teste: CT-01 - Montagem de CV

Requisitos associados:  
RF-03: A aplicação deve possuir um tópico de dicas de como montar um CV.
RF-06: A aplicação deve possuir layouts predefinidos e a opção de personalizar.

Objetivo de teste:
Conferir o acesso e a qualidade das informações disponibilizadas para a montagem de um CV.

Passos: 	 
1)	Acessar Home-Page.
2)	Acessar a opção dicas na tela inicial e localizar a opção dicas e selecionar.
3)	Acessar a opção layouts e selecionar a opção que mais se identifica com o usuário.
Critério de êxito:
•	Ao acessar a página inicial você deve ser direcionado para a página de dicas para a leitura de informações essenciais para a construção do seu CV.
•	Ao selecionar a opção de templates deve ser disponibilizados exemplos para o preenchimento dos seus dados.


Caso de teste: CT-02 – Navegabilidade* (ver uma palavra melhor, se necessário)
Requisitos Associados: RF-07 - A aplicação deve ter páginas de fácil navegação, para facilitar correções, caso seja necessário.
Objetivo do Teste: Pensado especialmente para pessoas que enfrentam dificuldades ao lidar com tarefas ou aplicações online.
Passos:
1)	Acessar Home-Page.
2)	Selecionar abas Site e Dicas
3)	Inserir dados.
4)	Finalizar o CV.

Critérios de Êxito:
•	Facilidade de navegação, voltar e avançar em qualquer aba sem a necessidade de voltar nas que foram acessadas.
•	A aba 'Dicas' é uma ferramenta útil que oferece orientações claras e práticas para auxiliar na criação de um currículo
