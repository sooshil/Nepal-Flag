# Flag of Nepal

As the only national flag in the world that is not rectangular or square in shape, Nepal's flag stands out as a unique national symbol. However, finding high-quality images of the flag online can be a challenge, especially ones that accurately reflect its original size and dimensions. This became apparent to me when I was working on some Android apps that required the use of Nepal's flag, but the images I found on the internet were either poor in quality or the wrong shape and size. To overcome this issue, I was inspired to create a vector drawable of Nepal's flag that would ensure its integrity and quality while maintaining its original dimensions.

[<img src="https://github.com/sooshil/Nepal-Flag/blob/main/Flag%20of%20Nepal.png" width="300"/>](https://github.com/sooshil/Nepal-Flag/blob/main/Flag%20of%20Nepal.png?raw=true)

## Size and Dimension
The size and dimensions of Nepal's flag, along with the step-by-step procedure for drawing it, are outlined in Schedule-1 of Nepal's Constitution of 2015. The same procedure and measurements used to draw this flag.

## Drawing techniques
To draw the flag with it's correct measurements, I used platform provided by [GeoGebra](https://www.geogebra.org/). GeoGebra has [tool](https://www.geogebra.org/geometry) or [this](https://www.math10.com/en/geometry/geogebra/fullscreen.html) where we can draw any mathematical object with great accuracy and precision. From there I got the coordinates of the points I need to draw the flag in vector drawable xml file. Then I drew it using Android studio with the path through the coordinates.
### Drawing from GeoGebra
The actual drawing I made in GeoGebra is also available here. To open that .ggb file, you need to open this [webpage](https://www.math10.com/en/geometry/geogebra/fullscreen.html) and simply drag the file to the webpage.

## Vector Drawable XML code
Here is the code to draw Flag of Nepal as a vector drawable in Android Studio.
```
<?xml version="1.0" encoding="utf-8"?>
<vector xmlns:android="http://schemas.android.com/apk/res/android"
    android:width="130.7dp"
    android:height="130.7dp"
    android:viewportWidth="130.7"
    android:viewportHeight="130.7">

    <!-- Blue border -->
    <path
        android:fillColor="#0151B3"
        android:pathData="M 0, 0 L 107.1,67.10 L 39.40,67.10 L 103.00,130.70 H 0 z"
        android:strokeWidth="0.5" />

    <!-- Red background -->
    <path
        android:fillColor="#F7CA2222"
        android:pathData="M 3.80, 6.90 L 93.80,63.30 L 30.20,63.30 L 93.80,126.90 L 3.80, 126.90 z"
        android:strokeColor="#011A73" />

    <!-- Crescents of Moon -->
    <path
        android:fillColor="@color/white"
        android:pathData="M 8.40,42.10 A 17.90,17.90 0 0 0 44.20,42.10 A 17.90, 12.20 0 0 180 8.40, 42.10"
        android:strokeWidth="0.2"
        android:strokeColor="#FFFFFF" />

    <!-- Angles of Moon -->
    <path
        android:fillColor="@color/white"
        android:pathData="M 16.17,52.03 L 18,50.5 L 14.9,48.2 L 18.6,47.3 L 16.7,44 L 20.4,44.6 L 19.9,40.8 L 23.1,42.8 L 24,39.1 L 26.3,42.1 L 28.6,39.1 L 29.5,42.8 L 32.7,40.8 L 32.2,44.6 L 35.9,44 L 34,47.3 L 37.7,48.2 L 34.6,50.5 L 36.53,51.93 L26.3,57.5 Z"
        android:strokeWidth="0.15"
        android:strokeColor="#FFFFFF" />

    <!-- The Sun -->
    <path
        android:fillColor="@color/white"
        android:pathData="M 26.3,75.9, L 29.5,83.3, L 35.9,78.5, L 34.9,86.5, L 42.9,85.5, L 38.1,91.9, L 45.5,95.1, L 38.1,98.2, L 42.9,104.7, L 34.9,103.7, L 35.9,111.7, L 29.5,106.9, L 26.3,114.3, L 23.1,106.9, L 16.7,111.7, L 17.7,103.7, L 9.7,104.7, L 14.5,98.2, L 7.1,95.1, L 14.5,91.9, L 9.7,85.5, L 17.7,86.5, L 16.7,78.5, L 23.1,83.3 Z"
        android:strokeWidth="0.1"
        android:strokeColor="#FFFFFF" />

</vector>
```


## Drawing Method described by Constitution of Nepal
This is the method to draw Nepal's flag correctly, which is outlined in Schedule-1 of Nepal's Constitition of 2015.

### SCHEDULE 1. Method of Making the National Flag of Nepal (RELATED WITH CLAUSE (2) OF ARTICLE 8)
#### A. Method of Making the shape inside the Border
1. On the lower portion of a crimson cloth, draw a line AB of the required length from left to right.
2. From A draw a line AC perpendicular to AB making AC equal to AB plus one third AB. From AC mark off D making the line AD equal to line AB. Join BD.
3. From BD mark off E making BE equal to AB.
4. Touching E draw a line FG, starting from the point F on line AC, parallel to AB to the right hand-side. Mark off FG equal to AB.
5. Join CG.
#### B. Method of making the Moon
6. From AB mark off AH making AH equal to one-fourth of line AB and starting from H draw a line HI parallel to line AC touching line CG at point I.
7. Bisect CF at J and draw a line JK parallel to AB touching CG at point K.
8. Let L be the point where lines JK and HI cut one another.
9. Join JG.
10. Let M be the point where line JG and HI cut one another.
11. With center M and with a distance shortest from M to BD mark off N on the lower portion of line HI.
12. Touching M and starting from O, a point on AC, draw a line from left to right parallel to AB.
13. With center L and radius LN draw a semi-circle on the lower portion and let P and Q be the points where it touches the line OM respectively.
14. With the center M and radius MQ draw a semi-circle on the lower portion touching P and Q.
15. With center N and radius NM draw an arc touching PNQ at R and S. Join RS. Let T be the point where RS and HI cut one another.
16. With center T and radius TS draw a semi-circle on the upper portion of PNQ touching at two points.
17. With center T and radius TM draw an arc on the upper portion of PNQ touching at two points.
18. Eight equal and similar triangles of the moon are to be made in the space lying inside the semi-circle of No (16) and outside the arc of No (17) of his Schedule.
#### C. Method of Making the Sun
19. Bisect line AF at U, and draw a line UV parallel to AB line touching line BE at V.
20. With center W, the point where HI and UN cut one another and radius MN draw a circle.
21. With center W and radius LN draw a circle.
22. Twelve equal and similar triangles of the sun are to be made in the space enclosed by the circle of No (20) and No (21) with the two apexes of two triangles touching line HI.
#### D. Method of Making the Border
23. The width of the border will be equal to the width of TN. This will be of deep blue color and will be provided on all the sides of the flag. However, on the given angles of the flag the external angles will be equal to the internal angles.
24. The above mentioned border will be provided if the flag is to be used with a rope. On the other hand, if it is to be hoisted on a pole, the hole on the border on the side AC can be extended according to requirements.
#### Explanation:- The lines HI, RS, FE, ED, JG, OQ, JK and UV are imaginary. Similarly, the external and internal circles of the sun and the other arcs except the crescent moon are imaginary. These are not shown on the flag.
