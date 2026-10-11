# Best Friends Quiz 💜

Aplicación web completa para crear tests de amistad con estilo gaming neón.

## Cómo usarla

### Opción rápida (local)
1. Abre el archivo `index.html` directamente en tu navegador (Chrome, Safari, Firefox...).
2. Funciona perfectamente en móvil y computadora.

### Opción recomendada (compartir enlaces reales)
1. Sube la carpeta a **Vercel**, **Netlify** o **GitHub Pages**.
2. Obtén una URL pública (ej: `https://best-friends-quiz.vercel.app`).
3. Los enlaces generados funcionarán en cualquier dispositivo.

#### Desplegar en Vercel (gratis y 30 segundos)
```bash
# Si tienes Node instalado:
npx vercel

# O arrastra la carpeta en https://vercel.com/new
```

## Funcionalidades incluidas

- ✅ Pantalla de inicio
- ✅ Crear test (nombre + 15 preguntas con respuesta correcta)
- ✅ Generar enlace único (codificado en la URL, sin backend)
- ✅ Compartir por WhatsApp / copiar enlace
- ✅ Responder el test desde otro dispositivo
- ✅ Barra de progreso + una pregunta por pantalla
- ✅ Cálculo automático de porcentaje y título
- ✅ Ranking local por aciertos + tiempo
- ✅ Diseño neón responsive (móvil primero)
- ✅ Animaciones y feedback táctil

## Títulos según puntuación

| Aciertos | Resultado | Título                    |
|----------|-----------|---------------------------|
| 0–5      | 0–33%     | Desconocido 👀            |
| 6–9      | 40–60%    | Amigo en entrenamiento 🤝 |
| 10–12    | 67–80%    | Amigo de confianza 🔥     |
| 13–14    | 87–93%    | Mejor amigo 🏆            |
| 15       | 100%      | Leyenda de la amistad 💜  |

## Notas importantes

- Los **retos se guardan en la URL** (base64). No necesitas servidor para que un amigo responda.
- El **ranking se guarda en localStorage** del navegador. Cada dispositivo ve solo los intentos que se han hecho desde él.
- Para ranking global real + base de datos → conecta **Supabase** (fase 3 del plan original).

## Próximos pasos opcionales

1. Conectar Supabase para ranking multi-dispositivo.
2. Añadir avatares / perfiles.
3. Sonidos y más animaciones.
4. Temporadas o ranking global.

¡Disfruta descubriendo quién te conoce de verdad! 🎮💜
