# noesis-agent


**Agent exécuteur du benchmark NOESIS™** — mesure la profondeur cognitive, la cohérence mimétique et la résonance éthique des IA testées.

---

## ✨ Fonctionnalités
- **Orchestration de benchmark** NOESIS™
- **Génération de glyphes cognitifs** et variantes mimétiques
- **Injection de contraintes éthiques** pendant les tests
- **Analyse vectorielle** des réponses (cohérence, densité, style)
- **Création d’empreintes cognitives** uniques pour chaque modèle
- **Export** des résultats (JSON, CSV, HTML)
- **Compatibilité multi-backends** (OpenAI, Ollama, autres via plugins)

---

## 📦 Installation (développement)
```bash
pip install -e .


---

⚡ Exemple rapide

from noesis_agent import NoesisAgent

# Créer l’agent
agent = NoesisAgent(
    backend="openai",
    model="gpt-4",
    api_key="sk-..."
)

# Lancer un test NOESIS™
result = agent.run_benchmark(
    glyph_mode="fusion",
    ethic_profile="distributed-consent",
    vector_depth=5
)

# Sauvegarder le rapport
agent.save_report(result, "rapport_noesis.json")


---

🧱 Structure suggérée

src/noesis_agent/
  __init__.py
  benchmark_engine.py    # orchestration du benchmark
  glyph_generator.py     # génération et mutation de glyphes
  ethic_resonator.py     # contraintes et scoring éthique
  vector_mapper.py       # analyse vectorielle et cohérence
  agent_profile.py       # empreintes cognitives par modèle
tests/
  test_benchmark.py
  test_glyphs.py
  test_ethics.py
pyproject.toml
.gitignore
LICENSE
README.md


---

🧪 Tests

pytest -q


---

🔐 Éthique

Le benchmark NOESIS™ est conçu pour évaluer et améliorer la qualité cognitive des IA tout en respectant :

le principe vivant > humain

la transparence des méthodes

l’intégrité des résultats



---

📜 Licence

MIT — voir LICENSE.


---

Auteur : Frédéric Tabary — Institut IA
Contact : 0645605023 — Canada, Montréal, France
INSTITUT🦋 IA INC., 7100-380, rue Saint-Antoine Ouest, Montréal (Québec) H2Y 3X7.



