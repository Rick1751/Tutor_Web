# Sitio Web Tutor: Cableado Estructurado 🌐🌐

Proyecto para la asignatura de **Fundamentos de Redes y Conectividad (GR1CD)** - Primer Bimestre 2026-A.

## Descripción del Proyecto
Este proyecto consiste en la implementación de un servidor web local utilizando **Windows Server 2025** e **IIS 10**. El sitio web funciona como un tutor interactivo que cubre todos los aspectos técnicos del cableado estructurado, desde la normativa hasta los dispositivos de interconexión modernos.

## Arquitectura Técnica
*   **SO Servidor:** Windows Server 2025 (Máquina Virtual).
*   **Servidor Web:** Internet Information Services (IIS) 10.
*   **Frontend:** HTML5 y **Bootstrap 5**
*   **Acceso Local:** Configuración de DNS local mediante archivo `hosts` (`http://mytutor.com`).

## Estructura del Sitio
- `index.html`: Definición y conceptos básicos.
- `topologias.html`: Características y diagramas de red.
- `elementos.html`: Cableado horizontal, vertical y cuartos de control.
- `tecnologia.html`: Medios de transmisión (UTP/Fibra) y Top 5 de equipos del mercado.
- `nosotros.html`: Perfiles profesionales de los integrantes del equipo.

## Requisitos de Instalación
1. Clonar el repositorio dentro de `C:\inetpub\wwwroot\`.
2. Habilitar el rol de **Servidor Web (IIS)** en Windows Server.
3. Crear un nuevo sitio web apuntando al directorio raíz del proyecto.
4. Mapear la IP del servidor al dominio `mytutor.com` en el archivo `hosts` del sistema anfitrión.

## 👥 Integrantes
* Paola Pacheco
* Matias Monge
* Karla Guaña
* Ricardo León

