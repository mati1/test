//[library](../../index.md)/[com.glovoapp.uds](index.md)/[Button](-button.md)

# Button

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Button](-button.md)(text: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, contentDescription: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = text, leadingIcon: [Icon](-icon/index.md)? = null, trailingIcon: [Icon](-icon/index.md)? = null, style: [ButtonStyle](-button-style/index.md) = ButtonStyle.Primary, size: [ButtonSize](-button-size/index.md) = ButtonSize.Medium, enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, loading: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, interactionSource: [MutableInteractionSource](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/MutableInteractionSource.html) = remember { MutableInteractionSource() }, onClick: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

Design System Button Component

[Button](-button.md) has a ButtonSurface that allows users to interact with the application calling for an action when clicked.

- 
   By default, it will use `Modifier.fillMaxWidth()`. If the use case requires wrapping the content, use `Modifier.wrapContentSize()`.
- 
   If the use case requires a button with only an icon and no text, use [IconButton](-icon-button.md).

#### Parameters

androidJvm

| | |
|---|---|
| text | the text to be shown in the button. |
| modifier | the modifier is applied to the internal ButtonSurface usage. By default, it fills the width. |
| contentDescription | optional content description for accessibility, defaults to the [text](-button.md). |
| leadingIcon | optional [Icon](-icon/index.md) foreground icon to be shown before the [text](-button.md). |
| trailingIcon | optional [Icon](-icon/index.md) foreground icon to be shown after the [text](-button.md). |
| style | define the [ButtonColors](-button-colors/index.md) of each button variant. |
| size | [ButtonSize](-button-size/index.md) is responsible for the size of the button, the icon, padding, and border width. |
| enabled | controls the enabled state of this button. When `false`, this component will not respond to user input, and it will appear visually disabled and disabled to accessibility services. |
| loading | whether the button is in a loading state. If true, the button will display a circular progress and hide the trailing icon |
| interactionSource | the [MutableInteractionSource](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/MutableInteractionSource.html) representing the stream of [Interaction](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/Interaction.html)s for this button. You can create and pass in your own `remember`ed instance to observe. |
| onClick | called when this button is clicked. |

#### See also

| |
|---|
| [ButtonStyle](-button-style/index.md) |
| [ButtonSize](-button-size/index.md) |
| [IconButton](-icon-button.md) |
| [CoreIcon](-core-icon/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Button
import com.glovoapp.uds.ButtonSize
import com.glovoapp.uds.ButtonStyle
import com.glovoapp.uds.CoreIcon
import com.glovoapp.uds.icon

fun main() { 
   //sampleStart 
   Button(
    text = "Button text",
    onClick = {}
) 
   //sampleEnd
}
```
```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Button
import com.glovoapp.uds.ButtonSize
import com.glovoapp.uds.ButtonStyle
import com.glovoapp.uds.CoreIcon
import com.glovoapp.uds.icon

fun main() { 
   //sampleStart 
   Button(
    text = "Button text",
    onClick = {},
    leadingIcon = CoreIcon.TAG.icon
) 
   //sampleEnd
}
```
