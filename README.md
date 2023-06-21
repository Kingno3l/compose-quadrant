# Compose Quadrant - Solution Code
 
This project contains a solution code for the Compose Quadrant practice problem. In this exercise,I built an app that displays the information about the Composable functions you learned.
 
## New Modifiers/Properties
 
Following is an overview of the Modifiers/Properties which were not covered in the Codelabs but are used to solve the problem.
 
**fontWeight**
 
This parameter in `Text` composable allows me to specify how bold or light the text content should appear. `FontWeight.Bold` is used to set the font style to bold
 
**textAlign**
 
This parameter in `Text` composable defines how I aligned the text horizontally.  The `TextAlign.Justify` property stretches the lines of text that end with a soft line break to fill the width of the container.
 
**Modifier.weight**

This modifier is scoped to Row composable. The modifier allows the size of the element's width proportional to its `weight` and relative to other weighted sibling elements. The parent will divide the horizontal space remaining after measuring unweighted child elements and distribute it according to this weight.
 
## Note:
 
The solution code uses the basic composables covered in Unit 1, Pathway 3 for Android Basics in Compose:
- [Build a simple app with text composables](https://developer.android.com/codelabs/basic-android-kotlin-compose-text-composables#0)
- [Add images to your Android app](https://developer.android.com/codelabs/basic-android-kotlin-compose-add-images#0)
