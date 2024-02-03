---
layout: splash
title: "Robotic Arm"
permalink: /roboticArm/
header:
  overlay_color: "#000"
  overlay_filter: "0.7"
  overlay_image: /_pages/projects/roboticArm/roboticArmHeader.jpg
excerpt: Symphony of CS MECH ELEC & AI 
---

## Overview
- 6DOF robotic arm driven by stepper drivers
- Incorporates cycloidal gearbox, planetary gearbox, and HTD belts
- Features a differential belt wrist to reduce end effector weight
- Utilizes closed-loop joint control with magnetic encoders

## Project Motivation
- Opportunity to practice full-stack robotics development
- Integration of mechanical design, embedded computer science, AI, and electronics
- Exploration of combining AI and robotics with the use of Transformer models

## MECH
<div style="display: flex; align-items: flex-start;">
  <div style="margin-right: 20px;">
    <video autoplay muted loop style="max-width: 250px">
      <source src="/_pages/projects/roboticArm/roboticArm_CycloidalDrive.mp4" type="video/mp4">
    </video>
    <p>Cycloidal Drive 1</p>
  </div>
  <div style="margin-right: 20px; max-width: 250px">
    <video autoplay muted loop style="max-width: 250px">
      <source src="/_pages/projects/roboticArm/roboticArm_thrustBearing_01.mp4" type="video/mp4">
    </video>
    <p>Custom Thrust Bearing</p>
  </div>
  <div style="margin-right: 20px; max-width: 250px">
    <video autoplay muted loop style="max-width: 250px">
      <source src="/_pages/projects/roboticArm/roboticArm_DOF0405_MECH.mp4" type="video/mp4">
    </video>
    <p>Belt driven differential joint</p>
    <p>Heavily influenced by Mishin Machine <a href="https://www.youtube.com/watch?v=jgyOXb1IKqw&list=PLfLlepaYmO2DNpGID9dzKq6MJUIjV4Q5L&index=1">link</a></p>
  </div>
</div>

## CS
<div style="display: flex; align-items: flex-start;">
  <div style="margin-right: 20px; max-width: 450px">
    <video autoplay muted loop style="max-width: 250px">
      <source src="/_pages/projects/roboticArm/roboticArm_COMP_MoveitRos.mp4" type="video/mp4">
    </video>
    <p>MoveIt Ros simulation</p>
  </div>
  <div style="margin-right: 20px; max-width: 450px">
    <video autoplay muted loop style="max-width: 250px">
      <source src="/_pages/projects/roboticArm/roboticArm_COMP_FullRun.mp4" type="video/mp4">
    </video>
    <p>Random motion test</p>
  </div>
</div>

## ELEC
<div style="display: flex; align-items: flex-start;">
  <div style="margin-right: 20px; max-width: 450px">
    <img src="/_pages/projects/roboticArm/roboticArm_PCB.jpg" width="450px" height="auto">
    <p>Iterated through multiple versions of PCB</p>
  </div>
</div>

