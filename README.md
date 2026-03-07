# automation-network-ansible

## Objetivo do Repositório

Este repositório contém **playbooks Ansible** voltados para automação em **Infraestrutura de Redes**.

O foco é:

- Administração de servidores Linux
- Troubleshooting automatizado
- Padronização de ambientes
- Infraestrutura de redes
- Execução remota de comandos em equipamentos

Os playbooks são desenvolvidos para uso prático em **laboratórios e ambientes corporativos**.

---

## Tipos de Automações

Este repositório inclui automações como:

- Padronização inicial de servidores Linux
- Instalação de ferramentas de diagnóstico de rede
- Configuração automatizada de gateway NAT
- Ativação de roteamento IP em servidores Linux
- Criação e persistência de regras de firewall (iptables)
- Preparação de ambiente para troubleshooting
- Execução remota de configurações de rede
- Padronização de configurações em servidores Ubuntu

Cada playbook contém **comentários detalhados no próprio código**, incluindo:

- objetivo
- cenário real de uso
- explicação das tarefas executadas

---

## Playbooks Disponíveis

Atualmente o repositório possui **2 playbooks**, incluindo:

- server-playbook.yml
- gateway_nat.yml
  
---

## Dependências

Algumas automações podem exigir:

- ansible
- acesso SSH aos dispositivos
- python3 (nos hosts gerenciados)
