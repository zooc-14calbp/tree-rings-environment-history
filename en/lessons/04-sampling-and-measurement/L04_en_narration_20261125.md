# Chapter 4　Sampling, measurement, and ring-width series

> Recording draft. Numbers follow the updated public PDF order.

## Slide 1　Reading Environment and History through Tree Rings

Sampling, measurement and ring-width series. This explanation follows the information from collection to chronology. Pause for the exercises corresponding to the ninety-minute classroom lesson.

## Slide 2　Learning objectives

Plan sampling and records. Explain a sampling plan and the metadata it needs. Measure widths from boundaries. Check the path, spatial calibration, boundary positions and units. Combine ring-width series. Distinguish detrending, tree weighting and sample depth. A central aim is to keep every value traceable to a specimen and measurement path.

### Slide 3　Connect specimens, measurements and chronology

Follow the top row from a question to specimens, images and paths, then continue along the lower row through widths, crossdating and chronology. This is not a claim that a fixed sequence guarantees correctness. Questionable crossdating calls for a return to images, boundary choices and units. Unexpected chronology features call for checks on tree contributions and standardization. Saving only the final curve prevents those checks. Link specimen records, original images, boundary positions, widths and processing versions.

> https://www.ncei.noaa.gov/products/paleoclimatology/tree-ring

## Slide 4　Start sampling with the question

Climate. Choose species, sites and comparison areas relevant to the climate variable. Forest history. Plan how spatial sampling will capture disturbance and regeneration. Buildings and objects. Record member location, working or reuse, and surviving inner and outer wood. The event of interest determines which positions, preserved edges and comparison material are needed.

### Slide 5　An increment borer: instrument and extracted core

The left photograph shows the disassembled parts above and the assembled instrument below. Label a identifies the hollow cutting bit, b the handle, and c the extractor. The right photograph shows a slender extracted core from earlier teaching material. A core records one sampling path, whereas a disc can reveal several radii and scar extent; a surface image records the readable surface. Consider existing material and imaging as alternatives, and plan the information needed before sampling.

> https://haglofsweden.com/project/increment-borers/

### Slide 6　Use the photographs to interpret core coverage and orientation

The photographs show insertion of a borer into wood and extraction of a core. They do not independently establish the same tree, a continuous sequence, species or location. The schematic distinguishes pith and bark sides from the sampled interval. Check whether the pith was reached, whether outer rings survive, and whether bending, breaks or compression affect the sequence. Other radii may retain layers or scars absent here. Sample under appropriate permission and record site, tree, height and direction.

> https://haglofsweden.com/project/increment-borers/

### Slide 7　IDs distinguish sites, trees, samples and paths

The hierarchy separates sites, trees, samples and paths. IDs such as S01 are fictional teaching identifiers. Taking samples A and B from one tree still represents one tree. Two measurement paths on sample A likewise do not represent additional trees. Use matching IDs in photographs, storage, boundary records and width files. IDs alone are insufficient: retain position, orientation, pith and bark preservation, image scale, operator, revision reasons and versions.

> https://www.ncei.noaa.gov/products/paleoclimatology/tree-ring

## Slide 8　Mini exercise: plan a collection

You want to study moisture variability in a forest with ridges and valleys. Choose sites, trees, radii and the records to keep. State one limitation arising from the places you did not sample. Pause and specify sample numbers, positions and comparisons, including an alternative if the preferred material is unavailable.

### Slide 9　Preserve sequence and orientation as well as the wood

Losing fragment order or orientation can destroy positional information even when wood survives. This fictional example illustrates a broken core. Match IDs on specimen and container; record pith and bark sides, fragment order and losses, and retain an initial overview photograph. Packaging and support depend on condition. Ordinary dry material and waterlogged archaeological wood require different handling decisions; consult conservation guidance for the latter. Record treatments and deformation so measurements remain traceable.

> https://historicengland.org.uk/images-books/publications/dendrochronology-guidelines/dendrochronology-pdf/

### Slide 10　Prepare a readable surface, then check cells and boundaries

The left photograph shows microtome work from earlier teaching material; the right is a separate transverse-surface example. They are not before/after views of one specimen. Check support and cell orientation, then select sanding, cutting or another suitable method for the material. Making a thin section and preparing a ring-width measurement surface can have different aims; no single procedure fits all samples. Inspect narrow rings and boundary cells under magnification. Distinguish preparation damage and tool marks from growth boundaries, and record treatment and any loss.

> https://static.wsl.ch/land/products/dendro/preparation.html

### Slide 11　Retain overlapping rings when photographing in sections

The left photograph of Yoshino cedar is by Hitoshi Yonenobu. Preserve specimen identity and context in an overview, then follow rings in overlapping detail images. The right-hand frames illustrate a layout, not actual exposures. Supplementary Text S2.2 describes typical half-to-two-thirds overlap, a distance spacer and a scale for each specimen. Check matching boundaries across overlap to avoid duplication or omission. A visually continuous composite does not guarantee dimensional accuracy: transformation and resampling require checks against originals and calibration. The supplement does not certify post-stitching measurement accuracy.

