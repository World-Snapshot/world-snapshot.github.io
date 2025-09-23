## DEMOs

<style>
/* Video Gallery Styles */
.video-gallery {
  max-width: 100%;
  margin-top: 30px;
  margin-bottom: 20px;
  margin-left: auto;
  margin-right: auto;
}

.gallery-tabs-container {
  display: flex;
  justify-content: center;
  gap: 5px;
  margin-bottom: 20px;
  flex-wrap: wrap;
}

.gallery-tab {
  padding: 6px 12px;
  border: 1px solid #ddd;
  background: white;
  cursor: pointer;
  border-radius: 4px;
  color: black;
  transition: all 0.3s ease;
}

.gallery-tab.active {
  background: #007bff;
  color: white;
}

.gallery-content {
  position: relative;
}

.gallery-prev,
.gallery-next {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: rgba(0, 0, 0, 0.5);
  color: white;
  border: none;
  padding: 20px 12px;
  cursor: pointer;
  font-size: 20px;
  border-radius: 4px;
  z-index: 10;
  transition: background 0.3s ease;
}

.gallery-prev:hover,
.gallery-next:hover {
  background: rgba(0, 0, 0, 0.7);
}

.gallery-prev {
  left: -40px;
}

.gallery-next {
  right: -40px;
}

.videos-container {
  display: flex;
  justify-content: space-between;
  gap: 5%;
  padding: 0 50px;
  overflow: hidden;
}

.video-item {
  width: 30%;
  display: none;
}

.video-item.active {
  display: block;
}

.video-wrapper {
  position: relative;
  padding-bottom: 100%;
  background: #f0f0f0;
  border-radius: 8px;
  overflow: hidden;
}

.video-wrapper video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.video-description {
  text-align: center;
  margin-top: 10px;
  font-size: 14px;
}

/* Grouped Gallery Styles */
.grouped-video-gallery {
  max-width: 100%;
  margin-top: 30px;
  margin-bottom: 20px;
  margin-left: auto;
  margin-right: auto;
}

.grouped-gallery-tabs-container {
  display: flex;
  justify-content: center;
  gap: 10px;
  margin-bottom: 20px;
  flex-wrap: wrap;
}

.grouped-gallery-tab {
  padding: 6px 12px;
  border: 1px solid #ddd;
  background: white;
  cursor: pointer;
  border-radius: 4px;
  color: black;
  transition: all 0.3s ease;
}

.grouped-gallery-tab.active {
  background: #007bff;
  color: white;
}

.grouped-gallery-tab:hover:not(.active) {
  background: #f8f9fa;
  border-color: #007bff;
}
</style>

***<center>"Unify Computer Vision, Expand Computer Vision, Transcend Computer Vision."</center>***

### Best Practices

