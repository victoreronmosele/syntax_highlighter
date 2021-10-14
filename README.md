This is a fork of [syntax_highlighter](https://github.com/viztushar/syntax_highlighter) that has been migrated to null safety.

You can use this fork if your app depends on `syntax_highlighter` but needs the null safety version of it.

In order to do that, simply add the line below to your `dependencies` in your `pubspec.yaml` file:

```yaml

dependencies:
  ...
  syntax_highlighter: 
    git:
      url: git://github.com/victoreronmosele/syntax_highlighter.git
      ref: c0554996f4ca454a4955c3a3fc68dec2cfa06ea4
  ...
```
