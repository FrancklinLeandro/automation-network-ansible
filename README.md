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

## Playbooks
### server-linux.yml
Playbook Ansible para **padronização inicial de servidores Linux**, realizando atualização do sistema, instalação de **ferramentas essenciais de diagnóstico de rede** e garantindo que o **serviço SSH esteja ativo**, além de preparar um diretório para logs de rede.

**Uso:**

```bash
ansible-playbook -i hosts.ini server-linux.yml -k -K
```

### gateway_nat.yml
Playbook Ansible para **configurar um servidor Ubuntu como Gateway NAT**, permitindo que uma rede interna acesse a internet através de uma interface WAN, com **IP Forward habilitado e regras de NAT persistentes via iptables**.

**Uso:**

```bash
ansible-playbook -i hosts.ini gateway_nat.yml -k -K
```

## Estrutura do Repositório
```
automation-network-ansible/
├── network-config/
│   └── gateway_nat.yml
├── server-management/
│   └── server-linux.yml
└── README.md
```
