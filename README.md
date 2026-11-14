# IRO · RPi 5 benchmark explorer

An interactive view of the vision benchmark that ran on IRO's Raspberry Pi 5 on 2026-11-13: face detectors,
emotion classifiers and a person check, each with its latency, peak memory and accuracy.

**Open it:** https://prithiveenkumaarramkumar.github.io/EdgeCNNLatency/

- Latency (each run's mean time per call at 1 thread) and peak process memory were measured on the Pi. IRO has no
  fan, so many runs were throttled; the table shows the CPU clock at each timed loop's start and end.
- Emotion accuracy and face recall are from the laptop run, since accuracy does not depend on the machine. Person
  found was measured on the Pi.
- The page is a single self-contained HTML file. It works offline and sends no data anywhere.
