# CDCO Release Notes

Crystallographic Defect Core Ontology (CDCO)

---

## v0.2.0 (current)

No structural changes relative to v0.2.0. This release includes minor annotation and metadata updates.

---

## v0.2.0

This release extends the defect relationship vocabulary to support defect complexes and relative spatial positioning of defects.

### New Object Properties (1)
- `isPartOfDefectComplex` — inverse of `hasDefectComplex`; allows a defect instance to assert membership in a defect complex

### New Datatype Properties (1)
- `hasRelativeDefectDistance` — numeric value capturing the relative distance between defects within a complex

---

## v0.0.1

Initial release of CDCO.

### Classes (7)
Core defect type hierarchy: `Material`, `CrystallineMaterial`, `CrystallographicDefect`, `PointDefect`, `LineDefect`, `PlanarDefect`, `DefectComplex`

### Object Properties (2)
`hasCrystallographicDefect` — links a crystalline material to its defects
`hasDefectComplex` — links individual defects into a complex
