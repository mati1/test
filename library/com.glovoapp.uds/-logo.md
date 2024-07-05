//[library](../../index.md)/[com.glovoapp.uds](index.md)/[Logo](-logo.md)

# Logo

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Logo](-logo.md)(brand: [LogoBrand](-logo-brand/index.md), type: [LogoType](-logo-type/index.md), size: [LogoSize](-logo-size/index.md), surface: [LogoSurface](-logo-surface/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, contentDescription: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null)

Design System Logo Component

Visual representation of the Logo. The logo is displayed based on the height of the LogoSize.

#### Parameters

androidJvm

| | |
|---|---|
| brand | [LogoBrand](-logo-brand/index.md) brand to be displayed. |
| type | [LogoType](-logo-type/index.md) type to be displayed. |
| size | [LogoSize](-logo-size/index.md) size to be displayed. |
| surface | [LogoSurface](-logo-surface/index.md) surface to be displayed. |
| modifier | the modifier to be applied to the Logo component. |
| contentDescription | the content description of the Logo component. |

#### Samples

```kotlin
import androidx.compose.foundation.background
import androidx.compose.foundation.layout.Box
import androidx.compose.foundation.layout.padding
import androidx.compose.runtime.Composable
import androidx.compose.ui.Modifier
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import androidx.compose.ui.unit.dp
import com.glovoapp.uds.CoreTheme
import com.glovoapp.uds.Logo
import com.glovoapp.uds.LogoBrand
import com.glovoapp.uds.LogoSize
import com.glovoapp.uds.LogoSurface
import com.glovoapp.uds.LogoType

fun main() { 
   //sampleStart 
   Logo(
    brand = LogoBrand.Main,
    type = LogoType.Logo,
    size = LogoSize.L,
    surface = LogoSurface.OnPrimary
) 
   //sampleEnd
}
```
