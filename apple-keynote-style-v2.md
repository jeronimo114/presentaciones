# Apple Keynote Style System v2 (más Apple)

Esto está diseñado para que tu deck se sienta como Apple: más aire, menos cajas, menos “UI de dashboard”, tipografía protagonista y acentos mínimos.

---

## 1) Qué está fallando en tus slides (y cómo corregirlo)

### 1. Demasiadas “tarjetas” tipo UI
- Apple rara vez usa 4 cards iguales con sombra en un slide de presentación.
- Solución: usa **1 mensaje grande** + **2–3 soportes** (texto corto o 1 visual).  
  Si necesitas grid, que sea **muy limpio**: sin borde, sin sombra, o borde casi invisible.

### 2. Mucho texto por bloque
- Tus bullets y descripciones son correctas, pero suenan a documento.
- Solución: recorta a **frases de 4–7 palabras**.

### 3. Acento azul aplicado como “decoración”
- La línea azul a la izquierda de cada bullet se siente “plantilla”.
- Solución: usa azul solo para **una palabra clave** o **un chip** por slide.

### 4. Falta de jerarquía brutal
- Apple exagera jerarquía: título enorme, soporte mínimo.
- Solución: títulos 72–96, cuerpo 28–34, caption 20–22, y mucho espacio vacío.

---

## 2) Tokens (colores, tipografía, radios, sombras)

### Colores (Apple neutral)
- Ink (texto): **#0B0B0F**
- Secondary (texto): **#5B5F6A**
- Hairline (líneas): **#E6E7EB**
- Fog (fondo suave): **#F5F5F7**
- White: **#FFFFFF**

### Acento (usa solo 1)
- Apple Blue: **#0071E3**

**Regla:** 95% neutros, 5% acento.

### Tipografía
- Preferida (Mac): **SF Pro Display / SF Pro Text**
- Alternativa: **Inter**

**Pesos recomendados**
- Títulos: Semibold (600)
- Cuerpo: Regular (400)
- Keywords: Medium (500)

### Tamaños (Keynote 16:9)
- H1 (cover): **96 pt**
- H1 (slide): **80 pt**
- H2 (slide): **64 pt**
- Body: **32 pt**
- Small: **24 pt**
- Caption: **20–22 pt**

### Espaciado
- Sistema 8pt: **8 / 16 / 24 / 32 / 48 / 64**
- Safe area recomendado: **96 px laterales**, **72 px arriba**, **72 px abajo**

### Radio y sombras
- Radio cards (si usas): **24**
- Sombra (si usas): muy leve  
  - Opacidad 8–10%  
  - Blur medio  
  - Sin borde marcado

---

## 3) Layouts Apple reales (para reemplazar tus slides)

### Layout A: Big Statement (recomendado)
**Uso:** “Qué es”, “Por qué”, “Qué resuelve”
- Título 72–90 pt
- 1 frase soporte 28–32 pt
- 1 palabra en azul

Ejemplo:
- **Gestión de Waves**  
  Control centralizado de formación y operación.  
  En **6 semanas** listo para demo.

### Layout B: 3 beneficios (sin cards)
- Título 64–72 pt
- 3 líneas con estructura:
  - Keyword en Ink
  - explicación corta en Secondary

Ejemplo:
- **Waves:** crea y administra grupos.  
- **Control diario:** asistencia y desempeño.  
- **Pagos:** cálculo por días reales.

### Layout C: 2 columnas (Apple)
- Izquierda: statement grande
- Derecha: 3 bullets cortos

---

## 4) Reescritura Apple de tus slides (texto)

### Slide 1 (cover)
**Plataforma de Waves**  
BPO Global Services

Opcional en pequeño:
- Showcase de flujo operativo de formación.

### Slide 2 (Qué es)
Título: **Qué es**  
Texto (elige 1 versión):

**Versión Apple 1**
- Un sistema para crear y operar **Waves** de formación.  
- Centraliza control diario, comunicaciones y trazabilidad.  
- Puente entre requisición y contratación.

**Versión Apple 2**
- Control de formación por cohortes (Waves).  
- Visibilidad diaria por agente.  
- Registro y trazabilidad de punta a punta.

### Slide 3 (Funcionalidades)
En vez de 4 cards, usa lista limpia:

Título: **Funcionalidades clave**
- **Waves:** creación y administración.  
- **Control diario:** asistencia y desempeño.  
- **Comunicaciones:** registro de envíos y plantillas.  
- **Pagos:** cálculo por días asistidos.

Si quieres mantener grid, que sea “Apple grid”:
- Sin borde, sin sombra, solo texto y mucho aire.
- Un ícono simple monocromo por bloque (opcional).

---

## 5) Animaciones (Keynote)

### Principios
- Nada de rebotes.
- Nada de efectos llamativos.
- Animación guía la mirada, no se nota.

### Duraciones
- Entrada: **0.35–0.5 s**
- Delay entre elementos: **0.06–0.12 s**
- Transición entre slides: **0.6–0.8 s**

### Recomendación
- Título: Fade + Move (12–18 px desde abajo)
- Texto soporte: Fade + Move (igual, con delay)
- Visual: Dissolve (0.5 s)
- Evita animar cada card por separado.

---

## 6) Check rápido (si cumple Apple)

- El slide tiene una sola idea.
- Hay más vacío que texto.
- El azul aparece 1 vez.
- No hay más de 25–30 palabras por slide (salvo excepciones).
- Si se imprime en blanco y negro, sigue viéndose bien.

---

## 7) Si estás en HTML/CSS (ajuste inmediato)

### Cambios directos que te acercan a Apple
- Fondo: White o Fog, sin degradados visibles.
- Elimina sombras en cards, o reduce a casi nada.
- Quita bordes marcados.
- Aumenta padding interno y gaps.
- Reduce el texto de cada bloque.
- Usa azul solo para 1 palabra o un label pequeño.

---

Fin.
