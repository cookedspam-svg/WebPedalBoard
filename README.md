<!DOCTYPE html>
<html lang="en">
<body>

<h1>Javascript/HTML Pedal Board for Modern Browsers</h1>
<p>Use your web browser to launch the pedal board. Example:</p>
<p><code>firefox WebPedalBoard.html</code></p>

<p>
    This manual covers the operation of the <strong>Master Studio Rig (Revision 2)</strong>, 
    which introduced the Stereo Widening switch and the corrected Chorus engine. 
    Created by Ronald Stoddard and Gemini in JavaScript using a text editor. 
    JavaScript is cross‑platform and works with any modern OS.
</p>

<h2>Getting Started</h2>

<h3>Power On</h3>
<ul>
    <li>Click the large <strong>OFF</strong> button at the top center.</li>
    <li>It will turn <strong>red</strong> and display <strong>POWER ON</strong>.</li>
    <li>Your browser will prompt for microphone access — choose <strong>Allow</strong> and the microphone you would like to use.</li>
</ul>

<h3>Audio Input</h3>
<p>The rig automatically uses your system’s default microphone or audio interface.</p>

<h3>Safety</h3>
<p>Start with low volume — distortion pedals can be loud.</p>

<h2>Signal Chain & Routing</h2>

<p>The signal flows from left to right through five customizable slots.</p>

<h3>Changing Effects</h3>
<p>Use the dropdown menu above any slot to change the effect (e.g., replace Delay with Distortion).</p>

<h3>Bypass (Stomp)</h3>
<ul>
    <li>Click the small ON/OFF button below any pedal.</li>
    <li><strong>Green</strong> = active.</li>
    <li><strong>Grey</strong> = bypassed (signal passes through unaffected).</li>
</ul>

<h3>Signal Path</h3>
<p>
    Input → Slot 1 → Slot 2 → Slot 3 → Slot 4 → Slot 5 → Master Limiter → EQ → Stereo/Mono → Output
</p>

<h2>Pedal Controls</h2>

<h3>Metal Zone 2 (MT‑2)</h3>
<ul>
    <li><strong>Gate:</strong> Noise gate threshold (left = more noise reduction).</li>
    <li><strong>Dist:</strong> Amount of saturation/gain.</li>
    <li><strong>Low/High:</strong> Bass and treble shelving EQ.</li>
    <li><strong>Mid Freq:</strong> Select midrange frequency (200Hz–5kHz).</li>
    <li><strong>Mid Gain:</strong> Boost/cut selected mid frequency.</li>
</ul>
<p><em>Tip: For classic metal, boost Dist and cut Mid Gain.</em></p>

<h3>Chorus (New Fixed Logic)</h3>
<ul>
    <li><strong>Rate:</strong> Modulation speed.</li>
    <li><strong>Mix:</strong> Wet/dry blend.</li>
</ul>
<p><strong>Update:</strong> Includes a 30ms base delay buffer to eliminate “scratching” artifacts.</p>

<h3>Flanger</h3>
<ul>
    <li><strong>Speed:</strong> Rate of the “jet plane” sweep.</li>
    <li><strong>Mix:</strong> Effect intensity.</li>
</ul>

<h3>Wah</h3>
<ul>
    <li><strong>Sweep:</strong> Manual filter frequency control.</li>
    <li><strong>Mix:</strong> Wah/clean blend.</li>
</ul>

<h3>Delay</h3>
<ul>
    <li><strong>Time:</strong> Echo length (0.1s–1.0s).</li>
    <li><strong>Mix:</strong> Volume of repeats.</li>
</ul>

<h2>Master Section</h2>

<h3>12‑Band Graphic EQ</h3>
<ul>
    <li>12 sliders from 32Hz (sub‑bass) to 16kHz (air/sparkle).</li>
    <li>Drag sliders up to boost or down to cut.</li>
    <li><strong>EQ Mix:</strong> Master fader blends EQ’d signal with raw signal.</li>
</ul>

<h3>Stereo / Mono Switch</h3>
<ul>
    <li><strong>STEREO OFF:</strong> Mono output.</li>
    <li><strong>STEREO ON (Cyan):</strong> Activates Haas Effect.</li>
</ul>

<p><strong>How it works:</strong></p>
<ul>
    <li>Left channel = dry.</li>
    <li>Right channel = delayed by 20ms.</li>
    <li>Creates a wide stereo image (like two guitars).</li>
</ul>

<h3>Waveform Visualizer</h3>
<p>Shows real‑time audio (post‑EQ, pre‑output).</p>

<h3>Recording</h3>
<ul>
    <li><strong>Start:</strong> Click <strong>START RECORDING</strong> (button turns red and pulses).</li>
    <li><strong>Stop:</strong> Click again (button labeled STOP).</li>
    <li><strong>Save:</strong> A green <strong>DL</strong> link appears — click to download .ogg file.</li>
</ul>

<h2>Troubleshooting</h2>

<h3>Feedback / Squealing</h3>
<ul>
    <li>Increase Gate threshold on Metal Zone.</li>
    <li>Lower speaker volume (use headphones if possible).</li>
</ul>

<h3>Latency (Delay)</h3>
<ul>
    <li>Often caused by browser or Bluetooth headphones.</li>
    <li>Use wired headphones for best performance.</li>
</ul>

<h3>No Sound</h3>
<ul>
    <li>Ensure Power On is active.</li>
    <li>Check browser microphone permissions.</li>
</ul>

</body>
</html>
