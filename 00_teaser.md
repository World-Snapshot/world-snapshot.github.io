<h2 style="display: none;">Teaser</h2>

<details>
<summary id="rotating-summary">TLDR (1/15): Requirements for implementing an ideal world model: 1. Encode all information to the boundary. 2. Conform to conformal symmetry. Follow this rule, flattens the world into a two-dimensional space, and visual generation is almost lossless world generation.</summary>
<center><a href="https://world-snapshot.github.io/doc/index.html?page=S6_materials/02_guideline.md#tldr-of-project-page">All TLDRs</a></center>
<!--
<div style="display: flex; justify-content: space-between; gap: 20px; margin-top: 15px;">
    <img src="./static/images/WaveGen_cover.jpg" alt="WaveGen Cover Image" style="max-width: calc(50% - 10px); height: auto;">
    <img src="./static/images/ControlWave_cover.jpg" alt="ControlWave Cover Image" style="max-width: calc(50% - 10px); height: auto;">
</div>
-->
</details>

<script>
// Array of rotating summary texts
const summaries = [
  "TLDR (1/15): Requirements for implementing an ideal world model: 1. Encode all information to the boundary. 2. Conform to conformal symmetry. Follow this rule, flattens the world into a two-dimensional space, and visual generation is almost lossless world generation.",
  "TLDR (2/15): World Snapshot Model: similar to a two-stage rich-information diffusion model, to a flow-based spatially conditioned generative model, to a 3DGS model that separates attributes from spatial information, to a model that fuses virtual NeRF and real point clouds, to an AI optical engine for rendering 3D models to 2D animation video (Cel shading/toon shading)...",
  "TLDR (3/15): Definition of an ideal world model: 1. Spatial sequence 2. Time sequence 3. Dense representation 4. Semantic instances 5. World core 6. Physical constraint 7. RIVE, Reasonable, Interpretable, Visualizable, and Editable. 8. Bidirectional training and inference 9. All living animals have posture information...",
  "TLDR (4/15): The method to make vision models understand physics is to create a core space and implement constraints within it.",
  "TLDR (5/15): ControlNet represents parameter-based controllable generation, while ControlWave represents data-based controllable generation, the second type of GenAI controllable generation mastered by humans.",
  "TLDR (6/15): Ideal world models possess conformal symmetry, e.g., representing data positions as \"relative positions\", allowing the core space to have tremendous freedom and robustness. Eg, this can solve the fixed resolution problem in ViT and aligns with human intuition.",
  "TLDR (7/15): Adding high-dimensional features/the complexity of the latent space manifold itself (using WSG), and reducing the actual distribution of the latent space (based on flow models or physically consistent data) all contribute to semantic consistency.",
  "TLDR (8/15): The key to the wave-based model is using waves to record spatial information to create multi-perspective consistency, human id consistency and behavior consistency.",
  "TLDR (9/15): The coordinates of a moving camera are one of the key pieces of information that help the model understand the world. Observing the world while moving is like querying a high-dimensional manifold, similar to how Earth is a sphere rather than a flat plane. Conventional generative models are equivalent to generating from a fixed perspective.",
  "TLDR (10/15): The principle of least action is the underlying principle of the world and can explain all known physical systems. Therefore, as long as we conform to the principle of least action, we hold the key to making models understand physics.",
  "TLDR (11/15): The breaking and merging of waves can represent a cup shattering or cars colliding, representing moments of sudden change in otherwise smoothly evolving systems. This is the final mile that visual models need to complete.",
  "TLDR (12/15): WaveGen is a type of wave-based model that, just as waves on the surface are driven by ocean currents below, is based on flow models. The World Snapshot Model is an ideal world model implemented through WaveGen. ControlWave utilizes the data characteristics of the world model itself to control the world.",
  "TLDR (13/15): All the pixels of our work exhibit wave-particle duality. In the field of world snapshots, waves represent reconstruction, time-space, order and existence, while particles represent generation, rendering, understanding and cognition.",
  "TLDR (14/15): In Computer Vision before WSM be proposed, all estimation tasks can be regarded as deriving WSG from images, all conditional generation tasks can be seen as generating WSG with fixed partial results, and all reconstruction tasks can be considered as obtaining WSG sets through known images.",
  "TLDR (15/15): The latent space of WaveGen has the characteristics of being Reasonable, Interpretable, Visualizable, and Editable. Unlike all the previous works: the parameter latent space of previous models only has the simplest I/O interface.",
];

// Get the summary element
const summaryElement = document.getElementById('rotating-summary');

// Current index
let currentIndex = 0;

// Simple rotation function
function rotateSummary() {
  currentIndex = (currentIndex + 1) % summaries.length;
  summaryElement.textContent = summaries[currentIndex];
}

// Set rotation interval (every 5.5 seconds)
setInterval(rotateSummary, 5500);
</script>

<!--
<video autoplay muted loop playsinline>
    <source src="./static/videos/teaser.mp4" type="video/mp4">
</video>
-->
<img src="./static/videos/srvae_generations_y12x5.png" alt="WSM Cover Image" style="width: calc(100% - 10px); height: auto;">

<center>
<b>This picture is a visualization of the training data for the part of information that our model can generate, estimate, control, and Reconstruct:</b>
Our model can control hundreds of information conditions at the pixel level and utilize them for more tasks (Note that a modal can have multiple information conditions).
Due to space limitations, we only present demonstrations for 60 information conditions.
We also provide <a href="#demos">more demonstrations</a> and the corresponding <a href="https://github.com/World-Snapshot/The-results-of-Augustus">task lists</a> supported by these information conditions.
</center>
