<!DOCTYPE html>
<html lang="en">
<body>

<h1>STOMP-IT-TO-DEATH: Javascript/HTML Pedal Board for Modern Browsers</h1>
<p>The nice thing about JavaScript, CSS and HTML is there is no compiling. Just use your web browser to launch the pedal board, or place it on a mini web server. The easiest way to launch is here  (Example - HOW TO USE):</p>
<p><code>firefox WebPedalBoard.html</code></p>

<p>
    <strong>STOMP-IT-TO-DEATH (Revision 11)</strong>: I made this because I was tired of messing with JACK, PipeWire, and Guitarix on Linux. I didn’t want to fire up a whole audio setup just for jamming; I just wanted to open a web browser and start playing.Google Gemini and I wrote this in JavaScript using a text editor (kwrite in linux). JavaScript is cross‑platform and works with any modern OS including Windows, Linux, Mac OS. This was written in a couple of hours on the weekend for myself, but I thought it would be fun to place this on GitHub, and make it available for the enjoyment of others. 
</p>

<p>
    Created by Ronald Stoddard with Google Gemini, Google Debugger, and a text editor. The design Ideas are entirely mine, which I got the idea from reading about Linus, of Linux fame creating guitar stomp boxes and placing those ideas on GitHub. It was a early Saturday morning idea, between reading Reddit and playing with the Guitars and my six year old. I had read that Linus was using AI to create guitar effects ideas and manipulate actual code. I thought... why... not!
</p>
<h2>Getting Started</h2>

<h3>Power On</h3>
<ul>
    <li>Click the large <strong>OFF</strong> button at the top center.</li>
    <li>It will turn <strong>red</strong> and display <strong>POWER ON</strong>.</li>
    <li>Your browser will prompt for microphone access — choose <strong>Allow</strong> and the microphone you would like to use.</li>
</ul>

<h3>Audio Input</h3>
<p>STOMP-IT-TO-DEATH automatically uses your system’s default microphone or audio interface.</p>

<h3>Suggestions on how to start</h3>
<ul>
    <li>Start with low volume — distortion pedals can be loud.</li>
    <li>Disable any stomp boxes that are not needed for your desired effect</li>
    <li>Start with only one or two instead of all 5. </li>
</ul>



<h2>Signal Chain & Routing</h2>

<p>The signal flows from left to right through five customizable slots.</p>

<h3>Changing Effects</h3>
<p>Use the dropdown menu above any slot to change the effect (e.g., replace Delay with Distortion, etc.).</p>

<h3>Bypass (Stomp)</h3>
<ul>
    <li>Click the small ON/OFF button below any pedal.</li>
    <li><strong>Green</strong> = active.</li>
    <li><strong>Grey</strong> = bypassed (signal passes through unaffected).</li>
</ul>

<h3>How are signals Routed within the JavaScript?</h3>
<p>
    Input → Slot 1 → Slot 2 → Slot 3 → Slot 4 → Slot 5 → Master Limiter → EQ → Stereo/Mono → Output
</p>

<h2>Pedal Controls</h2>

<h3>MZ-2 (MT‑2)</h3>
<ul>
    <li><strong>Gate:</strong> Noise gate threshold (left = more noise reduction).</li>
    <li><strong>Dist:</strong> Amount of saturation/gain.</li>
    <li><strong>Low/High:</strong> Bass and treble shelving EQ.</li>
    <li><strong>Mid Freq:</strong> Select midrange frequency (200Hz–5kHz).</li>
    <li><strong>Mid Gain:</strong> Boost/cut selected mid frequency.</li>
</ul>
<p><em>Tip: For classic metal, boost Dist and cut Mid Gain.</em></p>

<h3>Chorus</h3>
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

<h3>Stereo / Mono Switching</h3>
<ul>
    <li><strong>STEREO OFF:</strong> Mono output.</li>
    <li><strong>STEREO ON (Cyan):</strong> Activates Haas Effect.</li>
</ul>

<p><strong>How it works:</strong>Simulating a Stereo Sound FX</p>
<ul>
    <li>Left channel = dry.</li>
    <li>Right channel = delayed by 20ms.</li>
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
    <li>Use different System Microphone or Input type
    <li>Use wired headphones for best performance.</li>
</ul>

<h3>No Sound</h3>
<ul>
    <li>Ensure Power On is active.</li>
    <li>Check browser microphone permissions. Make sure to accept input</li>
</ul>

<section>
    <h1>PANCAKE MENU GUIDE</h1>
    <p>Preset Management & System Operations</p>

    <div>
        <h3>1. Load Preset</h3>
        <p>
            This dropdown list displays every tone you have saved to your browser database. 
            Selecting a name instantly reconfigures the entire pedalboard—including routing order, 
            knob positions, and bypass states.
        </p>
    </div>

    <div>
        <h3>2. Save Preset</h3>
        <p>
            Captures your current sound. It saves the <b>signal chain</b> (pedal order), 
            <b>parameter values</b> (all slider positions), and <b>global settings</b> 
            (Stereo/Mono) into the internal browser database.
        </p>
    </div>

    <div>
        <h3>3. Download JSON</h3>
        <p>
            Extracts your entire collection of presets from the browser and saves them 
            as a <code>.json</code> file on your hard drive. Use this for off-site 
            backups or to share your "Tone Pack" with others.
        </p>
    </div>

    <div>
        <h3>4. Upload JSON</h3>
        <p>
            Reads a <code>.json</code> file from your computer and merges those presets 
            into your current library. It does not overwrite your existing sounds unless 
            they share the exact same name.
        </p>
    </div>

    <div>
        <h3>5. Unload Presets (Reset)</h3>
        <p>
            <b>WARNING:</b> This is a destructive action. It performs a <b>Hard Reset</b> by:
        </p>
        <ul>
            <li>Wiping the internal browser database (IndexedDB).</li>
            <li>Returning all sliders and routing to factory default values.</li>
        </ul>
    </div>

    <hr>

    <p>
        <i><b>TECHNICAL NOTE:</b> This app uses <b>IndexedDB</b> technology. 
        Unlike standard cookies, this allows your presets to be stored locally on 
        your device with no size limit, ensuring your custom tones are ready every 
        time you load the page.</i>
    </p>
</section>

</body>
</html>
