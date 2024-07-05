//[library](../../../index.md)/[com.glovoapp.uds](../index.md)/[CoreAnimation](index.md)/[hint](hint.md)

# hint

[androidJvm]\

@[Stable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Stable.html)

fun &lt;[T](hint.md)&gt; [hint](hint.md)(): [TweenSpec](https://developer.android.com/reference/kotlin/androidx/compose/animation/core/TweenSpec.html)&lt;[T](hint.md)&gt;

Hints, tooltips, or brief visual cues.

#### Samples

```kotlin
import androidx.compose.animation.AnimatedVisibility
import androidx.compose.animation.core.TweenSpec
import androidx.compose.animation.fadeIn
import androidx.compose.animation.fadeOut
import androidx.compose.foundation.background
import androidx.compose.foundation.layout.Box
import androidx.compose.foundation.layout.size
import androidx.compose.runtime.Composable
import androidx.compose.ui.Modifier
import androidx.compose.ui.graphics.Color
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import androidx.compose.ui.unit.dp
import com.glovoapp.uds.CoreAnimation

fun main() { 
   //sampleStart 
   AnimatedVisibility(
    visible = true,
    enter = fadeIn(CoreAnimation.hint()),
    exit = fadeOut(CoreAnimation.hint()),
) {
    Box(
        modifier = Modifier
            .size(32.dp)
            .background(Color.Red)
    )
} 
   //sampleEnd
}
```
