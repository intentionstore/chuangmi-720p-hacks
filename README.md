# Chuangmi-720p-hacks
<img width="280" src="https://i.imgur.com/K5dGNPg.jpg">
Modified version of <a href="https://github.com/jymbob/fang-hacks">Fang-Hacks</a> to support Xiaomi Chuangmi 720p Camera.
Get telnet access to your Chuangmi 720p Camera.


<div id="quick-links">
<h2>Quick Links</h2>
<a href="#install-guide">Install guide</a><br>
<a href="#ip-address-find">Find your Camera's IP Address</a><br>
<a href="#install-guide">Install guide</a>
</div>

<div id="install-guide">
<h1>Install guide</h1>
<ol>
<li>Set up your Chuangmi camera in the Mi Home app.</a>
<li>Make note of the Camera's IP Address (e.g. 192.168.1.173), find out how to <a href="#ip-address-find">here</a>
<li>Unplug your Camera
<li>Format your Micro SD Card
<li>Copy <code>tf_recovery</code> to your Micro SD card using software like <a href="etcher.io">Etcher</a>
<li>Insert your SD card into the camera.
<li>Plug in your Camera
<li>Wait untill the yellow status light turns solid blue
<li><code>telnet YOUR_CAMERA'S_IP_ADDRESS</code> (Grab the IP Address from Step 2)
</ol>
</div>

<div id="default-logins">
<h1>Default Login</h1>
<code>
username: root
</code>
<code>
password: NONE
</code>
</div>

<div id="ip-address-find">
<h1>Find your Camera's IP Address</h1>
  <div class="steps-card">
    <img width="270" src="https://i.imgur.com/1jR5CKX.png">
    <br>
    <p>Tap the three dots at the top right corner.</p>
  </div>
  <div class="steps-card">
    <img width="270" src="https://i.imgur.com/ehohB7X.png">
    <p>Tap "Device Settings".</p>
    <br>
  </div>
  <div class="steps-card">
    <img width="270" src="https://i.imgur.com/x4kOJTA.png">
    <br>
    <p>Tap "Network info".</p>
  </div>
  <div class="steps-card">
    <img width="270" src="https://i.imgur.com/oiFTk7B.png">
    <br>
    The Camera's full IP address will be displayed.
  </div>
</div>
