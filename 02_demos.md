## DEMOs

***<center>"Unify Computer Vision, Expand Computer Vision, Transcend Computer Vision."</center>***

### Best Practices


### Advanced Features

<div id="videoGallery" style="max-width: 100%; margin: 40px auto;">
<div style="display: flex; justify-content: center; gap: 5px; margin-bottom: 20px; flex-wrap: wrap;">
<button class="gallery-tab" data-video="0" onclick="window.galleryShowFromTab(0)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">1: consistency</button>
<button class="gallery-tab" data-video="1" onclick="window.galleryShowFromTab(1)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">2: native 3D+t</button>
<button class="gallery-tab" data-video="2" onclick="window.galleryShowFromTab(2)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">3: variable resolution</button>
<button class="gallery-tab" data-video="3" onclick="window.galleryShowFromTab(3)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">4: unlimited duration</button>
<button class="gallery-tab" data-video="4" onclick="window.galleryShowFromTab(4)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">5: predicting the future</button>
<button class="gallery-tab" data-video="5" onclick="window.galleryShowFromTab(5)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">6: variable FPS</button>
<button class="gallery-tab" data-video="6" onclick="window.galleryShowFromTab(6)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">7: physics</button>
<button class="gallery-tab" data-video="7" onclick="window.galleryShowFromTab(7)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">8: causality</button>
<button class="gallery-tab" data-video="8" onclick="window.galleryShowFromTab(8)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">9: predicting the past</button>
<button class="gallery-tab" data-video="9" onclick="window.galleryShowFromTab(9)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">10: pixel-level control</button>
<button class="gallery-tab" data-video="10" onclick="window.galleryShowFromTab(10)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">11: synchronizing</button>
<button class="gallery-tab" data-video="11" onclick="window.galleryShowFromTab(11)" style="padding: 6px 12px; border: 1px solid #ddd; background: white; cursor: pointer; border-radius: 4px;">12: training the world</button>
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
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 1: consistency</p>
</div>
<div class="video-item" data-index="1" style="width: 30%; display: block;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video2.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 2: native 3D+t</p>
</div>
<div class="video-item" data-index="2" style="width: 30%; display: block;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video3.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 3: variable resolution</p>
</div>
<div class="video-item" data-index="3" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video4.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 4: unlimited duration</p>
</div>
<div class="video-item" data-index="4" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video5.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 5: predicting the future</p>
</div>
<div class="video-item" data-index="5" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video6.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 6: variable FPS</p>
</div>
<div class="video-item" data-index="6" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video7.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 7: physics</p>
</div>
<div class="video-item" data-index="7" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video8.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 8: causality</p>
</div>
<div class="video-item" data-index="8" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video9.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 9: predicting the past</p>
</div>
<div class="video-item" data-index="9" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video10.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 10: pixel-level control of the world distribution</p>
</div>
<div class="video-item" data-index="10" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video11.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 11: synchronizing the real world with model's core space</p>
</div>
<div class="video-item" data-index="11" style="width: 30%; display: none;">
<div style="position: relative; padding-bottom: 100%; background: #f0f0f0; border-radius: 8px; overflow: hidden;">
<video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" controls muted loop>
<source src="./static/demos/video12.mp4" type="video/mp4">
</video>
</div>
<p style="text-align: center; margin-top: 10px; font-size: 14px;">Video 12: training the world itself</p>
</div>
</div>
<button class="gallery-next" onclick="window.galleryNext()" style="position: absolute; right: -40px; top: 50%; transform: translateY(-50%); background: rgba(0,0,0,0.5); color: white; border: none; padding: 20px 12px; cursor: pointer; font-size: 20px; border-radius: 4px; z-index: 10;">›</button>
</div>
</div>

<center>As mentioned above, this is only a proof of concept. The core space for simulating the operation of the world was obtained solely from Depth Map training (without the need for RGB in the training process), and it is currently rather weak, but the advanced features therein are not present in the previous models. We aim to extend simple shapes to any realistic shapes in the next version.</center>

<script>
(function() {
  var currentStart = 0;
  var totalVideos = 12;
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