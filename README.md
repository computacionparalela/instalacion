# Playbook para Ansible

Instala suites de compiladores C y C++, profilers y herramientas
útiles para cursar Computación Paralela.

### Requerimientos

- Debian o Ubuntu
- Ansible (`sudo apt install ansible`)

### Ejecución

1. (Opcional) Si no tiene espacio para instalar Intel oneAPI HPCKit completo (32GB), apagar la variable `instalar_oneapi` en el playbook.
2. Correr el playbook con `sudo ansible-playbook -i ./inventory computacion_paralela.yml` y esperar a que termine.
