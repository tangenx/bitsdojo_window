# bitsdojo_window

A fork of [original repository][original repository], but with some fixes.

🎊 **Ready for Flutter 3.0.0!** 🎊

[original repository]: https://github.com/bitsdojo/bitsdojo_window

## Merged PRs

- [#100](https://github.com/bitsdojo/bitsdojo_window/pull/100)
- [#155](https://github.com/bitsdojo/bitsdojo_window/pull/155)

## How to use

Just add these lines in your project's `pubspec.yaml`:

```yaml
dependencies:
  flutter:
    sdk: flutter

  # other dependencies

  bitsdojo_window:
    git: 
      url: https://github.com/tangenx/bitsdojo_window.git
      path: bitsdojo_window
      ref: 21fc5740e614fefa90f627bafcc22093382f24a7

  # ...

dependency_overrides:
  bitsdojo_window_platform_interface:
    git:
      url: https://github.com/tangenx/bitsdojo_window.git
      path: bitsdojo_window_platform_interface
      ref: 21fc5740e614fefa90f627bafcc22093382f24a7
  bitsdojo_window_windows:
    git:
      url: https://github.com/tangenx/bitsdojo_window.git
      path: bitsdojo_window_windows
      ref: 21fc5740e614fefa90f627bafcc22093382f24a7
  bitsdojo_window_linux:
    git:
      url: https://github.com/tangenx/bitsdojo_window.git
      path: bitsdojo_window_linux
      ref: 21fc5740e614fefa90f627bafcc22093382f24a7
  bitsdojo_window_macos:
    git:
      url: https://github.com/tangenx/bitsdojo_window.git
      path: bitsdojo_window_macos
      ref: 21fc5740e614fefa90f627bafcc22093382f24a7
```
