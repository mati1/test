//[library](../../index.md)/[com.glovoapp.uds](index.md)/[Icon](-icon.md)

# Icon

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Icon](-icon.md)(icon: [Icon](-icon/index.md), contentDescription: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, size: [IconSize](-icon-size/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, foregroundTint: [Color](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/Color.html) = CoreTheme.colorScheme.iconColorForegroundPrimary, backgroundTint: [Color](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/Color.html)? = CoreTheme.colorScheme.iconColorBackgroundPrimary)

Design System Icon Component

#### Parameters

androidJvm

| | |
|---|---|
| icon | [Icon](-icon/index.md) to draw. |
| contentDescription | The content description of the icon. |
| size | The size of the icon. |
| modifier | The modifier to be applied to the icon. |
| foregroundTint | The color to be used to tint the foreground of the icon. |
| backgroundTint | The color to be used to tint the background of the icon. |

#### See also

| |
|---|
| [Icon](-icon/index.md) |
| [IconSize](-icon-size/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.graphics.Color
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
    size = IconSize.L,
    contentDescription = null,
) 
   //sampleEnd
}
```
