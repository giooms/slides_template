<div class="poster-header">
  <div class="poster-title-block">
    <h1>Your Research Title Goes Here</h1>
    <!-- <p class="poster-subtitle">Conference Name &amp; Year &mdash; Location</p> -->
  </div>
  <div class="poster-meta-container">
    <div class="poster-authors-container">
      <div class="poster-profile-pic"></div>
      <div class="poster-authors-block">
        <div class="poster-authors">Your Name<sup>1,*</sup>&ensp;Co-Author<sup>1</sup>&ensp;Collaborator<sup>2</sup></div>
        <!-- <div class="poster-affiliations">
          <div><sup>1</sup> Louvain Institute of Data Analysis and Modelling (LIDAM), UCLouvain, Belgium</div>
          <div><sup>2</sup> Optional second institution, Country</div>
          <div><sup>*</sup> firstname.lastname@uclouvain.be</div>
        </div> -->
      </div>
    </div>
    <div class="poster-logos-container">
      <img src="assets/logo_uclouvain.png" alt="UCLouvain" class="poster-logo">
      <img src="assets/logo_lidam.png" alt="LIDAM" class="poster-logo">
      <div class="poster-qr-header"></div>
    </div>
  </div>
</div>

<div class="col">

<section>

## Abstract

**Background:** Present the motivation for your work. Why does this problem matter? What gap does it address?

**Methodology:** Brief overview of your approach and what makes it novel.

</section>

<section>

## System Topology

The problem graph $\mathcal{G} = (\mathcal{V}, \mathcal{E})$ defines dispatch bounds under economic constraints.

<div class="poster-figure-box" style="height: 280px;">Network / Data Figure</div>

<div class="caption">Fig 1: Description of the figure and what it shows.</div>

</section>

<section>

## Constraints

- Thermal line limits $\mathcal{F}_{\max}$
- Generator ramping constraints
- Real-time nodal balance

</section>

</div>

<div class="col">

<section>

## Optimization Model

<div class="math-block">

$$\min_{x \in \mathcal{X}} \mathbb{E}_{\xi} \left[ c^\top x + \mathcal{Q}(x, \xi) \right]$$

</div>

Subject to two-stage recourse:

<div class="math-block">

$$\mathcal{Q}(x, \xi) = \min_{y} \; q^\top y \quad \text{s.t. } Wy = h(\xi) - Tx$$

</div>

| Parameter | Value |
|:----------|------:|
| $n$ samples | 1 200 |
| Time horizon | 8 760 h |
| Resolution | 1 h |

</section>

<section>

## Policy Surface

<div class="poster-figure-box" style="height: 360px;">Main Result Figure</div>

<div class="caption">Fig 2: Optimal policy projection over the cost surface.</div>

</section>

</div>

<div class="col">

<section>

## Results

<div class="poster-kpi-grid">
  <div class="poster-kpi"><span class="poster-kpi-value">91.7%</span><span class="poster-kpi-label">Accuracy</span></div>
  <div class="poster-kpi"><span class="poster-kpi-value">−29%</span><span class="poster-kpi-label">vs. Baseline</span></div>
  <div class="poster-kpi"><span class="poster-kpi-value">8 760</span><span class="poster-kpi-label">Hours</span></div>
</div>

<div class="poster-figure-box" style="height: 200px;">Convergence Graph</div>

<div class="caption">Fig 3: Iterative convergence comparison.</div>

<div class="poster-figure-box" style="height: 200px;">Dispatch Heatmap</div>

<div class="caption">Fig 4: Locational Marginal Pricing (LMP) variance.</div>

</section>

<section>

## Conclusions

- **Main result:** One-sentence summary of the key finding
- **Contribution:** What this adds to the literature
- **Outlook:** Next steps or open questions

</section>

<section>

## References

<div class="poster-references">

1. Author, A., & Author, B. (2024). Title of the paper. *Journal Name*, 15(3), 123–145.
2. Author, C. et al. (2023). Another important reference. *Conference Proceedings*, 45–56.
3. Author, D. (2022). Foundational work. *Journal of Field*, 10(2), 234–256.

</div>

</section>

<div class="engagement-block">
  <div class="contact-info">
    <strong>Contact &amp; Paper Access</strong>
    firstname.lastname@uclouvain.be &nbsp;&middot;&nbsp; <a href="https://github.com/giooms">github.com/giooms</a> &nbsp;&middot;&nbsp; UCLouvain / LIDAM
  </div>
</div>

</div>
