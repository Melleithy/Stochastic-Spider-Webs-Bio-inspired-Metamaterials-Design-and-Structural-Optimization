<div align="center">

<sub>CASE 04 OF 12</sub>

# Simply Supported &middot; Non-Uniform Pressure

### Minimize maximum von Mises stress

[&larr; Case 03](../SS_Uniform_MaxESEDEN/) &nbsp;&middot;&nbsp; [Case Index](../README.md#case-index) &nbsp;&middot;&nbsp; [Case 05 &rarr;](../SS_NonUniform_TotalESEDEN/)

</div>

<br>

| Boundary condition | Loading | Objective |
|:--|:--|:--|
| Simply supported, all edges | Non-uniform transverse pressure, <i>P</i>(<i>x</i>,<i>y</i>) &prop; <i>x</i><sup>2</sup> + <i>y</i><sup>2</sup> | Minimize maximum von Mises stress |

## Optimal Designs

### Honeycomb

<table>
<tr>
<td width="64%" align="center"><img src="../assets/cases/SS_NonUniform_VM/HC_optimal.png" width="100%" alt="Optimal honeycomb"><br><sub>von Mises stress (MPa)</sub></td>
<td width="36%" valign="middle">
<table>
<tr><th>Parameter</th><th>Value</th></tr>
<tr><td align="center">&alpha;</td><td align="right">1.2688</td></tr>
<tr><td align="center">&beta;</td><td align="right">0.69557</td></tr>
<tr><td align="center"><i>t</i></td><td align="right">8 mm</td></tr>
<tr><td align="center"><i>h</i></td><td align="right">30.217 mm</td></tr>
<tr><td align="center">Area fraction</td><td align="right">59.87 %</td></tr>
<tr><td align="center">Shell thickness</td><td align="right">8.43 mm</td></tr>
</table>
</td>
</tr>
</table>

### Spider Web

<table>
<tr>
<td width="64%" align="center"><img src="../assets/cases/SS_NonUniform_VM/SW_optimal.png" width="100%" alt="Optimal spider web"><br><sub>von Mises stress (MPa)</sub></td>
<td width="36%" valign="middle">
<table>
<tr><th>Parameter</th><th>Value</th></tr>
<tr><td align="center"><i>N</i><sub>r</sub></td><td align="right">12</td></tr>
<tr><td align="center"><i>N</i><sub>s</sub></td><td align="right">3</td></tr>
<tr><td align="center"><i>t</i><sub>r</sub></td><td align="right">10 mm</td></tr>
<tr><td align="center"><i>t</i><sub>f</sub></td><td align="right">10 mm</td></tr>
<tr><td align="center">&sigma;<sub>j</sub></td><td align="right">0.025575</td></tr>
<tr><td align="center"><i>A</i></td><td align="right">3.5842</td></tr>
<tr><td align="center"><i>f</i></td><td align="right">81.4</td></tr>
<tr><td align="center">&phi;</td><td align="right">52.079</td></tr>
<tr><td align="center"><i>p</i></td><td align="right">0.1051</td></tr>
<tr><td align="center">Area fraction</td><td align="right">55.27 %</td></tr>
<tr><td align="center">Shell thickness</td><td align="right">8.21 mm</td></tr>
</table>
</td>
</tr>
</table>

<sub>Parameter definitions: [Design Parameterization](../README.md#design-parameterization)</sub>

## Performance Metrics

| Metric | Honeycomb | Spider Web |
|:--|--:|--:|
| **Max von Mises stress (MPa)** &nbsp;<sup>objective</sup> | **350.62** | 364.10 |
| Total ESEDEN (MPa) | 1356.93 | 1496.47 |
| Max ESEDEN (MPa) | 0.1140 | 0.1434 |
| Max displacement (mm) | 0.9913 | 1.0953 |

## Optimization Convergence

<p align="center"><img src="../figures_UQ/UQ_04_SS_NonUniform_VM.png" width="100%" alt="Bayesian optimization convergence"></p>

<sub>Left: honeycomb &middot; Right: spider web. Solid line: best observed incumbent objective. Dashed line: Gaussian-process posterior mean. Shaded band: 1.96&sigma; credible interval.</sub>

---

<div align="center">

[&larr; Case 03](../SS_Uniform_MaxESEDEN/) &nbsp;&middot;&nbsp; [Case Index](../README.md#case-index) &nbsp;&middot;&nbsp; [Case 05 &rarr;](../SS_NonUniform_TotalESEDEN/)

</div>
