//[library](../../../index.md)/[com.glovoapp.uds](../index.md)/[CoreTypography](index.md)

# CoreTypography

[androidJvm]\
@[Immutable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Immutable.html)

open class [CoreTypography](index.md)(val feature1: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs64.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh72.sp,
        fontWeight = CoreFontWeight.Bold,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val feature2: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs49.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh52.sp,
        fontWeight = CoreFontWeight.Bold,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val feature3: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs37.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh40.sp,
        fontWeight = CoreFontWeight.Bold,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val title1: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs28.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh32.sp,
        fontWeight = CoreFontWeight.Bold,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val title2: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs24.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh28.sp,
        fontWeight = CoreFontWeight.Bold,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val title3: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs21.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh24.sp,
        fontWeight = CoreFontWeight.Bold,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val callout1: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs16.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh20.sp,
        fontWeight = CoreFontWeight.Bold,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val callout2: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs14.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh20.sp,
        fontWeight = CoreFontWeight.Bold,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val callout3: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs12.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh16.sp,
        fontWeight = CoreFontWeight.Bold,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val body1: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs16.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh20.sp,
        fontWeight = CoreFontWeight.Book,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val body1Emphasis: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs16.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh20.sp,
        fontWeight = CoreFontWeight.Medium,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val body2: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs14.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh20.sp,
        fontWeight = CoreFontWeight.Book,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val body2Emphasis: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs14.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh20.sp,
        fontWeight = CoreFontWeight.Medium,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val caption: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs12.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh16.sp,
        fontWeight = CoreFontWeight.Book,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val captionEmphasis: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs12.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh16.sp,
        fontWeight = CoreFontWeight.Medium,
        lineHeightStyle = DefaultLineHeightStyle,
    ), val captionLink: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(
        fontFamily = CoreFontFamily,
        fontSize = CorePrimitive.textPropertiesFontSizeFs12.sp,
        lineHeight = CorePrimitive.textPropertiesLineHeightLh16.sp,
        fontWeight = CoreFontWeight.Bold,
        lineHeightStyle = DefaultLineHeightStyle,
        textDecoration = TextDecoration.Underline,
    ))

Design System Typography

This class is used to define the text styles of the CoreTheme.

#### Samples

```kotlin
import androidx.compose.foundation.text.BasicText
import androidx.compose.runtime.Composable
import androidx.compose.ui.text.TextStyle
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.tooling.preview.PreviewParameter
import androidx.compose.ui.tooling.preview.PreviewParameterProvider
import com.glovoapp.uds.CoreTheme

fun main() { 
   //sampleStart 
   BasicText(
    text = "Hello, World!",
    style = CoreTheme.typography.body1
) 
   //sampleEnd
}
```

## Constructors

