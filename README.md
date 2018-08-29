# common-styles
## styles starter


### File structure:

* **main**
* -- **abstracts = files that do not output css when compiled**
* ---- **fonts**
* ------ *imports*
* ------ primary
* ------ secondary
* ---- **functions**
* ------ *imports*
* ------ asset-pathing
* ------ unit-conversions
* ---- **mixins**
* ------ *imports*
* ------ breakpoints
* ------ button-reset
* ------ flexbox-prefixing
* ------ fluid-type
* ------ headings
* ------ on-event
* ------ outer-spacing
* ------ positionings
* ------ typography
* ------ vertical-rhythm
* ---- **variables**
* ------ *imports*
* ------ asset-patting
* ------ breakpoints
* ------ colors
* ------ font-weights
* ------ fonts
* ------ outer-spacing
* ------ transitions
* ------ typography
* ------ vertical-rhythm
* -------- **theme**
* ---------- *imports*
* ---------- theme-colors
* -- **base = project standard styles for global and common elements**
* ---- *imports*
* ---- base
* ---- color-classes
* ---- helpers
* ---- typography 

## File Header

#### Character set:
For files that **get compiled** start with `@charset 'UTF-8';`

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

