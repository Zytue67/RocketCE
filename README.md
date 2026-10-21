# RocketCE

3D car soccer for the **TI-84 Plus CE**, including Python Edition.

Play against a bot, practice in Free Play, or connect two calculators for local USB multiplayer.

## Install

1. Download **RocketCE-v1.0.0.zip** from [Releases](../../releases/latest) and extract it.
2. Send `ROCKETCE.8xp`, `RCETITLE.8xv`, `RCEMENU.8xv` and `clibs.8xg` to your calculator using TI Connect CE. Keep the artwork AppVars and libraries archived.
3. Open **ROCKETCE** from Cesium.

### Need arTIfiCE or Cesium?

- [arTIfiCE — download and setup instructions](https://yvantt.github.io/arTIfiCE/)
- [Cesium — latest download](https://github.com/mateoconlechuga/cesium/releases/latest)

Follow arTIfiCE's instructions for your calculator and OS, then install Cesium to launch the game.

## Controls

- **Arrows:** drive / steer; rotate in the air.
- **2nd:** jump; release and press again to double jump. Add arrows to flip.
- **ALPHA:** boost.
- **MODE:** powerslide; hold with Left/Right in the air to roll.
- **GRAPH:** brake. **TRACE:** change camera. **ZOOM:** change detail.
- **CLEAR:** back / exit.

The in-game Controls page has a quick reference.

## Two-player USB

Install the same version on both calculators. Connect them with a calculator-to-calculator USB data cable and select **Calculator Link** on both. Player assignments are automatic. Allow a few seconds to connect; ENTER retries if needed.

## Build

Install [CEdev](https://github.com/CE-Programming/toolchain), then run `make`. Run `sh tests/run.sh` for host checks.

See [MECHANICS.md](MECHANICS.md) for movement details and [THIRD_PARTY.md](THIRD_PARTY.md) for credits.

An unofficial fan project; not affiliated with Rocket League or Psyonix.