<!-- Grouped Best Practices Gallery - One button controls 3 videos -->
<div class="grouped-video-gallery" data-gallery-id="best-practices-grouped">
<div class="grouped-gallery-tabs-container">
<button class="grouped-gallery-tab" data-group="0">Relative Depth</button>
<button class="grouped-gallery-tab" data-group="1">Absolute Depth</button>
<button class="grouped-gallery-tab" data-group="2">Surface Normal</button>
<button class="grouped-gallery-tab" data-group="3">Curvature</button>
<button class="grouped-gallery-tab" data-group="4">Edge</button>
<button class="grouped-gallery-tab" data-group="5">2D Optical Flow</button>
<button class="grouped-gallery-tab" data-group="6">2D Skeletal Human</button>
<button class="grouped-gallery-tab" data-group="7">3D Mesh Human</button>
<button class="grouped-gallery-tab" data-group="8">3D Skeletal Human</button>
<button class="grouped-gallery-tab" data-group="9">Human Segmentation</button>
<button class="grouped-gallery-tab" data-group="10">Object/Animal 3D</button>
<button class="grouped-gallery-tab" data-group="11">Diffuse</button>
<button class="grouped-gallery-tab" data-group="12">Height</button>
<button class="grouped-gallery-tab" data-group="13">Roughness</button>
<button class="grouped-gallery-tab" data-group="14">Metallic</button>
<button class="grouped-gallery-tab" data-group="15">Specular</button>
<button class="grouped-gallery-tab" data-group="16">Opacity</button>
<button class="grouped-gallery-tab" data-group="17">Object Volume</button>
<button class="grouped-gallery-tab" data-group="18">Video Sound</button>
<button class="grouped-gallery-tab" data-group="19">Video Description</button>
<button class="grouped-gallery-tab" data-group="20">Semantic Mask</button>
<button class="grouped-gallery-tab" data-group="21">LiDAR Point Cloud</button>
<button class="grouped-gallery-tab" data-group="22">mmWave Radar</button>
<button class="grouped-gallery-tab" data-group="23">WiFi CSI</button>
</div>
<div class="gallery-content">
<button class="gallery-prev">‹</button>
<div class="videos-container">
<div class="video-item" data-index="0">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Relative Depth Generation</p>
</div>
<div class="video-item" data-index="1">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best2.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Relative Depth Estimation</p>
</div>
<div class="video-item" data-index="2">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best3.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Relative Depth GT</p>
</div>
<div class="video-item" data-index="3">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best4.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Absolute Depth Generation</p>
</div>
<div class="video-item" data-index="4">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best5.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Absolute Depth Estimation</p>
</div>
<div class="video-item" data-index="5">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best6.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Absolute Depth GT</p>
</div>
<!-- Group 1: Absolute Depth -->
<div class="video-item" data-index="6">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best7.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Surface Normal Generation</p>
</div>
<div class="video-item" data-index="7">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best8.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Surface Normal Estimation</p>
</div>
<div class="video-item" data-index="8">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best9.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Surface Normal GT</p>
</div>
<!-- Group 3: Curvature -->
<div class="video-item" data-index="9">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best10.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Curvature Generation</p>
</div>
<div class="video-item" data-index="10">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best11.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Curvature Estimation</p>
</div>
<div class="video-item" data-index="11">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best12.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Curvature GT</p>
</div>
<!-- Group 4: Edge -->
<div class="video-item" data-index="12">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best13.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Edge Generation</p>
</div>
<div class="video-item" data-index="13">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best14.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Edge Estimation</p>
</div>
<div class="video-item" data-index="14">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best15.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Edge GT</p>
</div>
<!-- Group 5: 2D Optical Flow -->
<div class="video-item" data-index="15">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best16.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">2D Optical Flow Generation</p>
</div>
<div class="video-item" data-index="16">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best17.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">2D Optical Flow Estimation</p>
</div>
<div class="video-item" data-index="17">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best18.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">2D Optical Flow GT</p>
</div>
<!-- Group 6: 2D Skeletal Human -->
<div class="video-item" data-index="18">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best19.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">2D Skeletal Human Generation</p>
</div>
<div class="video-item" data-index="19">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best20.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">2D Skeletal Human Estimation</p>
</div>
<div class="video-item" data-index="20">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best21.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">2D Skeletal Human GT</p>
</div>
<!-- Group 7: 3D Mesh Human -->
<div class="video-item" data-index="21">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best22.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">3D Mesh Human Generation</p>
</div>
<div class="video-item" data-index="22">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best23.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">3D Mesh Human Estimation</p>
</div>
<div class="video-item" data-index="23">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best24.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">3D Mesh Human GT</p>
</div>
<!-- Group 8: 3D Skeletal Human -->
<div class="video-item" data-index="24">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best25.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">3D Skeletal Human Generation</p>
</div>
<div class="video-item" data-index="25">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best26.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">3D Skeletal Human Estimation</p>
</div>
<div class="video-item" data-index="26">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best27.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">3D Skeletal Human GT</p>
</div>
<!-- Group 9: Human Segmentation -->
<div class="video-item" data-index="27">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best28.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Human Segmentation Generation</p>
</div>
<div class="video-item" data-index="28">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best29.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Human Segmentation Estimation</p>
</div>
<div class="video-item" data-index="29">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best30.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Human Segmentation GT</p>
</div>
<!-- Group 10: Object/Animal 3D -->
<div class="video-item" data-index="30">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best31.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Object/Animal 3D Generation</p>
</div>
<div class="video-item" data-index="31">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best32.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Object/Animal 3D Estimation</p>
</div>
<div class="video-item" data-index="32">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best33.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Object/Animal 3D GT</p>
</div>
<!-- Group 11: Diffuse -->
<div class="video-item" data-index="33">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best34.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Diffuse Generation</p>
</div>
<div class="video-item" data-index="34">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best35.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Diffuse Estimation</p>
</div>
<div class="video-item" data-index="35">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best36.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Diffuse GT</p>
</div>
<!-- Group 12: Height -->
<div class="video-item" data-index="36">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best37.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Height Generation</p>
</div>
<div class="video-item" data-index="37">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best38.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Height Estimation</p>
</div>
<div class="video-item" data-index="38">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best39.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Height GT</p>
</div>
<!-- Group 13: Roughness -->
<div class="video-item" data-index="39">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best40.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Roughness Generation</p>
</div>
<div class="video-item" data-index="40">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best41.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Roughness Estimation</p>
</div>
<div class="video-item" data-index="41">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best42.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Roughness GT</p>
</div>
<!-- Group 14: Metallic -->
<div class="video-item" data-index="42">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best43.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Metallic Generation</p>
</div>
<div class="video-item" data-index="43">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best44.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Metallic Estimation</p>
</div>
<div class="video-item" data-index="44">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best45.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Metallic GT</p>
</div>
<!-- Group 15: Specular -->
<div class="video-item" data-index="45">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best46.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Specular Generation</p>
</div>
<div class="video-item" data-index="46">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best47.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Specular Estimation</p>
</div>
<div class="video-item" data-index="47">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best48.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Specular GT</p>
</div>
<!-- Group 16: Opacity -->
<div class="video-item" data-index="48">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best49.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Opacity Generation</p>
</div>
<div class="video-item" data-index="49">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best50.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Opacity Estimation</p>
</div>
<div class="video-item" data-index="50">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best51.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Opacity GT</p>
</div>
<!-- Group 17: Object Volume -->
<div class="video-item" data-index="51">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best52.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Object Volume Generation</p>
</div>
<div class="video-item" data-index="52">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best53.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Object Volume Estimation</p>
</div>
<div class="video-item" data-index="53">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best54.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Object Volume GT</p>
</div>
<!-- Group 18: Video Sound -->
<div class="video-item" data-index="54">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best55.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video Sound Generation</p>
</div>
<div class="video-item" data-index="55">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best56.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video Sound Estimation</p>
</div>
<div class="video-item" data-index="56">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best57.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video Sound GT</p>
</div>
<!-- Group 19: Video Description -->
<div class="video-item" data-index="57">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best58.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video Description Generation</p>
</div>
<div class="video-item" data-index="58">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best59.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video Description Estimation</p>
</div>
<div class="video-item" data-index="59">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best60.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video Description GT</p>
</div>
<!-- Group 20: Semantic Mask -->
<div class="video-item" data-index="60">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best61.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Semantic Mask Generation</p>
</div>
<div class="video-item" data-index="61">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best62.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Semantic Mask Estimation</p>
</div>
<div class="video-item" data-index="62">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best63.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Semantic Mask GT</p>
</div>
<!-- Group 21: LiDAR Point Cloud -->
<div class="video-item" data-index="63">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best64.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">LiDAR Point Cloud Generation</p>
</div>
<div class="video-item" data-index="64">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best65.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">LiDAR Point Cloud Estimation</p>
</div>
<div class="video-item" data-index="65">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best66.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">LiDAR Point Cloud GT</p>
</div>
<!-- Group 22: mmWave Radar -->
<div class="video-item" data-index="66">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best67.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">mmWave Radar Generation</p>
</div>
<div class="video-item" data-index="67">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best68.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">mmWave Radar Estimation</p>
</div>
<div class="video-item" data-index="68">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best69.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">mmWave Radar GT</p>
</div>
<!-- Group 23: WiFi CSI -->
<div class="video-item" data-index="69">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best70.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">WiFi CSI Generation</p>
</div>
<div class="video-item" data-index="70">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best71.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">WiFi CSI Estimation</p>
</div>
<div class="video-item" data-index="71">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/best72.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">WiFi CSI GT</p>
</div>
</div>
<button class="gallery-next">›</button>
</div>
</div>

