# Requisitos.
### 1. Tener Kubuntu Desktop 20.04 actualizado.
Para actualizar Kubuntu Desktop se puede ejcutar lo siguiente desde el terminal:
```
sudo apt update
sudo apt upgrade -y
sudo apt dist-upgrade -y
```
### 2. Tener Ansible instalado.
```
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```
### 3. Instalar los módulos de la comunidad.
```
sudo ansible-galaxy collection install community.general
```

# Instrucciones.
Clonar el repositorio y ejecutar el playbook `install_software.yml` con `sudo`.
```
sudo ansible-playbook install_software.yml
```