# Projeto QA usando JIRA 🔍

Neste pequeno projeto, utilizo o Jira, uma ferramenta flexível para o gerenciamento de projetos. É uma ferramenta incrível da qual pude usufruir, mesmo tendo pouco conhecimento.

Optei por utilizar a metodologia Scrum com o Jira para o desenvolvimento do projeto devido às diversas vantagens que essa combinação oferece. O Scrum é uma abordagem ágil que promove a colaboração, a adaptabilidade e a entrega iterativa de resultados.

Tenho certeza de que, com o passar do tempo, irei aprimorar ainda mais os conhecimentos sobre essa ferramenta, contribuindo sempre para melhorar o desenvolvimento dos meus projetos.

## :boom: Objetivo do Projeto :boom: 

:point_right: 1. Produzir um mind-map de uma User Story escolhida por você, podendo utilizar as seguintes ferramentas: **Xmind, MindMup, Miro...**
    
 :point_right:  2.  Anexar o mind-map na User Story escolhida.
    
 :point_right: 3.  Gerar um plano de teste de acordo com o contexto do projeto.
    
:point_right: 4.  Criar casos de teste no JIRA:
    
    -   2 Casos utilizando técnica step-by-step.
    -   2 Casos utilizando BDD.
:point_right: 5.  Criar um ciclo de testes adicionando os test cases criados.
    

## :pencil2: Explicação do Projeto

