# Android button asset table for outlined button

The following examples show tables for the Android outlined button with asset attributes in separate tables vs asset attributes in one table.

* [Multiple tables](#outlined-button-assets-mulitple-tables)
* [Single table](#outlined-button-assets-single-table)


## Outlined button assets, multiple tables


### Anatomy and key properties

An outlined button has a text label, a stroked container and an optional icon.


![<Placeholder diagram of outlined button anatomy. Replace this text if/when there is an approved diagram\>](button-examples/Android/assets/outline_button_anatomy_wide.png)


<details>
<summary><b>Text label</b> attributes</summary>
<br>

|  | Attribute | Related method(s) | Default value |
| --- | --- | --- | --- |
| **Text label** | `android:text` | `setText`<br/>`getText` | `null` |
| **Color** | `android:textColor` | `setTextColor`<br/>`getTextColor` | `?attr/colorPrimary` |
| **Typography** | `android:textAppearance` | `setTextAppearance` | `?attr/textAppearanceButton` |

</details>

<details>
<summary><b>Container</b> attributes</summary>
<br>

|  | Attribute | Related method(s) | Default value |
| --- | --- | --- | --- |
| **Color** | `app:backgroundTint` | `setBackgroundColor`<br/>`setBackgroundTintList`<br/>`getBackgroundTintList` | `@android:color/transparent` |
| **Stroke color** | `app:strokeColor` | `setStrokeColor`<br/>`setStrokeColorResource`<br/>`getStrokeColor` | `?attr/colorOnSurface` at 12% opacity |
| **Stroke width** | `app:strokeWidth` | `setStrokeWidth`<br/>`setStrokeWidthResource`<br/>`getStrokeWidth` | `1dp` |
| **Shape** | `app:shapeAppearance` | `setShapeAppearanceModel`<br/>`getShapeAppearanceModel` | `?attr/shapeAppearanceSmallComponent` |
| **Elevation** | `app:elevation` | `setElevation`<br/>`getElevation` | `0dp` |
| **Ripple color** | `app:rippleColor` | `setRippleColor`<br/>`setRippleColorResource`<br/>`getRippleColor` | `?attr/colorPrimary` at 12% opacity (pressed) |

</details>

<details>
<summary><b>Icon</b> attributes</summary>
<br>

|  | Attribute | Related method(s) | Default value |
| --- | --- | --- | --- |
| **Icon** | `app:icon` | `setIcon`<br/>`setIconResource`<br/>`getIcon` | `null` |
| **Color** | `app:iconTint` | `setIconTint`<br/>`setIconTintResource`<br/>`getIconTint` | `?attr/colorPrimary` |
| **Size** | `app:iconSize` | `setIconSize`<br/>`getIconSize` | `wrap_content` |
| **Gravity** (position relative to text label) | `app:iconGravity` | `setIconGravity`<br/>`getIconGravity` | `start` |
| **Padding** (space between icon and text label) | `app:iconPadding` | `setIconPadding`<br/>`getIconPadding` | `4dp` |

</details>

<details>
<summary><b>Styles</b></summary>
<br>

|  | Style |
| --- | --- |
| **Default style** | `Widget.MaterialComponents.Button.OutlinedButton` |
| **Icon style** | `Widget.MaterialComponents.Button.OutlinedButton.Icon` |

Default style theme attribute: `?attr/materialButtonOutlinedStyle`

See the full list of [styles](https://github.com/material-components/material-components-android/blob/master/lib/java/com/google/android/material/button/res/values/styles.xml) and [attrs](https://github.com/material-components/material-components-android/blob/master/lib/java/com/google/android/material/button/res/values/attrs.xml).

</details>

## Outlined button assets, single table 
### Anatomy and key properties

An outlined button has a text label, a stroked container and an optional icon.


![<Placeholder diagram of outlined button anatomy. Replace this text if/when there is an approved diagram\>](button-examples/Android/assets/outline_button_anatomy_wide.png)


<details>
<summary><b>Attributes</b></summary>
<br>

| Asset |  | Attribute | Related method(s) | Default value |
| --- | --- | --- | --- | --- |
| Text label | **Text label** | `android:text` | `setText`<br/>`getText` | `null` |
| Text label | **Color** | `android:textColor` | `setTextColor`<br/>`getTextColor` | `?attr/colorPrimary` |
| Text label | **Typography** | `android:textAppearance` | `setTextAppearance` | `?attr/textAppearanceButton` |
| Container | **Color** | `app:backgroundTint` | `setBackgroundColor`<br/>`setBackgroundTintList`<br/>`getBackgroundTintList` | `@android:color/transparent` |
| Container | **Stroke color** | `app:strokeColor` | `setStrokeColor`<br/>`setStrokeColorResource`<br/>`getStrokeColor` | `?attr/colorOnSurface` at 12% opacity |
| Container | **Stroke width** | `app:strokeWidth` | `setStrokeWidth`<br/>`setStrokeWidthResource`<br/>`getStrokeWidth` | `1dp` |
| Container | **Shape** | `app:shapeAppearance` | `setShapeAppearanceModel`<br/>`getShapeAppearanceModel` | `?attr/shapeAppearanceSmallComponent` |
| Container | **Elevation** | `app:elevation` | `setElevation`<br/>`getElevation` | `0dp` |
| Container | **Ripple color** | `app:rippleColor` | `setRippleColor`<br/>`setRippleColorResource`<br/>`getRippleColor` | `?attr/colorPrimary` at 12% opacity (pressed) |
| Icon | **Icon** | `app:icon` | `setIcon`<br/>`setIconResource`<br/>`getIcon` | `null` |
| Icon | **Color** | `app:iconTint` | `setIconTint`<br/>`setIconTintResource`<br/>`getIconTint` | `?attr/colorPrimary` |
| Icon | **Size** | `app:iconSize` | `setIconSize`<br/>`getIconSize` | `wrap_content` |
| Icon | **Gravity** (position relative to text label) | `app:iconGravity` | `setIconGravity`<br/>`getIconGravity` | `start` |
| Icon | **Padding** (space between icon and text label) | `app:iconPadding` | `setIconPadding`<br/>`getIconPadding` | `4dp` |

</details>

<details>
<summary><b>Styles</b></summary>
<br>

|  | Style |
| --- | --- |
| **Default style** | `Widget.MaterialComponents.Button.OutlinedButton` |
| **Icon style** | `Widget.MaterialComponents.Button.OutlinedButton.Icon` |

Default style theme attribute: `?attr/materialButtonOutlinedStyle`

See the full list of [styles](https://github.com/material-components/material-components-android/blob/master/lib/java/com/google/android/material/button/res/values/styles.xml) and [attrs](https://github.com/material-components/material-components-android/blob/master/lib/java/com/google/android/material/button/res/values/attrs.xml).

</details>
