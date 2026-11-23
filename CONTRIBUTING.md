# Contributing

Submit a public source URL, author handle, the complete original prompt and the media associated with that exact prompt. Identify any required reference image and any later editing or animation. Do not substitute a caption or a summary for a prompt.

Check `data/prompts.json` for duplicates. A different prompt from the same post can be a separate case when its source location is clear. Keep original prompt bytes and use a descriptive title. Add a case to the matching category and update navigation in all eleven languages; localize labels and descriptions while preserving the original prompt.

Run `python3 scripts/verify_content.py` before opening a pull request. Media must be visible, associated with the correct case and linked to a playable file when it is a video. Do not commit credentials or large media caches.

For credit corrections or removal requests, open an issue with the case number, source URL and requested correction. You do not need to contribute a replacement case.

## Repository About and topics

When the featured model or prompt count changes, update the About description alongside the README introduction. For the GPT Image 2.6 collection, use:

> 15 GPT Image 2.6 prompt cases with GIF and SVG demos, plus 250 original GPT Image 2.5 prompts with examples. Available in 11 languages.

Add the `gpt-image-2-6` topic and keep `gpt-image-2-5` for the original collection. A repository administrator can apply the description and topic using the gear beside **About** on the repository home page.
