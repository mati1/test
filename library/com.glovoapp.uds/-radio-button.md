//[library](../../index.md)/[com.glovoapp.uds](index.md)/[RadioButton](-radio-button.md)

# RadioButton

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [RadioButton](-radio-button.md)(selected: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, onSelectedChange: ([Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null)

Design System RadioButton

#### Parameters

androidJvm

| | |
|---|---|
| selected | to toggle between selected and not selected |
| modifier | the Modifier to be applied to this RadioButton |
| enabled | to allow or not the radio button to be interactive |
| onSelectedChange | to listen to changes in the component |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.runtime.getValue
import androidx.compose.runtime.mutableStateOf
import androidx.compose.runtime.remember
import androidx.compose.runtime.setValue
import androidx.compose.ui.tooling.preview.Preview
import com.glovoapp.uds.RadioButton

fun main() { 
   //sampleStart 
   var selected by remember { mutableStateOf(false) }

RadioButton(
    selected = selected,
    onSelectedChange = { selected = !selected }
) 
   //sampleEnd
}
```
