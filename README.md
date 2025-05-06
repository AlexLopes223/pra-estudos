Projeto: Cadastro de Clientes 
Tipo de Arquitetura: Monolitica
----
[ Interface (componentes visuais) ]
                ↓
[ Lógica de Negocio (Funçôes/Estados) ]
                ↓
[ Acesso a Dados (LocalStorage, ou API locais/simulados) ]
----

Interface: JSX visivel ao usuário.
lógica de Negócio: validaçôes, manipulação de dados, regras.
Acesso aos Dados: estados (useState(() ou comunicçôes com serviços API.
