//[library](../../index.md)/[com.glovoapp.uds](index.md)/[Avatar](-avatar.md)

# Avatar

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Avatar](-avatar.md)(shape: [AvatarShape](-avatar-shape/index.md), size: [AvatarSize](-avatar-size/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, isLoading: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, content: @[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null)

Design System Avatar Component

Visual representations that identify people or business entities in the UI.

#### Parameters

androidJvm

| | |
|---|---|
| shape | [AvatarShape](-avatar-shape/index.md) shape to be displayed. |
| size | [AvatarSize](-avatar-size/index.md) size to be displayed. |
| modifier | the modifier to be applied to the Avatar component. |
| isLoading | if the Avatar is loading. |
| content | the content to be displayed inside the Avatar. If null the Avatar will be considered as unset or empty. |

#### See also

| |
|---|
| [AvatarShape](-avatar-shape/index.md) |
| [AvatarSize](-avatar-size/index.md) |

#### Samples

```kotlin
import androidx.compose.foundation.Image
import androidx.compose.foundation.background
import androidx.compose.foundation.layout.Box
import androidx.compose.foundation.layout.fillMaxSize
import androidx.compose.runtime.Composable
import androidx.compose.ui.Modifier
import androidx.compose.ui.graphics.Color
import androidx.compose.ui.graphics.vector.rememberVectorPainter
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Avatar
import com.glovoapp.uds.AvatarShape
import com.glovoapp.uds.AvatarSize

fun main() { 
   //sampleStart 
   Avatar(
    shape = AvatarShape.Square,
    size = AvatarSize.S
) {
    Image(painter = rememberVectorPainter(SampleImageVector), contentDescription = "")
} 
   //sampleEnd
}
```
```kotlin
import androidx.compose.foundation.Image
import androidx.compose.foundation.background
import androidx.compose.foundation.layout.Box
import androidx.compose.foundation.layout.fillMaxSize
import androidx.compose.runtime.Composable
import androidx.compose.ui.Modifier
import androidx.compose.ui.graphics.Color
import androidx.compose.ui.graphics.vector.rememberVectorPainter
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Avatar
import com.glovoapp.uds.AvatarShape
import com.glovoapp.uds.AvatarSize

fun main() { 
   //sampleStart 
   Avatar(
    shape = AvatarShape.Square,
    size = AvatarSize.S,
    text = "AB"
) 
   //sampleEnd
}
```
```kotlin
import androidx.compose.foundation.Image
import androidx.compose.foundation.background
import androidx.compose.foundation.layout.Box
import androidx.compose.foundation.layout.fillMaxSize
import androidx.compose.runtime.Composable
import androidx.compose.ui.Modifier
import androidx.compose.ui.graphics.Color
import androidx.compose.ui.graphics.vector.rememberVectorPainter
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Avatar
import com.glovoapp.uds.AvatarShape
import com.glovoapp.uds.AvatarSize

fun main() { 
   //sampleStart 
   Avatar(
    shape = AvatarShape.Square,
    size = AvatarSize.S,
    isLoading = true,
    content = { }
) 
   //sampleEnd
}
```
```kotlin
import androidx.compose.foundation.Image
import androidx.compose.foundation.background
import androidx.compose.foundation.layout.Box
import androidx.compose.foundation.layout.fillMaxSize
import androidx.compose.runtime.Composable
import androidx.compose.ui.Modifier
import androidx.compose.ui.graphics.Color
import androidx.compose.ui.graphics.vector.rememberVectorPainter
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.Avatar
import com.glovoapp.uds.AvatarShape
import com.glovoapp.uds.AvatarSize

fun main() { 
   //sampleStart 
   Avatar(
    shape = AvatarShape.Square,
    size = AvatarSize.S,
    isLoading = true,
    content = null
) 
   //sampleEnd
}
```

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Avatar](-avatar.md)(shape: [AvatarShape](-avatar-shape/index.md), size: [AvatarSize](-avatar-size/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, isLoading: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, text: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, overflow: [TextOverflow](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/style/TextOverflow.html) = TextOverflow.Clip)

Design System Avatar

Convenience function to create an [Avatar](-avatar.md) with a text content.

#### Parameters

androidJvm

| | |
|---|---|
| shape | [AvatarShape](-avatar-shape/index.md) shape to be displayed. |
| size | [AvatarSize](-avatar-size/index.md) size to be displayed. |
| modifier | the modifier to be applied to the Avatar component. |
| isLoading | if the Avatar is loading. |
| text | the text to be displayed inside the Avatar. Usually limited to 1 character. If null the Avatar will be considered as unset. |

#### Samples

com.glovoapp.uds.samples.AvatarPreview
