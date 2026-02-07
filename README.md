📦 EstoqueApp — Sistema de Controle de Estoque (C# WinForms + SQLite)

Sistema desktop de controle de estoque desenvolvido em C# (.NET) com Windows Forms, voltado para pequenas empresas. Permite gerenciar produtos com cadastro, edição, controle de status, histórico de entregas e persistência local de dados usando SQLite.

Projeto criado com foco em Programação Orientada a Objetos, CRUD completo, interface gráfica e armazenamento persistente.

🚀 Funcionalidades

✅ Cadastro de produtos

✅ Edição de nome, preço e quantidade

✅ Controle de status de entrega

✅ Marcar produto como entregue (move para histórico)

✅ Histórico de produtos entregues

✅ Busca por nome

✅ Filtro por status

✅ Duplo clique para editar

✅ Grid com layout profissional

✅ Contador de total de itens em estoque

✅ Persistência de dados com SQLite

✅ Backup automático em JSON

✅ Importação e exportação de backup

🧱 Tecnologias Utilizadas

C#

.NET 9

Windows Forms (WinForms)

SQLite (Microsoft.Data.Sqlite)

Programação Orientada a Objetos (POO)

CRUD

JSON (backup de segurança)

🖥️ Interface

O sistema possui interface gráfica desktop com:

Tabela de produtos

Botões de ação (Cadastrar, Editar, Entregar, Histórico)

Campo de busca

Filtro por status

Alteração de status via ComboBox

Rodapé com total de itens

💾 Persistência de Dados

Os dados são salvos automaticamente em:

📂 Banco SQLite local

AppData/Local/EstoqueApp/estoque.db


📂 Backup JSON

AppData/Local/EstoqueApp/dados.json


Isso garante que os dados não sejam perdidos ao fechar o programa.


📚 Conceitos Aplicados

Arquitetura em camadas (Domain / Application / WinForms)

Encapsulamento

Separação de responsabilidades

Serviços de domínio

Persistência com banco local

Tratamento de erros

Interface desktop orientada a eventos

🎯 Objetivo do Projeto

Demonstrar na prática:

Desenvolvimento de aplicação desktop

Integração com banco de dados

Modelagem orientada a objetos

Construção de CRUD completo

Criação de sistema utilizável por empresa pequena

👨‍💻 Autor

Desenvolvido como projeto de portfólio para evolução como desenvolvedor C# / .NET.
