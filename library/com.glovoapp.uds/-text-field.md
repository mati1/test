//[library](../../index.md)/[com.glovoapp.uds](index.md)/[TextField](-text-field.md)

# TextField

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [TextField](-text-field.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), onValueChange: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, labelText: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, secondaryLabel: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, tooltipClick: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null, leadingIcon: [Icon](-icon/index.md)? = null, trailingIcon: @[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)[FieldTextIconDefaults](-field-text-icon-defaults/index.md).() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null, placeholder: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;&quot;, prefix: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, suffix: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, visualTransformation: [VisualTransformation](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/input/VisualTransformation.html) = VisualTransformation.None, helperText: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, showHelperIcon: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, counterLimit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, isError: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, singleLine: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, maxLines: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = if (singleLine) 1 else Int.MAX_VALUE, minLines: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1, keyboardOptions: [KeyboardOptions](https://developer.android.com/reference/kotlin/androidx/compose/foundation/text/KeyboardOptions.html) = KeyboardOptions.Default, keyboardActions: [KeyboardActions](https://developer.android.com/reference/kotlin/androidx/compose/foundation/text/KeyboardActions.html) = KeyboardActions.Default, interactionSource: [MutableInteractionSource](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/MutableInteractionSource.html) = remember { MutableInteractionSource() })

Design System TextField Component

#### Parameters

androidJvm

| | |
|---|---|
| value | the text to be shown in the TextField. |
| onValueChange | function to listen when text was changed. |
| modifier | the modifier is applied to the internal FieldText |
| labelText | label added on top of TextInput |
| secondaryLabel | the optional label added after label text as support text if needed |
| tooltipClick | optional click label action. When not null a clickable icon appears after the label or secondary label |
| leadingIcon | the optional leading icon to be displayed at the beginning of the text field container |
| trailingIcon | the optional trailing icon to be displayed at the end of the text field container |
| placeholder | the optional placeholder to be displayed when the text field is in focus and the input text is empty. |
| prefix | the optional prefix to be displayed before the input text in the text field |
| suffix | the optional suffix to be displayed after the input text in the text field |
| visualTransformation | transforms the visual representation of the input input |
| helperText | optional text added below TextInput |
| showHelperIcon | when `true` it shows an icon before [helperText](-text-field.md) |
| counterLimit | optional count adding a value the TextInput will present FieldCounter |
| isError | indicates if the text field's current value is in error state. If set to true, the border and helper text will be displayed in error color from FieldStyle.Error |
| enabled | controls the enabled state of this text field. When `false`, this component will not respond to user input, and it will appear visually disabled as defined by FieldStyle.Disable |
| singleLine | when `true`, this text field becomes a single horizontally scrolling text field instead of wrapping onto multiple lines. |
| maxLines | the maximum height in terms of maximum number of visible lines. It is required that 1 <= [minLines](-text-field.md)<= [maxLines](-text-field.md). This parameter is ignored when [singleLine](-text-field.md) is true. |
| minLines | the minimum height in terms of minimum number of visible lines. It is required that 1 <= [minLines](-text-field.md)<= [maxLines](-text-field.md). This parameter is ignored when [singleLine](-text-field.md) is true. |
| interactionSource | the [MutableInteractionSource](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/MutableInteractionSource.html) representing the stream of [Interaction](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/Interaction.html)s for this text field. You can create and pass in your own `remember`ed instance to observe [Interaction](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/Interaction.html)s and customize the appearance / behavior of this text field in different states. |
| keyboardOptions | software keyboard options that contains configuration such as [KeyboardType](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/input/KeyboardType.html) and [ImeAction](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/input/ImeAction.html) |
| keyboardActions | when the input service emits an IME action, the corresponding callback is called. |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.runtime.getValue
import androidx.compose.runtime.mutableStateOf
import androidx.compose.runtime.remember
import androidx.compose.runtime.setValue
import androidx.compose.ui.tooling.preview.Preview
import com.glovoapp.uds.CoreIcon
import com.glovoapp.uds.TextField
import com.glovoapp.uds.icon

fun main() { 
   //sampleStart 
   var value by remember { mutableStateOf("Hello, World!") }

TextField(
    labelText = "Label",
    secondaryLabel = "Optional",
    tooltipClick = {},
    enabled = true,
    isError = false,
    onValueChange = { value = it },
    helperText = "Some help",
    placeholder = "Placeholder",
    counterLimit = 4,
    showHelperIcon = true,
    value = value,
    prefix = "P",
    suffix = "S",
    leadingIcon = CoreIcon.BADGE.icon,
    trailingIcon = {
        Icon(
            icon = CoreIcon.CROSS.icon,
            contentDescription = null,
            onClick = { }
        )
    }
) 
   //sampleEnd
}
```
