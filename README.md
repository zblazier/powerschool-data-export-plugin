# powerschool-data-export-plugin
Export clean section data for import into Clever

# PowerSchool Data Export Plugin

## Overview
This project demonstrates a custom PowerSchool plugin designed to extract and export section-level data for integration with external systems such as Clever and curriculum vendors.

The plugin leverages PowerSchool PowerQuery to generate structured datasets that can be scheduled and delivered through the Data Export Manager.

---

## Problem
Educational systems often require:

- consistent section-level data exports
- integration with third-party platforms (e.g., Clever, curriculum tools)
- accurate term, course, and teacher mappings

Out-of-the-box exports may not meet vendor-specific requirements.

---

## Solution
This plugin provides:

- custom SQL-based data extraction
- structured output aligned to vendor requirements
- integration with PowerSchool Data Export Manager
- automated, repeatable data delivery

---

## Features

- Custom PowerQuery definition for section-level data
- Joins across:
  - sections
  - terms
  - courses
- Standardized output fields including:
  - term dates
  - course details
  - section identifiers
  - teacher and school associations
- Permission mapping for controlled access
- Plugin-based deployment within PowerSchool

---

## Example Query

The plugin defines a PowerQuery that extracts section data with term and course context:

:contentReference[oaicite:0]{index=0}

---

## Technologies Used

- SQL (PowerSchool / Oracle-based)
- PowerQuery framework
- XML plugin architecture
- PowerSchool plugin system

---

## How It Works

1. Plugin is installed in PowerSchool
2. PowerQuery becomes available via API
3. Query can be:
   - accessed directly
   - scheduled via Data Export Manager
4. Output is used for vendor integrations

---

## Notes

- Sensitive identifiers and environment-specific details have been removed or generalized
- Designed for demonstration of enterprise data extraction workflows
- Reflects real-world SIS integration patterns

---

## Purpose

This project demonstrates:

- SQL-based data modeling
- system integration design
- enterprise plugin development
- structured data export pipelines
