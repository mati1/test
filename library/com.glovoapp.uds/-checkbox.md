//[library](../../index.md)/[com.glovoapp.uds](index.md)/[Checkbox](-checkbox.md)

# Checkbox

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Checkbox](-checkbox.md)(checked: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, onCheckedChange: ([Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null)

Design System Checkbox Component

#### Parameters

androidJvm

| | |
|---|---|
| checked | select or unselect the checkbox this variant does not the [CheckboxState.Indeterminate](-checkbox-state/-indeterminate/index.md) state |
| enabled | makes the component interactive or not |
| modifier | the Modifier to be applied to this checkbox |
| onCheckedChange | called when this checkbox is clicked. If null, then this checkbox will not be interactable. |

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
import com.glovoapp.uds.Checkbox
import com.glovoapp.uds.CheckboxState

fun main() { 
   //sampleStart 
   var checked by remember { mutableStateOf(false) }

Checkbox(checked = checked) {
    checked = it
} 
   //sampleEnd
}
```
```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.runtime.getValue
import androidx.compose.runtime.mutableStateOf
import androidx.compose.runtime.remember
import androidx.compose.runtime.setValue
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Checkbox
import com.glovoapp.uds.CheckboxState

fun main() { 
   //sampleStart 
   var state by remember { mutableStateOf(CheckboxState.Unselected) }

Checkbox(state = state) {
    state = when (state) {
        CheckboxState.Selected -> CheckboxState.Unselected
        CheckboxState.Indeterminate -> CheckboxState.Selected
        CheckboxState.Unselected -> CheckboxState.Indeterminate
    }
} 
   //sampleEnd
}
```

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Checkbox](-checkbox.md)(state: [CheckboxState](-checkbox-state/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, onClick: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null)

Design System Checkbox

#### Parameters

androidJvm

| | |
|---|---|
| state | the state of checkbox |
| modifier | the Modifier to be applied to this checkbox |
| enabled | makes the component interactive or not |
| onClick | called when this checkbox is clicked. If null, then this checkbox will not be intractable. |

#### See also

| |
|---|
| [CheckboxState](-checkbox-state/index.md) |

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
import com.glovoapp.uds.Checkbox
import com.glovoapp.uds.CheckboxState

fun main() { 
   //sampleStart 
   var checked by remember { mutableStateOf(false) }

Checkbox(checked = checked) {
    checked = it
} 
   //sampleEnd
}
```
```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.runtime.getValue
import androidx.compose.runtime.mutableStateOf
import androidx.compose.runtime.remember
import androidx.compose.runtime.setValue
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Checkbox
import com.glovoapp.uds.CheckboxState

fun main() { 
   //sampleStart 
   var state by remember { mutableStateOf(CheckboxState.Unselected) }

Checkbox(state = state) {
    state = when (state) {
        CheckboxState.Selected -> CheckboxState.Unselected
        CheckboxState.Indeterminate -> CheckboxState.Selected
        CheckboxState.Unselected -> CheckboxState.Indeterminate
    }
} 
   //sampleEnd
}
```
