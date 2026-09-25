## 🧑‍💻 About Me

Building and maintaining **[Obyflow](https://github.com/Obyflow/obyflow)** — a local-first observability platform for debugging LLM, RAG, and agent systems.

Focused on evidence-first root-cause investigation across traces, failures, and AI workflows.

<br>

## 🌱 Selected Open Source Contributions

<table>
<td width="50%" valign="top">

<div align="center">

[![Google ADK](https://img.shields.io/badge/Google%20ADK-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://github.com/google/adk-java)
[![Merged PR](https://img.shields.io/badge/Merged%20PRS-8957e5?style=for-the-badge&logo=git&logoColor=white)](https://github.com/google/adk-java/pulls?q=is%3Apr+author%3AAnupamKumar-1)

</div>

- [adk-js](https://github.com/google/adk-js) - Fixed Cloud SQL Unix-socket connections for MySQL, MariaDB and Postgres, merged to `main` [PR #871](https://github.com/google/adk-js/pull/871) and released in [v2.1.0](https://github.com/google/adk-js/releases/tag/main-v2.1.0) ([3b59a2c](https://github.com/google/adk-js/commit/3b59a2c0b361e229ee3b8c26e93588fb512773db))
- [adk-java](https://github.com/google/adk-java) - Fixed **`ChatCompletionsHttpClient`** to expose non-success HTTP status via a typed exception instead of a plain `IOException`, merged to `main` [PR #1452](https://github.com/google/adk-java/pull/1452) and released in [v1.9.0](https://github.com/google/adk-java/releases/tag/v1.9.0) ([052f31a](https://github.com/google/adk-java/commit/052f31ad3799124a36bb3bb732458d748fcc6586))
- [adk-java](https://github.com/google/adk-java) - Fixed Vertex AI session response handling to validate HTTP status before parsing the response, preventing non-success responses from being parsed as valid session data, merged to `main` [PR #1467](https://github.com/google/adk-java/pull/1467) and released in [v1.10.0](https://github.com/google/adk-java/releases/tag/v1.10.0) ([4192aca](https://github.com/google/adk-java/commit/4192aca586bf0bd47f3fa14bbd7d5959d3c07fdb))
<div align="center">

[![Swiftlang](https://img.shields.io/badge/Swiftlang-FA7343?style=for-the-badge&logo=swift&logoColor=white)](https://github.com/swiftlang)
[![Merged PR](https://img.shields.io/badge/Merged%20PRS-8957e5?style=for-the-badge&logo=git&logoColor=white)](https://github.com/swiftlang)

</div>

- [llvm-project](https://github.com/swiftlang/llvm-project) - Migrated Sema call sites to use `Type::isSinglePointerType()` instead of reading the ptrattr directly off `PointerType`, consolidating pointer-singleness checks under BoundsSafety — [PR #13846](https://github.com/swiftlang/llvm-project/pull/13846)
- [swift-build](https://github.com/swiftlang/swift-build) - Fixed a **Build Server Protocol (BSP)** issue — corrected transposed `indexStorePath` / `indexDatabasePath` values in the `build/initialize` response, improving BSP client compatibility — [PR #1576](https://github.com/swiftlang/swift-build/pull/1576)
</td>
<td width="50%" valign="top">

<div align="center">

[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://github.com/tensorflow/tensorflow)
[![Merged PR](https://img.shields.io/badge/Merged%20PRS-8957e5?style=for-the-badge&logo=git&logoColor=white)](https://github.com/tensorflow/tensorflow/pulls?q=is%3Apr+author%3AAnupamKumar-1)

</div>

- Fixed **`tf.reshape()`** to reject multiple **`-1`** dimensions, matching eager and `jit_compile=True` behavior — [PR #125093](https://github.com/tensorflow/tensorflow/pull/125093)
- Fixed **`tf.tuple()`** `AttributeError` for `tf.Variable` inputs under `tf.function` by routing them through `convert_to_tensor()` instead of skipping conversion — [PR #125420](https://github.com/tensorflow/tensorflow/pull/125420)
- Fixed **`tf.tuple()`** to consistently reject nested structures across eager and graph execution — [PR #124931](https://github.com/tensorflow/tensorflow/pull/124931)
- Fixed eager **`tf.while_loop`** corrupting shape for single-element loop variables when the body returned a bare Tensor — [PR #125616](https://github.com/tensorflow/tensorflow/pull/125616)

<div align="center">


[![Microsoft VS Code](https://img.shields.io/badge/Microsoft-VS%20Code-5E5E5E?style=for-the-badge&logo=data:image%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU%2BTWljcm9zb2Z0PC90aXRsZT48cGF0aCBmaWxsPSIjZmZmZmZmIiBkPSJNMCAwaDExLjM3N3YxMS4zNzJIMFYwem0xMi42MjMgMEgyNHYxMS4zNzJIMTIuNjIzVjB6TTAgMTIuNjIzaDExLjM3N1YyNEgwVjEyLjYyM3ptMTIuNjIzIDBIMjRWMjRIMTIuNjIzVjEyLjYyM3oiLz48L3N2Zz4%3D&logoColor=white&labelColor=5E5E5E)](https://github.com/microsoft/vscode)
[![Merged PRs](https://img.shields.io/badge/Merged%20PR-8957e5?style=for-the-badge&logo=git&logoColor=white)](https://github.com/microsoft/vscode/pulls?q=is%3Apr+author%3AAnupamKumar-1)

</div>

- Fixed `fix(chat)` — preserved an inline `#file:` reference when editing text before it; edits that touch the reference still remove it, while non-overlapping edits now recompute the reference range from the net offset delta — shipped in [VS Code 1.139](https://code.visualstudio.com/updates/v1_139) — [PR #333965](https://github.com/microsoft/vscode/pull/333965)

<div align="center">
  
[![Prisma ORM](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)](https://github.com/prisma/prisma)
[![Merged PRs](https://img.shields.io/badge/%20Merged%20PRs-8957e5?style=for-the-badge&logo=git&logoColor=white)](https://github.com/prisma/prisma/pulls?q=is%3Apr+author%3AAnupamKumar-1)

</div>

- Fixed the **Microsoft SQL Server adapter** — [PR #29630](https://github.com/prisma/prisma/pull/29630), shipped in [**Prisma ORM 7.9.0**](https://github.com/prisma/prisma/releases/tag/7.9.0)
- Resolved incorrect **`P2002` `modelName`** resolution in nested-create unique constraint errors, across adapters — [PR #29628](https://github.com/prisma/prisma/pull/29628)

</td>
</tr>
</table>
<br>

## 🌐 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-AnupamKumar--1-24292e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnupamKumar-1)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-185fa5?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anupam2025kumar@gmail.com)

</div>
