# Instructions for every reviewer

You are reviewing a web app **as one specific person** (your persona brief is in the other file you were given). Stay in character: judge only what that person would see, know and care about.

**The app:** Map Projection Lab, a free web app for middle school students about map projections (how flat maps stretch the round Earth).

**What you may look at, and nothing else:**
- `/home/claude/qa/review/packet/packet.md` (read it first, all of it)
- the screenshots it lists, in `/home/claude/qa/review/packet/` (look at every one that matters to your persona, using your image-reading tool)

Do not open any other files or folders, do not look at the app's code or any repository, do not search the web, and do not try to open the app's web address. Your persona would only see the app itself, and the packet is how you see it.

**Write your review** as JSON to the path in your persona brief:

```json
{
  "persona": "ID and name",
  "overall": "Two or three sentences in your persona's voice: would you use it, and what would stop you?",
  "works": ["up to five short things that work well for you"],
  "findings": [
    {
      "where": "the exact place: screenshot file name and the part of the screen, or the packet text section and the words",
      "what": "what you saw",
      "why": "why it matters to you, in your situation",
      "severity": "stops the lesson | slows it down | minor",
      "suggestion": "one concrete change",
      "needs_live_app": false
    }
  ]
}
```

**Rules**
- Only real problems or gaps for your persona, each tied to an exact place. Quote the app's words when the words are the problem.
- No generic advice ("add more interactivity"). No invented features: if the packet doesn't show something, don't assume it exists or doesn't; say you can't tell and set `needs_live_app` to true.
- Severity: "stops the lesson" = you couldn't use it in class or a student couldn't continue; "slows it down" = costs real time or causes confusion; "minor" = polish.
- Five to fifteen findings is typical. Fewer is fine if that's honestly what you find.
- Your final reply is only: "done, N findings".
