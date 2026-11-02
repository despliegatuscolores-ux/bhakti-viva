# BHAKTI · El Fuego de la Entrega

### Śaraṇāgati & Prema · La Vía del Corazón Rendido

> *Herramienta contemplativa de código abierto para encarnar el amor divino incondicional y el vaciamiento del ego: altar de entrega (Śaraṇāgati), Japa Mālā táctil de 108 cuentas, síntesis acústica de armonio devocional en tiempo real y las 9 puertas del Bhakti.*

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-blue.svg)](index.html)
[![Offline First](https://img.shields.io/badge/Architecture-Offline--First-orange.svg)](#arquitectura-t%C3%A9cnica)
[![Deploy with GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-violet.svg)](#despliegue-en-github-pages)
[![Collection: Tetralogía Contemplativa](https://img.shields.io/badge/Collection-Tetralog%C3%ADa%20Contemplativa-crimson.svg)](#la-tetralog%C3%ADa-contemplativa)

---

## 🌹 Visión Filosófica: Vaciar para que lo Divino Habite en Ti

Mientras que el intelecto analiza y el asceta entrena su voluntad, el devoto (*Bhakta*) elige la rendición absoluta por enamoramiento cósmico. En la tradición del Bhakti y la mística perenne (desde los *Nārada Bhakti Sūtras* y la *Bhagavad Gītā* hasta San Juan de la Cruz, Rūmī, Kabīr y Mīrābāī), **la libertad interior no es una conquista del ego, sino el don que surge al soltar el timón personal**.

> *«Dios no puede llenar un recipiente que ya rebosa de orgullo, queja y necesidad de control. Cuando el corazón se vacía de pretensiones, la Presencia infinita hace de él su morada.»*

**bhakti-viva** es el cuarto volumen de la serie contemplativa de código abierto. Ha sido concebida bajo una premisa estricta de **cero dependencias externas**, privacidad radical en el dispositivo y funcionamiento 100% desconectado (*offline-first*).

---

## ✨ Módulos Principales

### 1. Bhavā Viva (El Verso del Día)
* **Fuentes canónicas y mística universal:** Aforismos de los *Nārada Bhakti Sūtras*, *Bhagavad Gītā*, poesía sufí de Rūmī, la *Noche Oscura* carmelitana, los cantos de amor intrépido de Mīrābāī y las sentencias directas de Kabīr.
* **Transcripción fonética y sánscrita:** Cuidado fónico para preservar la cadencia original.
* **Clave del Corazón:** Interpretación despojada de dogmatismos estrechos o mercantilismo espiritual.
* **Micro-Práctica de Entrega:** Una acción conductual concreta para ofrendar una tarea, desmantelar una barrera defensiva o soltar una exigencia en la jornada diaria.
* **Contador de Ofrendas (🌹):** Registro persistente en `localStorage` que honra la continuidad del anhelo devocional.

### 2. El Altar del Vaciamiento (*Śaraṇāgati / Kenosis*)
Espacio interactivo para soltar el esfuerzo inútil de gobernar el mundo mediante la preocupación:
1. **Nombrar la Carga:** Identificar la ansiedad, el resentimiento, el miedo a la escasez o la obsesión perfeccionista.
2. **El Fuego de la Ofrenda:** Animación ritual de disolución con toques de campana de bronce donde la carga arde simbólicamente en el altar del Amor.
3. **Descanso Sagrado (*Kenosis*):** Asentamiento en la certeza corporal de que la vida está sostenida por una Inteligencia mayor.

### 3. Japa Mālā Contemplativo (108 Cuentas)
* Rosario táctil circular renderizado en SVG dinámico con indicador de progreso angular.
* Retroalimentación sonora en cada cuenta y campana armónica ceremonial (*Manjira*) al completar el ciclo sagrado de 108 repeticiones.
* Soporte para vibración háptica en dispositivos móviles compatibles (`navigator.vibrate`).
* Selector de nombres sagrados y oraciones del corazón:
  * *Rāma* (La Dicha Suprema interior).
  * *Oṃ Namo Nārāyaṇāya* (El Refugio Universal).
  * *Kṛṣṇa Prema* (El Amor Atractivo Absoluto).
  * *Hu / El Amado* (El Aliento Divino del misticismo sufí).
  * *Kyrie Eleison* (La Oración Hesicasta del Corazón).
  * *Paz, Confianza y Entrega* (Invocación secular ecuménica).

### 4. Las 9 Puertas de la Devoción (*Navadhā Bhakti*)
Módulo pedagógico basado en el *Bhāgavata Purāṇa* (7.5.23) para explorar y activar las nueve avenidas del amor divino:
* **Śravaṇa:** Escuchar la palabra sagrada y el silencio elocuente.
* **Kīrtana:** Cantar la alabanza con alegría desinteresada.
* **Smaraṇa:** Mantener el recuerdo continuo en medio de lo cotidiano.
* **Pāda-sevana:** Servir a los pies de lo divino a través del cuidado a los vulnerables.
* **Arcana:** La ofrenda ritual sencilla (agua, luz, flor o presencia).
* **Vandana:** La postración humilde que pone la cabeza por debajo del corazón.
* **Dāsya:** La actitud del servidor fiel que cuida lo que no le pertenece.
* **Sakhya:** La amistad íntima y sincera con lo sagrado.
* **Ātma-nivedana:** La entrega completa del propio ser en el océano de la Gracia.

### 5. Motor Acústico Procedural: Armonio Devocional y Manjira
* **Síntesis nativa en tiempo real (Web Audio API):** Cero archivos `.mp3` o bibliotecas de audio externas pesadas.
* **Dron de Armonio en Re (D):** Emulación de cuatro voces polifónicas ricas en armónicos (D3, A3, D4 y F#4 suave) con filtro paso-bajo que recrea las lengüetas de caña tradicionales y un oscilador de baja frecuencia (LFO) que reproduce la marea del fuelle de viento (*bellows*).
* **Crótalos / Manjira:** Campana de aleación metálica con parciales senoidales inarmónicos y decaimiento exponencial natural.

### 6. Hṛdaya Patra (Diario del Corazón Rendido)
* Registro íntimo y confidencial para escribir oraciones, cartas de desahogo, peticiones de gracia y agradecimientos.
* Clasificación por actitudes interiores: *Confianza & Rendición*, *Alabanza & Gratitud*, *Duelo / Desahogo Sincero* y *Petición de Instrumento*.
* Copias de seguridad locales en formatos **JSON** estructurado y **TXT** formateado para lectura personal.

### 7. Compendio de la Llama Viva
* Biblioteca clasificada por vertientes devocionales: *Védico / Gītā*, *Sufismo*, *Mística Carmelitana* y *Amor Extático de Mīrābāī*.
* Buscador en tiempo real por palabras clave, versos o autores con botón para fijar cualquier enseñanza en la práctica del día.

---
## 📜 La Tetralogía Contemplativa

Este proyecto constituye el cuarto y último volumen de una tetralogía unificada que abarca las cuatro dimensiones maestras del despertar interior:

```text
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                                TETRALOGÍA CONTEMPLATIVA                                │
├──────────────────────┬──────────────────────┬───────────────────┬──────────────────────┤
│ Vol. I · SŪTRA YOGA  │ Vol. II · DHARMA     │ Vol. III · TANTRA │ Vol. IV · BHAKTI     │
├──────────────────────┼──────────────────────┼───────────────────┼──────────────────────┤
│ Repo: sutra-yoga     │ Repo: sutra-dharma   │ Repo: tantra-viva │ Repo: bhakti-viva    │
│ Raja Yoga (Patañjali)│ Budismo Canónico     │ Śaivismo de Trika │ Mística Devocional   │
│ El Hilo de la Calma  │ El Sendero Lúcido    │ El Tejido Vivo    │ El Fuego del Amor    │
│ Cese y contención    │ Vacuidad y atención  │ Energía y asombro │ Rendición y entrega  │
└──────────────────────┴──────────────────────┴───────────────────┴──────────────────────┘
---

## 🛡️ Privacidad y Ética Digital

1. **Cero Rastreo:** Sin herramientas analíticas, sin píxeles de seguimiento publicitario y sin telemetría de comportamiento.
2. **Cero Conexiones Salientes:** Tras cargarse en el navegador, el código opera de forma local e independiente de la red.
3. **Diseño para la Quietud:** Sin notificaciones intrusivas ni mecánicas de retención adictiva. La tecnología se orienta a cerrar la pantalla y retornar a la presencia viva.

---
