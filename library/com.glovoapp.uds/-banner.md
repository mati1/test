//[library](../../index.md)/[com.glovoapp.uds](index.md)/[Banner](-banner.md)

# Banner

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Banner](-banner.md)(title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), bottomLink: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, style: [BannerStyle](-banner-style/index.md), size: [BannerSize](-banner-size/index.md), painter: [Painter](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/painter/Painter.html)? = null)

Design System Banner

Banner with a title, description, and a bottom link. Plus, depending on the [size](-banner.md) if will have an icon or an illustration.

#### Parameters

androidJvm

| | |
|---|---|
| title | The title of the banner. |
| description | The description of the banner. |
| bottomLink | The bottom link of the banner. |
| modifier | The modifier to be applied to the banner. |
| style | The colors of the banner. |
| size | The size of the banner. |
| painter | The painter to draw inside the banner. |

#### See also

| |
|---|
| [BannerStyle](-banner-style/index.md) |
| [BannerSize](-banner-size/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.graphics.painter.Painter
import androidx.compose.ui.graphics.vector.rememberVectorPainter
import androidx.compose.ui.res.painterResource
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Banner
import com.glovoapp.uds.BannerSize
import com.glovoapp.uds.BannerStyle
import com.glovoapp.uds.BlobShapeType
import com.glovoapp.uds.R

fun main() { 
   //sampleStart 
   Banner(
    title = "Lorem ipsum dolor sit amet",
    description = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam eget nunc nec nunc. " +
        "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam eget nunc nec nunc.",
    bottomLink = "Learn more",
    style = variant.style,
    size = variant.size,
    painter = variant.painter(),
) 
   //sampleEnd
}
```
