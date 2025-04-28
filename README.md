# 🛒 E-Commerce System

## Este projeto é um sistema de loja virtual desenvolvido em Python que roda no terminal. Ele permite:
- Cadastrar usuários
- Fazer login
- Comprar produtos
- Gerenciar um carrinho de compras
- Administrar produtos (para usuários administradores)

## 📋 Funcionalidades
### Para Usuários Comuns:
- Cadastro de novo usuário
- Login com usuário e senha
- Visualizar lista de produtos disponíveis
- Comprar um produto diretamente
- Adicionar produtos ao carrinho
- Visualizar, remover ou comprar itens do carrinho

### Para Administradores:
- Login com usuário e senha pré-cadastrados
- Adicionar novos produtos
- Editar produtos existentes
- Remover produtos do catálogo

### Os administradores cadastrados inicialmente no sistema são:
- Usuário: admin | Senha: admin123
- Usuário: gestor | Senha: gestor123

## 🎯 Estrutura do Código
- admins: Lista com dados de administradores.
- products: Lista inicial de produtos disponíveis para compra.
- cart: Carrinho de compras do usuário logado.

### Funções principais:
- show_products(): Exibe todos os produtos.
- buy_or_add_to_cart(): Permite comprar ou adicionar um produto ao carrinho.
- view_cart(): Exibe e gerencia o carrinho de compras.
- admin_menu(): Área administrativa para gerenciar os produtos.

## ⚡ Tecnologias Utilizadas
- Linguagem: Python 3
- Ambiente: Console/Terminal

## ✍️ Observações
- Os dados de usuários comuns (cadastrados via programa) não são persistidos após o encerramento do sistema (não há banco de dados ou arquivo de armazenamento).
- O login diferencia usuários comuns de administradores para permitir acesso especial ao menu de administração.
