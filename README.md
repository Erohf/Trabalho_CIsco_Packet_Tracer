# Trabalho Cisco Packet Tracer

Este repositório contém os arquivos e configurações relacionadas ao trabalho desenvolvido no simulador Cisco Packet Tracer. O projeto aborda a criação e configuração de redes LAN e WAN, integração de serviços de rede e testes de conectividade.

## Estrutura do Projeto

### Redes LAN

Foram configuradas duas redes locais (LAN):
- **LAN 01 (Domínio Amarelo):** 
  - Topologia em estrela.
  - Dispositivos wireless e cabeados conectados a um roteador SOHO.
  - Endereçamento: 192.168.1.0/24.

- **LAN 02 (Domínio Vermelho):** 
  - Topologia em estrela.
  - Dispositivos wireless e cabeados conectados a um roteador SOHO.
  - Endereçamento: 192.168.2.0/24.

### Rede WAN

A WAN interliga as redes locais e provê serviços adicionais:
- Servidores DNS (primário e secundário), DHCP e HTTP.
- Endereçamento: 192.168.254.0/24.

## Configurações Realizadas

1. **Endereçamento IP:**
   - Configuração de sub-redes distintas para cada rede.
   - Definição de gateways e servidores DNS.

2. **Serviços de Rede:**
   - DHCP configurado para distribuição automática de IPs.
   - Servidores DNS configurados com entradas de resolução.
   - Servidor HTTP configurado para responder a requisições web.

3. **Segurança:**
   - Redes wireless protegidas com WPA2-PSK (AES).

4. **Testes de Conectividade:**
   - Testes de ping para verificar a comunicação entre dispositivos.
   - Validação dos serviços configurados.

## Como Executar

1. Abra o Cisco Packet Tracer.
2. Importe os arquivos do projeto disponibilizados neste repositório.
3. Explore as topologias criadas para cada rede (LAN e WAN).
4. Realize seus próprios testes para entender as configurações e integrações realizadas.

## Requisitos

- Cisco Packet Tracer.
- Conhecimento básico de configurações de rede e uso do simulador.

## Autores

- **Lucas Andrade**  
- **Francisco Santana**  
- **Bruno Henrique**  
- **Estácio Gonçalves**

## Licença

Este projeto foi desenvolvido para fins acadêmicos e segue as diretrizes da disciplina de Redes de Computadores na Universidade Federal da Bahia (UFBA).
