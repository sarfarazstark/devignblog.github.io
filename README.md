[

![Flutter Community](https://miro.medium.com/fit/c/64/64/1*nE4OFcqk2kx2-Lzhey8QKA.png)



](https://medium.com/flutter-community?source=post_page-----c7fd71adfb7e-----------------------------------)

Published in

[

Flutter Community

](https://medium.com/flutter-community?source=post_page-----c7fd71adfb7e-----------------------------------)

·

[

![Mo Malaka](https://miro.medium.com/fit/c/96/96/0*V_W91m8PFSgWBF5t.jpg)



](/@mmalaka?source=post_page-----c7fd71adfb7e-----------------------------------)

[Mo Malaka](/@mmalaka?source=post_page-----c7fd71adfb7e-----------------------------------)

·

[Follow](/m/signin?actionUrl=https%3A%2F%2Fmedium.com%2F_%2Fsubscribe%2Fuser%2F38b5f1b791b1&operation=register&redirect=https%3A%2F%2Fmedium.com%2Fflutter-community%2F100-flutter-dart-tips-code-c7fd71adfb7e&user=Mo+Malaka&userId=38b5f1b791b1&source=post_page-38b5f1b791b1----c7fd71adfb7e---------------------follow_sidebar--------------)

Oct 18, 2021

·

9 min read

100+ Flutter & Dart Tips
========================

A Collection of **Flutter** and Dart **Tips** and Tricks
--------------------------------------------------------

![](https://miro.medium.com/max/1400/0*0Xfk9DO3jirs6mqJ)

Photo by [Artur Shamsutdinov](https://unsplash.com/@roketpik?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)

Hello Reader,

I have written this article to list down 100+ tips and tricks that I have tweeted in the last couple of months. If you are new to this Flutter/Dart world, some of these might help you.

1- You can iterate through a map in a null-safe manner using entries.

2- Lists can hold duplicate items. So If you want a collection of unique values, Use a Set instead.

In a Set, two elements cannot be equal, so the code below won’t compile.

3- You can wait for the results of multiple Futures to complete using Future.wait

4- You can use GridView.count to create a grid that’s two tiles wide in portrait mode and three tiles wide in landscape mode

5- You can randomly select an item from a list using Random from dart:math

6- You can use the services library to lock the device orientation

7- You can use the dart:io library to write a platform-specific code

8- You can turn any color to a Material Color

9- You can use the services library to hide the status bar.

10- The http package contains a set of functions and classes to consume HTTP resources. The example below use the http package to make http request.

> Follow me on [Twitter](https://twitter.com/_Mo_Malaka_) for more tips about #coding, #learning, #technology… etc.
> 
> Check my Apps on [Google Play](https://bit.ly/3h05gQ7) & [Apple Store](https://apple.co/3hZXoBx)

11- You can use the FadeInImage widget & transparent\_image package to display a transparent placeholder waiting for the image to fade in as it gets loaded.

12- To add icons to TextFields use “icon”, “prefixIcon” and “suffixIcon” from InputDecoration

13- The cursor of TextField is Customizable. The example below will set it to purple.

14- To pack the children of a Row close together, set its mainAxisSize to MainAxisSize.min

15- You can size the widgets to fit within a row or column using the Expanded widget.

16- Use the Hero widget to animate a widget from one screen to the next. e.g., an icon on the first page flying to the second page.

17- Use Stack to overlap widgets, The first widget will be the bottommost item, and the last widget will be the topmost item.

18- Use themes to define a set of colors, fonts, shapes, and design styles throughout your app. It’s a way to centralize all your stylistic decisions in one place.

19- Use the constant (kReleaseMode) from (package:flutter/foundation.dart) to execute a code in debug or release mode

20- Use Cascade notation to make a sequence of operations on the same object.

21- You can use the Timer class to execute a piece of code after some time

22- Use the ClipOval widget to clip the child widget in oval or circle shape. If width and height are equal, the shape will be circular. If the width and height are different, then the shape will be oval.

23- Use padLeft and padRight to add character padding on the left and right sides, respectively.

24- Use the List class method join() can to join a List of any type to a String.

25- Set debugShowCheckedModeBanner to false to remove the Debug Banner Tag

26- To get access to the index on an Item in a list, you need to convert the list to a map using the asMap

27- AppBar is the topmost component of the app (or sometimes the bottom-most), the AppBar’s layout contains three components: leading, title, and actions

28- To write any Dart program, be it a script or a Flutter app, you must define a function called main(). It is the entry point of every app.

29- You can change the text color of a button when it’s pressed.

30- The example below is about running a code after dismissing a GetX dialog.

> Follow me on [Twitter](https://twitter.com/_Mo_Malaka_) for more tips about #coding, #learning, #technology… etc.
> 
> Check my Apps on [Google Play](https://bit.ly/3h05gQ7) & [Apple Store](https://apple.co/3hZXoBx)

31- Enums and extension methods can make code cleaner to read. In the example below, we are converting Enums to Strings.

32- Dart allows you to create a callable class so you can call the instance of the class as a function

33- You can use InkWell to create a ripple effect to produce a visual experience for touch response.

34- In the example below we are using BoxDecoration & DecorationImage to set a background image an App

35- You can use the ListWheelScrollView widget to build ListView in a scrollable wheel with 3D-effect as if the children are rotating in a wheel.

36- You can have a background color behind a text and add a curve at the start and the end.

37- Use the ready-made widget ‘AboutListTile’ to show an about box displaying extra information about the app like its Version, Privacy policy, Official website, etc.

38- Use FittedBox to scale and fit the child widget inside. It restricts its child widgets from growing their size beyond a specific limit. It re-scales them according to the size available.

39- SafeArea is a padding widget that inserts its child with enough padding to keep it from being blocked by the system status bar, notches, holes, rounded corners, and others.

40- Use MediaQuery to get information about the current device size, its orientation, and user preferences.

41- Mixins allow you to plug in blocks of code without needing to create subclasses.

42- You can pass a function as a parameter to another function.

43- Getters and setters are special methods that provide read and write access to an object’s properties.

44- There are four different ways to append or concatenate Strings

45- You can use the validator widget to validate the Form Inputs in your submit function and apply the validation condition on each TextFormField.

46- Use the ListView to create a horizontal list by setting the scrollDirection parameter to Axis.horizontal

47- Center the FloatingActionButton by setting the floatingActionButtonLocation parameter as below

48- You can provide an action label in SnackBar to act when pressed on it as below

49- Use the barrierDismissible property to prevent dismissing the AlertDialog when the user taps on the screen outside the alert box.

50- You can create a circular icon button using ElevatedButton. Check the following example.

> Follow me on [Twitter](https://twitter.com/_Mo_Malaka_) for more tips about #coding, #learning, #technology… etc.
> 
> Check my Apps on [Google Play](https://bit.ly/3h05gQ7) & [Apple Store](https://apple.co/3hZXoBx)

51- You can use the ShaderMask widget to apply a gradient look and feel to its child.

52- AnimatedSize is a widget that automatically transitions its size over a given duration whenever the given child’s size changes.

53- Use the flutter\_staggered\_grid\_view to create a gridview of multiple columns & rows of varying sizes

54- You can use the ColorFiltered widget to apply a color filter to its child widgets

55- Use the flutter\_speed\_dial plugin to create more than one floating button on the same screen

56- You can create multiple shadows for a Text widget. Check the following example.

> Try it on DartPad [here](https://gist.github.com/offlineprogrammer/5a288e2a2c90380784f09cbe541e683e)

57- LayoutBuilder helps to create a widget tree that can depend on the size of the parent widget.

> Try it on DartPad [here](https://dartpad.dev/?id=e4cac9818ebd1bfad62323c834b489b0&null_safety=true)

58- The wrap is a widget that displays its children in horizontal or vertical runs. It will try to place each child next to the previous child on the main axis. If there is not enough space, it will create a new run adjacent to its existing children in the cross axis.

> Try it on DartPad [here](https://dartpad.dev/?id=5c0b7e70d19ec7c640fbdd10583b7484&null_safety=true)

59- AnimatedIcon is a Flutter widget that animates the switching of an icon with another.

> Try it on DartPad [here](https://dartpad.dev/?id=ea830ec764f187e1bd372427509dfd93&null_safety=true)

60- The AnimatedContainer widget is a container widget with animations. It can be animated by altering the values of its properties.

> Try it on DartPad [here](https://dartpad.dev/?id=3a4291b177882967d3e5ab48c00988dc&null_safety=true)

61- The SliverAppBar is a widget that gives a floating app bar.

> Try it on DartPad [here](https://dartpad.dev/?id=fba7a3ae6b78ab7933c7635e24d7ecf2&null_safety=true)

62- AnimatedOpacity Widget automatically transitions the child’s opacity over a duration whenever the opacity changes.

> _Try it on DartPad_ [_here_](https://dartpad.dev/?id=5d1c2edf4adbf720616a766466a0cdfc&null_safety=true)

63- The SlideTransition Widget animates the position of a widget relative to its normal position.

> Try it on DartPad [here](https://dartpad.dev/?id=c6ebb51a3ddd21b0800d30b1c5d8ec34&null_safety=true)

64- The FadeTransition Widget fades a widget in and out by animating its opacity.

> Try it on DartPad [here](https://dartpad.dev/?id=20d74b6728c65c054c1a17826aa3c2cd&null_safety=true)

65- The AnimatedCrossFade Widget cross-fades between two given children and animates itself between their sizes.

> Try it on DartPad [here](https://dartpad.dev/?id=1023012f302ebee99120e707791ff23c&null_safety=true)

66- The CupertinoContextMenu Widget is a full-screen modal route that opens when the child is long-pressed.

> Try it on DartPad [here](https://dartpad.dev/?id=b396a1f4ac24a0818992f62a159e4133&null_safety=true)

67- The BackdropFilter Widget applies a filter to the existing painted content.

> Try it on DartPad [here](https://dartpad.dev/?id=c06e654eff1605fa163490610767ee66&null_safety=true)

68- The RotatedBox Widget rotates its child by an integral number of quarter turns.

> Try it on DartPad [here](https://dartpad.dev/?id=0bf40d753a62ce589aca742c356d04af&null_safety=true)

69- Use the Spacer Widget to create spacing between widgets.

> Try it on DartPad [here](https://dartpad.dev/?id=f7646609316b5daca866e6f662e7ba25&null_safety=true)

70- FractionallySizedBox Widget is a widget that sizes its child to a fraction of the total available space.

> Try it on DartPad [here](https://dartpad.dev/?id=d219fd156398e23e943a45398960cc9e&null_safety=true)

> Follow me on [Twitter](https://twitter.com/_Mo_Malaka_) for more tips about #coding, #learning, #technology… etc.
> 
> Check my Apps on [Google Play](https://bit.ly/3h05gQ7) & [Apple Store](https://apple.co/3hZXoBx)

71- Use the AnimatedSwitcher widget to create animation when switching between two widgets.

> Try it on DartPad [here](https://dartpad.dev/?id=42b9a6bda83c007403ed305332cbe4b1&null_safety=true)

72- Use the CupertinoAlertDialog to create an iOS-style widget that informs the user about situations that require acknowledgement.

> Try it on DartPad [here](https://dartpad.dev/?id=feba39bdd3a04d1c288cd5e2f89bf48c&null_safety=true)

73- Use CupertinoButton Widget to create an iOS-style button that Takes in a text or an icon that fades out and in on touch.

> Try it on DartPad [here](https://dartpad.dev/?id=0e04c1d6280046a45ea789a80bc297a5&null_safety=true)

74- The CupertinoActionSheet is an ios-themed widget that has action sheets design specifications.

> Try it on DartPad [here](https://dartpad.dev/?id=77144ea31ab1f0211e5e715bf6ef5582&null_safety=true)

75- Use GestureDetector to detect gestures like tap, double Tap, press, LongPress, pan, drag, zoom etc.

> Try it on DartPad [here](https://dartpad.dev/?id=d3daa0de6fe631bba547be8e3a4102c3&null_safety=true)

76- The AnimatedDefaultTextStyle will transitions the default text style over a given duration whenever the given style changes.

> Try it on DartPad [here](https://dartpad.dev/?id=a82531b2e6eecdbfd9cb1aa4fccf98b2&null_safety=true)

77- Use Future.delayed() to pause program flow for a certain duration.

> Try it on DartPad [here](https://dartpad.dev/?id=230fb0247df945825748ef604d8a4fd2&null_safety=true)

78- Use DecoratedBoxTransition to animates the different properties of DecoratedBox.

> Try it on DartPad [here](https://dartpad.dev/?id=28a524e10a8f6d340d28903f4f5f1851&null_safety=true)

79- Use Divider widget to create a one pixel thick horizontal line, with padding on either side.

> Try it on DartPad [here](https://dartpad.dev/?id=f8be87547bc96b27c6497b2c34fbc545&null_safety=true)

80- Use DropdownButton widget to create a button for selecting from a list of items.

> Try it on DartPad [here](https://dartpad.dev/?id=493bbe309514d6c84cd8f570cfb65c23&null_safety=true)

81- Flow is a widget which arranges its child widgets based on FlowDelegate

> Try it on DartPad [here](https://dartpad.dev/?id=a67c355c62725999d6a417a0eb685b45&null_safety=true)

82- You can fix Text Overflow error with Flexible Widget

> Try it on DartPad [here](https://dartpad.dev/?id=fb82031cdedbe6c9abf91348fb54e780&null_safety=true)

83- CheckboxListTile is a widget that combines a checkbox and a list tile. It allows you to create a checkbox along with the title, subtitle, and icon.

> Try it on DartPad [here](https://dartpad.dev/?id=389130de4f57c93cba50fe242f3ea03b&null_safety=true)

84- LinearProgressIndicator widget is a material design linear progress indicator.

> Try it on DartPad [here](https://dartpad.dev/?id=bd83a2b0a37b825cee7ed54dba841b08&null_safety=true)

85- PageView is a scrollable list that works page by page.

> Try it on DartPad [here](https://dartpad.dev/?id=eab388bf8e1a404b738a669f31fd0e84&null_safety=true)

86- PhysicalModel widget allows you to add custom shadow effects and customize its color and shape

> Try it on DartPad [here](https://dartpad.dev/?id=15e63520f768302b0fa01e1ac36405d9&null_safety=true)

87- RadioListTile widget is a radio button with a label.

> Try it on DartPad [here](https://dartpad.dev/?id=7fed35179926802ce6c12427e3a1fe00&null_safety=true)

88- RangeSlider widget is used to select a range from a range of values.

> Try it on DartPad [here](https://dartpad.dev/?id=441d0e53491317b61e762f191f81092c&null_safety=true)

89- RefreshIndicator is a widget that supports Material’s swipe-to-refresh.

> Try it on DartPad [here](https://dartpad.dev/?id=b6f699755b9fdd138806ed703f108e69&null_safety=true)

90- Switch widget is used to toggle the on/off state of a single setting.

> Try it on DartPad [here](https://dartpad.dev/?id=64b2459c64c70462073479d77beb86db&null_safety=true)

> Follow me on [Twitter](https://twitter.com/_Mo_Malaka_) for more tips about #coding, #learning, #technology… etc.
> 
> Check my Apps on [Google Play](https://bit.ly/3h05gQ7) & [Apple Store](https://apple.co/3hZXoBx)

91- Tooltip widget helps explain the function of a button or other user interface action.

> Try it on DartPad [here](https://dartpad.dev/?id=dce517bb186603a800e676298c223b8c&null_safety=true)

92- SelectableText Widget allows the user to Select/Copy the content on the UI.

> Try it on DartPad [here](https://dartpad.dev/?id=4fc3709439d285f5af25ff0dfab206b5&null_safety=true)

93- Transform is a widget that applies a transformation before painting its child.

> Try it on DartPad [here](https://dartpad.dev/?id=41defd810d85225bb313634bc4665d1b&null_safety=true)

94- VerticalDivider widget is a one device pixel thick vertical line, with padding on either side.

> Try it on DartPad [here](https://dartpad.dev/?id=597d1aabc7d972e0d082468ea1b6d510&null_safety=true)

95- TimePicker widget shows a dialog containing a material design time picker.

> Try it on DartPad [here](https://dartpad.dev/?id=c04e270f668ecc63b613911df41ac47b&null_safety=true)

96- Stepper widget displays progress through a sequence of steps.

> Try it on DartPad [here](https://dartpad.dev/?null_safety=true&id=15b62b7ffd262ef6a20ad3a088f63c9a)

97- ActionChip widget used to create compact elements called chips, which trigger an action when the user presses on it.

> Try it on DartPad [here](https://dartpad.dev/?null_safety=true&id=25817a978bb813734dae6e1138f5c7a3)

98- ExpansionPanel widget is a panel with a header and a body and can be either expanded or collapsed. The body of the panel is only visible when it is expanded.

> Try it on DartPad [here](https://dartpad.dev/?null_safety=true&id=91e4cbb77f160a598ef1716f815f47af)

99- LongPressDraggable Widget is used to create a widget that can be dragged starting from LongPress.

> Try it on DartPad [here](https://dartpad.dev/?null_safety=true&id=d9bde43fb445a8c582f7e86a57b9d5bf)

100- Baseline is a widget that positions its child according to the child’s baseline.

> Try it on DartPad [here](https://dartpad.dev/?id=a0353aa71d153aee1d0a4ce2e9cc9d4b&null_safety=true)

101- Banner widget displays a diagonal message above the corner of another widget.

> Try it on DartPad [here](https://dartpad.dev/?id=a799c8a8476f779a064aa37529099770&null_safety=true)

102- BottomNavigationBar is a widget that’s displayed at the bottom of an app for selecting among a small number of views, typically between three and five.

> Try it on DartPad [here](https://dartpad.dev/?id=2bf05d6b33d1c3bfe0ac4a9f1bc4b9a4&null_safety=true)

103- IntrinsicWidth is a widget that sizes its child to the child’s maximum intrinsic width.

> Try it on DartPad [here](https://dartpad.dev/?id=826269fe74debd89bd3d1e991671aba7&null_safety=true)

104- IntrinsicHeight Widget is a widget that sizes its child to the child’s intrinsic height.

> Try it on DartPad [here](https://dartpad.dev/?id=7366cab480aeae41e96afe56aaa0df0b&null_safety=true)

Thank you. 👋🏻

> Follow me on [Twitter](https://twitter.com/_Mo_Malaka_) for more tips about #coding, #learning, #technology… etc.
> 
> Check my Apps on [Google Play](https://bit.ly/3h05gQ7) & [Apple Store](https://apple.co/3hZXoBx)

Follow Flutter Community on Twitter: [https://www.twitter.com/FlutterComm](https://www.twitter.com/FlutterComm)
