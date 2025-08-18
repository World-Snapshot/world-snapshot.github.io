## Abstract

In this article, we define and propose a kind of ideal world model called the [World Snapshot Model](https://world-snapshot.github.io/doc/index.html?page=S5_blogs/00_world_model.md#definition) (WSM). This model aims to unify, record, understand, and generate the digitized world at the pixel level. It is trained using the [WaveGen](https://github.com/World-Snapshot/WaveGen) framework and employs [ControlWave UI](https://github.com/World-Snapshot/ControlWave) for conditional control. WaveGen is a new [wave-based generative method/concept](https://world-snapshot.github.io/doc/index.html?page=S3_get_start/01_wave_gen.md) that we proposed and designed, consisting of three data space domains: text, core/wave space, and pixel layer, and bidirectional transformations between different domains of world snapshot model are implemented through flow models. The [core space](https://world-snapshot.github.io/doc/index.html?page=S3_get_start/01_wave_gen.md#core-space-mechanism-and-usage-method) is a wave space that accommodates multiple sets of wave functions with shape probability and serves as the world core of the World Snapshot Model.

The World Snapshot Model achieves: 1. By creating a wave space, it enables the encoding of spatiotemporal information into the visual model's latent space, allowing for explicit control and utilization. 2. It embeds physical rules into the visual model's latent space, namely our wave/core space. 3. By leveraging the characteristics of the data structure itself, it achieves pixel-level control without requiring secondary training like ControlNet, enabling hundreds of conditional controls. Our Snapshot Model uses newly defined data structures ([WSG](https://world-snapshot.github.io/doc/index.html?page=S2_standard/02_wsg_ver1.md), [WSV](https://world-snapshot.github.io/doc/index.html?page=S2_standard/03_wsv_ver1.md), [WSF](https://world-snapshot.github.io/doc/index.html?page=S2_standard/04_wsf_ver1.md)) that we have developed to train and generate.

Our model demonstrates good performance in semantic consistency, human ID consistency, 4D spatiotemporal consistency, physical realism, degree of control in conditional generation, generation speed, image-to-video generation, and 3D reconstruction capabilities. Our model can play a forward-looking role in film production, world generation and understanding, XR content creation, and AI animation engines.


*More [TLDRs](https://world-snapshot.github.io/doc/index.html?page=S6_materials/02_guideline.md#tldr-of-project-page) can explain our design principles. More our summary/contribution at [here](https://world-snapshot.github.io/doc/index.html#summary).*

*The new model/method are still at a [very early stage](https://world-snapshot.github.io/doc/index.html?page=S6_materials/04_questions.md#future-work-full-roadmap). Don't expect to generate high-quality 70B-parameter-level content/videos here.*


<!--
<details>
<summary>More Intro.</summary>

</details>
-->