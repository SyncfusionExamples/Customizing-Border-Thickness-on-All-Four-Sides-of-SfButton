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
![Button Customization.png](https://support.syncfusion.com/kb/agent/attachment/inline?token=eyJhbGciOiJodHRwOi8vd3d3LnczLm9yZy8yMDAxLzA0L3htbGRzaWctbW9yZSNobWFjLXNoYTI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjI5NDg4Iiwib3JnaWQiOiIzIiwiaXNzIjoic3VwcG9ydC5zeW5jZnVzaW9uLmNvbSJ9.kbZBIyhn7VoNgSTNbQ77DDNB_8ZognQnn1t4KqkcOjE)

