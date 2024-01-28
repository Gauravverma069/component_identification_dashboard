# component_identification_dashboard
PowerBI dashboard which works as a software to identify unknown component in manufacturing house.
Component Identification Dashboard (C.I.D.) is a PowerBI dashboard which works as an identification software where,
to identify correct part no. of a component using its physical attributes or vice-versa., 
the dashboard contains physical attributes of a components like length, oreintation, and other attributes which displays an image for that component.

>>>>> the data in dashboard is manipulated and changed.

## **Lets Go through some visuals of dashboard**

![image](https://github.com/Gauravverma069/component_identification_dashboard/assets/121911821/13a53d59-118c-4975-8ab0-229e8b9d97f6)

to identify the correct component either selecting/entering input about its physical attributes like lenght,diameter,thread type,electrical type it narrows down the list on the left ,

also on top right by entering part no, or even initials we can get the resultant picture of the product.

to get dynamic connections with Image with data, each image was first coverted to base64 data using following code.

![image](https://github.com/Gauravverma069/component_identification_dashboard/assets/121911821/a8b63b42-b567-4e1e-b661-dfd817da0f39)

this convert image binary into excel cell input further, based on index of cell each image concate and results in an image.

actual excel data took month due to for each component its BOM & enginnering drawing is analyised. 
