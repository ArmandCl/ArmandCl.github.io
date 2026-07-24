---
title: "Tuning a Keycube into a music instrument "
show_permalink: false
excerpt: "<img src='/images/keycube.jpg' alt='The Keycube'>"
collection: portfolio
---

<div style="text-align: justify;">

<p>During my year in Canada, I had the opportunity to work with Damien Brun, one of the creators of the Keycube. My project consisted of repurposing this innovative tool to transform it into a real musical instrument.</p>
<div style="text-align: center;">
    <img src='/images/keycube_usage.jpg' alt='The Keycube usage' height="350" width="265">
    <p><i>Example of the Keycube being used with a mixed reality headset</i></p>
</div>

<h3>What is the Keycube?</h3>
<p>The Keycube is a tangible, portable, cubic text-entry device. It was designed to adapt to virtual, augmented, and mixed environments. Its main features are:</p>
<ul>
  <li>It has 80 physical keys distributed across five of its faces.</li>
  <li>It features a touch screen on its sixth face, which also serves as a base to rest the device.</li>
  <li>It is equipped with a 6-DoF inertial measurement unit (accelerometer and gyroscope) and a motor providing vibrotactile feedback.</li>
  <li>Its form factor allows for high mobility and adapts to numerous body postures.</li>
</ul>

<p>You can learn more about the Keycube by reading the paper written by Damien Brun, Charles Gouin-Vallerand, and Sébastien George: <a href='https://dumas.ccsd.cnrs.fr/IUTLAVAL/hal-02942093v1' target='_blank'>click here</a>.
</p>

<div style="text-align: center;">
    <img src='/images/keycube_upper_view.png' alt='The Keycube view from above' height="300" width="425">
    <p><i> Image of the Keycube software including interactive layout, mapping and emulation</i></p>
</div>

<h3>My project: Turning the Keycube into an instrument</h3>
<p>For my project, I worked on transforming this interface into an interactive musical instrument, notably by using an Adafruit MacroPad RP2040. Here is how I proceeded:</p>
<ul>
  <li><strong>Initial approach with sound frequencies:</strong> I initially programmed the board in CircuitPython via the Mu Editor IDE to directly generate a specific sound frequency (standard musical notes) when a key was pressed.</li>
  <li><strong>Evolution into a MIDI controller:</strong> To achieve more realistic sounds, I modified the code by integrating the <code>adafruit_midi</code> and <code>usb_midi</code> libraries to send MIDI messages directly to the computer via USB.</li>
  <li><strong>Sound interpretation on PC:</strong> I used the VirtualMIDISynth software combined with a digital soundbank (<code>.sf2</code> file) and the MIDI-OX software to capture the MIDI signals from the board and translate them into real piano notes.</li>
  <li><strong>Adding advanced features:</strong> To finalize the project, I utilized specific keys on the device to allow the user to change instruments on the fly (for instance, switching from a piano to a violin or a guitar), while the other keys were used to play the melody.</li>
</ul>

<p>This experience was not only highly engaging but also incredibly rewarding, opening the door to an area of computer science and hardware integration I had never explored before.</p>

<p>Feel free to contact me if you have any questions about this project.</p>

</div>

