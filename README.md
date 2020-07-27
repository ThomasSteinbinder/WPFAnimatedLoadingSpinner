# WPFAnimatedLoadingSpinner
A simple animeted loading spinner in WPF / C#.

![Loading animation gif](http://blog.trustmycode.net/wp-content/uploads/2019/03/loadingAnimation.gif)

Read my [blog post](http://blog.trustmycode.net/?p=133) for more information!


### How to use:

![Different loading spinners](http://blog.trustmycode.net/wp-content/uploads/2019/03/spinners.jpg)

```xml
<StackPanel Orientation="Horizontal" VerticalAlignment="Center" HorizontalAlignment="Center">
      <local:LoadingControl Diameter="60" Color1="Red" Color2="Black"/>
      <local:LoadingControl Diameter="36" Color1="Green" Color2="Transparent"/>
      <local:LoadingControl Diameter="100" Color1="Blue" Color2="Transparent"/>
      <local:LoadingControl Diameter="48" Color1="Orange" Color2="Transparent"/>
</StackPanel>
```
