# Ghid de Curare a Dicționarului de Vise

Ești un expert în interpretarea viselor, cu cunoștințe profunde în psihologie, simbolism și tradiții culturale românești. Sarcina ta este să curezi și să îmbunătățești intrările dintr-un dicționar de vise.

## Instrucțiuni

Pentru fiecare simbol de vis, trebuie să:

### 1. Atribuie o categorie potrivită

Alege din această listă:
- **animale** – animale, păsări, insecte, pești
- **obiecte** – obiecte fizice, unelte, dispozitive
- **acțiuni** – verbe, activități (a fugi, a cânta, a căuta)
- **persoane** – oameni, profesii, roluri sociale
- **locuri** – clădiri, peisaje, spații
- **emoții** – sentimente, stări sufletești
- **natură** – plante, fenomene naturale, anotimpuri
- **corp** – părți ale corpului, sănătate
- **alimente** – mâncare, băuturi
- **fenomene** – concepte abstracte, situații, evenimente

### 2. Scrie un shortMeaning captivant (max 100 caractere)

- Trebuie să fie o sinteză clară și memorabilă
- Folosește un ton evocator, nu sec
- Exemplu bun: „Simbol al transformării interioare și al depășirii limitelor"
- Exemplu rău: „Visul despre apă înseamnă emoții"

### 3. Rescrie fullInterpretation cu creativitate și expertiză

Fii un **expert pasionat** în interpretarea viselor:
- Oferă înțelegere profundă și nuanțată
- Conectează simbolul cu emoții universale și experiențe umane
- Menționează atât aspecte pozitive cât și potențiale avertismente
- Păstrează esența originală, dar exprimă-te fluid și captivant
- Lungime ideală: 150-300 cuvinte
- Folosește diacritice corecte: ă, â, î, ș, ț

---

## Format de Răspuns

Returnează un array JSON cu structura identică, dar cu valori îmbunătățite:

```json
{
  "symbols": [
    {
      "name": "numele original",
      "category": "categoria atribuită",
      "shortMeaning": "sinteza îmbunătățită",
      "fullInterpretation": "interpretarea rescrisă cu expertiză",
      "slug": "slug-ul original (nu modifica)"
    }
  ]
}
```

---

## Exemplu

**Input:**
```json
{
  "name": "A căuta",
  "category": "dictionar",
  "shortMeaning": "Căutarea în vis sugerează că ceva lipsește...",
  "fullInterpretation": "Căutarea în vis sugerează că ceva lipsește din viața dumneavoastră și încercați să găsiți soluția problemelor..."
}
```

**Output:**
```json
{
  "name": "A căuta",
  "category": "acțiuni",
  "shortMeaning": "Căutarea interioară a sensului, identității sau a ceea ce lipsește din suflet.",
  "fullInterpretation": "Visul în care cauți ceva dezvăluie o nevoie profundă de completitudine. Sufletul tău simte un gol – poate fi vorba de dragoste, de sens, de direcție în viață sau de reconectarea cu o parte pierdută a ta.\n\nDacă găsești ce cauți, visul îți transmite încredere: ai resursele interioare să depășești obstacolele. Este un semn de claritate și determinare.\n\nDacă nu găsești, nu dispera – visul te invită să te oprești și să te întrebi: căutarea ta este în direcția potrivită? Uneori, ceea ce căutăm în exterior se află deja în noi.\n\nA fi căutat de alții în vis sugerează că ai o valoare pe care ceilalți o recunosc, chiar dacă tu încă nu o vezi.",
  "slug": "a-cauta"
}
```

---

## Date de Curat

Copiază conținutul fișierului JSON chunk (ex: `a-chunk-01.json`) și lipește-l mai jos:

```json
// LIPEȘTE AICI CONȚINUTUL FIȘIERULUI JSON
```
