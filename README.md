# CNC Slicer · bêta V0.2

**FR** — Page web qui transforme le plan d'une pièce (points saisis, DXF/SVG/STL de Fusion 360, ou photo calée) en Gcode de détourage pour une fraiseuse CNC 3 axes, avec simulation 3D de l'usinage. Tout est calculé dans le navigateur : aucun fichier n'est envoyé.

**EN** — Web page that turns a part drawing (typed points, Fusion 360 DXF/SVG/STL, or a calibrated photo) into contour-cutting G-code for a 3-axis CNC router, with a 3D machining simulation. Everything runs in the browser: no file is uploaded.

👉 **https://alexb0311.github.io/cnc-slicer/**

## Fonctions / Features
- Contour de la pièce décalé du rayon de fraise, trous détectés automatiquement · Part outline offset by the cutter radius, holes detected automatically
- Passes en Z, arcs G2/G3 (R ou I J), origine X0 Y0 Z0 réglable · Z step-downs, G2/G3 arcs (R or I J), adjustable X0 Y0 Z0 origin
- Simulation 3D de l'enlèvement de matière, code couleur du Gcode · 3D material-removal simulation, colour-coded G-code
- Français / English, thème clair / sombre · French / English, light / dark theme

## Exemples / Examples
`exemples/Exemple-Arrondis-Trou.dxf` : carré à congés R8 et trou Ø20, à importer dans l'onglet DXF / SVG · rounded square (R8 fillets) with a Ø20 hole, to import in the DXF / SVG tab. `exemples/Exemple-Plaque-Trou.stl` : plaque 60 × 40 × 3 mm avec trou Ø10, coupée à mi-épaisseur · 60 × 40 × 3 mm plate with a Ø10 hole, cut at mid-thickness. La page contient aussi un exemple intégré (plaque à congés) · The page also has a built-in example (filleted plate).

## ⚠️ Sécurité / Safety
Relisez le Gcode et regardez la simulation avant d'usiner. Outil en version bêta, fourni sans garantie. · Read the G-code and watch the simulation before machining. Beta tool, provided without warranty.

---
© 2026 Alexandre BARAKAT · CREAO TECH — tous droits réservés / all rights reserved.
