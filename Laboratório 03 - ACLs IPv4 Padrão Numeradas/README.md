# Laboratório 03 – Configuração de ACLs IPv4 Padrão Numeradas

## Sobre o laboratório

Neste laboratório, desenvolvido no **Cisco Packet Tracer**, foi realizada a configuração de ACLs (Access Control Lists) IPv4 padrão numeradas, com o objetivo de controlar o tráfego de rede com base nos endereços IP de origem.

A atividade envolveu a criação de regras para bloquear a comunicação entre determinadas redes, mantendo a permissão para os demais tráfegos.

## Objetivos

- Compreender o funcionamento das ACLs IPv4 padrão;
- Criar ACLs padrão numeradas em roteadores;
- Configurar regras de permissão e bloqueio de tráfego;
- Aplicar as ACLs nas interfaces dos roteadores;
- Verificar o funcionamento das regras por meio de testes de conectividade.

## Configurações realizadas

Durante a atividade, foram configuradas ACLs nos roteadores R2 e R3.

As regras implementadas foram:

- Bloqueio do tráfego originado na rede `192.168.11.0/24` com destino à rede `192.168.20.0/24`;
- Permissão dos demais tráfegos;
- Bloqueio do tráfego originado na rede `192.168.10.0/24` com destino à rede `192.168.30.0/24`;
- Permissão dos demais tráfegos.

As listas foram aplicadas às interfaces dos roteadores utilizando o comando `ip access-group`.

## Configuração da ACL

Abaixo, registro da configuração das ACLs padrão numeradas realizada nos roteadores durante a atividade.

![Configuração das ACLs IPv4 padrão numeradas](imagens/configuracao-acl.png)

## Verificação e testes

Após a configuração, foram utilizados comandos para verificar as ACLs e sua aplicação nas interfaces, além de testes de conectividade com o comando `ping`.

Os testes permitiram observar quais comunicações eram autorizadas e quais eram bloqueadas de acordo com as regras estabelecidas.

![Testes de conectividade](imagens/testes-conectividade.png)

## Tecnologias e conceitos

- Cisco Packet Tracer
- IPv4
- ACLs padrão numeradas
- Roteamento
- Controle de tráfego de rede
- Segurança de redes

## Aprendizados

A prática contribuiu para compreender como as ACLs padrão podem ser utilizadas para implementar políticas de controle de acesso em uma rede, restringindo comunicações com base nos endereços IP de origem.

**Ferramenta utilizada:** Cisco Packet Tracer.
