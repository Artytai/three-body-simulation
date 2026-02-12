<h1>🌌 Three-Body Problem — Advanced Simulation</h1>

<p>
An interactive browser-based simulation of the <strong>gravitational three-body problem</strong>
featuring multiple high-accuracy numerical integrators, adaptive time stepping,
and real-time conservation diagnostics.
</p>

<p><strong>Built with vanilla JavaScript + HTML5 Canvas (no dependencies).</strong></p>

<hr/>

<h2>✨ Features</h2>

<ul>
  <li><strong>Integrators</strong>
    <ul>
      <li>Symplectic Verlet (Leapfrog)</li>
      <li>Yoshida 4th Order (Symplectic)</li>
      <li>RK4</li>
      <li>Adaptive RKF45 (Cash–Karp)</li>
    </ul>
  </li>
  <li><strong>Live Physics Monitoring</strong>
    <ul>
      <li>Total Energy (E)</li>
      <li>Linear Momentum (|P|)</li>
      <li>Angular Momentum (|L|)</li>
      <li>Adaptive timestep display</li>
    </ul>
  </li>
  <li><strong>Collision Modes</strong>
    <ul>
      <li>Merge (momentum conserving)</li>
      <li>Elastic collisions</li>
      <li>Pass-through</li>
    </ul>
  </li>
  <li><strong>Visualization</strong>
    <ul>
      <li>Adjustable trails</li>
      <li>Velocity vectors</li>
      <li>Zoom &amp; pan</li>
      <li>Center-of-mass mini view</li>
    </ul>
  </li>
  <li><strong>Presets</strong>
    <ul>
      <li>Figure-8 orbit</li>
      <li>Lagrange triangle orbit</li>
    </ul>
  </li>
  <li>Import / Export simulation state (JSON)</li>
</ul>

<hr/>

<h2>🚀 Run Locally</h2>

<pre><code>git clone https://github.com/yourusername/three-body-simulation.git
</code></pre>

<p>Open <code>index.html</code> in your browser. No setup required.</p>

<hr/>

<h2>🎮 Controls</h2>

<ul>
  <li><strong>Space</strong> — Play / Pause</li>
  <li><strong>S</strong> — Step</li>
  <li><strong>R</strong> — Reset</li>
  <li><strong>C</strong> — Clear trails</li>
  <li>Drag to pan, scroll to zoom, double-click to recenter</li>
</ul>

<hr/>

<h2>📚 About</h2>

<p>
The three-body problem has no general closed-form solution and exhibits chaotic behavior.
This simulation allows exploration of:
</p>

<ul>
  <li>Long-term energy conservation (symplectic vs RK methods)</li>
  <li>Adaptive timestepping during close encounters</li>
  <li>Sensitivity to initial conditions</li>
  <li>Chaotic orbital motion</li>
</ul>

<hr/>

<h2>📄 License</h2>

<p>MIT License (or your preferred license)</p>

