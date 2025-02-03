---
#title: "AudioMiXR"
#layout: home
---
<style>
.wrapper {
    width: 100%;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
}
#teaser {
    background: black;
    width: 100%;
    height: 600px;
    margin: 0;
    padding: 0;
    position: absolute;
    right: 0;
    overflow: hidden;
}

#ghost {
    width: 100%;
    height: 600px;
}

/* Style the video: 100% width and height to cover the entire window */
#myVideo {
  position: relative;
  right: 0;
  top: -300px;
  min-width: 50%;
  min-height:100%;
}

/* Add some content at the bottom of the video/page */
.content {
  position: fixed;
  bottom: 0;
  background: rgba(0, 0, 0, 0.5);
  color: #f1f1f1;
  width: 100%;
  padding: 20px;
}

/* Style the button used to pause/play the video */
#myBtn {
  width: 200px;
  font-size: 18px;
  padding: 10px;
  border: none;
  background: #000;
  color: #fff;
  cursor: pointer;
}

</style>
<div id="teaser">
    <video autoplay muted loop id="myVideo">
    <source src="./static/temple.MOV" type="video/mp4">
    </video>
</div>

<div id="ghost">
    <span>Hello</span>
</div>

AudioMiXR, an AR interface intended to assess how users manipulate virtual audio objects situated in their physical space using 6DoF deployed on a head-mounted display (Apple Vision Pro) for 3D sound design.

<!--
Here is a list of all our posts available at the moment:
<ul>
  {% for post in site.posts reversed %}
    <li>
      <a href="{{margaritageleta.github.io}}{{site.baseurl}}{{post.permalink}}">{{post.title}}</a><br/>
      {{ post.description }}
  </li>
    {% if {{post.image}} != null %}
    <div style="width: 100%; height:200px; display:flex; justify-content: center; align-items: center; margin-top: 15px; margin-bottom: 15px;">  
      <div style="background-image: url('{{post.image}}'); height:100%; width:80%; background-repeat: no-repeat; background-size: cover;"></div>
    </div>
    {% endif %}
  {% endfor %}
</ul>

-->