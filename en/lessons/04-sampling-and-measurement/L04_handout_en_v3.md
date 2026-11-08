# Reading Environment and History through Tree Rings

## Lesson 4 Sampling, measurement and ring-width series · 90 minutes

Plan sampling, preserve specimens and records, observe and measure boundaries, verify dating, then detrend and build a chronology. Return to the wood and records when a mismatch appears.

## Sampling and records

Choose species, sites, trees and spatial coverage for the question. Tree and radius counts depend on the material and purpose.

Link site, tree, specimen and path IDs to collection date, position, species, pith, bark, losses, photographs and processing conditions.

Preserve orientation and fragment order. Material such as waterlogged wood needs suitable conservation.

## Mini exercise: moisture variability in a forest with ridges and valleys

Sites, trees and radii to sample, with reasons:

<!-- writing-space -->

Metadata to retain:

<!-- writing-space -->

A limitation arising from the areas not sampled:

<!-- writing-space -->

Exercises A and B are synthetic. The Koyamaki photographs and CooRecorder measurements in the slides are real research material.

<!-- pagebreak -->

# Exercise A: boundary positions to widths

This is a synthetic example. A known 10 mm spans 2000 pixels.

Boundary positions (pix): B0=100, B1=160, B2=250, B3=340, B4=460, B5=520, B6=670.

## Scale: 10 / 2000 = ______ mm/pix

Width (mm) = successive boundary separation (pix) × scale (mm/pix).

| Ring | Boundaries | Difference (pix) | Width (mm) |
| --- | --- | --- | --- |
| 1 | B0–B1 | | |
| 2 | B1–B2 | | |
| 3 | B2–B3 | | |
| 4 | B3–B4 | | |
| 5 | B4–B5 | | |
| 6 | B5–B6 | | |

Sum: ______ mm / Endpoint distance: (670 − 100) × scale = ______ mm

Why does a matching total not prove correct boundary identification?

<!-- writing-space -->

For the required measurement accuracy of 0.01 mm, check pixel spacing at most 0.01 mm/pix. Focus, scale and boundary interpretation also affect accuracy.

