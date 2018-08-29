# common-styles
## styles starter

### SCSS file markup

#### File start:
First line on compiled files start with `@charset 'UTF-8';`
**not needed on partial files*

#### File introduction:
Introduction comments for organization, notes, and file search help. 

**Required items:**

* Type: Name
* A TL;DR of what this file does

Example:

```
// -----------------------------------------------------------------------------
// Component: Hero
// A large image section with title and description text
// -----------------------------------------------------------------------------
```

For partial files that get imported into a parent style file

```
// -----------------------------------------------------------------------------
// Component: Hero - Text
// Hero text styles
// -----------------------------------------------------------------------------
```

```
// -----------------------------------------------------------------------------
// Component: Hero - Image
// Hero image styles
// -----------------------------------------------------------------------------
```

**Mixins** add the @include and the possible variable options

```
// -----------------------------------------------------------------------------
// Mixin: Name
// Description
// @include name();
// -----------------------------------------------------------------------------
```

```
// -----------------------------------------------------------------------------
// Mixin: Name
// Description
// @include name();
//
// Option(s):
// • $var1(value = type) - default = value - description
// • $var2(value = type) - default = value - description
// • $variable(value = true of false) - default = true - shows something
// -----------------------------------------------------------------------------
```

