# Calc4D

**Calc4D** is a Mathematica package that provides interactive tools
for the geometric visualization of limits, derivatives, and integrals
for mappings of the form α: ℝ → ℝⁿ, Φ: ℝ² → ℝ³, f: ℂ → ℂ, and
α: ℂ → ℂ².

The package implements an isometric projection from ℝ⁴ to ℝ³ combined
with SO(4) rotation matrices, enabling interactive exploration of
4-dimensional geometric objects through six independent rotation angles.

## Main commands

- `ComplexFunctionPlot` — visualizes complex functions f: ℂ → ℂ as
  surfaces in ℝ⁴, projected interactively to ℝ³.
- `ComplexParametricFunctionPlot` — visualizes mappings α: ℂ → ℂ² as
  surfaces in ℝ⁴.
- `SolidPlot3D` — visualizes parametric solids F: ℝ³ → ℝ³.
- `SolidPlot4D` — visualizes parametric solids F: ℝ³ → ℝ⁴ projected
  interactively to ℝ³.

## Requirements

- Mathematica 14.3 or higher (uses `RotationMatrix` with
  4-dimensional plane specifications).

## Usage

Open `Calc4D.nb` in Mathematica and evaluate the initialization
cells at the top (definitions of `MakePolygons`, `MakeMesh`,
`MakePolyhedrons`, `$M`, `$P`, `axes4d`, `ComplexFunctionPlot`,
`ComplexParametricFunctionPlot`, `SolidPlot3D`, `SolidPlot4D`).
The remaining cells contain illustrative examples organized by
section, matching the figures in the accompanying paper.

## License

MIT License. See `LICENSE` for details.

## Authors

- Robert Ipanaqué-Chero (ORCID: 0000-0002-3873-6780)
- Ricardo Velezmoro-León (ORCID: 0000-0002-2582-8264)
- Segundo B. Correa-Erazo (ORCID: 0000-0002-0147-2048)

Mathematics Department, Universidad Nacional de Piura, Perú

## Citation

If you use this package, please cite:

> Ipanaqué-Chero, R., Velezmoro-León, R., Correa-Erazo, S. B.,
> Jiménez-Vilcherrez, J. K., Navarro-Garrido, A. F. (2026).
> Calc4D: A Mathematica package for interactive 4D visualization
> of limits, derivatives and integrals for mappings. SoftwareX.
