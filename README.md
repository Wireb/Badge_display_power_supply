# Badge display power supply
This design is a dual 6V to 18V input to settable 1.5A output switching regulator supply.   
Main purpose is to power up conference badges in display cases.   
  
The output voltage is set by R8 and R10. Pick the proper resistor value based on the table below:

|Rx|output V|Typical use|
| --- | --- | --- |
|7.68k|5V|USB powered|
|8.66k|4.5V|3x AA/AAA replacement|
|13k|3.3V|LiPo replacement mid charge|
|14.7k|3V|coin cell or 2x AA/AAA replacement|

**NOTE you MUST remove the battery when using this design as a battery replacement!**

J1, J2, and J3 are supply side input / output jacks. Cards are designed to be daisy chained between display using 5.5x2.5mm cables  
J4, J5, J6, J7, and J8 are output 1 controlled by R8  
J9, J10, J11, J12, and J13 are output 2 controlled by R10  
Populate connectors based on your needs.  

Thinking about making a smaller / cheaper single reg version as well in the future. 

## KiCad
This is a KiCad 5.0 project. 

## documentation
This is a XLS/PDF dump of the spreadsheet documentation I was using during development. 

## OSHpark PCBs
PCB design can be found here:
https://www.oshpark.com/shared_projects/n03EZh99


Copyright (c) 2018 Peter Shabino

Permission is hereby granted, free of charge, to any person obtaining a copy of this hardware, software, and associated documentation files 
(the "Product"), to deal in the Product without restriction, including without limitation the rights to use, copy, modify, merge, publish, 
distribute, sublicense, and/or sell copies of the Product, and to permit persons to whom the Product is furnished to do so, subject to the 
following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Product.

THE PRODUCT IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF 
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE 
FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION 
WITH THE PRODUCT OR THE USE OR OTHER DEALINGS IN THE PRODUCT.