> https://doi.org/10.1016/j.dendro.2026.126572

### Slide 12　An oblique path is longer between the same boundaries

The blue line crosses two parallel boundaries perpendicularly; the orange line crosses them obliquely. Their endpoints lie on the same two boundaries, but the oblique segment is longer. This schematic isolates a directional effect and is not a measurement from a specimen. Real ring boundaries curve, and a straight line towards the stem centre need not be locally appropriate everywhere. Choose a path suited to the observation and preserve its position and direction in the image. Be explicit about which distance you measured as ring width.

> https://www.ncei.noaa.gov/products/paleoclimatology/tree-ring

### Slide 13　Calibration: distinguish pixel spacing from measurement accuracy

The left image is a Kiso koyamaki specimen, not the Yoshino sample on the preceding slide. Divide a known scale length by its pixel distance to obtain millimetres per pixel. The 10 mm / 2000 pixel calculation is an exercise, not a fresh measurement of this displayed image. The original koyamaki image has a recorded calibration of about 0.0058 mm/pixel; that does not establish measurement accuracy at the same value. Focus, distortion, scale placement and boundary interpretation also matter. Recheck calibration after resizing or geometric transformation, and preserve original images and processing records.

> https://doi.org/10.1016/j.dendro.2026.126565
> https://doi.org/10.50974/0002007852
> https://imagej.net/ij/docs/menus/analyze.html#scale

### Slide 14　Trace a ring width through image, coordinates and file

A, B and C correspond to saved measurement positions. The paired original coordinate and ring-width records were checked. Coordinates in this POS file are already in millimetres; their Euclidean distance is a width in millimetres, without another mm/pixel conversion. In the displayed order, A–B is about 0.74 mm and B–C about 0.76 mm, corresponding to stored values 74 and 76 at 0.01 mm units. Stored digits do not guarantee accuracy. Point labels are not calendar dates. The following calculation exercise uses separate synthetic data.

> https://doi.org/10.1016/j.dendro.2026.126565
> https://doi.org/10.50974/0002007852
> https://www.cybis.se/forfun/dendro/

## Slide 15　Exercise A: calculate six ring widths

Scale: 600 px = 10 mm. Record each successive pixel difference and width in mm. Compare the sum of six widths with the endpoint distance. Pause to calculate the six differences and their units, and inspect whether any boundary position needs checking.

## Slide 16　Exercise A: calculations and checks

600 divided by 10 = 60 px/mm. (670 − 100) divided by 60 = 9.50 mm. An endpoint check does not prove the boundaries were identified correctly. Compare boundary order and unit conversion as well as arithmetic when reviewing the answers.

## Slide 17　Pixel spacing and visibility of ring boundaries

Both images show the same area. The left crop is six hundred by three hundred thirty-six pixels. The right is one hundred fifty by eighty-four. Reducing both dimensions to one quarter makes each pixel represent about four times the original length. Zooming cannot recover the discarded detail. Recalibrate if you measure the reduced image.

### Slide 18　Separate measurement checks from calendar dating

First check the measurement chain: connect specimen 20ko478, its image, POS and ring-width record, and verify units and order. Numbers such as 1 or 10 in this segmented file must not be interpreted as CE years. Dating is a separate step: crossdate the resulting sequence against a securely dated reference. Return to images and paths when a mismatch appears, checking boundaries, local discontinuity and path changes. Preserve originals and document changes and candidate-date evidence rather than editing values merely to force a match.

> https://doi.org/10.1016/j.dendro.2026.126565
> https://doi.org/10.50974/0002007852
> https://www.ltrr.arizona.edu/skeletonplot/introcrossdate.htm

## Slide 19　Growth levels differ among trees

Width reflects species, size, individual history and other influences. A raw mean alone need not isolate the signal of interest. Different widths in the same year do not automatically indicate different dates. Distinguish growth level from the sequence of variation. The vertical axis uses a log10 scale. Tick labels show the original widths, and equal ratios span equal distances.

## Slide 20　Standardization relative to a growth curve

Here, index = ring width divided by supplied growth-curve value. An index of 1 matches the curve; 1.2 is 1.2 times it. The curve choice affects the variation retained. Dividing by a reference growth curve produces a dimensionless index. The chosen reference affects which variations remain. The vertical axis uses a log10 scale. Tick labels show the original widths, and equal ratios span equal distances.

## Slide 21　Which variation is retained?

A is indexed against two different reference curves. A flexible reference can remove longer-term variation. Record the question, method and settings; compare results. A smooth fitted curve can remove slow variation of interest as well as an age trend.

### Slide 22　Average within trees before averaging among trees

Tree A has indices 0.8 and 1.2; its mean is 1.0. Tree B has one radius at 1.5. Equal weighting of the two tree means gives 1.25. A direct mean of all three radii is about 1.17, giving tree A twice the weight. This is a simple aggregation example; document the grouping and method used.

