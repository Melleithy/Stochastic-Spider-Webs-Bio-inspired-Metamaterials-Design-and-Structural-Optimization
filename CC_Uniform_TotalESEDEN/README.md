<div align="center">

<sub>CASE 08 OF 12</sub>

# Clamped &middot; Uniform Pressure

### Minimize total ESEDEN

[&larr; Case 07](../CC_Uniform_VM/) &nbsp;&middot;&nbsp; [Case Index](../README.md#case-index) &nbsp;&middot;&nbsp; [Case 09 &rarr;](../CC_Uniform_MaxESEDEN/)

</div>

<br>

| Boundary condition | Loading | Objective |
|:--|:--|:--|
| Clamped, all edges | Uniform transverse pressure | Minimize total elastic strain energy density (ESEDEN) |

## Optimal Designs

### Honeycomb

<table>
<tr>
<td width="64%" align="center"><img src="../assets/cases/CC_Uniform_TotalESEDEN/HC_optimal.png" width="100%" alt="Optimal honeycomb"><br><sub>Elastic strain energy density, ESEDEN (MPa)</sub></td>
<td width="36%" valign="middle">
<table>
<tr><th>Parameter</th><th>Value</th></tr>
<tr><td align="center">&alpha;</td><td align="right">1.0338</td></tr>
<tr><td align="center">&beta;</td><td align="right">0.15278</td></tr>
<tr><td align="center"><i>t</i></td><td align="right">7 mm</td></tr>
<tr><td align="center"><i>h</i></td><td align="right">31.742 mm</td></tr>
<tr><td align="center">Area fraction</td><td align="right">57.05 %</td></tr>
<tr><td align="center">Shell thickness</td><td align="right">8.29 mm</td></tr>
</table>
</td>
</tr>
</table>

### Spider Web

<table>
<tr>
<td width="64%" align="center"><img src="../assets/cases/CC_Uniform_TotalESEDEN/SW_optimal.png" width="100%" alt="Optimal spider web"><br><sub>Elastic strain energy density, ESEDEN (MPa)</sub></td>
<td width="36%" valign="middle">
<table>
<tr><th>Parameter</th><th>Value</th></tr>
<tr><td align="center"><i>N</i><sub>r</sub></td><td align="right">12</td></tr>
<tr><td align="center"><i>N</i><sub>s</sub></td><td align="right">23</td></tr>
<tr><td align="center"><i>t</i><sub>r</sub></td><td align="right">2 mm</td></tr>
<tr><td align="center"><i>t</i><sub>f</sub></td><td align="right">7 mm</td></tr>
<tr><td align="center">&sigma;<sub>j</sub></td><td align="right">-0.16330</td></tr>
<tr><td align="center"><i>A</i></td><td align="right">1.0835</td></tr>
<tr><td align="center"><i>f</i></td><td align="right">-3.2448</td></tr>
<tr><td align="center">&phi;</td><td align="right">-87.266</td></tr>
<tr><td align="center"><i>p</i></td><td align="right">0.10426</td></tr>
<tr><td align="center">Area fraction</td><td align="right">57.49 %</td></tr>
<tr><td align="center">Shell thickness</td><td align="right">8.32 mm</td></tr>
</table>
</td>
</tr>
</table>

<sub>Parameter definitions: [Design Parameterization](../README.md#design-parameterization)</sub>

## Performance Metrics

| Metric | Honeycomb | Spider Web |
|:--|--:|--:|
| Max von Mises stress (MPa) | 768.85 | 496.84 |
| **Total ESEDEN (MPa)** &nbsp;<sup>objective</sup> | 2089.54 | **570.79** |
| Max ESEDEN (MPa) | 0.5564 | 0.2319 |
| Max displacement (mm) | 0.8699 | 0.4626 |

## Optimal Spider Web &middot; Field Outputs

<table>
<tr><th width="33%">ESEDEN (MPa)</th><th width="33%">von Mises stress (MPa)</th><th width="33%">Displacement (mm)</th></tr>
<tr>
<td align="center"><img src="../assets/cases/CC_Uniform_TotalESEDEN/SW_optimal.png" width="100%"></td>
<td align="center"><img src="../assets/cases/CC_Uniform_TotalESEDEN/SW_optimal_VM.png" width="100%"></td>
<td align="center"><img src="../assets/cases/CC_Uniform_TotalESEDEN/SW_optimal_U.png" width="100%"></td>
</tr>
</table>

## Optimization Convergence

<p align="center"><img src="../figures_UQ/UQ_08_CC_Uniform_TotalESEDEN.png" width="100%" alt="Bayesian optimization convergence"></p>

<sub>Left: honeycomb &middot; Right: spider web. Solid line: best observed incumbent objective. Dashed line: Gaussian-process posterior mean. Shaded band: 1.96&sigma; credible interval.</sub>

---

<div align="center">

[&larr; Case 07](../CC_Uniform_VM/) &nbsp;&middot;&nbsp; [Case Index](../README.md#case-index) &nbsp;&middot;&nbsp; [Case 09 &rarr;](../CC_Uniform_MaxESEDEN/)

</div>
