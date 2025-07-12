# Yoruba_TTS_Project
Yoruba Text-to-Speech App using ElevenLabs, Gradio and Google Collab

## Language Focus
This project focuses on converting **Yoruba** text into speech using ElevenLabs API and Gradio for the web interface. Yoruba is a Nigerian language, and tones are essential for correct pronunciation.

## Voice ID Used
Voice ID: `eOHsvebhdtt0XFeHVMQY`  
(This voice was selected for been the closest Nigerian-Yoruba accent.)

## Language Pronunciation Handling
Yoruba tones and diacritics were automatically applied using a **custom word-mapping function**. For example, input like `mo nife re` is converted to `Mo nífẹ̀ẹ́ rẹ`. This formatting improves pronunciation when sent to the ElevenLabs API. Some other yoruba word mapping includes `["nife": "nífẹ̀ẹ́", "mo": "Mo", "re": "rẹ", "e": "ẹ", "je": "jẹ", "gba": "gbọ́", etc]`.

## How to Use
1. Enter Yoruba text (with tones)
2. Paste your ElevenLabs Voice ID and API Key
3. Click Submit to play and download the generated audio

## Kí Ọlọ́run bù kún ẹ.
---
