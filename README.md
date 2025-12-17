# 🎓 UniBot: Asistente Académico Inteligente e Inclusivo

> **Hackathon 2025** - Automatización, Eficiencia y Accesibilidad Universitaria.

![Banner](https://img.shields.io/badge/Status-Hackathon_Demo-success) 
![Stack](https://img.shields.io/badge/Tech-n8n_|_Supabase_|_OpenAI_|_PDFMonkey-blue)

## El Problema
La gestión académica actual enfrenta dos grandes desafíos:
1.  **Ineficiencia Burocrática:** El 90% de los estudiantes pierde horas en filas o navegando portales web complejos para trámites simples (certificados, consultas), lo que satura a las secretarías.
2.  **Barreras de Acceso:** Las plataformas tradicionales son rígidas y excluyentes. Un estudiante con dificultades motoras o visuales depende de terceros para realizar gestiones básicas.

## La Solución
**UniBot** es un sistema de **Automatización Inteligente** diseñado para **TODOS**. Transforma la burocracia en una conversación fluida en Telegram.

Su enfoque es **Multimodal y Universal**:
* **Para el estudiante ocupado:** Ofrece inmediatez. Permite gestionar trámites en segundos mediante menús rápidos o notas de voz mientras se desplaza.
* **Para el estudiante con discapacidad:** Elimina las barreras de entrada, permitiendo una gestión 100% autónoma mediante comandos de voz natural.

**No es solo un chatbot, es una ventanilla virtual 24/7 que:**
1.  **Escucha y Lee:** Procesa tanto Texto como Voz (Whisper AI).
2.  **Razona:** Entiende la intención del usuario sin necesidad de comandos rígidos.
3.  **Ejecuta:** Genera documentos oficiales válidos al instante.


## Características Clave

### 1. Interfaz Multimodal (Texto y Voz) 
El sistema se adapta al usuario, no al revés.
* **Modo Texto:** Menús visuales claros y navegación rápida para consultas silenciosas.
* **Modo Voz:** Potente motor *Voice-to-Text* que permite solicitar trámites complejos (ej: "Dame mis notas, cédula 123...") hablando naturalmente. Ideal para agilizar procesos o para personas con dificultades de escritura.

### 2. Generación Dinámica de Documentos 
Los certificados se generan en tiempo real inyectando datos SQL en plantillas profesionales.
* *Tecnología:* Liquid Templates + CSS Print.

### 3. Seguridad y Validez 
Cada documento generado incluye medidas de seguridad antifraude:
* **Código QR Dinámico:** Enlace de validación único por documento.
* **Hash SHA-256:** Simulación de firma electrónica para integridad de datos.

### 4. Robustez y Manejo de Errores 
El agente cuenta con reglas estrictas (Guardrails) para guiar al usuario si ingresa opciones inválidas, evitando que el sistema colapse ante entradas inesperadas.



