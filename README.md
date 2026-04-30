# 🚀 automation-network-ansible

## 🎯 Objetivo

Repositório de automação com **Ansible** voltado para **infraestrutura Linux, administração de sistemas e operações**, com foco em **provisionamento, padronização e deploy de serviços**.

Os playbooks foram desenvolvidos para automatizar cenários reais de:

- Provisionamento e configuração de servidores Linux  
- Administração de infraestrutura e serviços  
- Monitoramento de infraestrutura  
- Auditoria e troubleshooting  
- Deploy automatizado de serviços  

---

## 🔥 Casos de Uso

Os playbooks simulam atividades comuns em ambientes de:

- Infraestrutura Linux  
- Administração de sistemas  
- NOC (Network Operations Center)  
- Operações de rede  
- Automação de ambientes (Infra as Code)  

---

## 🛠️ Tipos de Automação

- Padronização inicial de servidores Linux  
- Instalação automatizada de ferramentas  
- Configuração de gateway NAT (roteamento e NAT)  
- Gerenciamento de firewall com iptables  
- Auditoria de sistema e rede  
- Deploy de monitoramento com Docker  
- Execução remota de tarefas administrativas  

Todos os playbooks incluem:
- cenários reais de uso  
- comentários explicativos  
- organização modular  

---

## 📂 Playbooks

### 🖥️ server-linux.yml
Provisionamento inicial de servidores Linux com instalação de ferramentas e configuração básica

### 🌐 gateway_nat.yml
Configuração de servidor como **Gateway NAT**, com IP Forward e regras persistentes

### 🔍 auditoria_rede.yml
Auditoria de sistema e rede com coleta de interfaces, rotas, portas e conectividade

### 📊 netdata_docker.yml
Deploy automatizado de monitoramento com **Netdata via Docker**

---

## 🗂️ Estrutura
```
automation-network-ansible/
├── diagnostics/
│   └── auditoria_rede.yml
├── monitoring/
│   └── netdata_docker.yml
├── network-config/
│   └── gateway_nat.yml
├── server-management/
│   └── server-linux.yml
├── NOTA.md
└── README.md
```
---

## 🚀 Diferencial

- Automação de infraestrutura com Ansible (Infra as Code)  
- Administração e provisionamento de servidores Linux  
- Deploy automatizado de serviços  
- Organização modular de playbooks  
- Foco em cenários reais de ambiente corporativo    
