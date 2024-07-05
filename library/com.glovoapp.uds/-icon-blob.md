//[library](../../index.md)/[com.glovoapp.uds](index.md)/[IconBlob](-icon-blob.md)

# IconBlob

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [IconBlob](-icon-blob.md)(icon: [Icon](-icon/index.md), style: [IconBlobStyle](-icon-blob-style/index.md), size: [IconBlobSize](-icon-blob-size/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, contentDescription: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, blobShape: [BlobShapeType](-blob-shape-type/index.md) = Shape02)

Design System IconBlob

IconBlob is a composable that draws an icon inside a blob. The icon is centered inside the blob.

#### Parameters

androidJvm

| | |
|---|---|
| icon | The icon to draw inside the blob. |
| style | The colors of the icon blob. |
| size | The size of the icon blob. |
| modifier | The modifier to be applied to the icon blob. |
| contentDescription | The content description of the icon blob. |
| blobShape | The shape of the blob. |

#### See also

| |
|---|
| [IconBlobStyle](-icon-blob-style/index.md) |
| [IconBlobSize](-icon-blob-size/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.graphics.vector.rememberVectorPainter
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.CoreIcon
import com.glovoapp.uds.IconBlob
import com.glovoapp.uds.IconBlobSize
import com.glovoapp.uds.IconBlobStyle
import com.glovoapp.uds.icon

fun main() { 
   //sampleStart 
   IconBlob(
    icon = CoreIcon.ROCKET.icon,
    style = IconBlobStyle.Neutral,
    size = IconBlobSize.M,
    contentDescription = "Rocket",
) 
   //sampleEnd
}
```

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [IconBlob](-icon-blob.md)(painter: [Painter](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/painter/Painter.html), style: [IconBlobStyle](-icon-blob-style/index.md), size: [IconBlobSize](-icon-blob-size/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, contentDescription: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, blobShape: [BlobShapeType](-blob-shape-type/index.md) = Shape02)

Design System IconBlob

Convenience function to draw an icon blob with a painter using the specified size. And show the Blob behind the icon.

#### Parameters

androidJvm

| | |
|---|---|
| painter | The painter to draw. |
| style | The colors of the icon blob. |
| size | The size of the icon blob. |
| modifier | The modifier to be applied to the icon blob. |
| contentDescription | The content description of the icon blob. |
| blobShape | The shape of the blob. |

#### See also

| |
|---|
| [IconBlobStyle](-icon-blob-style/index.md) |
| [IconBlobSize](-icon-blob-size/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.graphics.vector.rememberVectorPainter
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.CoreIcon
import com.glovoapp.uds.IconBlob
import com.glovoapp.uds.IconBlobSize
import com.glovoapp.uds.IconBlobStyle
import com.glovoapp.uds.icon

fun main() { 
   //sampleStart 
   IconBlob(
    painter = rememberVectorPainter(SampleImageVector),
    size = IconBlobSize.M,
    contentDescription = "RemoteVector",
) 
   //sampleEnd
}
```

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [IconBlob](-icon-blob.md)(painter: [Painter](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/painter/Painter.html), size: [IconBlobSize](-icon-blob-size/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, contentDescription: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)

Design System IconBlob

Convenience function to draw an icon blob with a painter using the specified size.

#### Parameters

androidJvm

| | |
|---|---|
| painter | The painter to draw. |
| size | The size of the icon blob. |
| modifier | The modifier to be applied to the icon blob. |
| contentDescription | The content description of the icon blob. |

#### See also

| |
|---|
| [IconBlobSize](-icon-blob-size/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.graphics.vector.rememberVectorPainter
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.CoreIcon
import com.glovoapp.uds.IconBlob
import com.glovoapp.uds.IconBlobSize
import com.glovoapp.uds.IconBlobStyle
import com.glovoapp.uds.icon

fun main() { 
   //sampleStart 
   IconBlob(
    painter = rememberVectorPainter(SampleImageVector),
    size = IconBlobSize.M,
    contentDescription = "RemoteVector",
    style = IconBlobStyle.Positive
) 
   //sampleEnd
}
```
