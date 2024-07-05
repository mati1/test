//[library](../../index.md)/[com.glovoapp.uds](index.md)/[IconButton](-icon-button.md)

# IconButton

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [IconButton](-icon-button.md)(icon: [Icon](-icon/index.md), contentDescription: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, style: [IconButtonStyle](-icon-button-style/index.md) = IconButtonStyle.Primary, size: [IconButtonSize](-icon-button-size/index.md) = IconButtonSize.Medium, enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, loading: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, interactionSource: [MutableInteractionSource](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/MutableInteractionSource.html) = remember { MutableInteractionSource() }, onClick: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

Design System Icon Button Component

Icon Button with an [Icon](-icon/index.md) or a CircularProgressIndicator in the center.

#### Parameters

androidJvm

| | |
|---|---|
| icon | sets the icon based on [Icon](-icon/index.md) to be shown when the button is not in a loading state. Only the foreground resource is used. |
| contentDescription | optional content description for accessibility. |
| modifier | the modifier is applied to the internal ButtonSurface usage. |
| style | is used to define the background and other behaviors of each button variant. |
| size | [IconButtonSize](-icon-button-size/index.md) is responsible for the size of the button, the icon, padding, and border width. |
| enabled | controls the enabled state of this button. When `false`, this component will not respond to user input, and it will appear visually disabled and disabled to accessibility services. |
| loading | whether the button is in a loading state. If true, the button will display a circular progress indicator and hide the icon. |
| interactionSource | the [MutableInteractionSource](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/MutableInteractionSource.html) representing the stream of [Interaction](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/Interaction.html)s for this button. You can create and pass in your own `remember`ed instance to observe. [Interaction](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/Interaction.html)s and customize the appearance/behavior of this button in different states. |
| onClick | called when this button is clicked. |

#### See also

| |
|---|
| [ButtonStyle](-button-style/index.md) |
| [IconButtonSize](-icon-button-size/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.IconButton
import com.glovoapp.uds.IconButtonSize
import com.glovoapp.uds.CoreIcon
import com.glovoapp.uds.IconButtonStyle
import com.glovoapp.uds.icon

fun main() { 
   //sampleStart 
   IconButton(
    icon = CoreIcon.PLUS.icon,
    contentDescription = "Content description",
    style = IconButtonStyle.Primary,
    size = IconButtonSize.Large,
    onClick = {}
) 
   //sampleEnd
}
```

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [~~IconButton~~](-icon-button.md)(icon: [Icon](-icon/index.md), contentDescription: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, colors: [ButtonColors](-button-colors/index.md), sizes: [IconButtonSizes](-icon-button-sizes/index.md), enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, loading: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, interactionSource: [MutableInteractionSource](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/MutableInteractionSource.html) = remember { MutableInteractionSource() }, onClick: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

---

### Deprecated

Prefer to use IconButton with an `IconButtonStyle` and a `IconButtonSize`

---
