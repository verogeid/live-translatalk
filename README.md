<a id="indice"></a>
![Status][En-Diseno]

[![LinkedIn][linkedin-logo]][linkedin-link] (C) Diego González Fernández  
---

<h1 align="center">🎙️ live-translatalk 🎙️</h1>

![python-logo]
![Whisper][whisper-logo]
![DeepL][deepl-logo]
![pyttsx3][pyttsx3-logo]
![Tkinter][tkinter-logo]
![OBS Studio][obs-logo]
![VB_Cable][VB-Cable-logo]
![Docker][docker-logo]

**Sistema real de traducción de voz a voz multilingüe para videollamadas con subtítulos integrados.**

---

> ⚠️ Este README no es solo una *idea bonita*: es una solución técnica en desarrollo.  
> Ya existe una versión híbrida funcional.  
> El código completo se encuentra en un repositorio privado a la espera de pruebas y setup automatizado.

---

## 🧭 Índice

- [🧠 Descripción del Proyecto](#descripcion-del-proyecto)
- [🧰 Tecnologías utilizadas](#tecnologias)
- [🔧 Tecnologías previstas](#tech-previstas)
- [🚀 Casos de uso](#casos-de-uso)
- [📦 Instalación](#instalacion)
- [🤝 Contribuciones](#contribuciones)
- [🚧 Estado del proyecto](#estado-actual)

---

<a id="descripcion-del-proyecto"></a>
## 🧠 Descripción del Proyecto

**🎯 Objetivo:**  
Traducir y subtitular en tiempo real lo que dice cada interlocutor en una videollamada internacional, sin depender de plataformas externas ni extensiones de navegador.

### 📤 Emisión (usuario):
- Captura de voz desde auriculares
- Transcripción en tiempo real (*Whisper*)
- Traducción automática (*DeepL API*)
- Voz sintética traducida enviada a la videollamada
- Subtítulos sincronizados en pantalla (original + traducido)

### 📥 Recepción (interlocutor):
- Captura de audio recibido (VB-Cable)
- Transcripción y traducción
- Voz traducida en auriculares del usuario
- Subtítulos sobreimpresos en el vídeo

[Volver al inicio](#indice)

---

<a id="tecnologias"></a>
## 🧰 Tecnologías utilizadas

- 🎤 **Audio de entrada**: VB-Cable, VoiceMeeter, PyAudio
- 🧠 **STT y traducción**: *Whisper* (OpenAI), *DeepL API*
- 🔊 **TTS**: pyttsx3, gTTS, Coqui TTS
- 📺 **Visualización**: OBS Studio + Browser Source (HTML local)
- 📦 **Ecosistema**: Python + Docker

[Volver al inicio](#indice)

---

<a id="tech-previstas"></a>
## 🔧 Tecnologías previstas

- Backend: Python (captura, lógica, síntesis, traducción)
- GUI: Tkinter
- Reconocimiento de voz: Whisper, Vosk
- API de traducción: DeepL, LibreTranslate
- TTS: Coqui TTS, pyttsx3
- Contenedorización: Docker

[Volver al inicio](#indice)

---

<a id="casos-de-uso"></a>
## 🚀 Casos de uso

- QA o Devs con inglés limitado en *calls* técnicas
- Tutores o formadores remotos en entornos bilingües
- Soporte técnico o webinars multilingües
- Entornos inclusivos donde no se espera fluidez oral

[Volver al inicio](#indice)

---

<a id="instalacion"></a>
## 📦 Instalación (prevista)

- Entorno Python local o contenedor Docker autoejecutable
- Configuración mínima: claves de API + dependencias vía `pip`
- Documentación futura incluirá guía paso a paso

[Volver al inicio](#indice)

---

<a id="contribuciones"></a>
## 🤝 Contribuciones

Pull requests, ideas y sugerencias son bienvenidas.  
Algunos retos abiertos:
- Manejo de silencios y *overlapping*
- Fallback en caso de alta latencia
- Shortcuts para activar/desactivar traducción

[Volver al inicio](#indice)

---

<a id="estado-actual"></a>
## 🚧 Estado del proyecto

🚧 En pausa por otras prioridades.  
🧪 El prototipo híbrido (local + remoto) está listo en privado.  
🔉 Planificada versión 2.0 con selección automática de voz digital similar al timbre del usuario (sin clonación, sin IA propietaria).  
💡 Idea: crear base pública de perfiles sonoros libres y seleccionables.

[Volver al inicio](#indice)

---

## 📄 Licencia

Licencia MIT

[Volver al inicio](#indice)

---

© 2025 – Este es un experimento de código abierto y un trabajo en curso.

<!-- Workspace -->
[En-Construccion]: https://img.shields.io/badge/status-en%20construcci%C3%B3n-orange
[En-Diseno]: https://img.shields.io/badge/status-en%20dise%C3%B1o-yellow

<!-- Speech & Traducción -->
[whisper-logo]: https://img.shields.io/badge/Whisper-000000?style=for-the-badge&logo=openai&logoColor=white
[deepl-logo]: https://img.shields.io/badge/DeepL-0A83FF?style=for-the-badge&logo=deepl&logoColor=white
[pyttsx3-logo]: https://img.shields.io/badge/pyttsx3-FF9900?style=for-the-badge&logo=python&logoColor=white
[VB-Cable-logo]: https://img.shields.io/badge/VB-Cable-00ADEF?style=for-the-badge&logo=windows&logoColor=white

<!-- GUI -->
[tkinter-logo]: https://img.shields.io/badge/Tkinter-3776AB?style=for-the-badge&logo=python&logoColor=white

<!-- Video -->
[obs-logo]: https://img.shields.io/badge/OBS%20Studio-302E31?style=for-the-badge&logo=obsstudio&logoColor=white

<!-- Container -->
[docker-logo]: https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white

<!-- Language -->
[python-logo]: https://img.shields.io/badge/Python-black?logo=python&style=for-the-badge

<!-- Othen -->
[linkedin-logo]: https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-link]: https://www.linkedin.com/in/diego-gonzalez-fernandez/
