# trabalho-final-mobile
Relatório do Trabalho final da disciplina de Programação para dispositivos móveis

> 0. Integrantes do grupo

Aluno: Matheus Biesdorf (2020.1904.050-3)

> 1. Visão Geral do Software 

O aplicativo desenvolvido tem como objetivo gerenciar usuários e produtos, especificamente celulares. Ele oferece funcionalidades de registro, edição e exclusão de dados para administradores, bem como busca e filtragem de produtos para clientes. A interface do usuário é simples e intuitiva, facilitando a navegação e a realização das tarefas.

1.1 Papéis e Usuários

1.1.1 Administrador:
Gerenciar contas de usuários (registrar, editar e excluir pessoas).
Gerenciar produtos (registrar, editar e excluir celulares).
Acessar listas completas de usuários e produtos.

1.1.2 Cliente:
Buscar e filtrar celulares de acordo com suas preferências.
Visualizar informações detalhadas dos celulares.

> 2. Requisitos funcionais

2.1 Usuários Permitidos e funcionalidades por usuário:

2.1.1 Administrador:
Registrar nova pessoa com nome, e-mail, telefone, senha e permissão (Administrador ou Cliente).
Registrar novo celular com modelo, marca, armazenamento interno, memória RAM, sistema operacional, processador, tipo de tela, resolução de tela, tamanho da tela, capacidade da bateria e valor.
Editar informações de pessoas e celulares existentes.
Excluir pessoas e celulares.
Visualizar listas de todas as pessoas e celulares cadastrados.

2.1.2 Cliente
Buscar celulares aplicando filtros de marca, armazenamento interno, memória RAM e faixa de preço.
Visualizar informações detalhadas dos celulares filtrados.

2.2 Entradas Necessárias

2.2.1 Para cadastro de usuários
Nome, e-mail, telefone, senha, permissão.

2.2.2 Para cadastro de celulares
Modelo, marca, armazenamento interno, memória RAM, sistema operacional, processador, tipo de tela, resolução de tela, tamanho da tela, capacidade da bateria, valor.

2.2.3 Para login
E-mail, senha.

2.2.4 Para filtros de busca
Marcas, capacidade de armazenamento, memória RAM, faixa de preço.

2.3 Processamento Realizado

Verificação de credenciais de login.
Armazenamento de novos registros de usuários e celulares.
Atualização de dados existentes.
Filtragem de celulares de acordo com as preferências dos clientes.
Exclusão de registros de usuários e celulares.

2.4 Relatórios e Saídas:

2.4.1 Para administradores
Listas de usuários com ID, nome, telefone, e-mail e permissão.
Listas de celulares com ID, modelo, marca, armazenamento interno, memória RAM, sistema operacional, processador, tipo de tela, resolução de tela, tamanho da tela e capacidade da bateria.

2.4.2 Para clientes
Lista de celulares filtrados contendo imagem do celular, modelo, marca, armazenamento interno, memória RAM, sistema operacional, processador, tipo de tela, resolução de tela, tamanho da tela e capacidade da bateria.





