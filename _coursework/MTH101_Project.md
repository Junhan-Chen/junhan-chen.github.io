---
title: "Design of a Technique for Analyzing Linear Time-Invariant Systems with Time-Varying Parameters Using Laplace Transform"
permalink: /coursework/MTH101_Project/
author_profile: true
---

# Design of a Technique for Analyzing Linear Time-Invariant Systems with Time-Varying Parameters Using Laplace Transform

**Team:** Junhan Chen, Shengda Gao, Yiwen Wang, Yulin Xia, Yang Tian, Siyuan Lin  
**Course:** MTH101 Engineering Mathematics  
**Institution:** Xi'an Jiaotong-Liverpool University  
**Date:** Oct 2024 – Dec 2024

---

## Project Overview

This project investigates how Linear Time-Invariant (LTI) systems with time-varying parameters can be analysed using a modified Laplace transform framework. Classical Laplace-transform-based analysis typically assumes constant system parameters, which limits its ability to represent real engineering systems whose parameters change over time.

To address this limitation, the project explores the use of a **Modified Laplace Transform (MLT)** that extends the traditional transform framework to handle differential equations with time-varying coefficients. :contentReference[oaicite:0]{index=0}

---

## Problem Background

LTI systems are widely used in control systems, signal processing, and communications. However, many real systems contain parameters that vary with time due to environmental disturbances or internal dynamics. Traditional analysis methods often assume constant coefficients, which makes modelling these systems less accurate. :contentReference[oaicite:1]{index=1}

This project examines whether a modified transform-based approach can provide a practical analytical method for studying such systems.

---

## Mathematical Approach

The project first revisits the classical **Laplace Transform**, which converts time-domain differential equations into algebraic equations in the frequency domain.

Based on this framework, a **Modified Laplace Transform (MLT)** is introduced by incorporating a correction factor that allows time-varying parameters to be represented within the transform process. This extension enables differential equations with variable coefficients to be analysed using transform-based techniques. :contentReference[oaicite:2]{index=2}

---

## Case Study: Spring–Mass–Damper System

To demonstrate the approach, the method was applied to a **spring–mass–damper system with time-varying parameters**, including time-dependent mass, damping coefficient, and spring stiffness.

The governing differential equation of the system was derived and transformed using the modified Laplace framework, allowing the dynamic behaviour of the system to be analysed analytically. :contentReference[oaicite:3]{index=3}

*(A conceptual diagram of the spring–mass–damper system is shown in the report.)*

---

## Numerical Verification

To evaluate the effectiveness of the proposed method, the analytical solution obtained through the Modified Laplace Transform was compared with numerical simulations.

MATLAB was used to simulate the displacement response of the system over time. The comparison between analytical displacement and numerical displacement showed strong agreement, indicating that the proposed method can effectively capture the dynamic behaviour of systems with time-varying parameters. :contentReference[oaicite:4]{index=4}

---

## Key Takeaways

This project demonstrates how classical transform-based system analysis can be extended to systems with time-varying parameters. The Modified Laplace Transform provides a useful framework for analysing differential equations with variable coefficients and offers insights into modelling dynamic engineering systems more accurately.
