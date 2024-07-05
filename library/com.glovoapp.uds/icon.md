//[library](../../index.md)/[com.glovoapp.uds](index.md)/[icon](icon.md)

# icon

[androidJvm]\

@get:[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

val [CoreIcon](-core-icon/index.md).[icon](icon.md): [Icon](-icon/index.md)

Design System Icons

#### See also

| |
|---|
| [Icon](-icon/index.md) |
| [CoreIcon](-core-icon/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.CoreIcon
import com.glovoapp.uds.Icon
import com.glovoapp.uds.IconSize
import com.glovoapp.uds.icon

fun main() { 
   //sampleStart 
   Icon(
    icon = CoreIcon.CASH.icon,
    contentDescription = "Cash",
    size = IconSize.M
) 
   //sampleEnd
}
```
