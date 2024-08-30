## JOILLE README

## 1. [Introdução](#introdução)
Introdução as funcionalidades do projeto Joille baseado na estrutura MVC.
Um projeto SaaS com o intuito de oferecer um servilo de assinatura para empresas do ramo de joalheria.
## 2. [Autenticação](#autenticação)
Processos de autenticação realizados a partir de tokens de autenticação da entrada de ususarios normais e administradores, 
assim como a autenticação para navegar em rotas pré-definidas
## 3. [Rotas da API](#rotas-da-api)
   A API conta com 10 rotas em sua versão atual, contendo GET,POST,DELETE e PUT para realizar requisições ao banco de dados,
   Entre essa funções temos:
   Inserção de dados ao banco de dados por metodo insert.
   Remoção de dados por metodo delete.
   listagem de dados por metodo get, em listagem normal e listagem por id.
   as entidades que tomam parte nessas requisições são respectivamente:Services(Entidades que controla os serviços disponibilizados) e Categories(Entidade que controla as categorias)
   ## 4. [Códigos de Status HTTP](#códigos-de-status-http)
   401 Unauthorized: A autenticação é necessária e falhou ou não foi fornecida.
   403 Forbidden: O servidor entendeu a solicitação, mas se recusa a autorizá-la.
   404 Not Found: O recurso solicitado não foi encontrado.