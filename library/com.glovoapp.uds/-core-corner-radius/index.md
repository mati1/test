//[library](../../../index.md)/[com.glovoapp.uds](../index.md)/[CoreCornerRadius](index.md)

# CoreCornerRadius

[androidJvm]\
data object [CoreCornerRadius](index.md)

Design System Corner Radii.

This group includes predefined corner radii.

#### Samples

```kotlin
import androidx.compose.foundation.background
import androidx.compose.foundation.layout.Box
import androidx.compose.foundation.layout.size
import androidx.compose.foundation.shape.RoundedCornerShape
import androidx.compose.runtime.Composable
import androidx.compose.ui.Modifier
import androidx.compose.ui.graphics.Color
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import androidx.compose.ui.unit.Dp
import androidx.compose.ui.unit.dp
import com.glovoapp.uds.CoreCornerRadius

fun main() { 
   //sampleStart 
   Box(
    modifier = Modifier
        .size(128.dp)
        .background(
            color = Color.Red,
            shape = RoundedCornerShape(CoreCornerRadius.L)
        )
) 
   //sampleEnd
}
```

## Properties

| Name | Summary |
|---|---|
| [Full](-full.md) | [androidJvm]<br>val [Full](-full.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
| [L](-l.md) | [androidJvm]<br>val [L](-l.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
| [M](-m.md) | [androidJvm]<br>val [M](-m.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
| [None](-none.md) | [androidJvm]<br>val [None](-none.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
| [S](-s.md) | [androidJvm]<br>val [S](-s.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
| [XL](-x-l.md) | [androidJvm]<br>val [XL](-x-l.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
| [XS](-x-s.md) | [androidJvm]<br>val [XS](-x-s.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
| [XXL](-x-x-l.md) | [androidJvm]<br>val [XXL](-x-x-l.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
| [XXS](-x-x-s.md) | [androidJvm]<br>val [XXS](-x-x-s.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
| [XXXS](-x-x-x-s.md) | [androidJvm]<br>val [XXXS](-x-x-x-s.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
