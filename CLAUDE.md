# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## GOAL

Beginners of RDBMS and SQL can tune databases after reading the documents

## Documents Philosophy - Important things of all things

1. Simplicity: Less Read, More Effective
2. Immediate Effectiveness: Within 1 minute of reading each section, readers can tune RDBMS, SQL, etc.

## Repository Overview

This is a comprehensive Japanese guide for database performance tuning (DBパフォーマンスチューニングの体系的ガイド). The repository contains educational content organized into 7 sequential sections covering different aspects of database optimization.

## Content Structure

The guide is structured as a progressive learning path with numbered sections:

1. **01_monitoring** - Database monitoring fundamentals, tools selection, key metrics, and alerting principles
2. **02_n_plus_1** - N+1 query problem identification and solutions using various ORMs (Prisma, Laravel, GORM)
3. **03_index_structure** - Index fundamentals, B-tree structure, and search optimization
4. **04_analyze_exec_plan** - Execution plan analysis concepts
5. **05_plan_slow_query** - Slow query identification and optimization strategies
6. **06_stress_test** - Load testing methodologies and implementation
7. **07_ex_db_arch** - Advanced database architecture topics

Each section contains:
- A main README.md with detailed explanations
- A res/ subdirectory with SVG diagrams for visual explanations
- Practical code examples using modern frameworks (Next.js, Laravel, Go)
- Implementation checklists for real projects

## Content Language and Audience

- **Primary Language**: Japanese
- **Target Audience**: Software engineers working on database performance optimization
- **Technical Level**: Intermediate to advanced, with practical code examples

## Working with This Repository

When editing content:
- Maintain the existing numbered section structure (01_ through 07_)
- Keep technical explanations in Japanese to match the established style
- Preserve the practical code examples and ORM-specific implementations
- Update SVG diagrams in res/ directories when modifying related concepts
- Maintain the progressive learning structure where concepts build upon previous sections

The guide emphasizes hands-on implementation with specific technology examples (Prisma, Laravel Eloquent, GORM) and includes practical checklists for real-world application.

## Review Standards

Follow ./claude_review.md
