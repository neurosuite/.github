# Contributing to Neurosuite

- Open pull requests against the repository's default branch, one topic per PR.
- The build system is CMake (3.16 or newer) with Qt 6 and C++17. Please do not add qmake files
  or Qt 4/Qt 5 code paths.
- Where a repository has a `.clang-format` file, run `clang-format` on the files you touch.
- Keep the on-disk formats (`.dat`, `.xml`, `.nrs`, `.clu`, `.res`, `.spk`, `.fet`) unchanged
  unless the change has been discussed in an issue first; several Python and MATLAB projects
  read them.
- The licence is GPL-3.0-or-later. New source files start with
  `// SPDX-License-Identifier: GPL-3.0-or-later`.
- For questions, open an issue in the repository concerned. Anything about the Qt 6 port
  belongs in the [roadmap issue](https://github.com/neurosuite/neuroscope/issues/7).
