//[library](../../index.md)/[com.glovoapp.uds](index.md)/[Toggle](-toggle.md)

# Toggle

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Toggle](-toggle.md)(selected: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, onCheckedChange: ([Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)?)

Design System Toggle

#### Parameters

androidJvm

| | |
|---|---|
| selected | select or unselect the toggle changing the position of the knob |
| modifier | the Modifier to be applied to this checkbox |
| enabled | makes the component interactive or not |
| onCheckedChange | called when this checkbox is clicked. If null, then this checkbox will not be intractable. |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.runtime.getValue
import androidx.compose.runtime.mutableStateOf
import androidx.compose.runtime.remember
import androidx.compose.runtime.setValue
import androidx.compose.ui.tooling.preview.Preview
import com.glovoapp.uds.Toggle

fun main() { 
   //sampleStart 
   var checkedState by remember { mutableStateOf(false) }

Toggle(selected = checkedState) {
    checkedState = it
} 
   //sampleEnd
}
```
