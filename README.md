# 🐧 Linux Admin Labs

Laboratórios voltados à **administração de sistemas Linux**, com foco em automações, segurança, scripts shell e gerenciamento de servidores para ambientes reais.

---

## 💡 Objetivo

Desenvolver habilidades práticas em:

- Administração de servidores Linux (Debian/Ubuntu)
- Hardening de sistemas
- Backup e restauração
- Criação de scripts Shell para automação
- Monitoramento e gerenciamento de usuários e serviços

---

## 🚀 Projetos disponíveis

| Projeto | Descrição | Tecnologias |
|---------|-----------|-------------|
| Hardening automatizado | Script que aplica boas práticas de segurança em sistemas Linux | Bash, UFW, Fail2ban |
| Gerenciador de backups | Script para backup automático e incremental | Bash, Cron, rsync |
| Provisionamento com Ansible | Automação de setup de servidores | Ansible, SSH |
| Monitoramento básico | Coleta de logs e uso de recursos | Bash, journalctl, top, htop |

---

## 🧰 Stack utilizada

- Distribuições: Ubuntu Server, Debian  
- Bash Script  
- Cron, rsync, UFW, Fail2ban  
- Ansible  
- Visual Studio Code + WSL ou máquinas virtuais com VirtualBox/Proxmox

---

## 🗂️ Estrutura do projeto

```bash
📁 linux-admin-labs/
├── hardening-script/
│   ├── harden.sh
├── backup-manager/
│   ├── backup.sh
│   ├── restore.sh
├── ansible-provisioning/
│   ├── playbook.yml
│   ├── inventory
├── monitoring-tools/
│   ├── usage_monitor.sh
│   ├── log_collector.sh
```

---

## 🧠 Como rodar localmente

Clone o repositório:

```bash
git clone https://github.com/AndreGoncallez/linux-admin-labs.git
cd linux-admin-labs/hardening-script
```

Dê permissão e execute o script:

```bash
chmod +x harden.sh
sudo ./harden.sh
```

Para testar o backup:

```bash
cd ../backup-manager
./backup.sh
```

---

## 🧪 Em breve

- Integração com Zabbix para monitoramento gráfico
- Playbook Ansible com Apache + Firewall
- Logs centralizados com Rsyslog + Logrotate
- Containerização de serviços com Podman
