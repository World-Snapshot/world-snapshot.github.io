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
</style>

***<center>"Unify Computer Vision, Expand Computer Vision, Transcend Computer Vision."</center>***

### Best Practices

<!-- Best Practices Gallery -->
<div class="video-gallery" data-gallery-id="best-practices">
<div class="gallery-tabs-container">
<button class="gallery-tab" data-video="0">Example 1</button>
<button class="gallery-tab" data-video="1">Example 2</button>
<button class="gallery-tab" data-video="2">Example 3</button>
<button class="gallery-tab" data-video="3">Example 4</button>
<button class="gallery-tab" data-video="4">Example 5</button>
<button class="gallery-tab" data-video="5">Example 6</button>
</div>
<div class="gallery-content">
<button class="gallery-prev">‹</button>
<div class="videos-container">
<div class="video-item" data-index="0">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/best1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Best Practice 1</p>
</div>
<div class="video-item" data-index="1">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/best2.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Best Practice 2</p>
</div>
<div class="video-item" data-index="2">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/best3.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Best Practice 3</p>
</div>
<div class="video-item" data-index="3">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/best4.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Best Practice 4</p>
</div>
<div class="video-item" data-index="4">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/best5.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Best Practice 5</p>
</div>
<div class="video-item" data-index="5">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/best6.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Best Practice 6</p>
</div>
</div>
<button class="gallery-next">›</button>
</div>
</div>

<center>Due to space limitations, we are only demonstrating some of the functions in certain areas: 1. Some functions are quite complex; 2. Some mechanisms are not easy to be displayed in short videos. 3. We can achieve too many tasks<sup class="footnote" data-note="One-to-many, many-to-one, any quantity to any quantity, any channel to any channel.">o</sup> (theoretically, is the limit of the world), and instead of creating a DEMO, it would be better to create plugins so that more people can use them immediately. 4. Some tasks are too abstract, for example, we can even simulate a blind person who cannot see RGB but can infer the material based on friction/ sound, and then guess the softness/hardness/category/color, this is the thinking chain in the World Snapshot Model (WSM). All the DEMOs can be accessed for viewing <a href="https://github.com/World-Snapshot/The-results-of-Augustus">results</a>, <a href="https://world-snapshot.github.io/doc/index.html?page=S3_get_start/04_best_practices.md">documentation</a> or <a href="https://github.com/World-Snapshot/ControlWave/tree/main/plugins">plugins</a>.</center>

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
<video controls muted loop>
<source src="./static/demos/video1.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 1: consistency</p>
</div>
<div class="video-item" data-index="1">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/video2.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 2: native 3D+t</p>
</div>
<div class="video-item" data-index="2">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/video3.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 3: variable resolution</p>
</div>
<div class="video-item" data-index="3">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/video4.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 4: unlimited duration</p>
</div>
<div class="video-item" data-index="4">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/video5.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 5: predicting the future</p>
</div>
<div class="video-item" data-index="5">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/video6.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 6: variable FPS</p>
</div>
<div class="video-item" data-index="6">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/video7.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 7: physics</p>
</div>
<div class="video-item" data-index="7">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/video8.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 8: causality</p>
</div>
<div class="video-item" data-index="8">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/video9.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 9: predicting the past</p>
</div>
<div class="video-item" data-index="9">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/video10.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 10: pixel-level control of the world distribution</p>
</div>
<div class="video-item" data-index="10">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/video11.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 11: synchronizing the real world with model's core space</p>
</div>
<div class="video-item" data-index="11">
<div class="video-wrapper">
<video controls muted loop>
<source src="./static/demos/video12.mp4" type="video/mp4">
</video>
</div>
<p class="video-description">Video 12: training the world itself</p>
</div>
</div>
<button class="gallery-next">›</button>
</div>
</div>

<center>As mentioned above, this is only a proof of concept. The core space for simulating the operation of the world was obtained solely from Depth Map training (without the need for RGB in the training process), and it is currently rather weak, but some advanced features therein are not present in the previous models. We aim to extend simple shapes to any realistic shapes in the next version. All the DEMOs can be accessed for viewing <a href="https://github.com/World-Snapshot/The-results-of-Augustus">results</a>, <a href="https://world-snapshot.github.io/doc/index.html?page=S3_get_start/05_advanced_features.md">documentation</a> or <a href="https://github.com/World-Snapshot/ControlWave/tree/main/plugins">plugins</a>.</center>

<script>
(function() {
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
    var galleryInstances = [];
    
    for (var i = 0; i < galleries.length; i++) {
      galleryInstances.push(new VideoGallery(galleries[i]));
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