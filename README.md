# SFML.UI - Library for creating UI for SFML. Completely written in C#

```csharp
public static void DrawButtonSamples() 
{

  UISettings.ButtonSettings settings = new UISettings.ButtonSettings();
  settings.position = new Vector2f(5.0f, 5.0f);
  settings.size = new Vector2f(10.0f, 6.0f);
  settings.buttonPressedTexture = new Texture(/*standart sfml texture*/);
  settings.buttonNormalTexture = new Texture(/*standart sfml texture*/);
  Button button = new Button(settings);
}
```
