# Comandos Vagrant

#
# Comandos de Provisionamento
#

# checando a versão do vagrant
$ vagrant --version

# criar um projeto do zero
$ vagrant init

# subir o ambiente 
$ vagrant up

# subir o ambiente e definir o provider 
$ vagrant up --provider virtualbox

# destruir o ambiente
$ vagrant destroy

#
# Comandos de Operações
#

# verificando status das VMs criadas
$ vagrant status

# acessando uma VM via SSH
$ vagrant ssh {vm-name}
