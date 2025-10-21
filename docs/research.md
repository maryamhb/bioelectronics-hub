---
layout: default
title: Research
permalink: /research/
---

# Research

This page catalogues key bioelectronics research projects — organised by development phase. Click on any project to expand and see details.

<div class="research-tabs">
  <button class="tab-button active" data-tab="current">Current Research</button>
  <button class="tab-button" data-tab="past">Past Research</button>
  <button class="tab-button" data-tab="future">Future Directions</button>
</div>

<div id="current" class="tab-content active">

<h3>Capacitive Sensing Front-Ends</h3>

<p><strong>Focus:</strong> High-resolution acquisition of biomedical signals with ultra-low power consumption</p>

<p><strong>Technical Approach:</strong> Low-noise analogue front-end design, adaptive gain control, noise filtering</p>

<p><strong>Clinical Impact:</strong> Enables precise long-term monitoring in wearable and implantable systems for real-time health tracking</p>

<p><strong>Key Challenges:</strong> Power efficiency, signal integrity in noisy environments, miniaturisation</p>

<hr>

<h3>Modular ASIC Architectures</h3>

<p><strong>Focus:</strong> Developing scalable, low-power mixed-signal designs for diverse bioelectronic applications</p>

<p><strong>Technical Approach:</strong> Reusable circuit blocks for sensing, stimulation, telemetry, and data processing</p>

<p><strong>Clinical Impact:</strong> Accelerates prototyping cycles and enables faster translation to clinical devices</p>

<p><strong>Key Advantages:</strong> Reduced design time, cost-effective scaling, modular system integration</p>

<hr>

<h3>Neurocare Collaboration Initiatives</h3>

<p><strong>Focus:</strong> Strategic clinical partnerships to advance bioelectronic support systems for neurological conditions</p>

<p><strong>Technical Approach:</strong> Signal acquisition and processing, closed-loop control algorithms, patient-specific device adaptation</p>

<p><strong>Clinical Impact:</strong> Enables personalised therapeutic strategies for diverse neurological conditions</p>

<p><strong>Collaboration Model:</strong> Co-design with clinicians, iterative validation, evidence-based optimisation</p>

<hr>

</div>

<div id="past" class="tab-content">

<h3>Mixed-Signal Sensor Interfaces</h3>

<p><strong>Focus:</strong> CMOS designs in 180nm and 65nm technology nodes for biomedical signal acquisition</p>

<p><strong>Technical Achievement:</strong> Low-power ADC implementations, innovative capacitive readout circuits for sensor interfaces</p>

<p><strong>Validation:</strong> Lab characterisation and preclinical testing in representative conditions</p>

<p><strong>Outcome:</strong> Foundation for current and future mixed-signal designs</p>

<hr>

<h3>Active Regenerative Neural Interface (aMNI)</h3>

<p><strong>Focus:</strong> Bidirectional cardiac control through autonomic nervous system modulation</p>

<p><strong>Technical Achievement:</strong> Closed-loop stimulation protocols with adaptive feedback mechanisms</p>

<p><strong>Clinical Application:</strong> Support for cardiac function in patients with autonomic dysfunction</p>

<p><strong>Impact:</strong> Demonstrated feasibility of closed-loop neuromodulation approaches</p>

<hr>

<h3>Epidural Electrical Stimulation (EES)</h3>

<p><strong>Focus:</strong> Motor recovery and rehabilitation in spinal cord injury patients</p>

<p><strong>Technical Achievement:</strong> Multi-site stimulation strategies with optimised gait pattern parameters</p>

<p><strong>Clinical Outcome:</strong> Restored walking function in previously paralysed patients</p>

<p><strong>Significance:</strong> Landmark study demonstrating feasibility of epidural stimulation for motor recovery</p>

<hr>

</div>

<div id="future" class="tab-content">

<h3>Tumour Monitoring via Capacitive Sensors</h3>

<p><strong>Vision:</strong> Real-time, non-invasive tracking of tumour dynamics and response to therapy</p>

<p><strong>Technical Approach:</strong> High-precision capacitive sensor arrays integrated with biofluid interfaces</p>

<p><strong>Clinical Potential:</strong> Enables adaptive therapy protocols and early intervention based on tumour status</p>

<p><strong>Research Goals:</strong> Sensor validation, biomarker identification, clinical pilot study design</p>

<hr>

<h3>Bioelectronic Therapy for Parkinson's Disease</h3>

<p><strong>Vision:</strong> Minimally invasive neuromodulation to improve motor control and quality of life</p>

<p><strong>Technical Approach:</strong> Implantable closed-loop devices with adaptive stimulation and wearable monitoring interfaces</p>

<p><strong>Clinical Target:</strong> Patients with advanced Parkinson's disease resistant to conventional treatments</p>

<p><strong>Research Roadmap:</strong> Animal studies, device optimisation, ethics approval, clinical trial design</p>

<hr>

</div>

<script>
// Tab switching
document.querySelectorAll('.research-tabs .tab-button').forEach(button => {
  button.addEventListener('click', () => {
    const tabName = button.getAttribute('data-tab');

    // Hide all tab contents
    document.querySelectorAll('.tab-content').forEach(content => {
      content.classList.remove('active');
    });

    // Remove active class from all buttons
    document.querySelectorAll('.research-tabs .tab-button').forEach(btn => {
      btn.classList.remove('active');
    });

    // Show selected tab and mark button as active
    document.getElementById(tabName).classList.add('active');
    button.classList.add('active');
  });
});
</script>
