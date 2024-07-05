//[library](../../../index.md)/[com.glovoapp.uds](../index.md)/[CoreBorderWidth](index.md)

# CoreBorderWidth

[androidJvm]\
data object [CoreBorderWidth](index.md)

Unified Deign System Border Widths

This group includes predefined sizes for border widths.

#### Samples

```kotlin
import androidx.compose.foundation.background
import androidx.compose.foundation.border
import androidx.compose.foundation.layout.Box
import androidx.compose.foundation.layout.size
import androidx.compose.runtime.Composable
import androidx.compose.ui.Modifier
import androidx.compose.ui.graphics.Color
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import androidx.compose.ui.unit.Dp
import androidx.compose.ui.unit.dp
import com.glovoapp.uds.CoreBorderWidth

fun main() { 
   //sampleStart 
   Box(
    modifier = Modifier
        .size(32.dp)
        .background(Color.White)
        .border(CoreBorderWidth.L, Color.Red)
) 
   //sampleEnd
}
```

## Properties

| Name | Summary |
|---|---|
| [L](-l.md) | [androidJvm]<br>val [L](-l.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
| [M](-m.md) | [androidJvm]<br>val [M](-m.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
| [None](-none.md) | [androidJvm]<br>val [None](-none.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
| [S](-s.md) | [androidJvm]<br>val [S](-s.md): [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) |
