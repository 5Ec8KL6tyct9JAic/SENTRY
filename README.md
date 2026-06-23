# SENTRY

## Overview

SENTRY is a lightweight security monitoring system designed to collect, process, and analyze system and network logs in order to detect suspicious activity in real time or near real time. The project simulates the core concepts of a Security Information and Event Management (SIEM) system in a simplified and modular form.

It is intended as a practical cybersecurity project focused on log analysis, detection logic, and security event correlation.

---

## Purpose

The main goal of SENTRY is to provide a structured approach to understanding how security monitoring systems operate in real environments.

It is designed to:

- Demonstrate how raw logs can be transformed into structured security events
- Implement basic detection logic for common attack patterns
- Simulate real-world SOC (Security Operations Center) workflows
- Serve as a foundation for more advanced security engineering projects

---

## Functionality

SENTRY processes incoming logs through a pipeline that standardizes and analyzes events. It applies rule-based detection logic to identify potentially malicious behavior and generates alerts when predefined conditions are met.

The system focuses on detecting patterns such as:

- Repeated authentication failures (brute-force attempts)
- Unusual login behavior or access patterns
- Suspicious privilege usage
- Anomalous system activity spikes

All events are normalized into a consistent format to enable correlation and rule evaluation.

---

## Intended Use

SENTRY is not intended for production deployment. It is designed for:

- Cybersecurity learning and practice
- Portfolio demonstration for SOC / blue team roles
- Experimentation with log analysis and detection techniques
- Understanding SIEM-like architectures at a simplified level

---

## Design Principles

The project is built around the following principles:

- Modularity: each component handles a specific stage of the pipeline
- Simplicity: minimal dependencies to focus on core security logic
- Extensibility: easy integration of new detection rules and data sources
- Transparency: readable and maintainable structure for educational use

---

## Limitations

SENTRY is a simplified model and does not include:

- Advanced threat intelligence integration
- Machine learning-based anomaly detection (by default)
- Large-scale distributed log processing
- Enterprise-grade security guarantees

It is intended as a conceptual and practical learning tool rather than a production-grade security solution.

---

## License

MIT License
