# How-to-create-Xamarin.Forms-image-button

This example demonstrates how to create image button in Xamarin.Forms with text and custom view.
Please refer KB links for more details,

[How to create Xamarin.Forms image button](https://www.syncfusion.com/kb/10808/?utm_medium=listing&utm_source=github-examples)

## <a name="imagebutton"></a>Create image button with ImageSource

You can create an image button by using the ImageSource property that is used to set the image in button. In addition, you have to set the value of the ShowIcon property as true. 

The following code example shows how to use ImageSource to instantiate an image button.
 
 ```
 
 <button:SfButton ShowIcon="True" BackgroundColor="DeepSkyBlue" 
                         HeightRequest="50" WidthRequest="95" CornerRadius="5" ImageSource="alarm.png"/>

```

## <a name="imageContentbutton"></a>Create image button with content
The Content property on our button is used to add any content view inside the button. You can use this Content property to create an image button.

The following code example shows how to use Content to instantiate an image button.
 
 ```
<button:SfButton BackgroundColor="DeepSkyBlue" CornerRadius="5" HeightRequest="45" WidthRequest="95">
 <button:SfButton.Content>
  <Grid  Margin="5">
   <Image Source="alarm.png" />
  </Grid>
 </button:SfButton.Content>
</button:SfButton>

```

## <a name="textbutton"></a>Create image button with text content

You can also create an image button with text using the properties Text and ImageSource. 

The following code example shows how to create an image button with text and image.
 
 ```
 
<button:SfButton ImageSource="alarm.png"
                 HeightRequest="50" WidthRequest="95"  TextColor="Black"
                 ShowIcon="True" BackgroundColor="DeepSkyBlue" Text="Alarm"
                 CornerRadius="5" />
 
 ```
 
## <a name="textimagebutton"></a>ImageButton with TextContent and Image
You can also change the alignment of the image in the button using the ImageAlignment property as shown in the example below.
 
 ```
 
<button:SfButton ImageSource="alarm.png" ImageAlignment="End" HeightRequest="45" WidthRequest="95"
                 TextColor="Black" ShowIcon="True" BackgroundColor="DeepSkyBlue"                 
                 Text="Alarm" CornerRadius="5" />
 
 ```
 
See Also:
 
[How to create simple button](https://help.syncfusion.com/xamarin/sfbutton/gettingstarted?_ga=2.65659374.1723461661.1572321968-2127342757.1556163962#creating-a-simple-sfbutton)
 
[How to set image in button background](https://help.syncfusion.com/xamarin/sfbutton/gettingstarted?_ga=2.65659374.1723461661.1572321968-2127342757.1556163962#button-background-image)
 
[How to create image button with label](https://help.syncfusion.com/xamarin/sfbutton/gettingstarted?_ga=2.65659374.1723461661.1572321968-2127342757.1556163962#button-icon)
 
[How to create button with label and image alignment](https://help.syncfusion.com/xamarin/sfbutton/customization?_ga=2.260616141.1723461661.1572321968-2127342757.1556163962#imagealignment)
 
Also refer our [feature tour](https://www.syncfusion.com/xamarin-ui-controls/xamarin-button) page to know more features available in our button.

## <a name="troubleshooting"></a>Troubleshooting ##
### Path too long exception
If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.

