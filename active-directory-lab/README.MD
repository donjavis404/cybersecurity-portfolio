# Active Directory Lab – Domain Controller

## Descripción

Implementación de un entorno empresarial basado en Active Directory para la gestión de usuarios, políticas y seguridad.

## Objetivo

Centralizar la administración y aplicar controles de seguridad por roles.

## Arquitectura

- Dominio: tecnocloud.local
- Subdominios:
  - soporte.tecnocloud.local
  - ventas.tecnocloud.local

## Organización

Se crearon Unidades Organizativas (OU):

- Dirección
- Administración
- Soporte
- Ventas

## Usuarios

Distribución de usuarios por área:

- Dirección: 1
- Administración: 2
- Soporte: 4
- Ventas: 3

## Implementación

- Instalación de AD DS
- Configuración de DNS
- Creación de usuarios y grupos
- Delegación de permisos

## Seguridad (GPO)

Se aplicaron políticas como:

- Contraseñas seguras (mínimo 8 caracteres)
- Expiración de contraseñas (90 días)
- Bloqueo por intentos fallidos
- Restricción de USB
- Deshabilitación de CMD
- Bloqueo de panel de control
- Protector de pantalla con contraseña

## Buenas prácticas

- Separación por roles
- Principio de mínimo privilegio
- Delegación de administración

## Tecnologías

- Windows Server
- Active Directory
- DNS
- GPO

## Resultado

Entorno empresarial funcional con control centralizado y políticas de seguridad aplicadas.


