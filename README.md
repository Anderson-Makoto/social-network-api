# Descrição
Projeto de system design do caso de uma rede social

# 1 - Levantamento de requisitos

## 1.1 - Requisitos funcionais

### 1.1.1 - Gerenciar usuário
- O usuário deve se cadastrar no sistem com seu nome, email, senha, e nickname
- O usuário deve conseguir editar seus dados de nome, email, senha, localização, e nickname
- O usuário deve ter a possibilidade de excluir seu perfil

### 1.1.2 - Feed
- O usuário deve conseguir ver o feed de postagens, sendo somente de usuários que ele segue, em ordem cronológica de postagem
- O usuário deve ter a possibilidade de ver o perfil de outro usuário, neste caso, ele irá ver o feed somente das postagens deste usuário

### 1.1.3 - Compartilhamento
- O usuário deve ter a possibilidade de compartilhar a postagem de outros usuários, neste caso, a postagem compartilhada estará no feed do usuário que compartilhou

### 1.1.4 - Seguir
- O usuário pode seguir vários outros usuários, pesquisando pelo nome

### 1.1.5 - Posts
- O usuário pode postar um texto, com uma imagem, ou um vídeo
- O usuário pode excluir um post

### 1.1.6 - Gerenciamento de interação com posts
- O usuário pode dar um like em um post

### 1.1.7 - Pesquisar usuários
- O usuário pode pesquisar pelo nickname de outros usuários, e selcionar o perfil

## 1.2 - Requisitos não funcionais

### 1.2.1 - Desempenho
- As páginas não devem demorar mais que 5 segundos para carregar com conexão à internet média

### 1.2.2 - Escalabilidade
- O sistema deve suportar até 1 milhão de usuário simultâneos, com possibilidade de aumentar

## 1.2.3 - Segurança
- Os dados de senha do usuário devem ser criptografados
- O sistem deve impedir compartilhamento de dados do usuário de acordo com a LGPD e conteúdos proibidos ou sensíveis

## 1.2.4 - Disponibilidade
- O serviço deve estar disponível 99.9%

# 2 - Estimativa de capacidade
Assumindo algumas metricas, temos:
- Por se tratar de uma rede social, podemos levar em conta que os usuário vão ver postagens muito mais que realizar postagens, em média 200:1 (postagens vistas/postagens feitas)
- Postagens feitas por dia em média: 1.5 milhão
- Postagens vistas por dia em média: 1.5 milhão * 200 = 300 milhões
- 

## 2.1 - Requisitos de throughput
- 

## 2.2 - Estimativa de storage
## 2.3 - Estimativa de banda
## 2.4 - Estimativa de cache
## 2.5 - Estimativa de infra

# 3 - High-level design

# 4 - Database design
## 4.1 - Tipo de banco

# 5 - API design

# 6 - Aprofundando em conceitos chave

# 7 - Problemas chave e bottlenecks
## 7.1 - Escalabilidade
## 7.2 - Disponibilidade
## 7.3 - Integridade
## 7.4 - Segurança
