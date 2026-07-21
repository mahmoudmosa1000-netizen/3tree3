# 🌳 Tree of Knowledge

**Ein begehbares 3D-Universum aus 35 Philosophen** — Node-Netzwerk, Ollama-KI, Lernwerkzeuge, alles in einer einzigen HTML-Datei.

---

## Sofort starten

```bash
# Einfach doppelklicken oder im Browser öffnen:
index.html
```

Kein Server, kein Build-Schritt, keine Installation. Optional: [Ollama](https://ollama.ai) lokal laufen lassen für KI-Chat und den Wissensgraphen.

```bash
ollama pull llama3              # für KI-Chat mit Philosophen
ollama pull nomic-embed-text    # für den KI-Wissensgraph
OLLAMA_ORIGINS=* ollama serve
```

---

## Features

### 🌳 3D-Hauptszene
Foto-basierter, begehbarer Baum. WASD-Steuerung, Maus-Look, Klick auf einen Philosophen fliegt automatisch hin. 35 Philosophen sitzen auf den echten Astspitzen des Bildes.

### 🎮 Quiz
Drei Fragetypen (Zitat, Idee, Epoche), Serie-Tracking, persistenter Fortschritt.

### 🕸 Mind Map
Eigenständige Kraft-Simulation zeigt die kuratierten Einfluss-Beziehungen zwischen allen Philosophen. Ziehen, zoomen, anklicken.

### 🌌 Knowledge Galaxy
Alle Philosophen als Sterne, nach Epoche in Sternhaufen gruppiert. Konstellationslinien zeigen gemeinsame Ideen quer über Epochengrenzen.

### 📚 Hauptwerke
Jeder Philosoph hat 1–3 zentrale Werke mit Jahr hinterlegt (68 Werke insgesamt).

### 🎓 Lernkarten
Automatisch aus Zitaten, Ideen und Werken generiert (~95 Karten). 3D-Flip-Animation, „Weiß ich" / „Nochmal üben"-Tracking.

### 📖 Digitale Bibliothek
Jedes Werk verlinkt direkt zu Project Gutenberg und Internet Archive für kostenlose Volltexte.

### 🗺 Geo-Karte
Echte Weltkarte (Leaflet + OpenStreetMap) mit den recherchierten Geburtsorten aller 35 Philosophen.

### 🧠 KI-Wissensgraph
Berechnet **lokal via Ollama-Embeddings**, welche Philosophen sich inhaltlich am ähnlichsten sind — unabhängig von den kuratierten Einfluss-Daten. Findet verborgene Gedankenverwandtschaften über Epochengrenzen hinweg. Kein OpenAI-Key nötig, Ergebnis wird gecacht.

### 🦙 KI-Chat
Jeder Philosoph antwortet in seiner eigenen Stimme, gestreamt via lokales Ollama.

---

## Tastaturkürzel

| Taste | Aktion |
|---|---|
| `W A S D` | Fliegen |
| `Maus-Drag` | Umsehen |
| `Klick` auf Knoten | Philosoph besuchen |
| `1`–`4` | Quiz-Antwort wählen |
| `←` `→` | Lernkarten blättern |
| `Space` | Lernkarte umdrehen |
| `ESC` | Aktives Overlay schließen |

---

## Deployment

**GitHub Pages** — automatisch via `.github/workflows/pages.yml` bei jedem Push auf `main`.

**Andere Hosts** — `index.html` ist eine einzelne Datei, läuft überall (Netlify, Vercel, eigener Server, USB-Stick).

---

*„Ideas grow like trees. Every philosopher is a fruit of human thought."*
