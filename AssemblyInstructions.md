Solder parts from this list : [PartList](/Hardware/PartList.txt)

Following these 2 images :

Bottom part ![Bottom Side](/images/pcbBottom.jpeg)

Top part ![Up Side](/images/pcbUp.jpeg)

Writing fuse to : Low 0xE2 High 0xD7 Extended 0xFE . Action [AVRDUDE](http://www.nongnu.org/avrdude/) arguments -U lfuse:w:0xe2:m -U hfuse:w:0xd7:m -U efuse:w:0xfe:m
