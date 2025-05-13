This section explains how to customize the border thickness on different sides of the .NET MAUI Button. In the SfButton, the StrokeThickness property is a double type, which means it only allows for a single value to be assigned for uniform border thickness.

You can use the SfButton within a ContentView to set different border thicknesses on all four sides. You can simulate varying border thicknesses by adjusting the background color and padding properties in the ContentView. Specifically, modifying the padding for each side (left, top, right, and bottom) enables you to create the desired effect.

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
