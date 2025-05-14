


# Ansible Alura

Este repositório contém exemplos de automação utilizando o Ansible, com foco no aprendizado e aplicação dos conceitos adquiridos no curso da Alura.

## Descrição

O projeto contém diversas playbooks e scripts que demonstram o uso do Ansible para automação de tarefas em servidores, incluindo:

- Gerenciamento de pacotes
- Configuração de ambientes
- Implementação de infraestruturas automatizadas
- Tarefas de configuração de sistemas

## Pré-requisitos

Antes de rodar as playbooks, garanta que você tenha o Ansible instalado e configurado corretamente. Você pode instalar o Ansible usando o seguinte comando:

```bash
sudo apt update
sudo apt install ansible


## Como usar

1. Clone o repositório:

   ```bash
   git clone https://github.com/leonardodebs/ansible_alura.git
   cd ansible_alura
   ```

2. Execute uma playbook específica:

   ```bash
   ansible-playbook <nome-da-playbook>.yml
   ```

3. Personalize as variáveis de acordo com o seu ambiente, se necessário, no arquivo `vars.yml` ou diretamente nas playbooks.

## Estrutura do projeto

* `templates/` - Contém os arquivos das playbooks do Ansible.
* `vars/` - Contém os arquivos de variáveis.
* `roles/` - Contém os arquivos de roles do Ansible.

