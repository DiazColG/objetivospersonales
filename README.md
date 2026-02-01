# 🎯 Goal Tracker - OKRs + Traction

Tracker minimalista de objetivos combinando OKRs y metodología Traction.

## ✨ Features

- ✅ **Visión Anual**: Define tu norte
- ✅ **Rocks del Trimestre**: 3-7 prioridades (90 días)
- ✅ **Key Results**: Medibles y trackables
- ✅ **Progress Tracking**: Barra de progreso por Rock
- ✅ **Storage Persistente**: Data guardada entre sesiones
- ✅ **Stats Dashboard**: Vista rápida de tu progreso

## 🚀 Deploy en Vercel

### Opción 1: GitHub + Vercel
1. Sube estos archivos a un repo de GitHub
2. Conecta el repo en vercel.com
3. Deploy automático

### Opción 2: Vercel CLI
```bash
npm i -g vercel
vercel
```

### Opción 3: Drag & Drop
Arrastra la carpeta a vercel.com

## 📖 Cómo usar

### 1. Define tu Visión
Escribe dónde quieres estar al final del año.

### 2. Agrega Rocks
Tus 3-7 prioridades del trimestre. Ejemplos:
- "Lanzar MVP del producto"
- "Conseguir primeros 100 clientes"
- "Mejorar salud: 3x gym/semana"

### 3. Agrega Key Results
Para cada Rock, define resultados medibles:
- ✅ "Tener 5 usuarios beta testeando"
- ✅ "10 entrevistas con clientes potenciales"
- ✅ "Landing page con >100 visitas/semana"

### 4. Trackea Progreso
Marca KRs completados. La barra de progreso se actualiza automáticamente.

## 🔧 Para seguir desarrollando con Copilot

Sugerencias de features que puedes agregar:

### Scorecard Semanal
```javascript
// Agrega métricas semanales
const metrics = [
  { name: 'Ventas', target: 10, current: 7 },
  { name: 'Leads', target: 50, current: 45 }
];
```

### L10 Check-in
```javascript
// Weekly review template
const l10 = {
  wins: [],
  issues: [],
  todos: []
};
```

### Export/Import
```javascript
const exportData = async () => {
  const data = { vision, rocks };
  // Download as JSON
};
```

### Quarterly Archive
```javascript
// Guarda trimestres pasados
const quarters = ['Q1-2026', 'Q4-2025'];
```

## 🎨 Diseño

- Minimalista y funcional
- IBM Plex Sans (legible y profesional)
- Colores neutros con acentos azules
- Sin distracciones

## 💾 Storage

Usa el Artifact Storage API de Vercel:
- Persiste entre sesiones
- No requiere backend
- Gratis

---

**Metodología**: Inspirado en OKRs (Google) + Traction/EOS (Gino Wickman)
