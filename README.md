# DevBox FFmpeg Evidence

This repository hosts a small, bounded test record for one locally run FFmpeg audio-processing task. It is an independent DevBox evidence package, not an official FFmpeg release and not affiliated with FFmpeg or Gyan.dev.

The release contains three review artifacts: a ZIP of the redacted test materials, a guide describing the evidence and its limits, and a SHA-256 manifest. It contains no FFmpeg executable, library, installer, FFmpeg source code, third-party music, microphone recording, or user-supplied media. The WAV files in the package were synthesized locally for this test.

The test covered a single synthetic 10-second, 48 kHz mono PCM16 WAV: extracting seconds 2–7 and converting the output to 24 kHz mono PCM16. The saved report records 19 bounded checks and 10 commands that exited successfully. Listening and player compatibility were not tested. The result does not establish support for video, other formats, GPUs, other devices, performance, or the broader preparation task.

Use the fixed release tag [`ffmpeg-evidence-20261007-r1`](https://github.com/HiyodoGame/devbox-evidence/releases/tag/ffmpeg-evidence-20261007-r1) for these files. The package's `LOCAL_REVIEW_ONLY` field and “no public URL” note describe its state when the review package was prepared; publishing this release does not change the package or create a completed DevBox database record.

FFmpeg is a trademark of Fabrice Bellard. FFmpeg legal and licensing information is available from the [FFmpeg project](https://www.ffmpeg.org/legal.html). This repository distributes evidence files only, not FFmpeg software.
