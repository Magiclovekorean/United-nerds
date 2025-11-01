# 🤝 Guia de Contribució

**Tothom pot contribuir a aquest projecte!** Estem encantats de rebre contribucions de qualsevol persona que vulgui ajudar a fer créixer el moviment United nerds.

## 🌟 Per què contribuir?

United nerds és un moviment obert que busca aturar la discriminació cap als nerds. La teva contribució, per petita que sigui, pot fer una gran diferència. Pots ajudar de diverses maneres:

- 🐛 Reportar errors o bugs
- 📝 Millorar la documentació
- 🎨 Millorar el disseny i els estils
- 🌐 Traduir el contingut

## 🚀 Com Contribuir

### 1. Fork del Repositori

Primer, fes un fork del repositori al teu compte de GitHub:

1. Clica al botó "Fork" a la cantonada superior dreta
2. Això crearà una còpia del repositori al teu compte

### 2. Clonar el Repositori

Clona el teu fork localment:

```bash
git clone https://github.com/EL-TEU-USUARI/United-nerds.git
cd United-nerds
```

### 3. Configurar el Projecte

Instal·la les dependències:

```bash
pnpm install
```

Si no tens `pnpm` instal·lat, pots instal·lar-lo amb:

```bash
npm install -g pnpm
```

### 4. Crear una Branca

Crea una branca nova per a la teva contribució:

```bash
git checkout -b nom-de-la-teva-feina
```

**Consells per al nom de la branca:**
- `fix/nom-del-bug` - Per correccions de bugs
- `feat/nova-funcionalitat` - Per noves funcionalitats
- `docs/millora-documentacio` - Per millores a la documentació
- `style/millora-estils` - Per millores visuals
- `translate/idioma` - Per traduccions

### 5. Fer Canvis

Ara pots fer els teus canvis:

- Edita els fitxers necessaris
- Prova els canvis localment executant `pnpm dev`

### 6. Commit dels Canvis

Fes commit dels teus canvis amb missatges clars i descriptius:

```bash
git add .
git commit -m "Descripció clara del que has fet"
```

**Consells per als missatges de commit:**
- **Escriu-los en anglès**
- Siguen clars i descriptius
- Utilitzen l'imperatiu ("Add feature X" no "Added feature X")
- Siguen concisos (màxim 50 caràcters per a la primera línia)
- **Exemples:**
  - `fix: resolve navigation bar styling issue`
  - `feat: add new About section component`
  - `docs: update README with contribution guidelines`
  - `style: improve button hover effects`

### 7. Push i Pull Request

Puja els canvis al teu fork:

```bash
git push origin nom-de-la-teva-feina
```

Després, crea un Pull Request:

1. Vés al teu fork al GitHub
2. Clica a "Compare & pull request"
3. Completa el formulari del Pull Request:
   - **Títol**: Descripció clara del canvi
   - **Descripció**: Explica què has fet i per què
   - Marca qualsevol issue relacionat amb `closes #número`

### 8. Revisió

El teu Pull Request serà revisat i podria demanar-se't canvis o aclariments. No t'amoïnis, això és part normal del procés!

## 📋 Estil de Codi

Encara que no hi ha un estil estricte definit, intenta:

- Mantenir el codi net i llegible
- Utilitzar noms descriptius per a variables i funcions
- Comentar el codi complex si és necessari
- Seguir l'estil existent del projecte

## 🧪 Provar Abans de Contribuir

Abans de fer el Pull Request, assegura't que:

- ✅ El servidor de desenvolupament funciona: `pnpm dev`
- ✅ Els canvis funcionen correctament
- ✅ No has introduït errors nous

## 💬 Preguntes?

Si tens qualsevol pregunta o dubte:

- Obre una issue al repositori

## 🙏 Gràcies!

Gràcies per considerar contribuir a United nerds. La teva ajuda és molt apreciada i ajuda a fer créixer el moviment per acabar amb la discriminació cap als nerds!
