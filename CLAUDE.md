# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is the Reality Knowledge Framework (RKF) repository - a structured cross-disciplinary knowledge map containing 200 core concepts for understanding how the world works, sharpening thinking, and making better decisions. The framework is organized into 5 Parts, 20 Chapters, and 200 Core Concepts, all documented in Indonesian.

## Structure

The repository is currently documentation-only, containing:
- `README.md`: Complete framework documentation with all 200 concepts organized across 5 parts:
  - Part I: Foundations (40 concepts) - Basic thinking, logic, mathematical intuition, uncertainty
  - Part II: Causality (30 concepts) - Causal thinking, experiments, observational studies  
  - Part III: Systems (40 concepts) - System fundamentals, dynamics, networks, optimization
  - Part IV: Tools & Methods (50 concepts) - Data foundations, statistics, modeling, simulation, communication
  - Part V: Decisions & Action (40 concepts) - Decision frameworks, prioritization, implementation, ethics

## Content Language

All documentation is in Indonesian (Bahasa Indonesia). When working with content from this repository, maintain the Indonesian language unless specifically requested to translate.

## Repository Purpose

This is a knowledge framework repository designed to provide structured thinking tools rather than executable code. Any future development should focus on:
- Expanding the conceptual framework
- Creating implementation examples for the 200 concepts
- Building educational materials or interactive tools based on the framework
- Maintaining the structured organization of concepts across the 5 parts

## Development Commands

This repository is documentation-focused with no build system. Common tasks:

### Content Management
- **View structure**: `find . -name "*.md" | grep -E "(part-|chapter-)" | head -20`
- **Search concepts**: `grep -r "keyword" . --include="*.md"`
- **Check completeness**: Compare existing files against the 200-concept framework in README.md

### Git Operations
- Standard git workflow for version control
- No special build or deployment steps required
- All content is in markdown format

## Content Development Guidelines

### Writing Standards
Each concept file follows a proven narrative structure:
1. **Opening Story** - Real historical case or contemporary example
2. **Problem Definition** - Clear explanation of the concept
3. **Mechanism** - Why our brains work this way (evolutionary/psychological)
4. **Modern Applications** - Business, technology, personal applications
5. **Case Studies** - Multiple detailed examples across domains
6. **Practical Strategies** - Specific, actionable techniques
7. **Digital Age Context** - How internet/social media affects the concept
8. **Why It Matters** - Broader implications for decision-making
9. **Practice Exercises** - Concrete weekly challenges for readers

### Quality Requirements
- **Evidence-based**: Every claim supported by research or logical reasoning
- **Practical**: Always include actionable applications  
- **Cross-domain**: Show applications across personal, professional, societal contexts
- **Comprehensive**: ~3,000-4,000 words per concept
- **Engaging**: Narrative-driven storytelling mixed with rigorous analysis

### File Naming Convention
- Concepts: `001-concept-name.md` through `200-concept-name.md`
- Chapters: `chapter-##-descriptive-name/`
- Parts: `part-#-section-name/`