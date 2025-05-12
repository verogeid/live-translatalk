<a id="indice"></a>
![Status][En-Construccion]

[![LinkedIn][linkedin-logo]][linkedin-link] (C) Diego González Fernández. 
---

<h1 align="center">🎙️ live-translatalk 🎙️</h1>

![python-logo]
![Whisper][whisper-logo]
![DeepL][deepl-logo]
![pyttsx3][pyttsx3-logo]
![Tkinter][tkinter-logo]
![OBS Studio][obs-logo]
![Docker][docker-logo]

**Sistema de traducción de voz a voz en tiempo real con subtítulos en pantalla para videoconferencias multilingües.**

## 🧠 Descripción general

**🎯 Objetivo:**  
Facilitar la comunicación en reuniones internacionales **traduciendo y subtitulando en tiempo real** lo que dice cada interlocutor.

### 📤 Emisión (usuario de la app):
- Captura de la voz desde el micrófono del auricular.
- Transcripción en tiempo real.
- Traducción al inglés.
- Síntesis de voz traducida e inyección en la videollamada.
- Subtítulos (original + traducción) mostrados en ventana flotante.

### 📥 Recepción (interlocutor en la videollamada):
- Captura del audio recibido en la videollamada.
- Transcripción en tiempo real.
- Traducción al castellano.
- Síntesis de audio traducido en los auriculares del usuario.
- Subtítulo (texto original en inglés) sobreimpreso en la videollamada.

[Volver al inicio](#indice)

---

## 🚧 Estado del proyecto

**Este proyecto está actualmente en desarrollo activo.**  
Fase inicial de prototipado con flujos de entrada/salida independientes, pruebas de latencia, buffers de sincronización y primeros experimentos con OBS.

[Volver al inicio](#indice)

---

## 🔧 Tecnologías previstas
- Python (gestión de audio, lógica de traducción, GUI)
- Reconocimiento de voz: Whisper, Vosk
- API de traducción: DeepL, LibreTranslate
- Síntesis TTS: pyttsx3, gTTS, Coqui TTS
- GUI: Tkinter
- OBS Studio (para proyección en videollamadas)
- Docker (contenedor autoejecutable)

[Volver al inicio](#indice)

---

## 🚀 Casos de uso
- Reuniones técnicas con desarrolladores internacionales
- Equipos QA con perfiles técnicos y no técnicos en distintos idiomas
- Tutorías, webinars o asistencia remota bilingüe
- Apoyo a perfiles con nivel de inglés A2-B1 para participar en calls sin bloquearse

[Volver al inicio](#indice)

---

## 📦 Instalación (prevista)

Se añadirán las instrucciones de instalación a medida que el proyecto avance.  
Se prevé instalación local con Docker, configuración de API keys y dependencias vía `pip`.

[Volver al inicio](#indice)

---

## 🤝 Contribuciones

No dudes en abrir issues o pull requests.  
Este es un proyecto en fase prototipo, con mucho espacio para ideas y mejoras: detección de pausas naturales, buffer de cola para frases no solapadas, control por atajos de teclado, etc.

[Volver al inicio](#indice)

---

## 📄 Licencia

Licencia MIT

[Volver al inicio](#indice)

---

© 2025 – Este es un experimento de código abierto y un trabajo en curso.

<!-- Workspace -->
[En-Construccion]: https://img.shields.io/badge/status-en%20construcci%C3%B3n-orange

<!-- Speech & Traducción -->
[whisper-logo]: https://img.shields.io/badge/Whisper-000000?style=for-the-badge&logo=openai&logoColor=white
[deepl-logo]: https://img.shields.io/badge/DeepL-0A83FF?style=for-the-badge&logo=deepl&logoColor=white
[pyttsx3-logo]: https://img.shields.io/badge/pyttsx3-FF9900?style=for-the-badge&logo=python&logoColor=white

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
