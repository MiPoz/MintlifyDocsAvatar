# Source: https://avatarfactory.io/help/generation-failed-or-timed-out

Help Center

Troubleshooting

# Face or scene generation failed or timed out

What each face and scene error message means, what to try first, what happens to your credits, and what to send us if it keeps failing.

Avatars · Last reviewed September 28, 2026 · 3 min read

## First, the short answer

Most face and scene failures are one-off. Click **Try again** on the tile, or send the ask again in the Image Studio, and it usually works. A generation that failed should not use a credit. If it keeps failing, the fixes below are ordered from most to least likely.

## The messages and what they mean

| What you see | Where | What it means |
| --- | --- | --- |
| ”Couldn’t generate this face” with **Try again** | Face step, one tile | That one candidate failed. The other two are untouched. |
| ”Face generation failed.” | Face step | The whole batch was rejected. |
| ”Face generation timed out. Try again.” | Face step | The batch ran past eight minutes with no result. |
| ”The refine failed. Try again in a moment.” | Face step, refine sheet | The refine call did not come back. The original face is kept. |
| ”Uploading your photo failed. Try again.” | Face step or import Upload step | The file did not reach us. |
| ”Generation failed. Try again.” | Image Studio | The scene render was rejected. |
| ”Generation timed out. Try again.” | Image Studio | The scene ran past eight minutes with no result. |
| ”Couldn’t generate this one” on an option | Image Studio | That option failed; the other options still land. Click **Try again** under the reply. |
| ”Refine failed. Try again.” | Avatar page, Change profile picture | The regenerate with notes did not come back. |
| ”Upgrade to a paid plan to create scenes and videos.” | Image Studio, video wizard | Your account is on the trial. Scenes and videos start with your paid plan. |

## Fix it

1. **Try once more.** Click **Try again** under the failed reply, or send the ask again. Wait for the countdown; a face batch starts near “~75s left” and a refine near “~30s left”. The count holds near ten seconds at the end. That is normal.
2. **Leave the tab open during a face batch if you can.** If you do close it, reopening the wizard reattaches to the running job instead of starting a new one.
3. **Simplify the description.** Contradictions (“bald, long hair”), real celebrity names, brand logos, or anything the content rules block can make a generation fail every time. Remove the line and try again.
4. **Check the reference image.** In Exact match mode and in the import wizard, the file must be a PNG or JPG (WebP and HEIC work too) under 15 MB. If the message names the file, fix the file. A tiny, blurry or heavily filtered photo can also produce a failed face.
5. **Check your connection.** A timed-out generation often means the browser lost the poll. Refresh the page and look at the grid: the image may already be there.
6. **Check your credits.** Open **Billing**. If the balance is zero, generation stops. See [Out of credits or daily limit](https://avatarfactory.io/help/out-of-credits-or-daily-limit).
7. **Wait a few minutes.** If several generations fail in a row with the same message, the image service may be having a moment. Give it a while and try again.

> **Warning:** Each **Try again** on a face tile is a new generation, and a successful retry is one credit. Retrying five times on a description that will never pass costs five credits. Fix the description first.

## Your credits

A job that failed or produced nothing should not use a credit. If your balance went down anyway, send us the details below and we check the job on our side. Credits for failed generations go back; that is the policy, no argument needed. See [Credits and failed renders](https://avatarfactory.io/help/credits-and-failed-renders).

## If it still fails, write to us

Send one message to [Support@AvatarFactory.IO](mailto:Support@AvatarFactory.IO) with:

- your account email
- the avatar name, and the scene or face you were generating
- the exact message you saw, or a screenshot
- roughly when it happened, with your time zone
- the device and browser

We reply within one business day and tell you what we found.

## Frequently asked questions

Was I charged for a face that failed? +

A generation that never produced an image should not use a credit. If your balance dropped after a failed or timed-out generation, write to Support@AvatarFactory.IO with your account email, the avatar name, the time, and the message you saw. We check the job on our side and put the credits back.

Why does the countdown stop at about ten seconds? +

The countdown is an estimate. A face batch starts around 75 seconds and a refine around 30. When the estimate runs out and the image has not landed, the label holds near ten seconds instead of going to zero, because the tail end is unknowable. The generation is still running; give it a moment.

**Was this helpful?** One click. It tells us which articles to rewrite first.

Thanks, noted.

Yes, thanks No, I still need help

**Still stuck?** Tell us what happened, we answer within one business day.

[Contact Support](https://avatarfactory.io/help/contact) Include the email on your account so we can find you. Prefer your own mail app? [Support@AvatarFactory.IO](mailto:Support@AvatarFactory.IO) reaches the same inbox.