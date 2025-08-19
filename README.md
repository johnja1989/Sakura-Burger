# 🌸 Sakura Burger - Sitio Web

## Descripción

Sitio web para una hamburguesería ficticia con temática anime. El diseño combina elementos visuales del anime japonés con una estética cyberpunk moderna, creando una experiencia única que... bueno, definitivamente no pasa desapercibida.

## Características

### Visuales
- **Animación de pétalos de sakura**: Pétalos cayendo constantemente en el fondo (puede ser un poco mucho, lo sé)
- **Efectos neón**: Texto con gradientes y sombras luminosas estilo cyberpunk
- **Animaciones hover**: Prácticamente todo se mueve cuando pasas el cursor por encima
- **Diseño responsive**: Se adapta a móviles, aunque honestamente se ve mejor en pantalla grande

### Secciones
1. **Hero Section**: Presentación principal con el eslogan dramático
2. **Menú de Batalla**: 6 hamburguesas con referencias a diferentes animes populares
3. **Poderes Especiales**: Características del servicio presentadas como "power-ups"
4. **Footer**: Información de contacto minimalista

## Tecnologías Usadas

- HTML5 semántico (más o menos)
- CSS3 con animaciones y gradientes
- JavaScript vanilla para:
  - Generación dinámica de pétalos
  - Smooth scroll
  - Efecto parallax básico

## Instalación

La verdad es que es solo un archivo HTML. Literalmente:

1. Descarga el archivo `index.html`
2. Ábrelo en cualquier navegador moderno
3. Ya está

No necesitas servidor web ni nada complicado. Aunque si quieres puedes usar uno:

```bash
# Si tienes Python
python -m http.server 8000

# O si prefieres Node.js
npx serve
```

## Personalización

### Colores
Los colores principales están definidos como variables CSS al inicio:

```css
:root {
    --sakura-pink: #ff6b9d;
    --deep-purple: #4a0e4e;
    --electric-blue: #00d4ff;
    --warm-yellow: #ffd93d;
    --dark-bg: #1a0b2e;
}
```

### Pétalos de Sakura
Si los pétalos son demasiado (probablemente lo son), puedes ajustar la frecuencia en el JavaScript:

```javascript
// Línea ~290, cambia el intervalo
setInterval(createPetal, 1000); // Cambiar a 2000 o 3000 para menos pétalos
```

### Menú
Los items del menú están hardcodeados en el HTML. Para cambiarlos, busca la sección con `id="menu"` y edita directamente. Los precios están en pesos mexicanos, pero puedes cambiar eso fácilmente.

## Referencias de Anime Incluidas

Por si alguien no las capta:
- **Titan Burger**: Attack on Titan (Shingeki no Kyojin)
- **Rasengan Supreme**: Naruto
- **One Punch Burger**: One Punch Man
- **Dragon Ball BBQ**: Dragon Ball Z (la referencia a "más de 9000" es un meme clásico)
- **Kawaii Veggie**: Referencia general a la cultura kawaii
- **Demon Slayer Spicy**: Kimetsu no Yaiba

## Problemas Conocidos

- Los pétalos pueden ralentizar navegadores antiguos
- En móviles muy pequeños, algunos textos se ven apretados
- El efecto parallax puede causar un poco de lag en dispositivos lentos
- Las animaciones pueden ser... intensas para algunos usuarios

## Mejoras Futuras (si alguien quiere)

- [ ] Agregar un toggle para desactivar animaciones
- [ ] Sistema de pedidos real (actualmente los botones no hacen nada)
- [ ] Modo claro (aunque no sé si pegaría con la temática)
- [ ] Más easter eggs de anime
- [ ] Sonidos al hacer hover (no, mejor no)
- [ ] Galería de imágenes de las hamburguesas
- [ ] Integración con redes sociales real

## Licencia

Haz lo que quieras con esto. Es un proyecto de diversión, no hay restricciones.

## Notas del Desarrollador

Creo que me pasé un poco con las animaciones, pero la verdad es que cuando piensas en "hamburguesería anime", sutileza no es lo primero que viene a la mente. El sitio es completamente funcional pero obviamente es más una pieza de exhibición que un sitio de producción real.

Si alguien realmente quisiera usar esto para un negocio real, recomendaría:
1. Reducir las animaciones
2. Agregar fotos reales de las hamburguesas
3. Implementar un sistema de pedidos de verdad
4. Tal vez... bajarle un poco al drama en los textos

## Contacto

Este es un proyecto ficticio creado para demostración. No hay información de contacto real.

---

*"Donde los sueños y las hamburguesas se hacen realidad" - o algo así*