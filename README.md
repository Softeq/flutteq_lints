# Softeq Flutter Lints

Lint rules for Dart and Flutter used internally at Softeq.

This package is built on top of Dart/Flutter's recommended set of lints from [package:flutter_lints](https://pub.dev/packages/flutter_lints).

**Note**: This package was heavily inspired by [pedantic](https://github.com/dart-lang/pedantic).

## Usage

To use the lints, add as a dev dependency in your `pubspec.yaml`:

```yaml
dev_dependencies:

  flutteq_lints:
    git:
      url: git@github.com:Softeq/flutteq_lints.git
      ref: v1.0.0
```

Then, add an include in `analysis_options.yaml`:

```yaml
include: package:flutteq_lints/analysis_options.yaml
```

## Resources

- [Dart Linter rules](https://dart.dev/tools/linter-rules)
- [Customizing static analysis](https://dart.dev/tools/analysis)
