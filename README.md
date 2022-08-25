# cmumford's KiCAD Component Library

A collection of KiCAD symbols and footprints.

## Using

1. Define `CMUMFORD_COMPONENTS` path:
  a. Select _Preferences→ConfigurePaths..._ menu item.
  b. Enter path to checkout folder. Something like: `/path/to/cmumford-components`
2. Add symbol library:
  a. Select _Preferences→Manage Symbol Libraries..._ menu item.
  b. Select Global or Project Specific (recommended).
  c. Enter `${CMUMFORD_COMPONENTS}/cmumford.kicad_sym`
3. Add footprint library:
  a. Select _Preferences→Manage Footprint Libraries..._ menu item.
  b. Select Global or Project Specific (recommended).
  c. Enter `${CMUMFORD_COMPONENTS}/cmumford.pretty`

