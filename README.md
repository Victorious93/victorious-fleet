# Victorious Fleet

Monorepo of all **Victorious Fleet** apps. Each `apps/<name>` is either a **git submodule**
pointing at the live repo, or a **placeholder stub** (README only) for an app that has no
source repo yet.

## Clone

```bash
git clone --recurse-submodules https://github.com/Victorious93/victorious-fleet.git
# or, after a plain clone:
git submodule update --init --recursive
```

> Submodules that point at **private** repos will not clone for users without access.
> That is expected — the pointer still records the canonical URL.

## Apps

| App | Package id | Connection class | Repo | Type |
|-----|-----------|------------------|------|------|
| droidcommand-AI | `ai.droidcommand.app` | CONTROLLER | [droidcommand-AI](https://github.com/Victorious93/droidcommand-AI) | submodule |
| HackerAI-Commander | `ai.hackerai.companion` | BOUND_COMPANION | [HackerAI-Commander](https://github.com/Victorious93/HackerAI-Commander) | submodule |
| Pentest-Swarm-AI | `ai.pentestswarm.companion` | BOUND_COMPANION | [Pentest-Swarm-AI](https://github.com/Victorious93/Pentest-Swarm-AI) | submodule |
| EDL-Commander | `ai.edlcommander.companion` | BOUND_COMPANION | [EDL-Commander](https://github.com/Victorious93/EDL-Commander) | submodule |
| rootforge-os | `ai.rootforge.os` | EXTERNAL_NODE | [rootforge-os](https://github.com/Victorious93/rootforge-os) | submodule |
| File-Manager | `ai.victorious.filemanager` | EXTERNAL_NODE | [File-Manager](https://github.com/Victorious93/File-Manager) | submodule |
| Victorious-Keyboard | `com.victorious.keyboard` | EXTERNAL_NODE | [Victorious-Keyboard](https://github.com/Victorious93/Victorious-Keyboard) | submodule |
| Victorious-Flash | `com.victorious.flash.android` | EXTERNAL_NODE (desktop) | [victorious-flash](https://github.com/Victorious93/victorious-flash) | submodule |
| Victorious-Mesh | `com.victorious.mesh` | EXTERNAL_NODE | [victorious-mesh](https://github.com/Victorious93/victorious-mesh) | submodule |
| Victorious-Browser | `com.victorious.browser` | EXTERNAL_NODE | [victorious-browser](https://github.com/Victorious93/victorious-browser) | submodule |
| VictorSMS | `com.victorious.sms` | EXTERNAL_NODE | [victorsms](https://github.com/Victorious93/victorsms) | submodule |
| VictorLaunch | `com.victorious.launch` | EXTERNAL_NODE | [victorlaunch](https://github.com/Victorious93/victorlaunch) | submodule |
| VictorSpoof | `com.victorious.spoof` | EXTERNAL_NODE | [victorspoof](https://github.com/Victorious93/victorspoof) | submodule |
| VictorLink64 | `org.victoriousframework.victorlink64` | NOT_IN_FLEET_REMOTE (game) | [VictorLink64](https://github.com/Victorious93/VictorLink64) | submodule |
| VictorSuite | `com.termux` | TERMUX_IPC | [VictorSuite](https://github.com/Victorious93/VictorSuite) | submodule |
| KYC-AuditLab | `com.identityshield.companion` | HOST_PROCESS_TOOL | [KYC-AuditLab](https://github.com/Victorious93/KYC-AuditLab) | submodule |
| BakerPi-Installer | n/a | HOST_PROCESS_TOOL | [BakerPi-Installer](https://github.com/Victorious93/BakerPi-Installer) | submodule |
| fleet-manifest | n/a | (manifest) | [fleet-manifest](https://github.com/Victorious93/fleet-manifest) | submodule |
| MatchVictorious | `com.victorious.match` | SOCIAL | [matchvictorious](https://github.com/Victorious93/matchvictorious) | submodule |
| VictoryPed | `com.victorious.victoryped` | SOCIAL | [VictoryPed](https://github.com/Victorious93/VictoryPed) 🔒 private | submodule |
| VictorModem | hardware, no pkg | HARDWARE | [victormodem](https://github.com/Victorious93/victormodem) 🔒 private | submodule |
| VictorOps-Zombies | `com.victorious.zombie` | GAME | [victorops-zombies](https://github.com/Victorious93/victorops-zombies) 🔒 private | submodule |
| Pyra-Claw | hardware hub | HARDWARE | [pyra-claw](https://github.com/Victorious93/pyra-claw) | submodule |
| VictorCam | `com.victorious.cam` | EXTERNAL_NODE | repo TBD | stub |

🔒 = private repo; submodule pointer records the URL but will not clone without access.
