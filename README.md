# Automatización con Ansible y Docker

Este repositorio contiene un entorno automatizado para la gestión de contenedores Docker utilizando **Ansible**. Incluye:

- **Docker Compose** para orquestar múltiples contenedores.
- **Playbook de Ansible** para la configuración y despliegue de servicios.
- **Inventario dinámico** y archivo de configuración de Ansible.

**Tecnologías:**
- Ansible
- Docker
- Docker Compose

**Uso rápido:**
1. Clona el repositorio:
   ```bash
   git clone https://github.com/FCarpio03/ansible-docker-automation.git
   cd ansible-docker-automation

Levanta los servicios:
docker-compose up -d

Ejecuta el playbook de Ansible:
ansible-playbook -i inventory.ini playbook.yml

Este proyecto es ideal para automatizar la configuración y despliegue de entornos Docker, facilitando la gestión de infraestructuras de manera eficiente y reproducible.
