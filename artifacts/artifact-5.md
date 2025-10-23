

<style>
:root { color-scheme: dark; }
body { background:#0a2f1f; color:#e5e7eb; } /* dark green */
a { color:#86efac; }
hr { border-color:#134e33; }

.site-header { background:rgba(11,18,32,0.98); border:0; }
.site-title, .site-title:visited { color:#ffffff !important; }
.site-nav .page-link { color:#e5e7eb !important; }
.site-nav .page-link:hover, .site-nav .page-link:focus {
  color:#ffffff !important; text-decoration: underline;
}

.page-content a { /* lighter on hover just in main content area */
  color:#93c5fd;
}
.page-content a:hover,
.page-content a:focus {
  color:#ffffff;
}
.wrapper { max-width: 1080px; margin: 1.25rem auto; padding: 0 1rem; }
.player {
  position: relative; width: 100%; aspect-ratio: 16/9;
  background: #000; border-radius: 12px; overflow: hidden;
  box-shadow: 0 10px 30px rgba(0,0,0,.35);
}
.player video { width: 100%; height: 100%; display: block; }
</style>

<div class="wrapper">
  <h1>Artifact 5 — Demo Video</h1>

  <div class="player">
    <video
      autoplay
      playsinline
      loop
      controls
      preload="metadata"
      <source src="/assets/media/rick-roll-video-meme-template-video-1da252ec.mp44" type="video/mp4" />
      Your browser doesn’t support HTML5 video.
    </video>
  </div>

  <p style="margin-top:1rem">
    If autoplay doesn’t start, click play (some browsers require interaction).
    <a href="/assets/media/rick-roll-video-meme-template-video-1da252ec.mp44" download>Download the MP4</a>.
  </p>

  <p><a href="/">Back to Home</a></p>
</div>
