# WebPedalBoard
Javascript/HTML pedal board for Modern Browser to go Guitar Effects (Stomp Boxes)

Use your webbrowser to launch EXAMPLE: firefox WebPedalBoard.html

This manual covers the operation of the Master Studio Rig (Revision 2), which introduced the Stereo Widening switch and the corrected Chorus engine.
This was created by Ronald Stoddard and Gemini in JavaScript with a text editor :). Javascript has the destinction of being cross-platform and will work with any modern OS/System.  

1. Getting Started
Power On: Click the large OFF button at the top left. It will turn RED and say POWER ON.

Note: You must allow microphone access when prompted by your browser.

Audio Input: The rig automatically grabs your default system microphone or audio interface input.

Safety: Always start with your volume low, as the distortion pedals can be loud.

2. Signal Chain & Routing
The signal flows from Left to Right through 5 customizable slots.

Changing Effects: Use the dropdown menu above any slot to change the effect (e.g., swap a Delay for a second Distortion).

Bypass (Stomp): Click the small ON/OFF button below any pedal to bypass it instantly. Green means the effect is active. Grey means it is bypassed (signal passes through unaffected).

Signal Path: Input → Slot 1 → Slot 2 → Slot 3 → Slot 4 → Slot 5 → Master Limiter → EQ → Stereo/Mono → Output

3. Pedal Controls
Metal Zone 2 (MT-2)
Gate: Controls the noise gate threshold. Slide left to cut background hiss/feedback.

Dist: Controls the amount of saturation/gain.

Low/High: Shelving EQ for bass and treble response.

Mid Freq: Selects the specific midrange frequency to cut or boost (200Hz - 5kHz).

Mid Gain: Cuts or boosts the selected Mid Frequency. Tip: For a classic metal sound, boost the Dist, and cut the Mid Gain.

Chorus (New Fixed Logic)
Rate: Speed of the modulation.

Mix: Blends the wet (effected) and dry signal.

Update Note: This version features a 30ms base delay buffer to prevent the "scratching" artifacts present in older versions.

Flanger
Speed: Controls how fast the "jet plane" swoosh moves.

Mix: Intensity of the effect.

Wah
Sweep: Manually controls the filter frequency (like rocking a physical wah pedal).

Mix: Blends the wah effect with the clean signal.

Delay
Time: Length of the echo (0.1s to 1.0s).

Mix: Volume of the repeats.

4. Master Section
12-Band Graphic EQ
Located at the bottom of the screen.

Frequencies: 12 sliders ranging from 32Hz (sub-bass) to 16kHz (air/sparkle).

Usage: Drag sliders up to boost or down to cut specific frequencies.

EQ Mix: The master fader on the right blends the EQ'd signal with the raw signal.

Stereo / Mono Switch
Located next to the Record button.

STEREO OFF: The output is Mono (center channel only).

STEREO ON (Cyan): Activates the Haas Effect.

How it works: The left channel remains dry. The right channel is delayed by 20ms.

Result: This creates a psychoacoustic "wide" stereo image, simulating two guitars playing at once.

Waveform Visualizer
Displays the real-time audio signal (Post-EQ, Pre-Output).

5. Recording
Start: Click START RECORDING. The button will turn Red and pulse.

Stop: Click the button again (labeled STOP).

Save: A green DL (Download) link will appear next to the button. Click it to save your riff as a .ogg file.

6. Troubleshooting
Feedback/Squealing: Increase the Gate threshold on the Metal Zone pedal or lower your speaker volume (if not using headphones).

Latency (Delay): If there is a delay between playing and hearing, it is likely due to your browser or Bluetooth headphones. Wired headphones are recommended.

No Sound: Ensure "Power On" is active and your browser microphone permissions are set to "Allow".
