<p align="center">
  <img src="logo.png" alt="The Orange Case: an orange hard-shell suitcase" width="220">
</p>

<h1 align="center">The Orange Case</h1>

<p align="center">
  <b>Same game. Same telemetry. Same chaos. Only the observability backend changes.</b>
</p>

The Orange Case is a portable, self-contained cloud-native gaming rig in an orange hard case, and a reproducible
benchmark for observability backends. Players joust with motion controllers; every swing, death and win is
OpenTelemetry data, and every chaos challenge is switched live through OpenFeature and flagd.

## Repositories

| Repo | What it is |
|---|---|
| [JoustMania](https://github.com/orange-case/JoustMania) | The game and its services: OpenTelemetry for all signals, OpenFeature/flagd as the live control plane, an AI agent that tunes the game through flags. |
| [orange-case.github.io](https://github.com/orange-case/orange-case.github.io) | The website. |
| [kubecon-material](https://github.com/orange-case/kubecon-material) | Talk and conference material. |

## The challenges

- **Swing-to-screen latency:** from a knock-out to the death event in your UI.
- **Million-span match:** one match, one trace, about a million spans.
- **Find the cheater:** a flag makes one controller cheat; find it with your own tool.

Extended challenges (cardinality bomb, hostile Wi-Fi, clock-skewed controllers, all-signals correlation) run
through **stowaway**, a synthetic load CLI in development.

Coming to **KubeCon + CloudNativeCon Europe 2027** in Barcelona.
