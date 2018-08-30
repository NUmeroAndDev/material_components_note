# Material Theming の Color でどこが変わるか  

## SwitchMaterial

* colorSecondary
* colorSurface
* colorOnSurface
* colorText

## TabLayout  

### Default  

* colorSurface -> background
* colorPrimary -> tabIndicator

### Colored

* colorPrimary -> background
* colorOnPrimary -> tabIndicator

## Bottom Navigation

### Default  
* colorPrimary -> selectedItem
* colorSurface -> background
* colorOnSurface -> unSelectedItem

### Colored
* colorPrimary -> background  
* colorOnPrimary -> selectedItem, unSelectedItem

## Material Button

* colorPrimary -> background
* colorOnPrimary -> ripple,text
* colorOnSurface -> disabledBackground、disabledText、stroke

## [Default Color](https://github.com/material-components/material-components-android/blob/master/lib/java/com/google/android/material/color/res/values/colors.xml)
```
<resources>

  <color name="design_default_color_primary">#6200EE</color>
  <color name="design_default_color_primary_dark">#303F9F</color>
  <color name="design_default_color_primary_variant">#3700B3</color>
  <color name="design_default_color_secondary">#03DAC6</color>
  <color name="design_default_color_secondary_variant">#018786</color>
  <color name="design_default_color_background">#FFFFFF</color>
  <color name="design_default_color_error">#B00020</color>
  <color name="design_default_color_on_primary">#FFFFFF</color>
  <color name="design_default_color_on_secondary">#000000</color>
  <color name="design_default_color_on_background">#000000</color>
  <color name="design_default_color_on_surface">#000000</color>
  <color name="design_default_color_on_error">#FFFFFF</color>

  <!-- 32% opacity black -->
  <color name="mtrl_scrim_color">#52000000</color>

</resources>
```
