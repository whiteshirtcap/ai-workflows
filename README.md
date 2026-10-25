# AI Workflows & Structured JSON Templates

An open-source collection of structured prompt engineering frameworks, camera/media parameter JSON schemas, and regional language transcription workflows designed for OpenAI models.

## Features
- **Structured JSON Scripts:** Ready-to-use JSON schemas for consistent data extraction and generative media parameters.
- **Automated Workflows:** Multi-step prompt templates for text, vision, and audio processing.
- **Regional Localization:** Tools and conversational adaptation scripts for regional Indian languages (including Malayalam).

## Example: Camera & Lighting Specification Schema (JSON)
```json
{
  "scene_config": {
    "camera_movement": "360-degree orbital motion",
    "lens": "35mm prime, f/1.8",
    "lighting": "cinematic volumetric lighting, high contrast",
    "resolution": "8K ultra-realistic"
  }
}
System: You are an expert bilingual transcriber. 
Task: Generate a second-by-second timestamped transcript of the provided audio and adapt the spoken content into natural, conversational phrasing while preserving cultural context.
