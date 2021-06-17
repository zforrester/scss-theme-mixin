# SCSS Theme Mixin

A mixin for themeing elements without loops, and minimal code waste

### Usage

Call the mixin on a parent container and define your theme colors

```
.blue {
 @include theme($brand-blue, $brand-blue-light, $brand-blue-dark)
}
```

Extend the placeholder classes for each property you want to theme

```
.primary-cta {
  @extend %themed-gradient
 }
```
