What is media query?

Media queries are a CSS technique used to apply styles based on the characteristics of the device or viewport. They allow developers to create responsive designs that adapt to different screen sizes, orientations, and resolutions.

A media query checks for conditions like screen width, height, device type, orientation, etc., and applies CSS rules only if those conditions are true.

Media queries can be used to change styles based on:
- Screen width and height
- Device orientation (portrait or landscape)

Syntax:-

#css:-

.box{
    ht:x;
    wd:x;
    bgc:red;
}

@media (max-width:600px) {
    .box{
        bgc:blue;
        border-radius: 50%;
    }
}
