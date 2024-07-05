//[library](../../index.md)/[com.glovoapp.uds](index.md)/[SearchField](-search-field.md)

# SearchField

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [SearchField](-search-field.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), onValueChange: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, size: [SearchFieldSize](-search-field-size/index.md) = SearchFieldSize.Medium, enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, placeholder: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;&quot;, onImeActionSearch: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}, visualTransformation: [VisualTransformation](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/input/VisualTransformation.html) = VisualTransformation.None, keyboardOptions: [KeyboardOptions](https://developer.android.com/reference/kotlin/androidx/compose/foundation/text/KeyboardOptions.html) = KeyboardOptions(imeAction = ImeAction.Search), keyboardActions: [KeyboardActions](https://developer.android.com/reference/kotlin/androidx/compose/foundation/text/KeyboardActions.html) = KeyboardActions(onSearch = { onImeActionSearch() }), interactionSource: [MutableInteractionSource](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/MutableInteractionSource.html) = remember { MutableInteractionSource() })

Design System SearchField

Search Field contains an trailing icon that appears when the input is focused and there is some text. The trailing icon has the capability to clear the search field.

#### Parameters

androidJvm

| | |
|---|---|
| value | the text to be shown in the TextField. |
| onValueChange | function to listen when text was changed. |
| modifier | the modifier is applied to the internal FieldText |
| placeholder | the optional placeholder to be displayed when the text field is in focus and the input text is empty. |
| size | define the height of TextInput box and horizontal padding. not respond to user input, and it will appear visually disabled as defined by FieldStyle.Disable instead of wrapping onto multiple lines. |
| enabled | controls the enabled state of this text field. When `false`, this component will not respond to user input, and it will appear visually disabled as defined by FieldStyle.Disable |
| interactionSource | the [MutableInteractionSource](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/MutableInteractionSource.html) representing the stream of [Interaction](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/Interaction.html)s for this text field. You can create and pass in your own `remember`ed instance to observe [Interaction](https://developer.android.com/reference/kotlin/androidx/compose/foundation/interaction/Interaction.html)s and customize the appearance / behavior of this text field in different states. |
| keyboardOptions | software keyboard options that contains configuration such as [KeyboardType](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/input/KeyboardType.html) and [ImeAction](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/input/ImeAction.html) |
| visualTransformation | transforms the visual representation of the input [value](-search-field.md) |
| keyboardActions | when the input service emits an IME action, the corresponding callback is called. |
| onImeActionSearch | default imeAction is [ImeAction.Search](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/input/ImeAction.Companion.html#search) so use this parameter to react to interactions with [ImeAction.Search](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/input/ImeAction.Companion.html#search) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.runtime.getValue
import androidx.compose.runtime.mutableStateOf
import androidx.compose.runtime.remember
import androidx.compose.runtime.setValue
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.SearchField
import com.glovoapp.uds.SearchFieldSize

fun main() { 
   //sampleStart 
   var text by remember { mutableStateOf("") }

SearchField(
    onValueChange = { text = it },
    value = text,
    placeholder = "Search",
) 
   //sampleEnd
}
```
