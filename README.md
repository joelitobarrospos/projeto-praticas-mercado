# Projeto Aplicado: Práticas de Mercado

## Autor

**Joelito Barros**  
Pós-Graduação Lato Sensu em Segurança da Informação e Análise Forense - UNCISAL

---

# Descrição do Projeto

Este projeto foi desenvolvido como atividade avaliativa da disciplina **Projeto Aplicado: Práticas de Mercado**, com foco na aplicação dos conceitos de Cloud Computing, DevOps, CI/CD e Segurança da Informação.

A aplicação consiste em um sistema Web desenvolvido com Laravel contendo:

- Tela de Login
- Área restrita autenticada
- Logout funcional
- Controle de acesso por autenticação

A solução foi implantada em ambiente Cloud utilizando AWS EC2 e automatizada através de GitHub Actions.

---

# Endereços do Projeto

### Aplicação

https://joelitobarropos.duckdns.org

### Repositório GitHub

https://github.com/joelitobarrospos/projeto-praticas-mercado

---

# Tecnologias Utilizadas

## Infraestrutura

- AWS EC2
- Ubuntu Server
- Nginx
- DuckDNS
- Let's Encrypt
- Certbot

## Desenvolvimento

- PHP 8.5
- Laravel 12
- Laravel Breeze
- Blade
- Vite
- HTML5
- CSS3

## Banco de Dados

- MySQL

## DevOps

- Git
- GitHub
- GitHub Actions
- SSH

---

# Arquitetura da Solução

```text
Desenvolvedor
      │
      ▼
 GitHub Repository
      │
      ▼
 GitHub Actions
      │
      ▼
 AWS EC2 Ubuntu
      │
 ┌────┴────┐
 │         │
 ▼         ▼
Nginx    Laravel
 │
 ▼
 MySQL
