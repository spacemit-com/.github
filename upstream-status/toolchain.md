# Toolchain Upstream Status

Welcome to the Toolchain Upstream Status page for SpacemiT.

This page summarizes the upstream status of SpacemiT K1/K3 toolchain support across LLVM, GCC, and Binutils.

## Overview

This page summarizes upstream toolchain progress for SpacemiT K1/K3 platforms, covering LLVM, GCC, Binutils, and related processor or vendor-extension support.

Reference Documentation:

- X60 (Core for K1): https://github.com/spacemit-com/docs-chip/blob/main/en/key_stone/k1/k1_docs/k1_ds.md#spacemit-x60-risc-v-core
- X100 (Core for K3): https://github.com/spacemit-com/docs-chip/blob/main/en/key_stone/k3/k3_docs/k3_ds.md#211-spacemit-x100-risc-v-core
- A100 (AI Core for K3): https://github.com/spacemit-com/docs-chip/blob/main/en/key_stone/k3/k3_docs/k3_ds.md#212-spacemit-a100-ai-core
- SpacemiT Vendor Extensions: https://github.com/spacemit-com/docs-ai/blob/main/en/architecture/ime_extension.md

## K1 SoC

| Project | Component | Status | Link | Description |
|---|---|---|---|---|
| LLVM | X60 Processor Definition | Merged | [#94564](https://github.com/llvm/llvm-project/pull/94564) | Contributed by sunshaoce |
| LLVM | X60 Schedule Model | Merged | [#137343](https://github.com/llvm/llvm-project/pull/137343)<br>[#144564](https://github.com/llvm/llvm-project/pull/144564)<br>[#144730](https://github.com/llvm/llvm-project/pull/144730)<br>[#149207](https://github.com/llvm/llvm-project/pull/149207)<br>[#150618](https://github.com/llvm/llvm-project/pull/150618)<br>[#150644](https://github.com/llvm/llvm-project/pull/150644)<br>[#151572](https://github.com/llvm/llvm-project/pull/151572)<br>[#152336](https://github.com/llvm/llvm-project/pull/152336)<br>[#152737](https://github.com/llvm/llvm-project/pull/152737)<br>[#152738](https://github.com/llvm/llvm-project/pull/152738) | Contributed by mikhailramalho |
| LLVM | X60 Vendor Extension | Merged | [#151706](https://github.com/llvm/llvm-project/pull/151706)<br>[#174364](https://github.com/llvm/llvm-project/pull/174364) | `xsmtvdot`; Contributed by SpacemiT |
| LLVM | X60 Fusion | Merged | [#186967](https://github.com/llvm/llvm-project/pull/186967) | Contributed by SpacemiT; more fusion work is WIP |
| GCC | X60 Processor Definition & Schedule Model | Merged | [2025-November/700908](https://gcc.gnu.org/pipermail/gcc-patches/2025-November/700908.html)<br>[2025-December/704419](https://gcc.gnu.org/pipermail/gcc-patches/2025-December/704419.html)<br>[2026-April/714648](https://gcc.gnu.org/pipermail/gcc-patches/2026-April/714648.html) | Contributed by Austin Law and Milan Tripkovic |
| GCC | X60 Vendor Extension | Merged | [2025-November/702229](https://gcc.gnu.org/pipermail/gcc-patches/2025-November/702229.html) | Contributed by SpacemiT |
| Binutils | X60 Vendor Extension | Merged | [2026-May/149417](https://sourceware.org/pipermail/binutils/2026-May/149417.html) | Contributed by SpacemiT |

## K3 SoC

| Project | Component | Status | Link | Description |
|---|---|---|---|---|
| LLVM | X100 Processor Definition | Merged | [#173988](https://github.com/llvm/llvm-project/pull/173988)<br>[#186351](https://github.com/llvm/llvm-project/pull/186351) | Contributed by SpacemiT |
| LLVM | X100 Schedule Model | Merged | [#178189](https://github.com/llvm/llvm-project/pull/178189) | Contributed by SpacemiT |
| LLVM | X100 Vendor Extension | N/A | N/A | Same as X60 |
| LLVM | X100 Fusion | Merged | [#178594](https://github.com/llvm/llvm-project/pull/178594) | Contributed by SpacemiT |
| LLVM | A100 Processor Definition | Merged | [#174052](https://github.com/llvm/llvm-project/pull/174052) | Contributed by SpacemiT |
| LLVM | A100 Schedule Model | N/A | N/A | Same as X60 |
| LLVM | A100 Vendor Extension | Merged | [#202533](https://github.com/llvm/llvm-project/pull/202533) | `xsmtvdotii`; Contributed by SpacemiT |
| LLVM | A100 Fusion | N/A | N/A | Same as X60 |
| GCC | X100 Processor Definition & Schedule Model | Merged | [2026-June/722040](https://sourceware.org/pipermail/gcc-patches/2026-June/722040.html) | Contributed by SpacemiT |
| GCC | A100 Processor Definition & Schedule Model | Merged | [2026-June/722133](https://sourceware.org/pipermail/gcc-patches/2026-June/722133.html) | Contributed by SpacemiT |
| GCC | A100 Vendor Extension | Merged |  [2026-June/722133](https://sourceware.org/pipermail/gcc-patches/2026-June/722133.html) | Contributed by SpacemiT |
| Binutils | A100 Vendor Extension | Merged | [2026-May/149417](https://sourceware.org/pipermail/binutils/2026-May/149417.html) | Contributed by SpacemiT |

## Monthly Update Log

| Month | Summary | Updated by |
|---|---|---|
| 2026-06 | Initial status created | [Mark Zhuang](https://github.com/zqb-all), [yutingnie](https://github.com/YutingNie) |

