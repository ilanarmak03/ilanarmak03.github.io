---
layout: default
title: Ali Kamran
---

<div class="hero" id="about">
  <p class="eyebrow">ali@portfolio:~$ whoami</p>

  <h2>Computer Science student focused on low-level systems, compilers, and embedded computing.</h2>

  <p>
    I am interested in computer architecture, compiler infrastructure, real-time systems,
    and embedded development. My work includes LLVM and RISC-V compiler research,
    machine-level program analysis, safety-critical synchronization, STM32 firmware,
    robotics, FPGA design, and ROS2.
  </p>
</div>

<section id="experience">
  <div class="section-title">
    <span class="prompt">01.</span>
    <h2>Experience</h2>
  </div>

  <div class="card">
    <h3>Capstone Research — Timing-Predictable Atomic Synchronization</h3>

    <div class="meta">
      YorkArch Research Lab · York University · January 2026 – Present
    </div>

    <p>
      Working on timing-predictable atomic synchronization for safety-critical
      cyber-physical systems, with a focus on multicore computer architecture,
      RISC-V, and predictable execution behavior.
    </p>

    <p>
      My compiler work involves modifying LLVM's RISC-V backend and developing
      machine-level analysis and transformation passes for atomic LR/SC sequences,
      inline assembly, control flow, and instruction lowering. I also work with
      LLVM IR, MIR, backend pass pipelines, and RISC-V instruction selection.
    </p>

    <div class="tags">
      <span class="tag">LLVM</span>
      <span class="tag">RISC-V</span>
      <span class="tag">C++</span>
      <span class="tag">MIR</span>
      <span class="tag">Compiler Backend</span>
      <span class="tag">Computer Architecture</span>
    </div>
  </div>

  <div class="card">
    <h3>Embedded Systems Member — York University Robotics Society</h3>

    <div class="meta">
      Mars Rover Team · February 2025 – August 2025
    </div>

    <p>
      Developed embedded and navigation software for a Mars rover platform.
      Programmed STM32 microcontrollers with FreeRTOS, interfaced a u-blox GPS
      receiver over UART, transmitted telemetry over CAN bus, and built ROS2
      navigation software for coordinate-based distance and heading calculations.
    </p>

    <p>
      Also implemented ADC-based voltage monitoring on an ARM Cortex-M4 and
      transmitted measurements across the rover's CAN network.
    </p>

    <div class="tags">
      <span class="tag">STM32</span>
      <span class="tag">FreeRTOS</span>
      <span class="tag">CAN</span>
      <span class="tag">UART</span>
      <span class="tag">ROS2</span>
      <span class="tag">Python</span>
    </div>
  </div>
</section>

<section id="projects">
  <div class="section-title">
    <span class="prompt">02.</span>
    <h2>Selected Projects</h2>
  </div>

  <div class="card">
    <h3>Object Detection with ROS2 & YOLOv8</h3>

    <p>
      Built a ROS2 computer-vision pipeline that connects camera nodes with
      YOLOv8 for real-time object detection and classification, allowing image
      data and detection results to move between sensing and compute components.
    </p>

    <div class="tags">
      <span class="tag">ROS2</span>
      <span class="tag">Python</span>
      <span class="tag">YOLOv8</span>
      <span class="tag">Computer Vision</span>
    </div>
  </div>

  <div class="card">
    <h3>STM32 Air Quality Monitor</h3>

    <p>
      Developed an STM32-based environmental monitoring system using an AHT21
      temperature and humidity sensor together with an ENS160 gas sensor.
      Sensor data is acquired over I²C, used for environmental compensation,
      and reported through UART as air-quality measurements including AQI,
      eCO₂, and TVOC.
    </p>

    <div class="tags">
      <span class="tag">STM32</span>
      <span class="tag">C</span>
      <span class="tag">I²C</span>
      <span class="tag">UART</span>
      <span class="tag">Sensors</span>
    </div>
  </div>

  <div class="card">
    <h3>FPGA Note Generator</h3>

    <p>
      Designed a selectable digital note generator on a DE10-Lite FPGA using
      Verilog. The design includes hardware frequency measurement, seven-segment
      display output, UART telemetry, and a C++ host application for real-time
      audio playback.
    </p>

    <div class="tags">
      <span class="tag">FPGA</span>
      <span class="tag">Verilog</span>
      <span class="tag">UART</span>
      <span class="tag">C++</span>
      <span class="tag">Digital Logic</span>
    </div>
  </div>
</section>

<section id="skills">
  <div class="section-title">
    <span class="prompt">03.</span>
    <h2>Skills</h2>
  </div>

  <div class="skills-grid">

    <div class="card skill-group">
      <h3>languages[]</h3>
      <p>
        C, C++, Python, C#, Java, Verilog,
        RISC-V Assembly, Bash, PowerShell, JavaScript
      </p>
    </div>

    <div class="card skill-group">
      <h3>systems[]</h3>
      <p>
        LLVM, RISC-V, Linux, Git, compiler backends,
        machine-level analysis, LLVM IR, MIR
      </p>
    </div>

    <div class="card skill-group">
      <h3>embedded[]</h3>
      <p>
        STM32, ARM Cortex-M4, ATmega328P,
        FreeRTOS, CAN, UART, I²C, ADC, PWM
      </p>
    </div>

    <div class="card skill-group">
      <h3>hardware[]</h3>
      <p>
        FPGA development, electronic prototyping,
        soldering, sensor integration, robotics
      </p>
    </div>

    <div class="card skill-group">
      <h3>measurement[]</h3>
      <p>
        Oscilloscopes, multimeters, logic analyzers,
        spectrum analyzers, vector network analyzers
      </p>
    </div>

    <div class="card skill-group">
      <h3>databases[]</h3>
      <p>
        MySQL, PostgreSQL, SQLite,
        Microsoft SQL Server, MongoDB
      </p>
    </div>

  </div>
</section>

<section id="education">
  <div class="section-title">
    <span class="prompt">04.</span>
    <h2>Education</h2>
  </div>

  <div class="card">
    <h3>York University</h3>

    <div class="meta">
      Honours Bachelor of Computer Science · 2024 – 2027
    </div>

    <p>
      Toronto, Ontario, Canada
    </p>

    <p>
      <strong>Relevant coursework:</strong>
      Embedded Systems, Digital Logic Design, Computer Architecture,
      RISC-V, SystemVerilog, Computer Organization, Operating Systems,
      Signals and Systems, and Design & Analysis of Algorithms.
    </p>
  </div>
</section>

</section>
<section id="contact">
  <div class="section-title"><span class="prompt">05.</span><h2>Contact</h2></div>
  <div class="contact-grid">
    <div class="contact-item">
      <strong>github</strong>
      <a href="https://github.com/ilanarmak03" target="_blank" rel="noreferrer">github.com/ilanarmak03</a>
    </div>
    <div class="contact-item">
      <strong>email</strong>
      <a href="mailto:akamran0318@gmail.com">akamran0318@gmail.com</a>
    </div>
    <div class="contact-item">
      <strong>linkedin</strong>
      <a href="https://www.linkedin.com/in/ali-kamran813/" target="_blank" rel="noreferrer">LinkedIn</a>
    </div>
    <div class="contact-item">
      <strong>resume</strong>
      <a href="/assets/Ali_Kamran_Resume_June_18_2026.pdf">Download PDF</a>
    </div>
  </div>
</section>
