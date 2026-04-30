# ProLaia 💪

App d'entrenadora personal per a la Laia Millans. Gestiona clients, sessions, exercicis i factures des de qualsevol dispositiu.

🔗 **App:** `https://marcnavarrop.github.io/prolaia/`

---

## Què fa

- 📅 Agenda setmanal de sessions amb estats (feta / cancel·lada / pendent)
- 👥 Gestió de clients Vindi i Entrenar per BCN
- 💪 Planificació d'exercicis amb historial del client i plantilles
- 🧾 Factures automàtiques format oficial Vindi (PDF) amb enviament per email
- ☁️ Sincronització en temps real entre mòbil i ordinador via Supabase
- 🔒 Accés protegit amb PIN

---

## Tecnologia

| Què | Com |
|-----|-----|
| Interfície | HTML + CSS + JS (un sol fitxer) |
| Base de dades | Supabase |
| Allotjament | GitHub Pages |

---

## Actualitzar el codi

1. Ves al repositori → **"Add file" → "Upload files"**
2. Puja el nou `index.html`
3. **"Commit changes"**
4. Espera 1-2 minuts

> Les dades dels clients i sessions **no es perden** en actualitzar. Estan a Supabase, separades del codi.

---

## Canvis habituals

**Canviar el PIN** → App → ⚙️ Configuració → 🔒 Canviar PIN  
**Canviar preus** → App → 🧾 Factures → edita els camps → ✓ Desar preus  
**Restaurar dades** → App → ⚙️ Configuració → Historial de còpies → ↩ Restaurar