<center>Due to space limitations, we are only demonstrating part Generation and Estimation tasks, for condition control and for more task types, please refer to the <a href="https://github.com/World-Snapshot/ControlWave/tree/main/plugins">plugins</a>: 1. Some mechanisms/functions are not easy to be displayed in short videos. 2. We can achieve too many tasks<sup class="footnote" data-note="One-to-many, many-to-one, any quantity to any quantity, any channel to any channel.">o</sup> (theoretically, is the limit of the world), and instead of creating a DEMO, it would be better to create plugins so that more people can use them immediately. 3. Some tasks are too abstract, for example, we can even simulate a blind person who cannot see RGB but can infer the material based on friction/ sound, and then guess the softness/hardness/category/color, this is the thinking chain in the World Snapshot Model (WSM). All the DEMOs can be accessed for viewing <a href="https://github.com/World-Snapshot/The-results-of-Augustus">results</a>, <a href="https://world-snapshot.github.io/doc/index.html?page=S3_get_start/04_best_practices.md">documentation</a> or <a href="https://github.com/World-Snapshot/ControlWave/tree/main/plugins">plugins</a>.</center>

### Advanced Features

<!-- Advanced Features Gallery -->
<div class="video-gallery" data-gallery-id="advanced-features">
<div class="gallery-tabs-container">
<button class="gallery-tab" data-video="0">1: consistency</button>
<button class="gallery-tab" data-video="1">2: native 3D+t</button>
<button class="gallery-tab" data-video="2">3: variable resolution</button>
<button class="gallery-tab" data-video="3">4: unlimited duration</button>
<button class="gallery-tab" data-video="4">5: predicting the future</button>
<button class="gallery-tab" data-video="5">6: variable FPS</button>
<button class="gallery-tab" data-video="6">7: physics</button>
<button class="gallery-tab" data-video="7">8: causality</button>
<button class="gallery-tab" data-video="8">9: predicting the past</button>
<button class="gallery-tab" data-video="9">10: pixel-level control</button>
<button class="gallery-tab" data-video="10">11: synchronizing core space and real world</button>
<button class="gallery-tab" data-video="11">12: training the world itself</button>
</div>
<div class="gallery-content">
<button class="gallery-prev">‹</button>
<div class="videos-container">
<div class="video-item" data-index="0">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/advanced_1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 1: consistency</p>
</div>
<div class="video-item" data-index="1">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/advanced_1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 2: native 3D+t</p>
</div>
<div class="video-item" data-index="2">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/advanced_1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 3: variable resolution</p>
</div>
<div class="video-item" data-index="3">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/advanced_1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 4: unlimited duration</p>
</div>
<div class="video-item" data-index="4">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/advanced_1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 5: predicting the future</p>
</div>
<div class="video-item" data-index="5">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/advanced_1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 6: variable FPS</p>
</div>
<div class="video-item" data-index="6">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/advanced_1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 7: physics</p>
</div>
<div class="video-item" data-index="7">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/advanced_1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 8: causality</p>
</div>
<div class="video-item" data-index="8">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/advanced_1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 9: predicting the past</p>
</div>
<div class="video-item" data-index="9">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/advanced_1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 10: pixel-level control of the world distribution</p>
</div>
<div class="video-item" data-index="10">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/advanced_1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 11: synchronizing the real world with model's core space</p>
</div>
<div class="video-item" data-index="11">
<div class="video-wrapper">
<video controls autoplay muted loop>
<source src="./static/demos/advanced_1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 12: training the world itself</p>
</div>
</div>
<button class="gallery-next">›</button>
</div>
</div>

