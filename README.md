# Cellular-Automatum-3 (Making Art with CAs)

This is a collection of modified versions of CA source codes from NetLogo Web. 

## Async Learning Task: Cellular Automata

MEMBERS:
- ALABANZA, CHELSEA ALEXANDRA R.
- ALVAREZ, BRYAN KAHLIL G.
- ANTONIO, LUCIANA FRANCESCA B.

### CA 1D Rule 250
[Source Code](https://www.netlogoweb.org/launch#https://www.netlogoweb.org/assets/modelslib/Sample%20Models/Computer%20Science/Cellular%20Automata/CA%201D%20Simple%20Examples/CA%201D%20Rule%20250.nlogo)

**Description:**

**Modified Functions:** 
- do-rule
- setup-continue (deleted)

### CA 1D Elementary
[Source Code](http://www.netlogoweb.org/launch#http://www.netlogoweb.org/assets/modelslib/Sample%20Models/Computer%20Science/Cellular%20Automata/CA%201D%20Elementary.nlogo)

**Description:** In the modified version of the Elementary CA code, the rules were changed. You can find the new rules below.

### CA 1D Totalistic
[Source Code](http://www.netlogoweb.org/launch#http://www.netlogoweb.org/assets/modelslib/Sample%20Models/Computer%20Science/Cellular%20Automata/CA%201D%20Totalistic.nlogo)

**Description:** The helper functions in the original code performed long division in base 3. In the modified version, it was changed to base 5. Other than this, one of the main changes made to the code was under the do-rule function. The coordinates provided in the original code were fixed while in the modified version, sliders were used to allow a variety of artworks to be created.

**Modified Functions:** 
- setup-random
- do-rule
- switch-to-code
- code-to-switch
- quinary-div


## Artworks Created


| FILENAME                                                                                                            | SETTING                                                                                                                                                                                                                                   | VALUE                                                                                                                                              |
|---------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|
| **totalistic-1.png**<br><br>*(looks like a row <br>of either folders<br>or building)*                                   | max-pxcor<br>max-pycor<br><br>setup<br>density<br>one-two-proportion<br><br>code<br>sum-0<br>sum-1<br>sum-2<br>sum-3<br>sum-4<br>sum-5<br>sum-6<br><br>ask-x<br>ask-y<br>x1<br>y1<br>x2<br>y2<br><br>color-zero<br>color-one<br>color-two | 50<br>50<br><br>single<br>137%<br>135<br><br>16930<br>0<br>1<br>2<br>0<br>2<br>0<br>1<br><br>2<br>-1<br>-2<br>1<br>-5<br>2<br><br>99<br>37<br>93   |
| **totalistic-2.png**<br><br>*(looks like a guy<br>with sunglasses)*                                                     | max-pxcor<br>max-pycor<br><br>setup<br>density<br>one-two-proportion<br><br>code<br>sum-0<br>sum-1<br>sum-2<br>sum-3<br>sum-4<br>sum-5<br>sum-6<br><br>ask-x<br>ask-y<br>x1<br>y1<br>x2<br>y2<br><br>color-zero<br>color-one<br>color-two | 16<br>16<br><br>single<br>25%<br>44<br><br>1277<br>2<br>0<br>1<br>0<br>2<br>0<br>0<br><br>0<br>-1<br>-1<br>1<br>1<br>1<br><br>95<br>104<br>98      |
| **totalistic-3.png**<br><br>*(looks like the<br>Pyramids of Giza)*                                                      | max-pxcor<br>max-pycor<br><br>setup<br>density<br>one-two-proportion<br><br>code<br>sum-0<br>sum-1<br>sum-2<br>sum-3<br>sum-4<br>sum-5<br>sum-6<br><br>ask-x<br>ask-y<br>x1<br>y1<br>x2<br>y2<br><br>color-zero<br>color-one<br>color-two | 50<br>50<br><br>single<br>137%<br>135<br><br>16930<br>0<br>1<br>2<br>0<br>2<br>0<br>1<br><br>-1<br>-1<br>-2<br>2<br>-4<br>4<br><br>9<br>376<br>100 |
| **totalistic-4.png**<br><br>*(looks like overlapping<br>metal gates or bars)*                                           | max-pxcor<br>max-pycor<br><br>setup<br>density<br>one-two-proportion<br><br>code<br>sum-0<br>sum-1<br>sum-2<br>sum-3<br>sum-4<br>sum-5<br>sum-6<br><br>ask-x<br>ask-y<br>x1<br>y1<br>x2<br>y2<br><br>color-zero<br>color-one<br>color-two | 50<br>50<br><br>single<br>137%<br>135<br><br>7655<br>0<br>1<br>1<br>1<br>2<br>2<br>0<br><br>3<br>-1<br>0<br>3<br>-3<br>5<br><br>11<br>39<br>98     |
| **totalistic-5 folder**<br><br>*(set of optical illusions -<br>"go" button was clicked <br>5 times to produce 5 views)* | max-pxcor<br>max-pycor<br><br>setup<br>density<br>one-two-proportion<br><br>code<br>sum-0<br>sum-1<br>sum-2<br>sum-3<br>sum-4<br>sum-5<br>sum-6<br><br>ask-x<br>ask-y<br>x1<br>y1<br>x2<br>y2<br><br>color-zero<br>color-one<br>color-two | 50<br>50<br><br>single<br>269%<br>36<br><br>1560<br>0<br>2<br>2<br>2<br>2<br>0<br>0<br><br>1<br>-1<br>0<br>2<br>1<br>1<br><br>9<br>13<br>13        |
| **ElementaryCA.png**<br><br>*(lots of art can be generated by<br>turning on/off the other rules)*<br> <br> | lput ooo<br>lput ooi<br>lput oio<br>lput oii<br>lput ioo<br>lput ioi<br>lput iio<br>lput iii| true true true<br>true false true<br>true true  true<br>false true  false<br>true  false false<br>true  true true<br>false  false  false<br>true  false  true<br>
| **Rule250.png**<br><br>*(modifications done mainly<br>revolved around in the do-rule<br>function where specific color<br>and positioning of each shape<br>were set)* | N/A | N/A
      
