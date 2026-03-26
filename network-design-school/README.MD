# Network Design – School Infrastructure

## Descripción

Diseño e implementación de una red segmentada para una institución educativa utilizando VLANs y subnetting.

## Objetivo

Optimizar la comunicación interna y mejorar la seguridad mediante segmentación de red.

## Arquitectura

Se implementaron múltiples VLANs para separar áreas:

- VLAN 10 → Secretaría
- VLAN 20 → Dirección
- VLAN 30 → Preceptoras
- VLAN 40 → Informática 1
- VLAN 50 → Informática 2

## Diseño de red

Cada VLAN cuenta con su propia subred:

| VLAN | Red              | Hosts |
|------|-----------------|-------|
| 10   | 192.168.10.0/28 | 14    |
| 20   | 192.168.20.0/29 | 6     |
| 30   | 192.168.30.0/27 | 30    |
| 40   | 192.168.40.0/27 | 30    |
| 50   | 192.168.50.0/27 | 30    |

## Implementación

- Router-on-a-stick
- Switches en modo trunk
- Asignación manual de IPs
- Segmentación por áreas

## Tecnologías

- Cisco Packet Tracer
- VLANs
- Routing

## Resultado

Red funcional con comunicación entre VLANs y segmentación segura del tráfico.

![Ping entre VLANs](imagenes/numero 1.png)
![Funcionando](imagenes/numero 21.png)