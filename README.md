# Tema Hatsune Miku TM para Kino (con imagen de fondo)

Tema de app completo (apiVersion 26) inspirado en Hatsune Miku, con **imagen de fondo nocturna de la vocaloid detrás de toda la interfaz**.

**Versión actual: 1.0.0**

## Instalación

En Kino: **Ajustes ▸ Plugins ▸ Agregar** y escribe:

```
yumehotaru41-rgb/Mikutm
```

o pega la URL directa del manifest:

```
https://raw.githubusercontent.com/yumehotaru41-rgb/Mikutm/main/kino-plugin.json
```

Luego ve a **Ajustes ▸ Apariencia** y elige **Hatsune Miku TM**.

## Qué incluye

- **Imagen de fondo** (`assets/background.png`, 1824×1080) detrás de toda la app, con atenuado suave para que el texto siga legible. Kino la descarga al instalar el plugin, comprueba su sha256 y la guarda con el tema.
- Paleta de Hatsune Miku: acento turquesa **#39C5BB**, superficies azul noche y acentos rosados para favoritos.
- Logo del menú y de la cabecera: chibi de Miku junto al texto **MIKU**.
- Radios de tarjetas, botones y diálogos, escala de texto, tamaño de controles del reproductor, sombras y movimiento ajustables en **Ajustes ▸ Apariencia ▸ Personalizar**.

## Requisito

La imagen de fondo necesita **apiVersion 26**: usa una versión reciente de Kino (0.9.8x o más nueva). En versiones anteriores el manifiesto completo se rechaza con el mensaje «Este plugin necesita una versión más nueva de Kino».

## Notas

- En **Ajustes ▸ Experiencia visual** puedes apagar la imagen de fondo (u otros efectos) dispositivo por dispositivo; el tema sigue viéndose bien con todo apagado gracias al color de respaldo azulado.
- Algunas pantallas nunca toman el tema de un plugin (control parental, consentimientos, etc.): es diseño deliberado de Kino.

## Autor

- **author**: Hotaru Yume
- **creator**: hotaruyume
