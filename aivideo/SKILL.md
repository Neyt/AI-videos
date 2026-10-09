---
name: aivideo
description: Playbook de producción de videos e imágenes con IA (AI Video Bootcamp): flujos, modelos, fórmulas de prompt, viralidad y anuncios. Usar al crear reels, anuncios, avatares o cortos con IA.
---

# aivideo — Playbook de video con IA

Fuente: curso AI Video Bootcamp (Skool), 130 lecciones estudiadas el 8-oct-2026.
Resumen hecho por Ney Torres (linkedin.com/in/neytorres) con sus propias palabras. Para el detalle completo, el curso original es AI Video Bootcamp en Skool.

Regla de contenido: empezar en la acción (tensión primero, nunca la explicación), mostrar la apuesta en la escena, una regla del juego tan simple que la entienda un niño, contraste fuerte.

## 1. Regla de oro: imagen primero, video después
- Flujo: Idea → Chat (guion/prompts) → Imagen → Refinar/upscale → Video → Editar y publicar.
- Iterar en imagen (barato) y animar solo la ganadora como start frame.
- Si la imagen está al 90 % se corrige; si la base está mal, volver al chat, no pulir.
- El prompt de video describe SOLO movimiento (sujeto, cámara, ambiente, luz); no re-describir la imagen.

## 2. Modelos (según el curso, oct-2026 — verificar vigencia)
| Uso | Modelo | Nota |
|---|---|---|
| Imagen realista | GPT Image 2.0, Nano Banana Pro | terminar con "photorealism"; Nano Banana edita/fusiona multi-imagen |
| Video premium, acción, lip sync | Seedance 2.0 / 2.5 | el mejor y el más caro; 2.5 hasta 30 s y muchas referencias |
| Video multi-toma | Kling 3.0 | multi-shot 15 s, Omni Reference hasta 7 imágenes; falla lip sync >10 s |
| Video barato / pruebas | Gemini Omni, Veo 3.1 (Fast) | ~3× más barato; probar hooks aquí, rehacer el ganador en Seedance |
| Voz / SFX | ElevenLabs; música y SFX gratis en Pixabay | |
| Edición | CapCut; retoque en Canva | |
| Avatar propio | HeyGen + voz ElevenLabs | clon de video + clon de voz |
| Todo en uno | PromptWise (Studio, Flows, UGC Factory, MCP para Claude) | plataforma de los instructores; revisar precio de créditos |

## 3. Fórmulas de prompt
- Imagen (6 partes): `[Sujeto] en [entorno], [cámara], [fuente y dirección de luz], [ánimo], [estilo]`. Describir la luz por su FUENTE. Evitar "masterpiece/hyper-detailed".
- Anti-look-IA: "shot on iPhone 15, candid, natural framing, realistic skin texture".
- Profundidad: primer plano + plano medio + fondo + algo en el aire (niebla, polvo).
- Cámara de video (6 campos): Movement / Start / Speed / Framing / End / Time + "real time, normal speed, no slow motion". Un movimiento por toma.
- Seedance (orden): bloque de look idéntico → contexto → @image refs en orden de subida → número y posición de personas → cámara → acción con timestamps segundo a segundo → actuación → quién dice qué → SFX → negativos.
- Secuencia: "0-3s setup, 3-7s action, 7-12s escalation, 12-15s hero moment".
- Voz consistente: definir una vez (acento, tono, ritmo, textura) y copiarla idéntica; diálogo corto con "..." para pausas.
- Referencias: decir siempre QUÉ se conserva (cara, ropa, producto o solo pose).

## 4. Continuidad
- Hoja de personaje 16:9 (frente, perfil, 3/4, cuerpo entero) → biblioteca de escenas.
- "Passports" por personaje/objeto/locación; bloque de luz/look copiado palabra por palabra.
- Escenas largas: último fotograma como start frame del siguiente clip (clips de 8–15 s).
- Textos y cifras: agregarlos en CapCut como PNG después de animar.

## 5. Post-producción
- Quitar look IA en CapCut: contraste −−, saturación −, altas luces +, temblor de cámara casi imperceptible.
- Sonido en capas al final.
- Exportar TikTok/IG/Shorts 1080p 30 fps. Subir desde el celular. Marcar "contenido IA"; en YouTube "no hecho para niños".

## 6. Viralidad
- Hook ≤3 s con texto en pantalla; métrica que decide: retención a los 2 s.
- 3–5 posts/día, a hora fija, ≥1 h entre posts. Si uno pega, publicar otro ya.
- Repetir ganadores con un cambio pequeño. Recrear lo que viralizó ayer en el nicho.
- Misma pieza: TikTok → Instagram → Shorts.
- Responder comentarios con frases en la primera hora; ≤4 hashtags.
- NO usar segundas cuentas ni ocultar comentarios "es IA": violan normas de TikTok.

## 7. Anuncios
- Un anuncio = un deseo (salud, atracción, estatus, pertenencia, control, comodidad).
- Ajustar al nivel de conciencia: no correr conversión a audiencia fría.
- Re-anclar el precio contra la alternativa cara.
- Que no parezca anuncio; mostrar cómo funciona.
- Frameworks de guion: SPARK, Myth Killer, Countdown, Origin Story, Demo Drop, Face-Off, etc. (ver 05\_NOTAS.md).
- Estáticos: Nano Banana Pro con producto + anuncio ganador de referencia.

## 8. Clonarte a ti mismo (HeyGen + ElevenLabs)
- Voz: Multilingual v2, Similarity 75 %, Stability 65–70, Style 0.12, Speaker boost on.
- Guion en bloques ≤4 líneas; formato largo a 1.1–1.2× con B-roll cada pocos segundos.
- Avatar IV solo en hooks; Avatar III para el resto.

## 9. Cómo trabajar
1. Pedir la idea en una frase y el formato (duración, vertical u horizontal, plataforma).
2. Escribir guion por segundos y prompts de imagen y video siguiendo las fórmulas de arriba.
3. Correr la imagen, revisarla y solo después generar video.
4. Entregar: prompts usados, costo estimado en créditos, y qué probar si el hook no retiene.
