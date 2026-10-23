<div align="center">

<sub>CASE 10 OF 12</sub>

# Clamped &middot; Non-Uniform Pressure

### Minimize maximum von Mises stress

[&larr; Case 09](../CC_Uniform_MaxESEDEN/) &nbsp;&middot;&nbsp; [Case Index](../README.md#case-index) &nbsp;&middot;&nbsp; [Case 11 &rarr;](../CC_NonUniform_TotalESEDEN/)

</div>

<br>

| Boundary condition | Loading | Objective |
|:--|:--|:--|
| Clamped, all edges | Non-uniform transverse pressure, <i>P</i>(<i>x</i>,<i>y</i>) &prop; <i>x</i><sup>2</sup> + <i>y</i><sup>2</sup> | Minimize maximum von Mises stress |

## Optimal Designs

### Honeycomb

<table>
<tr>
<td width="64%" align="center"><img src="../assets/cases/CC_NonUniform_VM/HC_optimal.png" width="100%" alt="Optimal honeycomb"><br><sub>von Mises stress (MPa)</sub></td>
<td width="36%" valign="middle">
<table>
<tr><th>Parameter</th><th>Value</th></tr>
<tr><td align="center">&alpha;</td><td align="right">1.5759</td></tr>
<tr><td align="center">&beta;</td><td align="right">0.73028</td></tr>
<tr><td align="center"><i>t</i></td><td align="right">9 mm</td></tr>
<tr><td align="center"><i>h</i></td><td align="right">31.281 mm</td></tr>
<tr><td align="center">Area fraction</td><td align="right">59.77 %</td></tr>
<tr><td align="center">Shell thickness</td><td align="right">8.42 mm</td></tr>
</table>
</td>
</tr>
</table>

### Spider Web

<table>
<tr>
<td width="64%" align="center"><img src="../assets/cases/CC_NonUniform_VM/SW_optimal.png" width="100%" alt="Optimal spider web"><br><sub>von Mises stress (MPa)</sub></td>
<td width="36%" valign="middle">
<table>
<tr><th>Parameter</th><th>Value</th></tr>
<tr><td align="center"><i>N</i><sub>r</sub></td><td align="right">18</td></tr>
<tr><td align="center"><i>N</i><sub>s</sub></td><td align="right">2</td></tr>
<tr><td align="center"><i>t</i><sub>r</sub></td><td align="right">6 mm</td></tr>
<tr><td align="center"><i>t</i><sub>f</sub></td><td align="right">12 mm</td></tr>
<tr><td align="center">&sigma;<sub>j</sub></td><td align="right">0.17202</td></tr>
<tr><td align="center"><i>A</i></td><td align="right">7.7598</td></tr>
<tr><td align="center"><i>f</i></td><td align="right">64.030</td></tr>
<tr><td align="center">&phi;</td><td align="right">6.784</td></tr>
<tr><td align="center"><i>p</i></td><td align="right">2.9218</td></tr>
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
| **Max von Mises stress (MPa)** &nbsp;<sup>objective</sup> | **272.80** | 325.84 |
| Total ESEDEN (MPa) | 288.68 | 212.55 |
| Max ESEDEN (MPa) | 0.0801 | 0.1011 |
| Max displacement (mm) | 0.2966 | 0.2662 |

## Optimization Convergence

<p align="center"><img src="../figures_UQ/UQ_10_CC_NonUniform_VM.png" width="100%" alt="Bayesian optimization convergence"></p>

<sub>Left: honeycomb &middot; Right: spider web. Solid line: best observed incumbent objective. Dashed line: Gaussian-process posterior mean. Shaded band: 1.96&sigma; credible interval.</sub>

---

<div align="center">

[&larr; Case 09](../CC_Uniform_MaxESEDEN/) &nbsp;&middot;&nbsp; [Case Index](../README.md#case-index) &nbsp;&middot;&nbsp; [Case 11 &rarr;](../CC_NonUniform_TotalESEDEN/)

</div>
