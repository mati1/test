//[library](../../index.md)/[com.glovoapp.uds](index.md)/[PasswordField](-password-field.md)

# PasswordField

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [PasswordField](-password-field.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), onValueChange: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, labelText: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, secondaryLabel: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, tooltipClick: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null, placeholder: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;&quot;, prefix: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, suffix: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, helperText: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, showHelperIcon: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, counterLimit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, isError: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, onImeActionDone: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}, keyboardOptions: [KeyboardOptions](https://developer.android.com/reference/kotlin/androidx/compose/foundation/text/KeyboardOptions.html) = KeyboardOptions(imeAction = ImeAction.Done), keyboardActions: [KeyboardActions](https://developer.android.com/reference/kotlin/androidx/compose/foundation/text/KeyboardActions.html) = KeyboardActions(onDone = { onImeActionDone() }), interactionSource: [MutableInteractionSource](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/MutableInteractionSource.html) = remember { MutableInteractionSource() })

Design System PasswordField

This component contains a pre-defined trailing icon that adds or remove [PasswordVisualTransformation](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/input/PasswordVisualTransformation.html)

[HelperText](-helper-text.md) contains an [Icon](-icon/index.md) followed by a text

#### Parameters

androidJvm

| | |
|---|---|
| value | the text to be shown in the TextField. |
| onValueChange | function to listen when text was changed. |
| modifier | the modifier is applied to the internal FieldText |
| labelText | label added on top of TextInput |
| secondaryLabel | the optional label added after label text as support text if needed |
| tooltipClick | optional click label action. When not null a clickable icon appears after the label. |
| placeholder | the optional placeholder to be displayed when the text field is in focus and the input text is empty. |
| prefix | the optional prefix to be displayed before the input text in the text field |
| suffix | the optional suffix to be displayed after the input text in the text field |
| helperText | optional text added below TextInput |
| showHelperIcon | when `true` it shows an icon before [helperText](-password-field.md) |
| counterLimit | optional count adding a value the TextInput will present FieldCounter |
| isError | indicates if the text field's current value is in error state. If set to true, the border and helper text will be displayed in error color from FieldStyle.Error |
| enabled | controls the enabled state of this text field. When `false`, this component will not respond to user input, and it will appear visually disabled as defined by FieldStyle.Disable instead of wrapping onto multiple lines. |
| interactionSource | the [MutableInteractionSource](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/MutableInteractionSource.html) representing the stream of [Interaction](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/Interaction.html)s for this text field. You can create and pass in your own `remember`ed instance to observe [Interaction](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/Interaction.html)s and customize the appearance / behavior of this text field in different states. |
| onImeActionDone | default imeAction is [ImeAction.Done](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/input/ImeAction.Companion.html#done) so use this parameter to react to interactions with [ImeAction.Search](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/input/ImeAction.Companion.html#search) |
| keyboardOptions | software keyboard options that contains configuration such as [KeyboardType](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/input/KeyboardType.html) and [ImeAction](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/input/ImeAction.html) |
| keyboardActions | when the input service emits an IME action, the corresponding callback is called. |

#### See also

| |
|---|
| [CoreIcon](-core-icon/index.md) |
| [HelperText](-helper-text.md) |
| FieldCounter |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.runtime.getValue
import androidx.compose.runtime.mutableStateOf
import androidx.compose.runtime.remember
import androidx.compose.runtime.setValue
import androidx.compose.ui.tooling.preview.Preview
import com.glovoapp.uds.PasswordField

fun main() { 
   //sampleStart 
   var value by remember { mutableStateOf("Hello, World!") }

PasswordField(
    labelText = "Label",
    value = value,
    onValueChange = { value = it },
    helperText = "Some help",
) 
   //sampleEnd
}
```
