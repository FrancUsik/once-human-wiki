# Ilink/doc

Displays icon and name for linked page. This template is useful when creating lists.


    
        
Please note that by default, this template automatically displays the file that has the same name as the article. File names and page names are both case-sensitive, and must be entered exactly as they appear.

        
    


A different icon can be specified by using the altIcon parameter if needed (see examples below).

Syntax[]
Using only unnamed parameters:

{{ilink
|link name
|item quantity
}}

Using all parameters:

{{ilink
|link name
|item quantity
|size        = icon height
|altIcon     = Sample
|altLink     = Sample
|altLinkName = Sample
|altIconName = Sample
|fileType    = jpg
}}
Parameters[]



Parameter

Description

Type

Status


Link name

1

The name of the page that is to be linked.Example:&#160;&#160;&#160;&#160;Biomass

String

required


Item quantity

2

The quantity to be shown.Default:&#160;&#160;&#160;&#160;(hidden)Example:&#160;&#160;&#160;&#160;3

String

optional


Image size in pixels

size

The size in pixels of the icon to be shown.Default:&#160;&#160;&#160;&#160;24 pxExample:&#160;&#160;&#160;&#160;48 px

String

optional


File type

fileType

File type of the image file.Default:&#160;&#160;&#160;&#160;pngExample:&#160;&#160;&#160;&#160;gif

String

optional


Alt. icon name

altIconName

Alternative name of icon or image file. (E.g. if different from the page's name.)

String

optional


Alt. link name

altLinkName

Alternative link name if different from page name. (E.g. to exclude parentheticals.)

String

optional


Alt. link

altLink

Alternative link url  if different from item and icon name.

String

optional

Examples[]



Code

Result


{{ilink|Copper Ore}}

&#160;&#160;Copper Ore


{{ilink|Copper Ore|16}}

16x&#160;&#160;&#160;Copper Ore


{{ilink|Copper Ore|size=48px}}

&#160;&#160;Copper Ore


{{ilink|Copper Ore|altIconName=Copper Ore}}

&#160;&#160;Copper Ore


{{ilink|Iron Ore|altLink=Iron Ore}}

&#160;&#160;Iron Ore
