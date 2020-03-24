# NurtuganCard
My Second SwiftUI App

## Learned about...
+ extracting subview (cmd + click -> extract subview)
+ `RoundedRectangle(cornerRadius: 25)`
  - `.fill(Color.white)` preferable to use on __Shapes__ instead of `.foregroundColor()`
  - `.frame(height: 50)` if exist optional arguments you can leave them
  - `.overlay(Text("Hello"))` you can use it instead of `ZStack`
  - `.padding(.all)` just cool things
  
+ Previews
  - `.previewLayout(.sizeThatFits)` you can use it for extracted views to show only view instead of full device screen
  
+ `ZStack`
+ `Image("billie")`
  - `.clipShape(Circle())` rounds image
  - ```
    .overlay(
        Circle()
            .stroke(Color.white, lineWidth: 5) // adds border for a view
    )
    ```
+ `Divider()`

## Main view
<img src="https://github.com/nurtugan/NurtuganCard/blob/master/Screen%20Shot%202020-03-24%20at%2012.25.15%20AM.png" alt="" width="371" height="648">
