# Splunk App - SC4SNMP Dashboard

Esta aplicación contiene un **dashboard interactivo** desarrollado con **Dashboard Studio** para visualizar métricas recolectadas mediante **Splunk Connect for SNMP (SC4SNMP)**.

---

## 🎯 Objetivo

Esta aplicación busca **dar valor de forma rápida y visual** a los datos recolectados por **SC4SNMP**, proporcionando una **visualización básica pero efectiva** de métricas SNMP. 
El enfoque es **reducir el tiempo de revisión y análisis**, facilitando la operación y supervisión de la infraestructura de red desde Splunk.

---

## 📦 Contenido de la App

- Dashboard Studio con pestañas temáticas (`tabs`) y múltiples visualizaciones
- Navegación personalizada (`default.xml`)
- Compatible con índices:
  - `netmetrics` (métricas)
  - `netops` (eventos SNMP)

---

## ⚙️ Requisitos Previos

1. **Splunk Enterprise** (9.0 o superior recomendado)
2. **Splunk Connect for SNMP (SC4SNMP)** correctamente configurado
3. Datos SNMP deben estar llegando a los índices esperados (`netmetrics`, `netops`)
4. Acceso habilitado a Dashboard Studio

---

## 🚀 Instalación

### Subida manual desde la interfaz web

1. Ingresa a Splunk > Apps > Manage Apps > Install app from file  
2. Selecciona el archivo `.tar.gz` de la app  
3. Haz clic en **Upload**

---

## 📊 Dashboard incluido

SC4SNMP Dashboard v1.0
Este dashboard contiene pestañas con visualizaciones basicas per funcionales para la visualización rapida de elementos de red:

General: métricas de disponibilidad, número de dispositivos, distribución por tipo.

Hardware: CPU, memoria.

Interfaces: métricas como velocidad, utilización (kbps), etc.

---

## 🧾 MIBs Utilizados

La visualización de datos en este dashboard se basa en los siguientes perfiles y MIBs configurados en SC4SNMP:

-IF-MIB
-IP-MIB
-TCP-MIB
-UDP-MIB
-SNMPv2-MIB
-CISCO-MEMORY-POOL-MIB
-CISCO-PROCESS-MIB
-CISCO-SYSLOG-MIB
-CISCO-SYSTEM-MIB


