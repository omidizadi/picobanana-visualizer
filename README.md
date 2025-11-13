# Picobanana Visualizer

<img width="1459" height="1218" alt="Screenshot 2025-11-13 at 11 04 15 AM" src="https://github.com/user-attachments/assets/6a0822b0-3e39-47c4-8ec4-a47b98213c1d" />


Quick online version: [Link](https://snazzy-selkie-ebdccf.netlify.app/)

## Required Files

Download the following files from the [Picobanana repository](https://github.com/apple/pico-banana-400k):

### JSONL Files
- [sft.jsonl](https://ml-site.cdn-apple.com/datasets/pico-banana-300k/nb/jsonl/sft.jsonl)
- [preference.jsonl](https://ml-site.cdn-apple.com/datasets/pico-banana-300k/nb/jsonl/preference.jsonl)
- [multi-turn.jsonl](https://ml-site.cdn-apple.com/datasets/pico-banana-300k/nb/jsonl/multi-turn.jsonl)

### Manifest Files
- [sft_manifest.txt](https://ml-site.cdn-apple.com/datasets/pico-banana-300k/nb/manifest/sft_manifest.txt)
- [preference_manifest.txt](https://ml-site.cdn-apple.com/datasets/pico-banana-300k/nb/manifest/preference_manifest.txt)
- [multi_turn_manifest.txt](https://ml-site.cdn-apple.com/datasets/pico-banana-300k/nb/manifest/multi_turn_manifest.txt)

## Running a Local Server

To view the files in your browser, run a local HTTP server:

```bash
python3 -m http.server 8000
```

Then open your browser and navigate to:
```
http://localhost:8000
```

This will display the `index.html` file and allow you to browse the dataset files.