<center>As mentioned above, this is only a proof of concept. The core space for simulating the operation of the world was obtained solely from Depth Map training (without the need for RGB in the training process), and it is currently rather weak, but some <a href="https://github.com/World-Snapshot/WaveGen#abstract">advanced features</a> therein are not present in the previous models. We aim to extend simple shapes to any realistic shapes in the next version. All the DEMOs can be accessed for viewing <a href="https://github.com/World-Snapshot/The-results-of-Augustus">results</a>, <a href="https://world-snapshot.github.io/doc/index.html?page=S3_get_start/05_advanced_features.md">documentation</a> or <a href="https://github.com/World-Snapshot/ControlWave/tree/main/plugins">plugins</a>.</center>

<script>
(function() {
  // Grouped Gallery class - one button controls three videos
  function GroupedVideoGallery(container) {
    this.container = container;
    this.galleryId = container.getAttribute('data-gallery-id');
    this.currentGroupIndex = 0;
    this.videosPerGroup = 3;

    // Get gallery elements
    this.videos = container.querySelectorAll('.video-item');
    this.tabs = container.querySelectorAll('.grouped-gallery-tab');
    this.prevBtn = container.querySelector('.gallery-prev');
    this.nextBtn = container.querySelector('.gallery-next');

    this.totalVideos = this.videos.length;
    this.totalGroups = Math.ceil(this.totalVideos / this.videosPerGroup);

    // Bind event handlers
    this.init();
  }

  GroupedVideoGallery.prototype.showGroup = function(groupIndex) {
    // Ensure group index is valid
    if (groupIndex < 0 || groupIndex >= this.totalGroups) return;

    // Hide all videos
    for (var i = 0; i < this.videos.length; i++) {
      this.videos[i].classList.remove('active');
    }

    // Reset all tabs
    for (var i = 0; i < this.tabs.length; i++) {
      this.tabs[i].classList.remove('active');
    }

    // Show videos in the current group
    var startIndex = groupIndex * this.videosPerGroup;
    for (var i = 0; i < this.videosPerGroup; i++) {
      var videoIndex = startIndex + i;
      if (videoIndex < this.totalVideos) {
        this.videos[videoIndex].classList.add('active');
      }
    }

    // Highlight the active group tab
    if (groupIndex < this.tabs.length) {
      this.tabs[groupIndex].classList.add('active');
    }

    this.currentGroupIndex = groupIndex;
  };

  GroupedVideoGallery.prototype.prev = function() {
    var newGroupIndex = this.currentGroupIndex - 1;
    if (newGroupIndex < 0) {
      newGroupIndex = this.totalGroups - 1;
    }
    this.showGroup(newGroupIndex);
  };

  GroupedVideoGallery.prototype.next = function() {
    var newGroupIndex = this.currentGroupIndex + 1;
    if (newGroupIndex >= this.totalGroups) {
      newGroupIndex = 0;
    }
    this.showGroup(newGroupIndex);
  };

  GroupedVideoGallery.prototype.init = function() {
    var self = this;

    // Tab click handlers
    for (var i = 0; i < this.tabs.length; i++) {
      (function(index) {
        self.tabs[index].addEventListener('click', function() {
          var groupIndex = parseInt(this.getAttribute('data-group'));
          self.showGroup(groupIndex);
        });
      })(i);
    }

    // Arrow button handlers
    if (this.prevBtn) {
      this.prevBtn.addEventListener('click', function() {
        self.prev();
      });
    }

    if (this.nextBtn) {
      this.nextBtn.addEventListener('click', function() {
        self.next();
      });
    }

    // Initialize first group
    this.showGroup(0);
  };

  // Gallery class to manage individual galleries
  function VideoGallery(container) {
    this.container = container;
    this.galleryId = container.getAttribute('data-gallery-id');
    this.currentStart = 0;
    this.videosPerPage = 3;
    
    // Get gallery elements
    this.videos = container.querySelectorAll('.video-item');
    this.tabs = container.querySelectorAll('.gallery-tab');
    this.prevBtn = container.querySelector('.gallery-prev');
    this.nextBtn = container.querySelector('.gallery-next');
    
    this.totalVideos = this.videos.length;
    
    // Bind event handlers
    this.init();
  }
  
  VideoGallery.prototype.showVideos = function(startIndex) {
    // Hide all videos and remove active class
    for (var i = 0; i < this.videos.length; i++) {
      this.videos[i].classList.remove('active');
    }
    
    // Reset all tabs
    for (var i = 0; i < this.tabs.length; i++) {
      this.tabs[i].classList.remove('active');
    }
    
    // Show current page videos and highlight tabs
    for (var i = 0; i < this.videosPerPage; i++) {
      var index = startIndex + i;
      if (index < this.totalVideos) {
        this.videos[index].classList.add('active');
        if (index < this.tabs.length) {
          this.tabs[index].classList.add('active');
        }
      }
    }
    
    this.currentStart = startIndex;
  };
  
  VideoGallery.prototype.showFromTab = function(videoIndex) {
    var newStart = Math.max(0, Math.min(videoIndex - 1, this.totalVideos - this.videosPerPage));
    this.showVideos(newStart);
  };
  
  VideoGallery.prototype.prev = function() {
    var newStart = this.currentStart - this.videosPerPage;
    if (newStart < 0) {
      newStart = Math.max(0, this.totalVideos - this.videosPerPage);
    }
    this.showVideos(newStart);
  };
  
  VideoGallery.prototype.next = function() {
    var newStart = this.currentStart + this.videosPerPage;
    if (newStart >= this.totalVideos) {
      newStart = 0;
    }
    this.showVideos(newStart);
  };
  
  VideoGallery.prototype.init = function() {
    var self = this;
    
    // Tab click handlers
    for (var i = 0; i < this.tabs.length; i++) {
      (function(index) {
        self.tabs[index].addEventListener('click', function() {
          var videoIndex = parseInt(this.getAttribute('data-video'));
          self.showFromTab(videoIndex);
        });
      })(i);
    }
    
    // Arrow button handlers
    if (this.prevBtn) {
      this.prevBtn.addEventListener('click', function() {
        self.prev();
      });
    }
    
    if (this.nextBtn) {
      this.nextBtn.addEventListener('click', function() {
        self.next();
      });
    }
    
    // Initialize first page
    this.showVideos(0);
  };
  
  // Initialize all galleries on the page
  function initializeAllGalleries() {
    var galleries = document.querySelectorAll('.video-gallery');
    var groupedGalleries = document.querySelectorAll('.grouped-video-gallery');
    var galleryInstances = [];

    // Initialize regular galleries
    for (var i = 0; i < galleries.length; i++) {
      galleryInstances.push(new VideoGallery(galleries[i]));
    }

    // Initialize grouped galleries
    for (var i = 0; i < groupedGalleries.length; i++) {
      galleryInstances.push(new GroupedVideoGallery(groupedGalleries[i]));
    }

    // Store instances globally if needed for debugging
    window.videoGalleries = galleryInstances;
  }
  
  // Wait for DOM to be ready
  if (document.readyState === 'loading') {
    document.addEventListener('DOMContentLoaded', initializeAllGalleries);
  } else {
    // DOM is already ready, initialize immediately
    setTimeout(initializeAllGalleries, 100);
  }
})();
</script>