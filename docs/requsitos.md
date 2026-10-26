
# Requisitos iniciais

## 1. Objetivo

Desenvolver um CRM open source e autohospedado
para pequenos negócios de serviços.

## 2. Usuários e permissões

- Administrador: gerencia o negócio, usuários e configurações.
- Funcionário: acessa as funcionalidades autorizadas.

As permissões específicas serão definidas antes
da implementação da autenticação.

## 3. Funcionalidades previstas

### Clientes
- Cadastrar, consultar, editar e excluir clientes.
- Consultar o histórico de atendimentos.
- Registrar informações de contato.

### Funcionários
- Cadastrar e gerenciar funcionários.
- Definir permissões de acesso.
- Registrar disponibilidade de horários.

### Atendimentos e retornos
- Registrar atendimentos realizados.
- Consultar a última visita do cliente.
- Organizar retornos e agendamentos.

### WhatsApp
- Disponibilizar atalhos para abrir conversas.
- Permitir mensagens com texto pré-preenchido.

### Exportação
- Exportar dados autorizados em formatos definidos
  durante o desenvolvimento.

## 4. Instalação e operação

- Utilizar Docker Compose como caminho principal.
- Documentar instalação, atualização e backup.
- Proteger credenciais e dados dos clientes.

## 5. Fora do escopo inicial

- Envio automático de mensagens pelo WhatsApp.
- Aplicativo mobile nativo.
- Integrações pagas obrigatórias.

Esses itens poderão ser reavaliados futuramente.
