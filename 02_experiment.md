## Experiment

The results and evalution can be found at [World-Snapshot/The-results-of-Augustus](https://github.com/World-Snapshot/The-results-of-Augustus). The number of supported tasks is constantly updated. Please click to view.

For the time being, the updated results and usage methods will be stored in this repository. The plugins will be updated within [ControlWave](https://github.com/World-Snapshot/ControlWave). The qualitative assessment is in the [Demo Section](#demos).

## Video Gallery

<div id="videoGallery" style="max-width: 100%; margin: 40px auto;">
<div style="display: flex; justify-content: center; gap: 5px; margin-bottom: 20px; flex-wrap: wrap;">
<button class="gallery-tab" data-video="0" onclick="window.galleryShowFromTab(0)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">1</button>
<button class="gallery-tab" data-video="1" onclick="window.galleryShowFromTab(1)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">2</button>
<button class="gallery-tab" data-video="2" onclick="window.galleryShowFromTab(2)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">3</button>
<button class="gallery-tab" data-video="3" onclick="window.galleryShowFromTab(3)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">4</button>
<button class="gallery-tab" data-video="4" onclick="window.galleryShowFromTab(4)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">5</button>
<button class="gallery-tab" data-video="5" onclick="window.galleryShowFromTab(5)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">6</button>
<button class="gallery-tab" data-video="6" onclick="window.galleryShowFromTab(6)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">7</button>
<button class="gallery-tab" data-video="7" onclick="window.galleryShowFromTab(7)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">8</button>
<button class="gallery-tab" data-video="8" onclick="window.galleryShowFromTab(8)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">9</button>
</div>
<div style="position: relative;">
<button class="gallery-prev" onclick="window.galleryPrev()" style="position: absolute; left: -40px; top: 50%; transform: translateY(-50%); background: rgba(0,0,0,0.5); color: white; border: none; padding: 20px 12px; cursor: pointer; font-size: 20px; border-radius: 4px; z-index: 10;">‹</button>
<div id="videosContainer" style="display: flex; justify-content: space-between; gap: 5%; padding: 0 50px; overflow: hidden;">
<div class="video-item" data-index="0" style="width: 30%; display: block;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video1.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 1 Description</p>
</div>
<div class="video-item" data-index="1" style="width: 30%; display: block;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video2.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 2 Description</p>
</div>
<div class="video-item" data-index="2" style="width: 30%; display: block;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video3.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 3 Description</p>
</div>
<div class="video-item" data-index="3" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video4.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 4 Description</p>
</div>
<div class="video-item" data-index="4" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video5.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 5 Description</p>
</div>
<div class="video-item" data-index="5" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video6.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 6 Description</p>
</div>
<div class="video-item" data-index="6" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video7.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 7 Description</p>
</div>
<div class="video-item" data-index="7" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video8.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 8 Description</p>
</div>
<div class="video-item" data-index="8" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video9.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 9 Description</p>
</div>
</div>
<button class="gallery-next" onclick="window.galleryNext()" style="position: absolute; right: -40px; top: 50%; transform: translateY(-50%); background: rgba(0,0,0,0.5); color: white; border: none; padding: 20px 12px; cursor: pointer; font-size: 20px; border-radius: 4px; z-index: 10;">›</button>
</div>
</div>

<script>
(function() {
  var currentStart = 0;
  var totalVideos = 9;
  var videosPerPage = 3;
  
  function showVideos(startIndex) {
    var videos = document.querySelectorAll('#videoGallery .video-item');
    var tabs = document.querySelectorAll('#videoGallery .gallery-tab');
    
    if (!videos.length || !tabs.length) return;
    
    for (var i = 0; i < videos.length; i++) {
      videos[i].style.display = 'none';
    }
    
    for (var i = 0; i < tabs.length; i++) {
      tabs[i].style.background = 'white';
      tabs[i].style.color = 'black';
    }
    
    for (var i = 0; i < videosPerPage; i++) {
      var index = startIndex + i;
      if (index < totalVideos && index < videos.length) {
        videos[index].style.display = 'block';
        if (index < tabs.length) {
          tabs[index].style.background = '#007bff';
          tabs[index].style.color = 'white';
        }
      }
    }
    
    currentStart = startIndex;
  }
  
  window.galleryShowFromTab = function(videoIndex) {
    var newStart = Math.max(0, Math.min(videoIndex - 1, totalVideos - videosPerPage));
    showVideos(newStart);
  };
  
  window.galleryPrev = function() {
    var newStart = currentStart - videosPerPage;
    if (newStart < 0) {
      newStart = Math.max(0, totalVideos - videosPerPage);
    }
    showVideos(newStart);
  };
  
  window.galleryNext = function() {
    var newStart = currentStart + videosPerPage;
    if (newStart >= totalVideos) {
      newStart = 0;
    }
    showVideos(newStart);
  };
  
  showVideos(0);
})();
</script>