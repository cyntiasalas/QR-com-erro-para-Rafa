Descrição do Projeto
Este projeto é um sistema bancário simples que permite aos usuários realizar operações financeiras, como depósitos, saques e consultas de extrato. 
A aplicação é projetada com uma arquitetura hexagonal, estimulando boas práticas de engenharia de software e facilitando a manutenção e a extensão do sistema.
_______________________________________________________________________________________________________________________________________________________________________________________________________________


Objetivos
Proporcionar uma interface simples para operações bancárias básicas.
Permitir que os usuários gerenciem seu saldo de forma intuitiva.
Utilizar uma arquitetura modular e testável para facilitar futuras expansões e manutenções.

_____________________________________________________________________________________________________________________________________________________________________________________________________________
Arquitetura do Sistema
O sistema é organizado de acordo com os princípios da Arquitetura Hexagonal (ou Ports and Adapters), que divide a aplicação em diferentes camadas:
Domínio : Contém a lógica de negócios da aplicação.
Aplicação : Facilita a interação do usuário com a lógica de negócios, orquestrando a execução das operações.
Interface de Usuário : Onde o usuário interage com a aplicação, exibindo o menu e as opções.
Persistência : Onde os dados são armazenados e recuperados (simulado no código com variáveis em memória).

_____________________________________________________________________________________________________________________________________________________________________________________________________________
Tecnologias Utilizadas
Python : Linguagem de programação principal.
Terminal/Console : Interface de usuário (sem uso de frontend web no momento).

_____________________________________________________________________________________________________________________________________________________________________________________________________________
Estrutura do Projeto
bash
Copy code
/project-root
│
├── main.py            ## Código principal da aplicação
└── README.md          ## Este arquivo de documentação

_____________________________________________________________________________________________________________________________________________________________________________________________________________

Funcionalidades
- Depositar : Permite ao usuário adicionar um valor ao saldo.
- Sacar : Permite ao usuário retirar um valor do saldo, respeitando limites definidos.
- Extrato : Exibe um resumo das operações realizadas e do saldo atual.
- Sair : Encerra a aplicação.

_____________________________________________________________________________________________________________________________________________________________________________________________________________
Contribuição
Contribuições são bem-vindas! Para contribuir com este projeto, siga os passos abaixo:

Faça um fork do repositório.
Crie uma nova branch para suas alterações.
bash
Copy code
git checkout -b feature/nova-funcionalidade
Realize suas alterações e faça um commit.
bash
Copy code
git commit -m "Adiciona nova funcionalidade"
Envie suas alterações.
bash
Copy code
git push origin feature/nova-funcionalidade
Abra um Pull Request.

_____________________________________________________________________________________________________________________________________________________________________________________________________________
Licença
Este projeto está licenciado sob a MIT License . Consulte o arquivo LICENSE para mais detalhes.




