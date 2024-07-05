//[library](../../index.md)/[com.glovoapp.uds](index.md)/[CoreTheme](-core-theme.md)

# CoreTheme

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [CoreTheme](-core-theme.md)(colorScheme: [CoreColorScheme](-core-color-scheme/index.md) = CoreTheme.colorScheme, typography: [CoreTypography](-core-typography/index.md) = CoreTheme.typography, content: @[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

Design System Theme

Theming refers to the customization of the Core Theme. Applications can customize the Core Theme based on their design requirements.

Components such as [Button](-button.md) use the values provided here when retrieving default values.

All values may be set by providing this component with the [colorScheme](-core-color-scheme/index.md) and [typography](-core-typography/index.md). Use this to configure the overall theme of elements within this CoreTheme.

Any values that are not set will inherit the current value from the theme, falling back to the defaults if there is no parent CoreTheme. This allows using CoreTheme directly at the top of the application, or separate CoreThemes(s) such as CustomerTheme or CourierTheme for different applications or even parts of the app UI, overriding only the parts of the theme definition that need to change.

#### Parameters

androidJvm

| | |
|---|---|
| colorScheme | A complete definition of the Material Color theme for this hierarchy. |
| typography | A set of text styles to be used as this hierarchy's typography system. |
