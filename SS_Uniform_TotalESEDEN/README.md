<div align="center">

<sub>CASE 02 OF 12</sub>

# Simply Supported &middot; Uniform Pressure

### Minimize total ESEDEN

[&larr; Case 01](../SS_Uniform_VM/) &nbsp;&middot;&nbsp; [Case Index](../README.md#case-index) &nbsp;&middot;&nbsp; [Case 03 &rarr;](../SS_Uniform_MaxESEDEN/)

</div>

<br>

| Boundary condition | Loading | Objective |
|:--|:--|:--|
| Simply supported, all edges | Uniform transverse pressure | Minimize total elastic strain energy density (ESEDEN) |

## Optimal Designs

### Honeycomb

<table>
<tr>
<td width="64%" align="center"><img src="../assets/cases/SS_Uniform_TotalESEDEN/HC_optimal.png" width="100%" alt="Optimal honeycomb"><br><sub>Elastic strain energy density, ESEDEN (MPa)</sub></td>
<td width="36%" valign="middle">
<table>
<tr><th>Parameter</th><th>Value</th></tr>
<tr><td align="center">&alpha;</td><td align="right">1.0206</td></tr>
<tr><td align="center">&beta;</td><td align="right">0.43161</td></tr>
<tr><td align="center"><i>t</i></td><td align="right">9 mm</td></tr>
<tr><td align="center"><i>h</i></td><td align="right">39.009 mm</td></tr>
<tr><td align="center">Area fraction</td><td align="right">59.03 %</td></tr>
<tr><td align="center">Shell thickness</td><td align="right">8.39 mm</td></tr>
</table>
</td>
</tr>
</table>

### Spider Web

<table>
<tr>
<td width="64%" align="center"><img src="../assets/cases/SS_Uniform_TotalESEDEN/SW_optimal.png" width="100%" alt="Optimal spider web"><br><sub>Elastic strain energy density, ESEDEN (MPa)</sub></td>
<td width="36%" valign="middle">
<table>
<tr><th>Parameter</th><th>Value</th></tr>
<tr><td align="center"><i>N</i><sub>r</sub></td><td align="right">16</td></tr>
<tr><td align="center"><i>N</i><sub>s</sub></td><td align="right">9</td></tr>
<tr><td align="center"><i>t</i><sub>r</sub></td><td align="right">2 mm</td></tr>
<tr><td align="center"><i>t</i><sub>f</sub></td><td align="right">11 mm</td></tr>
<tr><td align="center">&sigma;<sub>j</sub></td><td align="right">-0.23455</td></tr>
<tr><td align="center"><i>A</i></td><td align="right">6.5148</td></tr>
<tr><td align="center"><i>f</i></td><td align="right">-31.241</td></tr>
<tr><td align="center">&phi;</td><td align="right">-84.589</td></tr>
<tr><td align="center"><i>p</i></td><td align="right">0.10332</td></tr>
<tr><td align="center">Area fraction</td><td align="right">59.43 %</td></tr>
<tr><td align="center">Shell thickness</td><td align="right">8.41 mm</td></tr>
</table>
</td>
</tr>
</table>

<sub>Parameter definitions: [Design Parameterization](../README.md#design-parameterization)</sub>

## Performance Metrics

| Metric | Honeycomb | Spider Web |
|:--|--:|--:|
| Max von Mises stress (MPa) | 740.86 | 731.07 |
| **Total ESEDEN (MPa)** &nbsp;<sup>objective</sup> | 8676.57 | **5224.40** |
| Max ESEDEN (MPa) | 0.7952 | 0.4873 |
| Max displacement (mm) | 2.5507 | 2.2074 |

## Optimization Convergence

<p align="center"><img src="../figures_UQ/UQ_02_SS_Uniform_TotalESEDEN.png" width="100%" alt="Bayesian optimization convergence"></p>

<sub>Left: honeycomb &middot; Right: spider web. Solid line: best observed incumbent objective. Dashed line: Gaussian-process posterior mean. Shaded band: 1.96&sigma; credible interval.</sub>

## Intermediate Spider Web Designs

<details>
<summary><b>Intermediate design 1</b></summary>
<br>

<table>
<tr><th width="33%">von Mises stress (MPa)</th><th width="33%">ESEDEN (MPa)</th><th width="33%">Displacement (mm)</th></tr>
<tr>
<td align="center"><img src="../assets/cases/SS_Uniform_TotalESEDEN/SW_intermediate1_VM.png" width="100%"></td>
<td align="center"><img src="../assets/cases/SS_Uniform_TotalESEDEN/SW_intermediate1_ESEDEN.png" width="100%"></td>
<td align="center"><img src="../assets/cases/SS_Uniform_TotalESEDEN/SW_intermediate1_U.png" width="100%"></td>
</tr>
</table>

</details>

<details>
<summary><b>Intermediate design 2</b></summary>
<br>

<table>
<tr><th width="33%">von Mises stress (MPa)</th><th width="33%">ESEDEN (MPa)</th><th width="33%">Displacement (mm)</th></tr>
<tr>
<td align="center"><img src="../assets/cases/SS_Uniform_TotalESEDEN/SW_intermediate2_VM.png" width="100%"></td>
<td align="center"><img src="../assets/cases/SS_Uniform_TotalESEDEN/SW_intermediate2_ESEDEN.png" width="100%"></td>
<td align="center"><img src="../assets/cases/SS_Uniform_TotalESEDEN/SW_intermediate2_U.png" width="100%"></td>
</tr>
</table>

</details>

---

<div align="center">

[&larr; Case 01](../SS_Uniform_VM/) &nbsp;&middot;&nbsp; [Case Index](../README.md#case-index) &nbsp;&middot;&nbsp; [Case 03 &rarr;](../SS_Uniform_MaxESEDEN/)

</div>
