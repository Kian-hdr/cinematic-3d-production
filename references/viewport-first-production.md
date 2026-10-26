# Viewport-first production and evidence

Use the actual scene early, keep review inexpensive, and choose final capture quality
from observed results. This is a production method, not a bundled capture backend.

## Timed story and motion proof

1. Select the editable source scene and cameras. For new boards, capture actual
   viewport stills or use rights-cleared source art and editable vector blocking.
   Do not generate raster concept imagery or textures for this workflow. Keep
   vector layouts editable; identify concept geometry and physical behavior as
   unverified until checked against the actual source.
2. Give each panel an action, framing, camera movement, approximate duration and
   sound intent. Cover the whole beginning-to-end story before detailed work.
3. Assemble an inexpensive complete edit at intended playback speed and duration.
   Include selected camera/model movement, transitions and available approved audio.
   A short native-quality sample proves rendering; it cannot establish a long
   mechanism's readability. Show the complete action at its intended speed too.
4. Plan horizontal and portrait shots against separate output gates. Share assets
   where useful, then adjust composition, timing and interface-safe areas for each.
   Preserve explicit review gates in the brief before final-quality work.

## Continuous evaluation and capture

Keep the engine loaded where practical and evaluate the sequence continuously.
When capture cannot keep up with real time, use fixed source-clock stepping that
preserves every required output frame. A jump/pause/screenshot loop is diagnostic
until motion evaluation, temporal history and rendered-frame alignment are shown
adequate for the requested result.

Benchmark existing engine capture facilities before writing a custom backend.
Retained-session raster capture, the engine's render queue, and asynchronous
readback are candidates to measure. Their availability and exact behavior depend
on the installed engine and integration. Every method still renders frames;
reduced cost may come from avoiding cold starts, excess samples, synchronous
readback, or redundant exports. Do not assume a universal speedup.

Keep the requested effects, materials, light and motion while diagnosing costs.
Measure startup/shaders, source evaluation, CPU, GPU, readback, writes and encode
separately. Bound queues and memory against observed RAM/VRAM, swapping, disk
throughput and session stability. Preserve a resumable source/recipe/frame manifest
and safe chunk boundaries with temporal warm-up. Use one owner per mutable scene
and active capture process; parallel work should use separate targets.

## Review moving results

Watch complete normal-speed output for dropped/repeated frames, bad cuts, temporal
contamination, flicker, ghosting, intersections, vanished objects and exposure jumps.
Inspect thin/glossy edges, emissive effects and moving joints. Compare raw frames,
finished frames and encoded output at the same timestamps. Repair coincident
surfaces, contact, materials or lighting at their source; antialiasing cannot repair
geometry. A still or a technically decodable video cannot prove temporal quality.

An enhanced viewport capture may serve as the final master if it passes the brief's
actual format, visual and audio checks. Offline high-sample/path-traced rendering
is a separate choice when the brief or observed quality requires it. State output
pixels separately from internal rendering percentage, reconstruction/upscaling,
frame interpolation and playback speed. Never label an upscaled result as native.

## Compact evidence manifest

For each reviewed result retain: source revision; scene/sequence/camera; frame range;
source clock and output fps; output dimensions; internal resolution; temporal method;
warm-up and runtime overrides; materials/light/effects recipe; color/encoder; output
hash/path; review scope; known defects; destination receipt and acceptance state.

Keep rendered, technically checked, visually reviewed, delivered and user accepted
as distinct states. Reuse unaffected valid shots. A recipe change requires a coherent
affected-shot result rather than mixing visually incompatible chunks. Measure total
cost per accepted revision, including review and finishing, against a comparable
baseline before claiming savings.
