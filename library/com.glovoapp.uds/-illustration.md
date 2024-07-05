//[library](../../index.md)/[com.glovoapp.uds](index.md)/[Illustration](-illustration.md)

# Illustration

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Illustration](-illustration.md)(painter: [Painter](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/painter/Painter.html), contentDescription: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, size: [IllustrationSize](-illustration-size/index.md))

Design System Illustration Component

Draw an Illustration with a painter using the specified size.

#### Parameters

androidJvm

| | |
|---|---|
| painter | the [Painter](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/painter/Painter.html) to be drawn |
| contentDescription | the content description of the illustration. |
| modifier | the [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) to be applied to [Illustration](-illustration.md) |
| size | the size of the illustration to be drawn. |

#### See also

| |
|---|
| [IllustrationSize](-illustration-size/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.graphics.vector.rememberVectorPainter
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Illustration
import com.glovoapp.uds.IllustrationSize

fun main() { 
   //sampleStart 
   Illustration(
    painter = rememberVectorPainter(SampleImageVector),
    contentDescription = "Illustration",
    size = IllustrationSize.XXL,
) 
   //sampleEnd
}
```
