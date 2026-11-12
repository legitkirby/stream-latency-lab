# Stream Latency Lab

A small lab for testing live-stream behaviour: push a video stream to a
media server, watch it in a browser, then change encoder settings and
network conditions and measure what happens.

## Pipeline

FFmpeg (generates + encodes test video) -> RTMP push -> MediaMTX server -> HLS -> browser

## Tools

Docker, MediaMTX, FFmpeg (running in Docker)

## Status

Work in progress. Step 1: server running. Step 2: first stream pushed and played.
