# WP8.1Parallax
Parallax efect for UIElements in Universal Apps for Windows and Windows Phone 8.1

# ABOUT:
I've created framework for developers, to simulate parallax efect in applications.

# COMPABILITY:
framework is compatible with Windows 8.1 and Windows Phone 8.1 Universal Apps


# HOW TO USE:
1. add reference in project
2. add line "using GZParallax"
3. Create instance of Parallax class object. Parallax(horizontalEnabled, verticalEnabled)
4. add graphic objects, who inharitates from UIElement, and set on what virtual layer it should be placed.
basic layer, which is not moving is layer 0. Each layer number indicates if its above ( numbers greater then 0) or under (numbers smaller then 0) basic layer.
5. Set maxSwingVertical, andmaxSwingHorizontal if you want to change. Default 5
6. when you are ready call start() on parallax object.
7. Its good to stop parallax when you don't need it.


# CONTACT:
For more information pls mail me.
Gabriel Żołnierczuk
gabriel.zolnierczuk@me.com
