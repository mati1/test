//[library](../../index.md)/[com.glovoapp.uds](index.md)/[Blob](-blob.md)

# Blob

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Blob](-blob.md)(shape: [BlobShapeType](-blob-shape-type/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, tint: [Color](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/Color.html) = Color.Unspecified)

Design System Blob

#### Parameters

androidJvm

| | |
|---|---|
| shape | [BlobShapeType](-blob-shape-type/index.md) shape to be displayed. |
| modifier | the modifier to be applied to the Blob component. |
| tint | the color to tint the blob with. |

#### See also

| |
|---|
| [BlobShapeType](-blob-shape-type/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.graphics.Color
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Blob
import com.glovoapp.uds.BlobShadowType
import com.glovoapp.uds.BlobShapeType

fun main() { 
   //sampleStart 
   Blob(
    shape = BlobShapeType.Shape03,
    tint = Color.Red,
) 
   //sampleEnd
}
```

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Blob](-blob.md)(shadow: [BlobShadowType](-blob-shadow-type/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, tint: [Color](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/Color.html) = Color.Unspecified)

Design System Blob

#### Parameters

androidJvm

| | |
|---|---|
| shadow | [BlobShadowType](-blob-shadow-type/index.md) shape to be displayed. For predefined blob shadows check [BlobShadowType](-blob-shadow-type/index.md). |
| modifier | the modifier to be applied to the Blob component. |
| tint | the color to tint the blob with. |

#### See also

| |
|---|
| [BlobShadowType](-blob-shadow-type/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.graphics.Color
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Blob
import com.glovoapp.uds.BlobShadowType
import com.glovoapp.uds.BlobShapeType

fun main() { 
   //sampleStart 
   Blob(
    shadow = BlobShadowType.Shadow03,
    tint = Color.Red,
) 
   //sampleEnd
}
```
