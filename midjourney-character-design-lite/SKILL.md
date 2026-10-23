---
name: midjourney-character-design-lite
description: Design one human character from a text brief and produce one complete full-body Midjourney prompt. Use for a first character concept in the user's chosen visual style or a simple follow-up change to that concept. This experience edition has no reference-image redesign, complex armor, nonhuman anatomy, multi-view, or advanced parameter workflow.
metadata:
  version: "0.1.0"
---

# Character Design Lite

Turn a Chinese idea into a specific, usable character design before writing its prompt. This is a standalone experience edition, not a style preset.

## Working scope

- Converse in Chinese; deliver one English Midjourney prompt for one human character in one complete full-body image.
- Support text-led original concepts and simple follow-up changes: appearance, proportions, clothing, color, pose, lighting or medium. Fantasy humans are welcome; elaborate armor engineering and nonhuman anatomy are outside this package.
- Keep the user's chosen medium. CGI, anime, ink painting, painterly illustration and photographic realism are choices, not a hierarchy. If unspecified, use a neutral character-concept illustration and name that reversible assumption briefly.
- Do not default to Asian identity, youth, beauty, a slim body, nine-head proportions, ornate clothes or cinematic backlighting. Use them when the brief calls for them.
- Deliver prompts by default. This package does not run an image generator or establish that an image has been rendered.

## Design from a short brief

A short idea is enough; do not start a questionnaire. Resolve ordinary gaps with coherent, reversible choices. Ask only when conflicting requirements or an indispensable missing detail prevent a faithful result.

Choose a primary impression and two or three visible recognition features. Make them belong to the same person: a profession can shape sleeves, pockets and carried equipment; an intended temperament can affect posture and expression. Do not turn every biographical detail into a symbol.

Resolve the silhouette and proportions, then garment shapes and how they fasten, then major colors and material contrast. Concentrate decoration where it can be read at full-body scale. Keep face and hair descriptions selective. Sparse input still deserves actual design decisions, not a literal translation padded with quality adjectives.

Show a coherent pose. Hands must have clear ownership of held objects; clothing and straps should plausibly support what they carry. Use a quiet background that supports the character. When presentation is unspecified, use an eye-level view and readable soft front-side light; explicit requested lighting takes precedence. A drawn medium needs line, ink, color or brush treatment appropriate to that medium, not automatic CG skin and lens vocabulary.

The examples in [references/examples.md](references/examples.md) demonstrate three briefs. Read them only when a user asks for examples or needs a starting point. They do not define a required face, ethnicity, body or style.

## Compile one prompt

State one character and full-body framing near the beginning. Include a lower-body or footwear cue when relevant and leave space around the silhouette. Framing language is an intention, not a guarantee against cropping.

Keep each garment's shape, color, material and attachment together. Name the owner of a prop when it could be ambiguous. Preserve the requested facial, body, costume and medium constraints. Remove redundant praise, invisible biography and competing style words.

Express the desired visible state when that accurately preserves an exclusion. For example, removing a coat's gold embroidery can become plain cloth with tonal seams while retaining requested gold earrings. Use a short `--no` list only when the excluded category is unwanted throughout the image. Each word may be interpreted separately; do not turn a local exception into a global material ban.

Keep basic MJ setup small:
- Put parameters at the end. Use `--ar 3:4` for an ordinary upright full-body concept unless the user specifies another suitable frame. Ratios use positive integers; convert decimal ratios rather than pasting decimal values.
- `--raw` is optional when reduced automatic styling serves the requested result. It is not a required CGI or realism switch.
- Leave the user's selected MJ model in the interface unchanged. Do not pin a version, switch to Niji, invent style codes or add a quality preset merely because of the chosen art style.
- This package supplies no advanced reference or parameter-selection workflow. Verify requested controls in current official documentation rather than guessing or importing the full edition.

Basic syntax was checked on 2026-10-23 against the official [Aspect Ratio](https://docs.midjourney.com/hc/en-us/articles/31894244298125-Aspect-Ratio), [Raw](https://docs.midjourney.com/hc/en-us/articles/32634113811853-Raw), and [No](https://docs.midjourney.com/hc/en-us/articles/32173351982093-No) pages. This is not a complete version-compatibility certification.

## Simple follow-up changes

Reuse the last accepted design description. Change the requested feature and its necessary consequences, keeping other accepted choices. Do not silently change age, face, hairstyle, outfit, proportions, framing or parameters while describing the revision as a lighting-only edit.

For a medium change, replace incompatible rendering language while retaining the character design. For a changed sleeve or held object, resolve the affected hand, fastening or pose. Summarize what actually changed in one sentence, then give one complete revised prompt. A textual preserve instruction does not promise identical faces in generated images.

There is no turn counter or artificial usage quota. Several simple revisions are still simple revisions; complex reference-led reconstruction and systematic multi-image consistency remain outside this package.

## Requests beyond the package

Reference-image likeness reconstruction, exact feature transfer, complex armor, nonhuman creatures, character sheets, multiple views, multi-character layouts, advanced MJ routing and image-failure diagnosis have no workflow here. State the relevant boundary briefly and offer a text-led single-human concept when useful; do not silently discard the requested complexity or pretend a substitute fulfills it.

Do not search for the full edition, load its private modules or promote it automatically to fill this package's gaps. Do not invent a paywall, unlock command or license enforcement. If a user explicitly changes the task, explain the scope change instead of claiming it is a capability this edition contains.

## Delivery and check

Give one short Chinese design direction, one English prompt block, and a setup sentence only when necessary. Honor prompt-only requests by omitting the explanation. Do not append a sales pitch.

Before delivery check the visible requirements, single complete body, hand/prop ownership, plausible garment connections, and consistent medium. For a revision, check the accepted features as well as the changed ones. A text review supports prompt correctness only; likeness, anatomy and visual quality need an actual generated image to assess.
