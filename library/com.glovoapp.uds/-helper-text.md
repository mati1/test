//[library](../../index.md)/[com.glovoapp.uds](index.md)/[HelperText](-helper-text.md)

# HelperText

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [HelperText](-helper-text.md)(text: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [HelperTextType](-helper-text-type/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, showLeadingIcon: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)

Design System Helper Text Component

[HelperText](-helper-text.md) contains an [Icon](-icon/index.md) followed by a text

#### Parameters

androidJvm

| | |
|---|---|
| text | the text to be shown in the helper text. |
| type | the predefined type supported. |
| modifier | the modifier is applied to the internal [HelperText](-helper-text.md) usage. By default,it just pass the modifier. |
| showLeadingIcon | to chose between showing or hiding the icon |

#### See also

| |
|---|
| [CoreIcon](-core-icon/index.md) |
| HelperTextColors |
