//[library](../../index.md)/[com.glovoapp.uds](index.md)/[IllustrationBlob](-illustration-blob.md)

# IllustrationBlob

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [IllustrationBlob](-illustration-blob.md)(painter: [Painter](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/painter/Painter.html), size: [IllustrationBlobSize](-illustration-blob-size/index.md), style: [IllustrationBlobStyle](-illustration-blob-style/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, contentDescription: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, blobShape: [BlobShapeType](-blob-shape-type/index.md) = BlobShapeType.Shape02)

Design System IllustrationBlob Component

IllustrationBlob is a composable that draws an illustration inside a blob. The illustration is centered inside the blob.

#### Parameters

androidJvm

| | |
|---|---|
| painter | The painter to draw inside the blob. |
| size | The size of the illustration blob. |
| style | The colors of the illustration blob. |
| modifier | The modifier to be applied to the illustration blob. |
| contentDescription | The content description of the illustration blob. |
| blobShape | The shape of the blob. |

#### See also

| |
|---|
| [IllustrationBlobSize](-illustration-blob-size/index.md) |
| [IllustrationBlobStyle](-illustration-blob-style/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.graphics.vector.rememberVectorPainter
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.IllustrationBlob
import com.glovoapp.uds.IllustrationBlobSize
import com.glovoapp.uds.IllustrationBlobStyle

fun main() { 
   //sampleStart 
   IllustrationBlob(
    painter = rememberVectorPainter(SampleImageVector),
    contentDescription = "",
    style = IllustrationBlobStyle.Neutral,
    size = IllustrationBlobSize.M,
) 
   //sampleEnd
}
```

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [IllustrationBlob](-illustration-blob.md)(painter: [Painter](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/painter/Painter.html), contentDescription: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, size: [IllustrationBlobSize](-illustration-blob-size/index.md))

Design System IllustrationBlob

Convenience function to draw an illustration blob with a painter using the specified size.

#### Parameters

androidJvm

| | |
|---|---|
| painter | The painter to draw. |
| contentDescription | The content description of the illustration blob. |
| modifier | The modifier to be applied to the illustration blob. |
| size | The size of the illustration blob. |

#### See also

| |
|---|
| [IllustrationBlobSize](-illustration-blob-size/index.md) |
