//[library](../../index.md)/[com.glovoapp.uds](index.md)/[Badge](-badge.md)

# Badge

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Badge](-badge.md)(style: [BadgeStyle](-badge-style/index.md), size: [BadgeSize](-badge-size/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, count: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null)

Design System Badge Component

#### Parameters

androidJvm

| | |
|---|---|
| style | [BadgeStyle](-badge-style/index.md) define the background color to be used in the badge |
| count | for [BadgeSize.S](-badge-size/-s/index.md) and [BadgeSize.M](-badge-size/-m/index.md) the badge supports a count text, to values bigger than 99 its recommended usage of 99+ as a count value |
| size | both badge and dot contains Medium and Small variants |
| modifier | the modifier to be applied to the Badge component. |

#### See also

| |
|---|
| [BadgeStyle](-badge-style/index.md) |
| [BadgeSize](-badge-size/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Badge
import com.glovoapp.uds.BadgeSize
import com.glovoapp.uds.BadgeStyle

fun main() { 
   //sampleStart 
   Badge(
    count = "99+",
    size = BadgeSize.M,
    style = BadgeStyle.Critical,
) 
   //sampleEnd
}
```
```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Badge
import com.glovoapp.uds.BadgeSize
import com.glovoapp.uds.BadgeStyle

fun main() { 
   //sampleStart 
   Badge(
    style = BadgeStyle.Critical,
    size = BadgeSize.M,
) 
   //sampleEnd
}
```
