# United Nerds

**United nerds** és un moviment que busca aturar la discriminació, segregació i discriminació indirecta cap als nerds (els diferents).

## 📖 Sobre el Projecte

Aquest és un lloc web creat amb Astro que presenta el moviment United nerds. El projecte busca crear consciència sobre la discriminació cap als nerds i promoure la inclusió i l'acceptació de les persones diferents.

## 🚀 Tecnologies Utilitzades

- **Astro** - Framework web modern per crear llocs estàtics ràpids
- **CSS** - Estils globals amb variables i responsivitat
- **Noto Sans** - Font de Google Fonts per a la tipografia

## 📁 Estructura del Projecte

```
/
├── public/
│   ├── favicon.svg
│   ├── icon.webp
│   └── github-icon.astro
├── src/
│   ├── components/
│   │   ├── Index/
│   │   │   ├── About.astro
│   │   │   └── Header.astro
│   │   └── Nav.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── pnpm-lock.yaml
```

## 🔧 Comands

Tots els comandos s'executen des de l'arrel del projecte, des d'un terminal:

| Comando              | Acció                                            |
| :------------------- | :----------------------------------------------- |
| `pnpm install`       | Instal·la les dependències                       |
| `pnpm dev`           | Inicia el servidor de desenvolupament a `localhost:4321` |
| `pnpm build`         | Construeix el lloc per a producció a `./dist/`  |
| `pnpm preview`       | Previsualitza la construcció localment abans de desplegar |
| `pnpm astro ...`     | Executa comandes CLI com `astro add`, `astro check` |
| `pnpm astro -- --help` | Obté ajuda usant l'Astro CLI                   |

## 📄 Pàgines i Components

### Pàgina Principal (`index.astro`)
Pàgina d'inici que inclou:
- **Header**: Títol principal "UNITED NERDS"
- **About**: Secció que explica què és el moviment United nerds

### Components

- **Nav.astro**: Navegació principal amb enllaços a:
  - Pàgina d'inici
  - Repositori de GitHub per contribuir
  
- **Hero.astro**: Component que mostra el títol principal del moviment

- **About.astro**: Component que conté la descripció i missatge del moviment

- **Layout.astro**: Layout principal que inclou:
  - Meta tags i configuració del document
  - Càrrega de la font Noto Sans de Google Fonts
  - Estructura HTML base amb el component Nav

## 🎨 Estils

El projecte utilitza un tema fosc amb:
- Color de fons: `#292E38`
- Color de text: blanc amb variacions
- Font: Noto Sans (Google Fonts)
- Navegació sticky amb icones i enllaços amb efectes hover

## 📚 Recursos

- [Documentació d'Astro](https://docs.astro.build)
