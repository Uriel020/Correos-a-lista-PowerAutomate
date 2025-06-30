# 📧 Correos a Lista SharePoint con IA

> Automatización inteligente para transformar correos de notificación de cambios en APIs a elementos estructurados de listas SharePoint usando Power Automate e Inteligencia Artificial.

## 🎯 Descripción del Proyecto

Este flujo automatizado recibe correos electrónicos que notifican cambios en APIs empresariales y los convierte automáticamente en elementos organizados de una lista SharePoint. La solución aprovecha la **Inteligencia Artificial** para extraer y estructurar información compleja de manera inteligente, eliminando el procesamiento manual.

## ✨ Características Principales

- **🤖 Procesamiento Inteligente con IA**: Extracción automática de datos estructurados desde correos no estructurados
- **📨 Automatización Completa**: Desde la recepción del correo hasta la creación del elemento en SharePoint
- **🔄 Flujo Continuo**: Manejo de múltiples cambios de API en tiempo real
- **📊 Datos Estructurados**: Información organizada y fácil de consultar
- **🏷️ Gestión de Estados**: Marcado automático de correos procesados

## 🏗️ Arquitectura del Flujo

### Flujo Principal: Transformación Inteligente

<div align="center">
<img width="607" alt="Diagrama de flujo principal" src="https://github.com/user-attachments/assets/472f2f93-7591-446f-aa66-4753a37d485c" />
</div>

### Pipeline de Procesamiento

<div align="center">
<img width="576" alt="Pipeline de procesamiento" src="https://github.com/user-attachments/assets/aa7b3788-7b1b-4bfa-a21b-658a6d433cea" />
</div>

## 🧠 El uso de la IA en el Flujo

### ⚡ Procesamiento Inteligente Multi-Etapa

La parte más innovadora de este flujo es el **uso estratégico de la IA** para automatizar tareas complejas que tradicionalmente requerirían múltiples procesos consecutivos:

<div align="center">
<img width="548" alt="Flujo con IA" src="https://github.com/user-attachments/assets/4d8d4156-e089-4fd9-82bf-310216d9e0c2" />
</div>

#### 🔍 Lo que hace la IA automáticamente:

1. **📖 Lectura Inteligente**: Analiza el contenido completo del correo
2. **🧩 Extracción de Datos**: Identifica y extrae información específica:
  - Nombre de la API
  - Versiones (anterior/nueva)
  - Fechas de despliegue
  - Responsables
  - Endpoints (nuevos/modificados/eliminados)
  - Notas adicionales
3. **🔄 Estructuración JSON**: Convierte texto libre en datos estructurados
4. **✅ Validación**: Asegura formato correcto para SharePoint

#### 🚀 Ventajas de usar IA:

- **Sin Reglas Complejas**: No necesitas escribir múltiples condiciones o expresiones regulares
- **Adaptabilidad**: Se ajusta a diferentes formatos de correo automáticamente
- **Precisión**: Reduce errores humanos en la extracción de datos
- **Escalabilidad**: Maneja grandes volúmenes sin degradación de rendimiento

## 📋 Datos Extraídos Automáticamente

La IA extrae y estructura la siguiente información:

| Campo | Tipo | Descripción |
|-------|------|-------------|
| **Nombre de la API** | String | Identificador de la API modificada |
| **Versión Anterior** | String | Versión previa antes del cambio |
| **Versión Nueva** | String | Nueva versión desplegada |
| **Fecha de Despliegue** | String | Cuándo se realizó el cambio |
| **Responsable del Cambio** | String | Persona encargada del despliegue |
| **Endpoints Nuevos** | Array/String | Nuevos endpoints añadidos |
| **Endpoints Modificados** | Array/String | Endpoints existentes modificados |
| **Endpoints Eliminados** | String | Endpoints removidos |
| **Notas Adicionales** | String | Información extra relevante |

## 🔄 Flujo de Trabajo

## Ejemplo 1

### 1. Recepción y Procesamiento
<div align="center">
<img width="828" alt="Recepción de correo" src="https://github.com/user-attachments/assets/4426da6a-4526-4367-92d0-f15c2774acc5" />
</div>

### 2. Creación en SharePoint
<div align="center">
<img width="1470" alt="Procesamiento con IA" src="https://github.com/user-attachments/assets/22c718c2-5e53-4c3b-bf4e-810c811d6358" />
</div>

## Ejemplo 2

### 1. Recepción y Procesamiento
<div align="center">
<img width="830" alt="Creación en SharePoint" src="https://github.com/user-attachments/assets/0cc86d15-2bc3-4d00-bc82-c821f7c59e4c" />
</div>

### 2. Creación en SharePoint
<div align="center">
<img width="1470" alt="Gestión final" src="https://github.com/user-attachments/assets/60ba38f3-8915-429d-8266-273b76bf592d" />
</div>

## 🚀 Casos de Uso

- **Gestión de APIs Empresariales**: Seguimiento de cambios y versiones
- **Auditoría de Sistemas**: Historial de modificaciones
- **Comunicación de Equipos**: Notificaciones estructuradas
- **Reportes Ejecutivos**: Dashboards basados en datos reales

