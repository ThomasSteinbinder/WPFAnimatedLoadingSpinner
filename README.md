# WPFAnimatedLoadingSpinner
A simple animeted loading spinner in WPF / C#.

![loadingAnimation](https://github.com/ThomasSteinbinder/WPFAnimatedLoadingSpinner/assets/10722017/282ef452-7763-4e6b-b997-9b8fa88b315b)



### How to use:

![spinners](https://github.com/ThomasSteinbinder/WPFAnimatedLoadingSpinner/assets/10722017/e50dce50-a3f5-4160-bae1-d49fa3940aeb)


```xml![Uploading spinners.jpg…]()

<StackPanel Orientation="Horizontal" VerticalAlignment="Center" HorizontalAlignment="Center">
      <local:LoadingControl Diameter="60" Color1="Red" Color2="Black"/>
      <local:LoadingControl Diameter="36" Color1="Green" Color2="Transparent"/>
      <local:LoadingControl Diameter="100" Color1="Blue" Color2="Transparent"/>
      <local:LoadingControl Diameter="48" Color1="Orange" Color2="Transparent"/>
</StackPanel>
```
