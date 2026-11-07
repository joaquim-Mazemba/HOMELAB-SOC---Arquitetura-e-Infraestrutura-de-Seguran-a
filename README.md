# HOMELAB-SOC. Arquitetura e Infraestrutura-de-Segurança
Laboratório SOC virtualizado para simulação de ataques, monitorização de eventos de segurança, deteção de ameaças e resposta a incidentes utilizando Elastic Security e FortiGate.

# HOMELAB SOC – Arquitetura e Infraestrutura de Segurança

## 1. Visão Geral

Este projeto consiste na conceção e implementação de um laboratório virtualizado de cibersegurança, desenvolvido para simular uma infraestrutura empresarial segmentada.

O objetivo é criar um ambiente prático para estudar segurança de redes, monitorização de eventos, deteção de ameaças, análise de incidentes e resposta a ataques.

## 2. Arquitetura da Infraestrutura

A infraestrutura foi organizada em quatro zonas de rede, com segmentação através de redes virtuais VMware e controlo de tráfego pelo firewall FortiGate.

### Diagrama da Arquitetura

#Arquitetura do HomeLab SOC

### Zonas de Rede

| Zona | Rede | Finalidade |
| WAN / Internet | 10.10.10.0/24 | Simulação de tráfego externo |
| LAN Corporativa | 10.100.10.0/24 | Ambiente interno de utilizadores |
| DMZ | 10.185.10.0/24 | Alojamento de servidores |
| SOC – Administração e Monitorização | 10.200.10.0/24 | Monitorização e análise de segurança |

## 3. Tecnologias Utilizadas

- VMware Workstation Pro – Virtualização.
- FortiGate VM – Firewall e controlo de tráfego.
- Elastic Stack – Centralização e análise de eventos de segurança.
- Windows 10 Pro – Sistema operativo(utilizador)
- Windows Server 2022 – Serviços de servidor.
- Ubuntu Server 22.04 LTS – Servidor Linux.
- Kali Linux – Simulação controlada de ataques.
- Metasploitable 2 – Máquina vulnerável para testes de segurança.

## 4. Objetivos Técnicos

- Implementar segmentação de rede em diferentes zonas.
- Configurar políticas de segurança no FortiGate.
- Controlar a comunicação entre redes.
- Centralizar eventos de segurança no Elastic SIEM.
- Simular atividades suspeitas em ambiente controlado.
- Desenvolver competências de análise e resposta a incidentes.

## 5. Estado do Projeto

Projeto em desenvolvimento. A documentação será atualizada à medida que forem implementadas e validadas as configurações de rede, firewall, recolha de eventos e deteção de ameaças.

## 6. Evidências Técnicas

Serão adicionadas capturas de ecrã das configurações, testes de conectividade, eventos recolhidos, alertas e investigações realizadas.

Área de estudo: SOC | Blue Team | Network Security | SIEM
