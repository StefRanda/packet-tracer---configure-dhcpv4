# 🧩 Laboratorio DHCP en Routers Cisco

## 📘 Descripción  
Este laboratorio tiene como objetivo practicar la configuración del **servicio DHCP (Dynamic Host Configuration Protocol)** en una red compuesta por varios routers Cisco.  
Se implementan distintas funciones del protocolo para administrar la asignación dinámica de direcciones IP y garantizar la conectividad entre diferentes redes.

---

## ⚙️ Parte 1: Configurar un router como **servidor DHCP**  
- Se definió un **pool DHCP** con su rango de direcciones IP.  
- Se especificó la **puerta de enlace predeterminada**, **máscara de subred** y **servidor DNS**.  
- Se excluyeron direcciones reservadas para los routers.

---

## 🌐 Parte 2: Configurar la **retransmisión DHCP (DHCP Relay)**  
- Se habilitó la función de **retransmisión** en los routers que conectan otras LANs.  
- Se agregó la **dirección auxiliar (ip helper-address)** que apunta al servidor DHCP en un segmento distinto.

---

## 🖥️ Parte 3: Configurar un router como **cliente DHCP**  
- Se configuró una interfaz del router para **obtener su dirección IP de manera automática** desde el servidor DHCP.

---

## 🔍 Parte 4: Verificar DHCP y la **conectividad**  
- Se comprobó que los **clientes recibieran direcciones IP válidas** del servidor.  
- Se realizaron pruebas de **ping** para confirmar la conectividad entre los dispositivos.  

---

## ✅ Resultados esperados  
- Los clientes obtienen sus direcciones IP dinámicamente.  
- El router cliente recibe su configuración automáticamente.  
- Hay conectividad completa entre los dispositivos de las distintas LAN.

---

## 🧠 Conocimientos aplicados  
- Configuración básica de routers Cisco  
- DHCP Server y DHCP Relay  
- Subneteo y direccionamiento IP  
- Comandos de verificación y diagnóstico de red
