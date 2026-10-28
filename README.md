# Producer–Consumer Video Streaming Simulation

A small, dependency-free browser simulation of the producer–consumer problem. A downloader (the producer) adds video chunks to a bounded buffer, while a player (the consumer) removes and plays them.

## Run

Open [`Producer-Consumer_ Video Streaming Simulation.html`](./Producer-Consumer_%20Video%20Streaming%20Simulation.html) in any modern web browser. No installation, build step, or server is required.

## Controls

- **Start** begins the simulation; **Pause** pauses it; **Reset** clears the buffer, counters, and event log.
- **Speed** adjusts how often the consumer plays a chunk relative to the producer.
- **Unsafe mode** enables the simulation's race-condition demonstration.

The buffer holds up to 6 chunks, and each streaming session downloads and plays 20 chunks. The interface displays producer and consumer status, buffer occupancy, event logs, and totals for downloaded chunks, played chunks, full/empty buffer events, and race-condition detections.