| | |
|---|---|
| [CoreTypography](-core-typography.md) | [androidJvm]<br>constructor(feature1: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs64.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh72.sp,         fontWeight = CoreFontWeight.Bold,         lineHeightStyle = DefaultLineHeightStyle,     ), feature2: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs49.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh52.sp,         fontWeight = CoreFontWeight.Bold,         lineHeightStyle = DefaultLineHeightStyle,     ), feature3: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs37.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh40.sp,         fontWeight = CoreFontWeight.Bold,         lineHeightStyle = DefaultLineHeightStyle,     ), title1: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs28.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh32.sp,         fontWeight = CoreFontWeight.Bold,         lineHeightStyle = DefaultLineHeightStyle,     ), title2: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs24.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh28.sp,         fontWeight = CoreFontWeight.Bold,         lineHeightStyle = DefaultLineHeightStyle,     ), title3: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs21.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh24.sp,         fontWeight = CoreFontWeight.Bold,         lineHeightStyle = DefaultLineHeightStyle,     ), callout1: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs16.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh20.sp,         fontWeight = CoreFontWeight.Bold,         lineHeightStyle = DefaultLineHeightStyle,     ), callout2: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs14.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh20.sp,         fontWeight = CoreFontWeight.Bold,         lineHeightStyle = DefaultLineHeightStyle,     ), callout3: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs12.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh16.sp,         fontWeight = CoreFontWeight.Bold,         lineHeightStyle = DefaultLineHeightStyle,     ), body1: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs16.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh20.sp,         fontWeight = CoreFontWeight.Book,         lineHeightStyle = DefaultLineHeightStyle,     ), body1Emphasis: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs16.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh20.sp,         fontWeight = CoreFontWeight.Medium,         lineHeightStyle = DefaultLineHeightStyle,     ), body2: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs14.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh20.sp,         fontWeight = CoreFontWeight.Book,         lineHeightStyle = DefaultLineHeightStyle,     ), body2Emphasis: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs14.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh20.sp,         fontWeight = CoreFontWeight.Medium,         lineHeightStyle = DefaultLineHeightStyle,     ), caption: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs12.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh16.sp,         fontWeight = CoreFontWeight.Book,         lineHeightStyle = DefaultLineHeightStyle,     ), captionEmphasis: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs12.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh16.sp,         fontWeight = CoreFontWeight.Medium,         lineHeightStyle = DefaultLineHeightStyle,     ), captionLink: [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html) = TextStyle(         fontFamily = CoreFontFamily,         fontSize = CorePrimitive.textPropertiesFontSizeFs12.sp,         lineHeight = CorePrimitive.textPropertiesLineHeightLh16.sp,         fontWeight = CoreFontWeight.Bold,         lineHeightStyle = DefaultLineHeightStyle,         textDecoration = TextDecoration.Underline,     )) |

## Properties

| Name | Summary |
|---|---|
| [body1](body1.md) | [androidJvm]<br>val [body1](body1.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used for most text in the product |
| [body1Emphasis](body1-emphasis.md) | [androidJvm]<br>val [body1Emphasis](body1-emphasis.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used to highlight a word, number or short phrase in the same hierarchy as body1 |
| [body2](body2.md) | [androidJvm]<br>val [body2](body2.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used as a smaller alternative to most text. Ideal for table content or other high density layouts |
| [body2Emphasis](body2-emphasis.md) | [androidJvm]<br>val [body2Emphasis](body2-emphasis.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used to highlight a word, number or short phrase in the same hierarchy as body2 |
| [callout1](callout1.md) | [androidJvm]<br>val [callout1](callout1.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used for large subheading or call-to-action |
| [callout2](callout2.md) | [androidJvm]<br>val [callout2](callout2.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used for medium subheading or call-to-action |
| [callout3](callout3.md) | [androidJvm]<br>val [callout3](callout3.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used for small subheading or call-to-action |
| [caption](caption.md) | [androidJvm]<br>val [caption](caption.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used as a smallest text size to be used sparingly |
| [captionEmphasis](caption-emphasis.md) | [androidJvm]<br>val [captionEmphasis](caption-emphasis.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used to highlight a word, number or short phrase in the same hierarchy as caption |
| [captionLink](caption-link.md) | [androidJvm]<br>val [captionLink](caption-link.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used for hyperlinks |
| [feature1](feature1.md) | [androidJvm]<br>val [feature1](feature1.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used to highlight a huge word, number, or short phrase (use sparingly) |
| [feature2](feature2.md) | [androidJvm]<br>val [feature2](feature2.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used to highlight a very large word, number, or short phrase |
| [feature3](feature3.md) | [androidJvm]<br>val [feature3](feature3.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used to highlight a large word, number, or short phrase |
| [title1](title1.md) | [androidJvm]<br>val [title1](title1.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used for large title |
| [title2](title2.md) | [androidJvm]<br>val [title2](title2.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used for medium title |
| [title3](title3.md) | [androidJvm]<br>val [title3](title3.md): [TextStyle](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/TextStyle.html)<br>Used for small title |
