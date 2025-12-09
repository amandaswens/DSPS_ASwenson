#Review of Amanda Swenson’s HW9 Visualizations
$1-- Overview$

Amanda’s HW9 contains:

1-Original coursework plot (comparison of linear regression models)

2-Revised/improved coursework plot

3-Good plot (stellar HR diagram using color to show stellar mass)

4-Bad plot (magnetization/H vs. Gauss with inset subplots)

Each visualization is evaluated using:

Ambiguity

Distortion

Distraction

5 Tufte Principles

Color practices / color-blind safety

#2-- Evaluation of Original vs. Revised Coursework Plot

$A)Original Plot$

![unrevised_plot](https://github.com/amandaswens/DSPS_ASwenson/blob/main/HW9/unrevised_plot.png)

A comparison of linear regression models fitted to log-time vs. magnitude.

$Issues:$

$Ambiguity:$ 

Points were heavily clustered, making it difficult to distinguish overlapping markers.

Axis labels lacked clarity: “Log time” did not specify units or context.

Colors for regression lines blended with point markers, reducing visual separation.

$Distortion$

No numerical distortion, but perceptual distortion occurred because overlapping points made patterns hard to interpret.

Limited horizontal spacing compressed the distribution, making slope differences less visible.

$Distraction$

Visual clutter from overlapping points created noise.

Similar colors between data points and regression lines reduced the signal-to-noise ratio.

$Tufte’s Rules$

Data-ink ratio moderate but harmed by overplotting.

Effect size mostly correct — slopes are accurate but hard to see.

Chart junk minimal, but overlap creates accidental “junk.”

No redundancy.

Small multiples, not required.

$B)Revised Plot$
![revised_plot](https://github.com/amandaswens/DSPS_ASwenson/blob/main/HW9/revised_plot.png)

The improvement made in the revised version seems to be very small. 
Actually, the only meaningful modification in the revised plot is a slightly clearer y-axis label (“Magnitude (lower = brighter)”),
which improves interpretability for readers unfamiliar with astronomical magnitude conventions.

However, aside from that minor change, the two figures are nearly identical in:

point distribution

regression line placement

legend content and placement

color choices

axis scaling

layout and overall size

$Ambiguity$

The revised y-axis label improves clarity, but

No other ambiguity issues were addressed (e.g., overlapping colors, dense clustering).

$Distortion$

Both versions use identical scaling.

No distortion was introduced nor corrected.

$Distraction$

Overplotting and marker clutter remain unchanged.

No reduction of noise between models or uncertainties.

$Tufte’s Rules$

Effect size unchanged

Data/ink ratio unchanged

No new chart junk, but also no reduction

No redundancy removed

Overall adherence the same

$Conclusion$

While the original plot was not fundamentally flawed, the “revised” version only includes a very small clarity
improvement. The assignment asked for a meaningful refinement according to the ambiguity–distortion–distraction framework
and Tufte’s rules, and this revision does not clearly demonstrate such improvements.

#3 -- Evaluation of the “Good” Plot (Stellar HR Diagram)

$(Good plot link: stellar Hertzsprung–Russell diagram encoding stellar mass via color)$
![good_plot](https://github.com/amandaswens/DSPS_ASwenson/blob/main/HW9/good_plot.jpeg)

$1. Ambiguity$

Strengths:

Axes are clearly labeled: luminosity and temperature, which are standard astrophysical quantities.

The color encoding has a clear physical meaning (stellar mass), providing an intuitive third dimension.

Data points are well spaced on the HR diagram, reducing overlap and making patterns easy to interpret.

Result:

Low ambiguity — relationships between variables are clear, and the plot is immediately interpretable for both experts and non-experts familiar with HR diagrams.

$2. Distortion$

Strengths:

No misleading axis scaling; the HR diagram convention (temperature decreasing left → right) is correctly used.

Relative distances between points reflect actual physical differences.

Color gradient changes smoothly with mass, honestly representing magnitude of variation.

Result:

No numerical or perceptual distortion — effect size visually matches the true physical relationships.

$3. Distraction$

Strengths

Minimalistic design; the figure contains no unnecessary borders, textures, or decorative elements.

No overcrowding — data density is high, but the space is used effectively.

Visual hierarchy is clear: overall HR structure first, then color patterns.

Result:

Low distraction — viewer attention stays on true data variation.

$4. Tufte’s Five Principles$

a. Effect Size ≈ 1 (Lie Factor)

The size and brightness of points accurately reflect differences in luminosity and color.

Mass information encoded via color is truthful and proportional.

➡ Fully satisfies the effect-size rule.

b. Data–Ink Ratio

Nearly all ink directly represents data (star positions and masses).

Background is plain and unobtrusive.

➡ High data–ink ratio.

 C. Chart Junk

No decorative shading, 3D effects, or extraneous labels.

Minimum graphical components required to understand the figure.

➡ No chart junk present.


d. Use Small Multiples (When Needed)

A single panel works because the HR diagram inherently compares objects in a unified space.

No need for small multiples here.

➡ Appropriate use — rule satisfied.

e. Avoid Redundancy in Communication

Each star is represented once, with no duplicated information.

Axes and legend communicate all essential information without repetition.

➡ No redundancy — rule satisfied.

5. Color Practices (Including Color-Blind Safety)

Strengths:

Colors represent mass in a physically meaningful gradient (cooler → warmer hue).

Good contrast between points and background.

Even if color distinctions weaken for some color-blind viewers, the spatial structure (main sequence, giant branch) still conveys hierarchy.

Potential Minor Issue:

Some red–green hues approach areas of reduced contrast for deuteranopia, though not severely.

Result:

Color practice is strong and mostly color-blind-friendly. The plot uses color functionally, not decoratively.

$6. Summary Evaluation of the Good Plot$

This HR diagram is an excellent example of a scientifically strong visualization. Its clarity, physical interpretability, 
and visual economy make it a highly effective plot and an appropriate choice for a “good” visualization.

#4-- Evaluation of the “Bad” Plot

![bad-plot](https://raw.githubusercontent.com/amandaswens/DSPS_ASwenson/main/HW9/bad_plot.gif)

$1. Ambiguity$



As mentioned correctly by Amanda, the plot suffers from severe ambiguity:

Panels (a), (b), and (c) are not explained anywhere.
The viewer, without reading the caption, has no idea what distinguishes these curves — are they different samples? Different experimental conditions? Replicates?

The inset plots above each panel are also unexplained.
Without the caption, it is not clear what range or what feature these insets highlight.

The scaling multipliers (×1, ×1, ×5) are not defined.
Without caption guidance, the viewer might incorrectly assume panel (c) shows a physically stronger signal.

The x-axis (“H(gauss)”) is unclear without explanation of the physical meaning of H.
Again it is up to caption to clarify this. The same problem can be mentioned for the y-axis!

Result:
The viewer is left uncertain about what each curve represents or how the subplots relate to one another, creating very high ambiguity.

$2. Distortion$

Scaling Problems:

The inset plots use different x-axis and y-axis scales than the main curves. Because this change is not annotated or justified, the inset subplots may mislead the viewer about signal amplitude or width.

The “×5” scaling on panel (c) changes effect size perception but is not visually encoded in the inset, causing inconsistent effect-size representation.

Misaligned axes between the three main panels make direct comparison difficult and distort the visual interpretation.

Result:

Significant perceptual distortion — The plot violates the principle that the size of visual effects should faithfully represent data magnitude (Tufte’s “lie factor”).

$3. Distraction$

Sources of distraction:

The unnecessary inset boxes dominate visual attention and interrupt the flow of the main plot.

Overly thick borders and repeated axis frames add heavy visual noise.

The plot is monochrome but cluttered due to repeated structural elements: multiple boxes, repeated axes, and duplicate curves.

The viewer’s eye is pulled between three different main curves and three inset figures, with no clear hierarchy.

Result:

High distraction — Design noise overwhelms data variation.

$4. Tufte’s Five Principles$

a. Effect Size ≈ 1 (Lie Factor) — Violated

Scaling inconsistencies (especially the ×5 panel) change perceived amplitudes without proper visual encoding.

b. Data–Ink Ratio — Low

Much of the ink is spent on:

thick subplot borders

repeated axis ticks

unnecessary inset frames

redundant labels

Very little ink actually shows data variation.

c. No Chart Junk — Violated

Inset boxes, repeated frames, and scaling multipliers create chart junk that obscures rather than clarifies

d. Use Small Multiples Properly — Violated

This should have been a classic case for small multiples (three comparable curves in a consistent format).
Instead:

Insets break standardization

Axes change between panels

Comparison becomes harder, not easier.

e. Avoid Redundancy — Violated

Axes, labels, and frames are repeated three times.

Redundant structural elements do not add new information.

$5. Color Practices / Accessibility$

The plot uses only black lines, which avoids color-blind issues, but monochrome alone does not fix structural clarity.

Lack of color coding makes it even harder to distinguish curves or associate insets with panels—they all look identical.

Result:
Technically color-blind safe, but color could have helped disambiguate panels/insets.

$Summary Evaluation of the Bad Plot$

This figure suffers from substantial problems across all three major evaluation categories:

Ambiguity from unclear meaning of insets, scaling multipliers, and panel arrangement

Distortion due to mismatched scales and inconsistent effect-size representation

Distraction from excessive visual clutter, repeated frames, and unnecessary inset boxes

The plot also violates several of Tufte’s core principles, especially data–ink ratio, chart junk, and redundancy in communication.

Overall, this is a strong example of a poor scientific visualization, and Amanda’s decision to categorize it as a “bad plot” is fully justified.

#5-- Final Assessment

Amanda understands the principles of ambiguity, distortion, distraction, and Tufte’s rules, as shown in her critiques of good and bad visualizations.
However:

The revised coursework plot shows only a very small improvement
(mainly the y-axis label),
and does not sufficiently address the issues required by HW9, such as reducing clutter, improving data-ink ratio, or clarifying model comparisons.

Her external plot evaluations, however, are correct and clearly grounded in best visualization practices.

