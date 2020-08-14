#Instalacao e configuracao do Virtualbox e Vagrant 

1 - Voce deverá de ter a versao 6.1  instalada

2 - Baixar o vagrant direto do site, não usar o do repositorio debian, pois ainda nao funciona na versao do 
virtualbox 6.1.
ps: Não testei com ubuntu, o meu debian é o 10.5. dia 13/08/2020

3 - Executar a seguinte:
```ssh
$vagrant up

```



## Detelhes dessa configuracão.

1 Maquina Firewall
* interfaces de redes(1 para comunicacao entre as vms e outra para    acesso a internet.)

1 Maquina database 
* Placa rede para acesso interno do servidores



## Acesso as maquinas virtuais.
### Nessa configuração estou dando o nome de db e firewall.

- Acessando o db
```
$vagrant ssh db
```
- Acessando o firewall
```
$vagrant ssh db
```

## Observacoes gerais. 
- Isso é um simples exemplo de como montar duas maquinas virutais de maneira automatica pelo Vagrant no Virtualbox.

