# Source: https://avatarfactory.io/help/render-times-models-and-the-receipt

Help Center

Explainer

# Render times, models, and what the render receipt means

How long a render takes, what Kling v3 and HeyGen Avatar IV each do and cost per second, and how to read the render receipt and the fallback badge.

Videos · Last reviewed September 15, 2026 · 4 min read

## How long a render takes

The oven screen gives the range: most videos are ready in 10 to 20 minutes, and long ones can take more. The confirmation dialog before the render says “Rendering takes a few minutes.” Both are ranges, not promises. The length of the video, the number of shots and the queue on our side all move the number.

While it runs:

- The video’s card on the Videos page shows the current stage (“Rendering shot 2 of 3”, “Stitching hook + body”, “Burning captions”) and a countdown such as “~2m left” once the system has enough history to estimate.
- The video page shows the same progress on the player, plus the scenes that are already ready.
- You can close the tab. We email you and add an in-app notification when the render finishes.

Adding captions from the video page afterwards is a separate, shorter job: “about a minute or two”, and the file downloads by itself when ready.

## The two video models

Every shot renders with one of two models. The wizard’s model menu names them:

| Model | What it does | Credits |
| --- | --- | --- |
| [HeyGen Avatar IV](https://avatarfactory.io/models/heygen) | Talking head, lip-synced. Your avatar speaks the transcript. | 1 credit per second |
| [Kling v3](https://avatarfactory.io/models/kling-3) | Cinematic motion, camera moves. Best for hooks and action shots. | 2 credits per second |

Voice is included in both rates. A talking-head shot can run 3 to 120 seconds; a cinematic shot runs 3 to 10 seconds. The Starter plan renders HeyGen Avatar IV only and caps a video at 45 seconds; Creator and Influencer unlock Kling v3 and remove the cap.

The credit cost of a render is the sum of each shot’s rate times its seconds. The Shots footer shows it on the button, **Generate · N cr**, and the confirmation dialog repeats it with what stays in your balance.

i

A Full Clone of a reel is a separate 10-credit charge for the shot-by-shot analysis. The render itself is priced as above.

## Reading the render receipt

The You Shipped screen shows a “Render Receipt” card with “wall time”, the real minutes and seconds the render took. Below it, one row per slice of the timeline:

- **A time range and a model**, for example “0:00 - 0:05 Kling v3, 5s clip” followed by “0:05 - 0:58 HeyGen Avatar IV, 53s clip”. This maps every second of the video to the engine that produced it.
- **voice**: the voice track, marked “full track”. The receipt names the voice engine, ElevenLabs v3.
- **subtitles**: “Captions subtitles added, word-level”. This row appears only when you set Subtitles to On.

Above the receipt, the title card carries chips for the length, the resolution (1080×1920 for a finished reel), the captions state, and the render path badge.

## The render path badge and fallbacks

The badge tells you what actually ran:

- **HeyGen + Kling**: both engines rendered their shots as planned.
- **HeyGen only**: the whole script rendered as a talking head.
- **HeyGen only (fallback)**: a cinematic shot or the stitch failed, and the talking-head engine rendered the full script instead. A “Fallback reason” line appears under the chips.

On the video page, the same information sits next to the status badge as ”⚠ Rendered with fallback” with a note such as “One or more shots fell back to HeyGen.” Each shot card also carries an engine pill, “Kling V3 · Motion” or “HeyGen · Avatar IV”, so you can see which take you are looking at.

A fallback is not a failure. The video is complete and downloadable. If the fallback take does not fit, use **Fix This Shot** on that shot to regenerate it. See [Download, captions, QA and regenerate](https://avatarfactory.io/help/download-captions-qa-and-regenerate).

## What slows a render down

- More shots and longer shots. Each shot is its own job, then everything is stitched.
- Cinematic shots. Motion rendering takes longer per second than a talking head.
- Scenes that still need generating. **Generate scenes + video** generates the missing scenes first, then renders.
- Captions. Burning captions is the last stage of the render when Subtitles is On.

If a render passes the top of the range by a wide margin and the card still shows a stage, write to [Support@AvatarFactory.IO](mailto:Support@AvatarFactory.IO) with the video ID and the time you started it. We check the job on our side.

## Frequently asked questions

Why does my video say HeyGen only (fallback)? +

A cinematic shot did not come back from its engine, so the talking-head engine rendered that part instead of failing the whole video. The badge and the note under the title tell you this happened, and the receipt shows which model produced each slice. Regenerate the shot if the fallback take does not fit.

**Ready to time your own render?** Pick a plan, add your card, and build the avatar that will front these renders.

[Start Your $1 Trial](https://app.avatarfactory.io/register) $1 three-day trial · 15 credits · Cancel anytime

**Was this helpful?** One click. It tells us which articles to rewrite first.

Thanks, noted.

Yes, thanks No, I still need help

**Still stuck?** Tell us what happened, we answer within one business day.

[Contact Support](https://avatarfactory.io/help/contact) Include the video name so we can find the render. Prefer your own mail app? [Support@AvatarFactory.IO](mailto:Support@AvatarFactory.IO) reaches the same inbox.