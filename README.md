# Enterprise Network IPv4/IPv6 Configuration Lab

## 📋 Descripción del Proyecto

Configuración de red empresarial con múltiples routers y subredes
utilizando IPv4 y IPv6. Incluye división VLSM, enrutamiento estático,
DHCP, DNS, túneles IPv6 y enlaces WAN.

## 🎯 Objetivos

- Implementar subredes con VLSM
- Configurar routing estático IPv4 e IPv6
- Establecer enlaces WAN con serial
- Crear túneles IPv6 para interconectar redes
- Configurar servicios (DHCP, DNS)

## 📐 Topología

- **Router R1**: Gateway de 3 subredes principales
- **Router R2**: DHCP server + intermediario WAN
- **Router R3**: Nodo distribuidor
- **Router R4**: Remoto con túnel IPv6

## 🔧 Tecnologías

- Cisco Packet Tracer
- IPv4 con VLSM
- IPv6 con direccionamiento manual y link-local
- Routing estático
- Túneles IPv6 sobre IPv4

## 📊 Información de Subredes

Ver documentación en `documentation/VLSM-SUBNETTING.md`

## 🚀 Cómo Usar

1. Descargar Packet Tracer (gratuito en Cisco Learning Network)
2. Abrir el archivo `packet-tracer-files/red-empresarial.pkt`
3. Consultar configuraciones en `configurations/`

## ✅ Validación

Todas las conexiones han sido testeadas:

- ✓ Conectividad IPv4 entre todas las subredes
- ✓ Conectividad IPv6 local y remota
- ✓ DNS funcional
- ✓ Túneles IPv6 activos