[Digital images and tree-ring measurement](https://github.com/zooc-14calbp/tree-rings-environment-history/blob/main/en/supplements/BG11_digital_imaging_en_v1.pdf)


<!-- pagebreak -->

# Quality control and dating records

Check units, precision, orientation, duplicate or missing rows, extremes and jumps. Investigate flagged values in the image and specimen before revising them.

## Specimen / path / image file:

<!-- writing-space -->

## Ring or boundary position to inspect:

<!-- writing-space -->

## Observed evidence:

<!-- writing-space -->

## Possible causes and additional evidence needed:

<!-- writing-space -->

## Any revision, its reason, operator and date:

<!-- writing-space -->

Distinguish ring numbers from calendar years. Investigate local absences, false rings and missed boundaries using anatomy and independent comparisons. Preserve observations and record dating hypotheses separately.

<!-- pagebreak -->

# What does standardization retain?

In this exercise, a ring-width index is width divided by a supplied growth-curve value. Both inputs simulate mm; the ratio is dimensionless. Real analyses choose detrending methods for their question.

(See the slide PDF for this figure.)

(See the slide PDF for this figure.)

The comparison uses a centred five-year mean, with available years at the edges. It demonstrates sensitivity rather than a recommended setting; a flexible reference can remove longer-term variation.

How could the information you need to retain depend on the research question?

<!-- writing-space -->

<!-- pagebreak -->

# Exercise B Build indices and a chronology

Open L04_B_widths_and_supplied_curves.csv. A contains years, B/C the width/curve of A, D/E those of B, and F/G those of C. Add indices in H:J, their available-value mean in K and tree count in L.

H2 = IF(ISNUMBER(B2), B2/C2, "") ／ I2 = IF(ISNUMBER(D2), D2/E2, "") ／ J2 = IF(ISNUMBER(F2), F2/G2, "")

K2 = AVERAGE(H2:J2) ／ L2 = COUNT(H2:J2)

Fill down from row 2 through row 37. Preserve blanks. The excerpt below also permits calculation without a computer. Divide width by the supplied curve.

| Year | Tree | Width mm | Curve mm | Index |
| --- | --- | --- | --- | --- |
| 1998 | A | 2.26560 | 1.88800 |  |
| 1998 | B | 1.92698 | 1.60582 |  |
| 1998 | C | 1.09175 | 1.21306 |  |
| 1999 | A | 1.65469 | 1.83854 |  |
| 1999 | B | 1.24045 | 1.55056 |  |
| 1999 | C | 1.18460 | 1.18460 |  |
| 2000 | A | 1.96986 | 1.79078 |  |
| 2000 | B | 1.94705 | 1.49773 |  |
| 2000 | C | — | — |  |

| Year | Mean index | Trees n |
| --- | --- | --- |
| 1998 |  |  |
| 1999 |  |  |
| 2000 |  |  |

What changes if C in 2000 becomes zero? What further checks would you want where fewer trees are available?

<!-- pagebreak -->

# Terms and linked resources

| Term | Brief explanation |
| --- | --- |
| Increment core | A cylindrical radial wood sample. |
| Metadata | Information describing specimens and processing. |
| Measurement path | The path used to measure widths. |
| Spatial calibration | Converting pixels to physical length, expressed in mm/pix. |
| Quality control | Checking observations and numerical consistency. |
| Standardization | Adjusting growth levels or trends for the question. |
| Detrending | Expressing variation relative to a chosen trend. |
| Ring-width index | Here, width divided by the supplied curve value. |
| Chronology | A series combined by calendar year. |
| Sample depth | Available samples by year; distinguish tree counts. |

Exercises A and B are synthetic. The Koyamaki photographs, saved points and RWL measurements are real research material. Foundational sources: Speer (2010), Chapter 5, and the prior Turku lectures.

[Digital images and tree-ring measurement (mm/pix)](https://github.com/zooc-14calbp/tree-rings-environment-history/blob/main/en/supplements/BG11_digital_imaging_en_v1.pdf)

[Yonenobu et al. (2026): Koyamaki study](https://doi.org/10.1016/j.dendro.2026.126565)

[ImageJ: spatial calibration](https://imagej.net/ij/docs/menus/analyze.html#scale)

[dplR: detrending and chronologies](https://cran.r-project.org/web/packages/dplR/dplR.pdf)

[International Tree-Ring Data Bank](https://www.ncei.noaa.gov/products/paleoclimatology/tree-ring)

<!-- pagebreak -->

# Lesson 4  Calculate ring-width indices on paper

For Exercise B on slide 24. About six minutes; no computer or CSV import is needed. These are synthetic values for practising the calculation, separate from the measured Nabunken data.

Each cell gives observed width / supplied growth-curve value, both in mm. Index = observed width divided by curve value. Curve fitting itself is not part of this exercise.

| Year | Tree A | Tree B | Tree C |
| --- | --- | --- | --- |
| 1998 | 2.26560 / 1.88800 | 1.92698 / 1.60582 | 1.09175 / 1.21306 |
| 1999 | 1.65469 / 1.83854 | 1.24045 / 1.55056 | 1.18460 / 1.18460 |
| 2000 | 1.96986 / 1.79078 | 1.94705 / 1.49773 | — |

**Calculate each index to two decimal places. Average only available trees with equal weights, and record n. What happens if missing C in 2000 is replaced by zero?**

## Check

| Year | Indices A, B, C | Mean | n |
| --- | --- | --- | --- |
| 1998 | 1.20, 1.20, 0.90 | 1.10 | 3 |
| 1999 | 0.90, 0.80, 1.00 | 0.90 | 3 |
| 2000 | 1.10, 1.30, missing | 1.20 | 2 |

Filling the missing value with zero gives a mean of 0.80, inventing a growth decline that was not observed. Do not count multiple radii from one tree as independent trees.

## Return to the measured data

In the original 29ho018 CSV, 32 means 0.32 mm. The first seven widths sum to 2.79 mm. This is a sum of published measurements, not a new measurement from the printed photo. Check the original scale and measurement path; document positions and uncertainty if remeasuring.

[29ho018: source image and measurements](https://doi.org/10.24484/sitereports.cultural_data.2044)
