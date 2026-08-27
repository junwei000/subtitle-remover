# Subtitle Remover

**Remove hardcoded subtitles. Keep videos clean.**

🌐 <https://subtitleremover.com>

Subtitle Remover is an AI tool that erases hard-coded subtitles, captions, watermarks and on-screen text from any video — reconstructing what was actually behind them, frame by frame, instead of covering them with a blur, mosaic or black bar.

---

## Why it's different

| | Typical editors (CapCut, VLC, ffmpeg) | Subtitle Remover |
| --- | --- | --- |
| Soft subtitle tracks | Can hide / strip them | Not needed — use ffmpeg `-sn` |
| Burned-in captions | Mosaic or cover-up only | Rebuilds the real pixels behind the text |
| Watermarks & logos | Manual patching | Auto or hand-drawn region erase |
| Result | Visible blur / bar | Clean frame, no artifacts |

Burned-in subtitles are part of the picture, not a separate track. Removing them properly requires reconstructing the image, which is what Subtitle Remover does using a temporal inpainting model — it looks at frames before and after to rebuild the missing pixels.

## Key features

- **Auto subtitle detection** — high-frame-rate OCR finds lower-screen captions for one-click removal
- **Manual region erase** — draw boxes around any text, watermark or logo for precise control
- **AI pixel reconstruction** — no blur, no mosaic, no black bars
- **Any language** — including Chinese and English burned-in captions, 30+ languages
- **Watermark & logo cleanup** — channel marks, overlays and timecode burn-ins
- **Large files** — uploads up to 1 GB, input up to 2K, clean MP4 output up to 1080p
- **Optional AI Video Enhancer** — sharpen details and reduce compression artifacts
- **Privacy first** — source and output files auto-delete after 30 days; your videos are never used for training

## How it works

1. **Upload your clip** — drag & drop MP4 / MOV / MKV; duration and resolution are read automatically
2. **Pick auto or manual** — let OCR detect captions, or box exactly what you want erased
3. **Let the AI rebuild** — every frame is inpainted in the background; no need to keep the page open
4. **Download the clean video** — subtitle-free 1080p MP4, available in your task list

## Use cases

- Clean subtitles out of Seedance and other AI-generated videos without paying to regenerate them
- Prepare subtitle-free source footage for localization into other languages
- Strip burned-in captions before adding your own branded subtitles
- Repurpose short-form drama and social clips for TikTok, YouTube Shorts, Instagram Reels and ads
- Restore legacy lecture, broadcast or archive footage with permanent on-screen overlays

> Only process videos you own or are authorized to edit.

## Pricing

Billing is **per second of video**, so you only pay for what you process:

| Mode | Cost |
| --- | --- |
| Auto detection | 1 credit / second |
| Manual region | 3 credits / second |

Credits come as one-time packs (valid 1 year) or a monthly subscription (refreshed each billing period, no rollover). Payments are processed by Stripe. Current packages: <https://subtitleremover.com/pricing>

## Processing time

Processing runs in the background and scales with clip length. Clips over 1 minute average roughly 6–10× real time (a 2-minute video ≈ 12–20 minutes); clips under 1 minute average around 25× real time.

## Built with

Next.js · React · Tailwind CSS · shadcn/ui · Vercel

## Links

- Website — <https://subtitleremover.com>
- Pricing — <https://subtitleremover.com/pricing>
- Blog — <https://subtitleremover.com/blog>
- Support — <mailto:support@subtitleremover.com>
