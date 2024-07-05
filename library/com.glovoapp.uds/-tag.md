//[library](../../index.md)/[com.glovoapp.uds](index.md)/[Tag](-tag.md)

# Tag

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [Tag](-tag.md)(style: [TagStyle](-tag-style/index.md), modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, text: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, icon: [Icon](-icon/index.md)? = null)

Design System Tag

Tag can be used with an Icon followed by a text, but also with only text or only an icon

#### Parameters

androidJvm

| | |
|---|---|
| style | [TagStyle](-tag-style/index.md) to be used |
| text | text to be shown inside the tag |
| icon | [Icon](-icon/index.md) to be shown inside the tag |

#### See also

| |
|---|
| [TagStyle](-tag-style/index.md) |
| [Icon](-icon/index.md) |

#### Samples

```kotlin
import androidx.compose.runtime.Composable
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.CoreIcon
import com.glovoapp.uds.Tag
import com.glovoapp.uds.TagStyle
import com.glovoapp.uds.icon

fun main() { 
   //sampleStart 
   Tag(
    style = TagStyle.Loyalty,
    text = "Label com",
) 
   //sampleEnd
}
```
