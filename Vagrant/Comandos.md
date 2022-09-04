## Comandos Vagrant

### Comandos de Provisionamento

#### checando a versão do vagrant
```console
$ vagrant --version
```


#### criar um projeto do zero
```console
$ vagrant init
```

#### subir o ambiente
```console
$ vagrant up
```

##### subir o ambiente e definir o provider
```console
$ vagrant up --provider virtualbox
```

##### destruir o ambiente
```console
$ vagrant destroy
```

### Comandos de Operações

#### verificando status das VMs criadas
```console
$ vagrant status
```

#### acessando uma VM via SSH
```console
$ vagrant ssh {vm-name}
```