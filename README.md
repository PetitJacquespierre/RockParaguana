# 🎸 Rock Paraguaná — Portal Web & Archivo Histórico

Portal oficial y archivo cultural del movimiento Rock & Metal en el estado Falcón y Venezuela.

- **Sitio Web en Vivo**: [https://rockparaguana.vercel.app](https://rockparaguana.vercel.app)
- **Repositorio GitHub**: [https://github.com/PetitJacquespierre/RockParaguana.git](https://github.com/PetitJacquespierre/RockParaguana.git)
- **Fundador & Director**: Jacquespierre Petit
- **Desarrollo**: Grow Studio

---

## ⚡ Características del Proyecto

1. **Splash Screen Interactivo**:
   - Video intro en alta definición (`RP_Splash.mp4`) con la púa 3D de dos caras (Insignia RP y Calavera del Chivo Padrote).
   - Adaptación responsive automática (`object-fit: contain`) para móviles y computadoras.

2. **Coberturas & Noticias en Vivo**:
   - Grilla fotográfica de eventos recientes y crónicas.
   - Panel de administración secreto (`#rockp`) protegido por clave para publicar directamente desde Instagram y añadir fechas pasadas o personalizadas.

3. **El Baúl de los Recuerdos**:
   - Descarga de paquetes completos en ZIP de más de 180 afiches, flyers y fotografías históricas.
   - Filtros rápidos por locales emblemáticos (*Moe's Bar, Tuvaru, Bar-Ril*) y bandas (*Maskhera, Blasphemy, Gillman, Cuarto Magno, Etnica*).
   - Visor Lightbox a pantalla completa con descarga individual de cada afiche.

4. **Archivo Histórico Blogspot (2012–2020)**:
   - Más de 1.100 artículos y crónicas recuperadas directamente de la base de datos XML original de Blogger.
   - Buscador en tiempo real por palabras clave, filtro por año y paginación rápida en JavaScript puro.

5. **Historia & Memoria**:
   - Relato fundacional desde los inicios en los 2000 con Marvin Primera, el renacer de 2012 con Jacquespierre Petit y las coberturas con Jackson Petit y Calfran Sivira.

6. **Soporte PWA (Progressive Web App)**:
   - Instalable en dispositivos móviles (Android/iOS) y computadoras a través de `manifest.json`.

---

## 📂 Estructura de Archivos

```text
Rock Paraguana/
├── index.html            # Estructura principal, estilos CSS y scripts
├── manifest.json         # Configuración para instalación como App (PWA)
├── README.md             # Documentación del proyecto
├── .gitignore            # Archivos excluidos de control de versiones
├── img/                  # Logos transparentes, favicons, fotos y video RP_Splash.mp4
├── js/
│   └── posts_data.js     # Base de datos JSON con 1.104 publicaciones históricas
├── descargas/            # Archivos ZIP de afiches y fotos de colección
└── backup_blogger/       # Respaldos XML originales de Blogspot
```
