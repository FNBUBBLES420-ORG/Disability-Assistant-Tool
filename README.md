# Disability Assistant Tool

## Overview

Disability Assistant Tool is an accessibility-focused perception and input conditioning system designed to support individuals with physical and cognitive challenges in video-based interactive environments.

This project combines real-time video analysis, adaptive input conditioning, and multimodal feedback to enhance user stability, spatial awareness, and control — while ensuring the user remains fully responsible for all actions.

The system is built using a modular research-oriented architecture to support transparency, reproducibility, and long-term maintainability.

---

## Research Purpose

The primary objective of this project is to explore how real-time perception systems and adaptive input conditioning can improve accessibility in interactive software environments.

The tool focuses on:

* Enhancing visual awareness through structured overlays
* Supporting motor stability through configurable input filtering
* Providing multimodal feedback to reinforce user intent
* Maintaining ethical and transparent system boundaries

This project does not aim to automate user actions. Instead, it strengthens user-driven control through adaptive assistance.

---

## Core Functional Capabilities

### 1. Real-Time Perception Assistance

The system processes a live video feed (e.g., USB capture device or camera input) and performs real-time object detection using configurable AI backends.

Capabilities include:

* Frame-by-frame visual analysis
* Configurable confidence thresholds
* Selectable inference backends (CPU, CUDA, DirectML)
* Optional region masking (left, right, center)
* Visual overlays to reinforce detected spatial information

All analysis occurs externally through video input. The system does not access or modify protected software processes.

---

### 2. Input Conditioning & Motor Stabilization

The tool provides configurable conditioning mechanisms to support users who experience tremors, inconsistent movement patterns, or reduced fine motor control.

Available mechanisms include:

* Adjustable smoothing filters
* Deadzone calibration
* Sensitivity scaling
* Output damping
* Curve-based response shaping
* Runtime enable/disable hotkey control

These features help improve steadiness and predictability while preserving user intent. Movement remains entirely user-driven.

---

### 3. Adaptive Control Modes

To accommodate diverse mobility needs, the system supports multiple control configurations:

* Standard input mode
* Quadriplegic mode
* Single-switch mode
* Joystick integration
* Controller abstraction support
* Adjustable dwell timing
* Breath and head sensitivity configuration

These modes allow customization based on individual accessibility requirements.

---

### 4. Multimodal Feedback System

The tool integrates layered feedback channels to enhance usability:

* Visual overlays
* Optional runtime performance (CPS) display
* Text-to-Speech support (SAPI / pyttsx3)
* Audio cue support
* Runtime state indicator

This multimodal design improves clarity and situational awareness for different sensory preferences.

---

### 5. Hardware Compatibility Framework

The system is engineered for broad hardware support and research flexibility:

* CPU-based inference
* NVIDIA CUDA acceleration
* AMD DirectML acceleration
* ONNX Runtime GPU providers
* USB capture device compatibility
* Standard camera input support

Built-in diagnostic tools report system configuration, GPU availability, device detection, and library support status.

---

## Who It Helps

Disability Assistant Tool is intended to support:

* Individuals with motor impairments
* Individuals experiencing tremors or reduced fine motor precision
* Individuals with limited mobility or muscle control challenges
* Users who rely on adaptive joystick or single-switch systems
* Individuals who benefit from enhanced visual or auditory reinforcement
* Veterans and individuals living with physical service-related disabilities
* Developers and educators researching accessible interface design

The system is configurable to accommodate a wide range of accessibility needs.

---

## Ethical & Safety Boundaries

This project is designed with strict safety and transparency principles.

The system:

* Operates exclusively on video input
* Does not modify external software
* Does not inject into running processes
* Does not alter protected files
* Does not implement automated target lock-on
* Keeps all motion and decision-making user-controlled

Its function is assistive, not autonomous.

---

## Architectural Design

The project follows a modular research architecture separating:

* Vision processing
* Accessibility input handling
* Output routing
* Feedback systems
* System diagnostics
* Educational resources

This separation ensures clarity of responsibility, ease of testing, and long-term scalability.

---

## Mission Statement

Our mission is to expand accessibility through ethical, transparent, and responsible technology.

We are committed to:

* Empowering individuals with disabilities through assistive innovation
* Promoting inclusive design in interactive software environments
* Supporting adaptive technology users with stable and configurable tools
* Enhancing capability without automating user agency
* Maintaining integrity, safety, and technical transparency in development

Disability Assistant Tool exists to improve awareness, stability, and confidence — while preserving user control at all times.

---

## Versioning

This project follows structured versioning to reflect architectural and research maturity.

* **Major Version (X.0.0)** — Significant architectural changes or research milestone releases
* **Minor Version (0.X.0)** — Feature expansions, new accessibility modes, or backend improvements
* **Patch Version (0.0.X)** — Stability fixes, performance refinements, and compatibility updates

Version numbers are intended to communicate development progression clearly to contributors, researchers, and end users.

---

## Nonprofit Attribution

Disability Assistant Tool is developed and maintained under the mission of **FNBubbles420 Org**, a registered 501(c)(3) nonprofit organization focused on accessibility, education, and inclusive technology innovation.

FNBubbles420 Org is committed to:

* Supporting disabled gamers, developers, students, and veterans
* Promoting ethical and responsible assistive technology
* Expanding STEM and accessibility education initiatives
* Building inclusive communities around adaptive innovation

This project reflects the organization’s dedication to empowering individuals through accessible engineering and transparent development practices.
