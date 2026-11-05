# Lesson 7  Read the axes and legend in an original figure

For slide 27. Use this enlargement in print. Ohyama et al. (2013), Figure 3(a), concerns March–May temperature in northeastern Asia.

![Panel (a), cropped from the original. Horizontal axis: calendar year. Both vertical axes use °C, but represent differently processed series and different scales.](assets/ohyama_fig3a.png)
[Ohyama et al., 2013, Fig. 3(a). CC BY 3.0.](https://doi.org/10.5194/cp-9-261-2013)

| Line | Axis and meaning |
| --- | --- |
| Solid black | Left: estimated temperature |
| Dotted black | Left: filtered observations |
| Dotted orange | Right: unfiltered observations |

**Identify the appropriate axis before comparing values. Does agreement in this panel establish predictive performance for unseen years?**

This is the 1887–1990 calibration fit, not an independent validation plot. Vertical separation of lines on different axes is not directly a temperature difference.

[Ohyama et al. (2013), Fig. 3(a), CC BY 3.0](https://doi.org/10.5194/cp-9-261-2013)


<!-- pagebreak -->

# Lesson 7  What does CE compare?

## In one sentence

The coefficient of efficiency, CE, measures the reduction in squared prediction error relative to predicting the verification-period observed mean in every year.

CE = 1 − Σ(observed − predicted)² / Σ(observed − verification mean)²

| CE | Interpretation |
| --- | --- |
| 1 | Perfect predictions for these verification data |
| 0 | Same squared error as the verification-mean benchmark |
| Negative | Larger squared error than that benchmark |

The mean is a retrospective benchmark used to assess predictions; it is not assumed to be known when forecasting unseen years. The expression is undefined if the observed verification series is constant.

**Table 2 reports split-period CE values of 0.019 and −0.040. Do both support a stable reconstruction? Distinguish the roles of Figure 3(a) and Table 2.**

## Check

The first represents only a small improvement over the benchmark; the second performs worse. A convincing calibration plot cannot substitute for independent testing. Consider periods, processing and validation design. The processed series in this study also cannot directly recover the long-term warming trend.

[Ohyama et al. (2013), Table 2](https://doi.org/10.5194/cp-9-261-2013)
