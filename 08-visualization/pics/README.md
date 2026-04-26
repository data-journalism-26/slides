# Pictures needed for `08-visualization.Rmd`

Each entry: filename used in the slides → where to grab it. Save into
this folder with the exact filename. Anything marked **(★)** is the
single highest-leverage image for that section; if pressed for time,
just get those.

---

## Title slide background

- **`burnmurdoch-covid-excess-deaths.png`** *(★)* — used as the
  full-bleed title-slide background.
  John Burn-Murdoch's annotated COVID excess-deaths line chart from FT.
  Source: <https://www.ft.com/coronavirus-latest> (or any of his
  threads at <https://twitter.com/jburnmurdoch>).
  Alternative if you can't find the excess-deaths one: the
  log-trajectory chart at
  <https://www.ft.com/content/a26fbf7e-48f8-11ea-aeb3-955839e06441>.

---

## Warm-up section (two charts, same data)

- **`georgia-covid-bad.png`** *(★)* — Georgia DPH's notorious May 2020
  reordered bar chart. Vox's coverage has the original screenshot:
  <https://www.vox.com/covid-19-coronavirus-us-response-trump/2020/5/18/21262265/georgia-covid-19-cases-declining-reopening>
- **`georgia-covid-fixed.png`** — same data, reordered chronologically
  (Vox's "fixed" version, in the same article).

- **`fox-news-tax-cuts.png`** — Fox News' Bush-tax-cut bar chart with
  the ridiculously truncated y-axis. Several copies online; e.g. Media
  Matters: <https://www.mediamatters.org/fox-news/dishonest-fox-charts-bush-tax-cut-edition>
  or Quartz: <https://qz.com/580859/the-most-misleading-charts-of-2015-fixed>
- **`fox-news-tax-cuts-fixed.png`** — the honest-y-axis remake (Quartz
  has a side-by-side).

---

## Principle 1 — Annotation

- **`burnmurdoch-covid-bare-vs-annotated.png`** *(★)* — a side-by-side
  showing one of his charts as a default ggplot vs. the published FT
  version. If you can't find an exact pair, render the inflation
  workshop chart in default ggplot vs. the worked-solution version
  (`good_chart_desktop.png`) and compose them in Keynote.
- **`burnmurdoch-covid-trajectories.png`** — the log-scale country
  trajectories chart; widely reproduced. FT page or
  <https://medium.com/nightingale/how-john-burn-murdochs-influential-dataviz-helped-the-world-understand-coronavirus-6cb4a09795ae>
- **`datawrapper-text-elements.png`** — the labelled-anatomy diagram
  from <https://blog.datawrapper.de/text-in-data-visualizations/>
  (scroll to the chart with all text elements named).

---

## Principle 2 — Defaults are editorial choices

- **`houses-ft.png`** — a representative FT chart screenshot. Pick any
  recent piece from <https://www.ft.com/visual-and-data-journalism>.
- **`houses-economist.png`** — a representative Economist chart with
  the red bar in top-left. Any recent Daily Chart works:
  <https://www.economist.com/graphic-detail>
- **`houses-nyt.png`** — a representative NYT Upshot chart:
  <https://www.nytimes.com/section/upshot>
- **`houses-reuters.png`** — a representative Reuters Graphics
  screenshot: <https://www.reuters.com/graphics/>

- **`sarah-leo-economist-redesign.png`** *(★)* — a screenshot of one
  of Sarah Leo's before/after panels:
  <https://medium.economist.com/mistakes-weve-drawn-a-few-8cdd8a42d368>
  (the "alphabetical order" or "truncated axis" example works well).

---

## Principle 3 — Uncertainty

- **`uncertainty-fan-chart-boe.png`** — a Bank of England fan chart.
  From any *Monetary Policy Report*:
  <https://www.bankofengland.co.uk/monetary-policy-report>
  (the inflation-projection fan chart, usually Chart 1).
- **`uncertainty-hurricane-cone.png`** — NOAA cone-of-uncertainty
  example. <https://www.nhc.noaa.gov/aboutcone.shtml> has reference
  graphics.
- **`uncertainty-hops.gif`** *(★)* — a HOPs animation. Easiest grab:
  the explainer GIF at
  <https://medium.com/hci-design-at-uw/hypothetical-outcomes-plots-experiencing-the-uncertain-b9ea60d7c740>
- **`uncertainty-538-ranges.png`** — FiveThirtyEight Senate forecast
  range bars. From the 2018 archive:
  <https://projects.fivethirtyeight.com/2018-midterm-election-forecast/senate/>
  (or any later cycle).

---

## Principle 4 — Interactivity

- **`pudding-engagement-funnel.png`** — illustrative; a screenshot of
  a Pudding piece, or one of their process notes at
  <https://pudding.cool/process/>. If you don't have analytics data
  to show, replace this with an annotated screenshot of any well-known
  scrollytelling piece showing where readers drop off.
- **`pudding-democracy.png`** *(★)* — the "democracy in Congress"
  scrollytelling piece from The Pudding. Open it on desktop, take a
  screenshot of one of the steps:
  <https://pudding.cool/2025/03/democracy/>
  (or substitute another recent Pudding piece if that link rots).

---

## Principle 5 — Mobile-first

- **`mobile-viewport-comparison.png`** *(★)* — same chart at desktop
  vs. mobile width. Easiest: take the worked-solution
  `good_chart_desktop.png` and `good_chart_mobile.png` from
  `code/visualization/` and compose them side by side in Keynote with
  a phone mock around the mobile one.
- **`one-finding-per-chart.png`** — illustrative example. Datawrapper
  has the "How to design a chart for mobile" post:
  <https://blog.datawrapper.de/mobile-chart-design/>
  (any of the side-by-side small-multiples-vs-stack examples).

---

## Notes

- All images should have at least 1200px on the long side to look
  crisp on the projector.
- For news-site screenshots, keep the byline and source visible — it
  does double duty (credit + house-style example).
- If a link rots before class, the *Datawrapper Blog Data Vis Dispatch*
  is the easiest fallback for "best chart of the week" examples.
