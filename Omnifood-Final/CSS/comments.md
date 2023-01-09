## MEDIA AT 1338px

### rem and em do NOT depend on the HTML font-size in media queries!

### Instead 1rem = 1em = 16px(Default browser font size)

### Basic breakpoint idea is that the breakpoint should work for atleast next 200 to 300 px

## MEDIA AT 1200px (Landscape tablets)

### As we have used the responsive units for length from the very beginning of the project. So, we don't need to scale every element individually as all are being scaled according to the font-size of the root element.

1.  Now at 1200px we can see the font-size is too large for the screen width.
2.  We can fix by just scaling down the font-size.

## MEDIA AT 1050px and 944px (Tablets)

### At this point the screen is becoming narrower. So we'll shift to one column layout.

### Hide navigation

- Allows NO transitions at all
- display: none;

  Instead we use the following procedure:

1.  Opacity is set to 0 (Hide it visually):

2.  Make it unaccessible for keyboard and mouse:

#### Pointer-events: The pointer-events CSS property sets under what circumstances (if any) a particular graphic element can become the target of pointer events.

3.  Hide it from screen readers:
