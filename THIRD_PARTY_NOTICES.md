# Third-party design references

This build uses no third-party runtime dependency. Its material/lighting layer was independently implemented after reviewing two MIT-licensed projects:

- **AmbientCSS** by kikkupico — MIT. Referenced for the architectural idea of one coherent light source driving surface highlights and shadows. No package or source code is bundled.
- **Plasma UI** by Crux Garden — MIT. Referenced for liquid-glass material concepts, quality budgeting, reduced-motion awareness, and interaction language. Its React/WebGL runtime is not bundled because the source artifact is a zero-dependency standalone document and already had GPU/animation pressure.

Retain upstream copyright/license notices if you later copy or vendor substantial portions of either project. This build deliberately does not do so.
