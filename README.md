This section explains how to customize the four side different border thickness of the [.NET MAUI Button](https://www.syncfusion.com/maui-controls/maui-button). In SfButton within .NET MAUI, the Strokethickness property is of type double, allowing only a single value to be assigned. To achieve the four side different border thickness in .Net Maui we can use the SfButton within a contentview. In the contentview set the background color and padding properties. By using the padding property, we can set the padding for each side of an SfButton (left, top, right, bottom) that is used to provide the four side different border thickness for the SfButton.

**XAML:**
```
<StackLayout VerticalOptions="Center" HorizontalOptions="Center">
<ContentView BackgroundColor="Red" padding="10,0,0,10">
         <buttons:SfButton Text="SfButton"
                           CornerRadius="0"
                           WidthRequest="100"/>
     </ContentView>
   
 </StackLayout>
```

**Output:**

![Button Customization](https://github.com/user-attachments/assets/5d357ceb-a614-40e0-94c8-74bd27c0f3c2)