:thought_balloon: Nesse projeto, utilizei o **SwagLabs** como base para desenvolver meus pensamentos técnicos e formalizar meus casos de testes. [Link do Site](https://www.saucedemo.com/v1/index.html)

Na sprint 01 **Entrada Segura**, propus uma suposta modificação na parte de Login, visando o lado do cliente e também a qualidade do software. Concluí que o cliente necessitaria de uma opção para fazer as devidas funcionalidades, tais como: Login, Cadastro e Redefinição de Senha. Essa é uma funcionalidade importante e indispensável para qualquer Software ou Página Web que necessite de contato direto com usuários.  

:warning: Os principais requisitos definidos foram:

-  **Interfaces** 
- **Dados**
- **Plataformas Ambientes**
- **Critérios de Aceite**

:warning:Desenvolvi meu mind-map usando o **Xmind** com os seguintes pontos:

### :pushpin: Cenários

-  Recuperação de Nome de Usuário
-  Autenticação de dois fatores
- Expiração da sessão de Login
-  Autenticação com biometria
-  Autenticação Social

 ### :pushpin: Cenários Principais

-  Acesso à página de Login
-  Cadastro de novo cliente
-  Login com credenciais válidas
-  Login com credenciais inválidas
- Recuperação de Senha - acesso à página de recuperação de senha
-  Recuperação de Senha - envio do e-mail de recuperação
- Acesso à página de cadastro após o Login
-  Acesso à página de login após o cadastro

### :pushpin:  Testes Adotados

- Teste de Unidade
- Teste de Integração
-  Teste de Sistema
- Teste de Aceitação
- Teste de Aceitação do Usuário (UAT)
- Teste de Regressão
- Teste de Estresse
- Teste de Segurança
- Teste de Usabilidade
- Teste de Compatibilidade
- Teste de Recuperação de Desastres

### :pushpin: Riscos Envolvidos

- Falha na conexão com o Banco de Dados
- Problemas de desempenho da página de Login
-   Exposição de Dados Sensíveis
-  Erro de validação de dados no cadastro do usuário
-   Ataques de força bruta

### :pushpin: Dados

- Nome completo
- Senha (Criptografia)
-Endereço de E-mail
- Número de Telefone

:dart: Usei dois modelos de teste como solicitado, o step-by-step e o BDD, usando a ferramenta do JIRA Zephyr Scale.

:pushpin: No primeiro caso de teste, fiz o BDD da seguinte forma:

:bomb: **Nome:** Autenticação do Usuário

:clipboard: **Objetivo:** Verificar se a funcionalidade de autenticação de usuário na loja virtual está funcionando corretamente, garantindo que os clientes e funcionários possam acessar de forma segura a plataforma. Isso inclui validar se o formulário de login é exibido corretamente, se os usuários podem realizar login com sucesso utilizando credenciais válidas, se a página de cadastro está acessível e se a opção de redefinição de senha está funcionando conforme esperado.

No segundo caso de teste, fiz o step-by-step da seguinte forma:

:bomb: **Nome:** Caso de teste Autenticação de Usuário

:clipboard: **Objetivo:** Verificar se a funcionalidade de autenticação de usuário permite que os usuários façam login de forma segura na loja virtual.

:white_check_mark: Então, seguindo esses dois casos de teste, defini um ciclo que une os mesmos e vinculei à sprint 01 **Entrada Segura**. De forma a deixar o projeto mais intuitivo e com mais situações, optei por deixar o teste BDD como aprovado e o teste step-by-step como falha, explicando o motivo e adicionando todas as informações necessárias em ambos os testes.

# :scroll: Sprint 02,


Na sprint 02, **Implementação de Filtragem de Produtos por Categoria**, percebi que faltava uma função muito importante: a de filtragem de produtos. Visando o lado do cliente quando ele acessa o site da loja, mas deseja olhar um produto específico por cores, faixa de preço, entre outros, surgiu a ideia de uma opção de filtragem.

:warning: Os principais requisitos definidos foram:

-  **Interfaces**
- **Dados**
 - **Plataformas Ambientes**
-   **Critérios de Aceite**

:warning:Desenvolvi meu mind-map usando o **Xmind** com os seguintes pontos:

### :pushpin: Cenários

-  Filtragem por nome da categoria
-  Filtragem por nome da categoria e outros critérios
- Filtragem por nome da categoria com busca
- Tempo de resposta do filtro


 ### :pushpin: Cenários Principais

-  Navegação e filtragem inicial
-  Aplicação de filtro múltiplo
-  Navegação e filtragem em dispositivos móveis 1
-    Verificação da facilidade de navegação 
-  Avaliação do desempenho e velocidade  


### :pushpin:  Testes Adotados

- Teste de precisão na filtragem
- Teste de facilidade de navegação
- Teste de resultados visíveis e relevantes
- Teste de compatibilidade com dispositivos 
- Teste de desempenho e velocidade 
- Teste de integração com banco de dados
- Teste de Integração com API de busca ou consulta
- Teste de erro



### :pushpin: Riscos Envolvidos

- Risco de performance lenta
- Risco de falha na integração com o banco de dados
- Risco de erro na API de busca ou consulta
- Risco de incompatibilidade com dispositivos 
- Risco de usabilidade pobre
- Risco de falha na navegação
- Risco de erros de segurança 
- Risco de erros de integração Front-End e Back-End
- Risco de falha na exibição dos resultados
- Risco de sobrecarga do sistema  

:dart: Usei dois modelos de teste como solicitado, o step-by-step e o BDD, usando a ferramenta do JIRA Zephyr Scale.


:pushpin:O primeiro caso de teste, fiz o step-by-step da seguinte forma:

:bomb: **Nome:**  Teste de Filtragem de Produtos por Categoria

:clipboard: **Objetivo:** Verificar se a funcionalidade de filtragem de produtos por categoria na loja virtual está funcionando corretamente, garantindo que os usuários possam encontrar rapidamente os produtos desejados e que os resultados sejam exibidos de forma clara e organizada, com tempo de resposta adequado e compatibilidade em diferentes dispositivos.

:pushpin: O segundo caso de teste, fiz o BDD da seguinte forma:

:bomb: **Nome:** Teste de Filtragem de Produtos por Categoria na Loja Online

:clipboard: **Objetivo:** Verificar se a funcionalidade de filtragem de produtos por categoria na loja online está operando conforme esperado, permitindo que os usuários selecionem categorias específicas, apliquem os filtros corretamente e visualizem os resultados de acordo com as categorias selecionadas. Além disso, garantir que a funcionalidade seja responsiva em diferentes dispositivos e que os resultados sejam exibidos dentro do tempo esperado.

:white_check_mark: Então, seguindo esses dois casos de teste, defini um ciclo que une os mesmos e vinculei à sprint 02 **Implementação de Filtragem de Produtos por Categoria**. De forma a deixar o projeto mais intuitivo e com mais situações, optei por deixar o teste BDD como aprovado e o teste step-by-step como falha, explicando o motivo e adicionando todas as informações necessárias em ambos os testes.