> https://cloud.r-project.org/web/packages/dplR/dplR.pdf

## Slide 23　Show sample depth through time

Average the available tree indices in each calendar year. A continuous chronology can have changing sample depth. Tree count alone is insufficient; consider agreement and sampling bias. Earlier chronology sections may have fewer trees. Read the mean together with the number of independent trees supporting each year.

### Slide 24　The direction of averaging changes the question

This synthetic table illustrates standardized ring-width indices rather than measured widths. Columns are calendar years and rows are trees A, B and C. Average the blue 2019 column vertically: 0.5, 0.7 and 0.6 give 0.60. Averaging members at the same time illustrates the basic idea of an ensemble mean. In chronology building, dates must first be aligned and samples from the same tree combined before averaging across trees. Trees share environmental influences and need not be independent realizations. Now average the orange row horizontally. Tree A has a mean of 1.00 over these seven years. This time mean describes the level of one series over a specified interval. The same table therefore answers different questions, depending on the direction of averaging. Decide whether you want the common dip in 2019 or the average level of tree A over seven years.

> https://glossary.ametsoc.org/wiki/ensemble-average/
> https://glossary.ametsoc.org/wiki/time-average/
> https://www.ncei.noaa.gov/pub/data/paleo/treering/treeinfo.pdf

### Slide 25　Time averaging weakens a short dip

The blue line is the annual chronology obtained by averaging vertically across the three trees. Its value in 2019 is 0.60. The orange line averages this chronology over a moving three-year window. A centred window places the mean of 2018, 2019 and 2020 at 2019: 0.9 plus 0.6 plus 1.0, divided by three, is about 0.83. A short dip becomes less pronounced. Time averaging can help reveal broader changes, but the annual series remains necessary when examining short extremes. No endpoint values are calculated because complete centred windows are unavailable there. This distinction will help when reading climate variability and period means in Chapter 7. In a climate-model ensemble, members are simulations representing the same target time rather than different trees. Averaging does not remove every error: shared biases and correlated variations can remain. Equating time means and ensemble means also requires additional conditions.

> https://glossary.ametsoc.org/wiki/ensemble-average/
> https://glossary.ametsoc.org/wiki/time-average/
> https://www.ncei.noaa.gov/pub/data/paleo/treering/treeinfo.pdf

## Slide 26　Exercise B: build indices and a chronology

Calculate A, B and C indices from widths and supplied curves in the CSV. Average the available indices by calendar year and count trees n. Compare 1998–2000 and consider the effect of replacing blanks with zero. Pause to calculate indices, combine within trees and then average by year. Missing observations must not be replaced with zeros.

## Slide 27　What can the chronology establish?

An index is not temperature or precipitation. Test environmental responses against independent evidence. A low index can have several causes. Distinguish drought, cold, disturbance and measurement problems. Review processing for the question. Removed variation may matter when studying growth release. A chronology documents shared growth variation, while its climatic or ecological cause requires additional evidence.

### Slide 28　Traceability: return from a result to its specimen

Here traceability means following data provenance. Start with a result and work back through processing, width files, paths, images and specimens. These IDs illustrate the record structure; they are not real measurement records. In an actual study, each arrow must connect real files and documentation. Preserve image scale and orientation, numeric units, calendar assignments, missing values, reasons for boundary revisions, software, settings and versions. Matching filenames alone does not establish reproducibility.

> https://www.ncei.noaa.gov/products/paleoclimatology/tree-ring

### Slide 29　What can others check with the shared records?

The top row uses images, scale and path or boundary records to remeasure the same area. The middle row uses original widths and documented processing to repeat an analysis. The bottom row tests the interpretation with independent paths, trees, sites or other evidence. Reproducing a result from the same files is different from supporting it with independent evidence. Supply versions, documentation, units, missing-value conventions and reuse conditions. Where access is restricted, state its scope and procedures, while providing reliable access to the material that is public.

> https://www.ncei.noaa.gov/products/paleoclimatology/tree-ring

## Slide 30　Check methods and evidence in research papers

Begin with the specimen and methods. Measurements called ring width can differ in their imaging, calibration, measurement path, or boundary choices. The DOI on screen opens the Yoshino cedar paper. Check access to the article and supplement, and record the passage that supports your interpretation.

## Slide 31　Links for methods and further study

Links for methods and further study. When consulting a method, check the relevant version, settings and assumptions for the data being analysed.

## Slide 32　Exit questions

Does a matching total length prove that the boundaries are correct?. If C is blank in 2000, should it become zero in a three-tree mean?. Write a one-sentence reason for each answer. Explain measurement direction, units, missing values and tree counts briefly in your own words.

## Slide 33　Next: wood dates and human history

Lesson 5 introduces dendroarchaeology. How does an outer-ring date relate to felling, working and construction?. Review surviving outer wood and evidence for the dating. Next we connect wood dates with human activity, using preserved outer edges and sampling context.
