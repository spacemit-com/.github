# SpacemiT Open Source Upstream Summary

Welcome to the SpacemiT Open Source Upstream Summary page!

This page provides an at-a-glance view of SpacemiT K1/K3 upstream support and SpacemiT-maintained open-source projects. Component coverage, patch history, versions, and deployment instructions are maintained in the linked Details pages.

It provides:

- Concise overview tables linking to each project's details
- A unified view of K1/K3 support progress across open-source software
- Pointers to communication channels and download resources

## Table of Contents

- [Upstream Status](#upstream-status)
- [Open Source Project Status](#open-source-project-status)
- [Download Resources](#download-resources)
- [Communication Platform](#communication-platform)

## Upstream Status

<!-- Maintenance: Keep this page at summary level; maintain versions and patch lists in Details.
Review each row against primary sources before changing its Updated date.
Verify merges against the project's current mainline branch; do not assume it is named master. -->

Updated indicates the latest status review. Merged support may cover only selected components; see Details for coverage, remaining work, and release availability.

| Software | Updated | K1 Progress | K3 Progress | Details |
|---|---|---|---|---|
| Linux kernel | 2026-11-03 | Mainline support (partial) | Mainline support (partial) | [Linux kernel Module Status](https://github.com/spacemit-com/linux/wiki) |
| OpenSBI | 2026-11-03 | Upstream platform support | Platform support merged upstream | [OpenSBI Module Status](https://github.com/spacemit-com/opensbi-upstream/wiki) |
| U-Boot | 2026-11-03 | Mainline support (partial) | Mainline support (partial) | [U-Boot Module Status](https://github.com/spacemit-com/u-boot/wiki) |
| llama.cpp | 2026-11-03 | CPU/IME support merged | CPU/IME2 support merged | [llama.cpp Module Status](https://github.com/spacemit-com/llama.cpp/wiki) |
| FlagGems | 2026-11-03 | Backend and selected operators merged | Backend and selected operators merged | [FlagGems Module Status](https://github.com/spacemit-com/spine-FlagGems/wiki) |
| LLVM | 2026-11-03 | Processor/extension support merged | Processor/extension support merged | [LLVM Upstream Status](https://github.com/spacemit-com/.github/blob/main/upstream-status/toolchain.md) |
| GCC | 2026-11-03 | Processor/extension support merged | Processor/extension support merged | [GCC Upstream Status](https://github.com/spacemit-com/.github/blob/main/upstream-status/toolchain.md) |
| Binutils | 2026-11-03 | Vendor extension support merged | Vendor extension support merged | [Binutils Upstream Status](https://github.com/spacemit-com/.github/blob/main/upstream-status/toolchain.md) |

## Open Source Project Status

Status describes the published project scope. See Details for supported configurations, installation requirements, and releases.

| Project | Type | Platform | Key | Status | Details |
|---|---|---|---|---|---|
| spine-triton | AI Infra | K1/K3 | Triton CPU backend, MLIR, RVV/IME/AME | Released | [Repository and releases](https://github.com/spacemit-com/spine-triton) |
| ONNX Runtime | AI Infra | K1/K3 | ONNX inference, SpacemiT EP | SpacemiT fork | [Repository and releases](https://github.com/spacemit-com/onnxruntime) |
| AI Gateway | AI services | K3 | HTTP/WS model services | Public source | [Repository](https://github.com/spacemit-com/ai-gateway) |
| Vision Model Zoo | Vision models | K1/K3 | Detection, segmentation, place recognition | Public SDK | [Repository](https://github.com/spacemit-com/model-zoo-vision) |
| Reachy Mini | Robotics | K3 | Desktop robot, vision and voice interaction | Public demo | [Repository](https://github.com/spacemit-robotics/reachy_mini) |
| Linksee | Robotics | K3 | Wheeled robot, SLAM, navigation, grasping | Public demo | [Repository](https://github.com/spacemit-robotics/linksee) |
| LeRobot App | Robotics | K3 | Arm task execution, MCP integration | Public demo | [Repository](https://github.com/spacemit-robotics/lerobot_app) |
| LingLong humanoid | Robotics | K3 | 28-DOF control, MuJoCo simulation | Public application | [Repository](https://github.com/spacemit-robotics/humanoid_linglong) |
| Unitree G1 | Robotics | K3 | Humanoid simulation, RL inference | Public simulation example | [Repository](https://github.com/spacemit-robotics/humanoid_unitree_g1) |
| Unitree Go2 | Robotics | K3 | Quadruped control, ONNX motion policies | Public demo | [Repository](https://github.com/spacemit-robotics/unitree-go2) |
| Perception | Robotics SDK | K3 | Image stitching, stereo matching | Public SDK | [Repository](https://github.com/spacemit-robotics/perception) |

## Download Resources

- SpacemiT mirror site: https://archive.spacemit.com/
- Documentation: https://www.spacemit.com/community/document
- SpacemiT GitHub organization: https://github.com/spacemit-com
- SpacemiT robotics organization: https://github.com/spacemit-robotics

## Communication Platform

- Forum: https://forum.spacemit.com
- X (Twitter): https://x.com/spacemit_riscv
- Reddit: https://www.reddit.com/r/spacemit_riscv/
- Tech contact: developer@spacemit.com
- Business contact: business@spacemit.com
- WeChat Groups Info: https://forum.spacemit.com/t/topic/942/5
