# VeriProof AI — Digital Content Verification MVP

## Overview

VeriProof AI is an early-stage prototype designed to help assess the authenticity and reliability of digital video content.

The MVP demonstrates an AI-assisted verification workflow that combines automated content analysis with a human verification layer.

## Problem

Digital platforms contain a large amount of manipulated, misleading, or unverifiable video content. Users often have difficulty determining whether a piece of content is trustworthy.

VeriProof aims to provide a structured verification workflow for digital content.

## MVP Workflow

1. Upload one or more video files.
2. The system creates a unique SHA-256 fingerprint for each video.
3. Video metadata is extracted.
4. The MVP samples video frames for analysis.
5. Audio information is analysed where supported by the browser.
6. Individual verification indicators are generated for each uploaded case.
7. The system calculates an overall AI screening result.
8. Cases requiring additional verification can be passed to human review.
9. A reviewer can record evidence, notes, and verification status.
10. Verification results can be exported as a case record.

## Key Features

- Multiple video upload
- Individual case processing
- SHA-256 content fingerprinting
- Video metadata extraction
- Frame sampling
- Browser-based analysis
- AI-assisted screening workflow
- Human verification layer
- Evidence and reviewer notes
- Verify / Reject / Pending workflow
- Case record export

## Technology

- HTML5
- JavaScript
- Web APIs
- File API
- Web Crypto API
- HTML Video API
- Browser-based processing

## Project Status

This project is an MVP/prototype developed to demonstrate the proposed VeriProof digital content verification workflow.

It is not intended to replace professional fact-checking or establish absolute truth about a video.

## Future Development

Future versions may integrate:

- Advanced AI/deepfake detection models
- Image and video forensic analysis
- Source verification
- Metadata and provenance analysis
- Trusted evidence sources
- Human reviewer networks
- Platform integrations
- Verification certificates
- Scalable cloud infrastructure

## Vision

The long-term vision of VeriProof is to make digital content independently verifiable and help users make more informed decisions about the content they encounter online.

---

**Project:** VeriProof AI Verification MVP  
**Developer:** Setti Ramasai  
**Domain:** AI / Digital Content Verification  
