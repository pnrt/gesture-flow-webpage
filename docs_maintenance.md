# User Documentation Maintenance Guide

This guide explains how to update the `docs.html` user manual to keep it accurate as you add new features to GestureFlow.

## 1. Style & Tone
The documentation is written for **non-technical users**. 
- Avoid technical jargon (e.g., instead of "Context Injection", use "Setting up").
- Use bullet points and step-by-step cards for readability.
- Keep descriptions focused on **benefits** (what the user can achieve).

## 2. Adding New Nodes
If you add a new node type (e.g., "Loop Start"):
1. Open `docs.html`.
2. Find the `<div class="node-grid">` section.
3. Add a new `<div class="node-item">` block.
4. Include a simple name, a 1-sentence description, and a `config-list` div for what settings the user needs to provide.

## 3. Updating Setup Instructions
If a new Android permission is required (e.g., "Screen Recording"):
1. Find the `<section id="setup">`.
2. Add a new `<div class="step-card">`.
3. Increment the step number in the `<div class="step-number">`.

## 4. Maintenance of "Pro Tips"
As you discover better ways to use the app:
- Add them to the `<section id="tips">` using the `<div class="tip-box">` class.
- Use emojis (like 💡, ⏳, 🔗) to make tips stand out.

## 5. Visual Consistency
- **Fonts:** The doc uses "Inter" from Google Fonts.
- **Colors:** Primary brand color is `#1A73E8` (Google Blue).
- **Navigation:** If you add a new major section, add an entry to the `<nav>` list and ensure the `id` in the `<section>` matches the `href`.

---
*Maintained by the GestureFlow Design Team.*
