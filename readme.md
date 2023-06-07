# Chocbox

The objective of this project was to create a stickless controller with a low height body. To achieve this I swapped from standard buttons to instead using a PCB housing choc switches and 3d printed buttons designed to slot into them.

I chose choc switches since their design holds a 3d printed button much more securely than an mx switch while also being easier to print.

Refer to the [OnShape project](https://cad.onshape.com/documents/75e113c9407cf422c65e0889/v/74a9f620865811870f0dd645/e/7d5beb43c80cf76b58155f77?renderMode=0&uiState=647fb75370b34f6be44eeb65) to see what assembly roughly looks like. Please feel free to clone the project and change it however it suits you.

[The buttons were also designed in OnShape](https://cad.onshape.com/documents/3c28af6b43d2c4966163a2e3/w/c3540472dc935fdd22f11141/e/71cabcc9b349a1862c93366c?renderMode=0&uiState=64277b5fd101cb2a61f906aa). Same thing, please clone it and change it to suit your needs.

The drawings I used to order the top and bottom plate are in the drawings directory. I recommend SendCutSend if you choose to order your own. They work fast and their prices are reasonable for what you get.

The kicad projects that define the PCBs are in the PCB directory. Please try not to judge too harshly, I'm an amateur at best when it comes to PCB design. For anyone that wants to learn, the [PCB Design Guide by AI03](https://wiki.ai03.com/books/pcb-design/page/pcb-guide-part-1---preparations) is a great resource for the basics. The produced gerbers are also housed with each board's project. JLPCB is a great service to order these from.

Feel free to raise an issue through the repo for any questions/concerns.

## Construction
First and foremost the most important thing is a Brook fighting board. I used a UFB for this but you can cut costs by working out which system you'll play on primarily and getting that instead. The UFB works on all of them. You can absolutely use whatever main board you like, this project is more concered with keeping all the right parts secured in the right spots than it is specifically designed for a Brook board.  
[Brook UFB](https://www.amazon.com/Universal-Fighting-Compatible-preinstalled-Android-iOS/dp/B08H1TCFB1)

I used heat-set brass inserts on the mid section pieces since I 3d printed them. If you're using wood you can probably get just using wood screws or using a tap to thread the hole.  
[8x M3x4x5 heat-set inserts](https://dfh.fm/products/black-nickel-coated-threaded-heat-set-inserts?variant=43580471673054)  

For securing the plates to the mid section, the screws should be at least 6mm long. I only say this because the screws I used were 6mm, you could easily go longer so long as they aren't hitting each other in the hole.  
[8x at least 6mm M3](https://www.mcmaster.com/91294A126/)  

Securing the PCBs to the top plate was tricky. On the first of these I built, I was able to drill the holes fairly well so there was no evidence on the face. The second one... not so much. It helps to have a stop collar for your particular bit. Set the collar at about ~3-4 mm to start and be very careful. Additionally you could order a thicker top plate to help alleviate the issue. The answer to "well why didn't you?" is "I'm not smart".  

For the face button and cardinal PCBs use M3s to secure them.  
[12x 5mm M3](https://www.mcmaster.com/92005A114/)  

For the 6x6x5 PCBs, use M2s to secure them.  
[8x 5mm M2](https://www.mcmaster.com/92005A019/)  

The boards for the main buttons and cardinals use 2.54mm pitch connectors. Screw terminals are great as are JST connectors. I went with screw terminals since crimping wire connectors can be a bit frustrating sometimes.  
[3x 5 position 2.54 mm pitch screw terminals](https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/691210910005/11477521)  

The small boards for the control buttons and L3/R3 use 2mm pitch connectors. I designed them with JST-PH connectors in mind. If you don't have crimpers and don't want to buy them just for this project, its totally valid to just solder the wires directly to the board. The following are link is for a connector kit since its kind of annoying to order all the bits of the connector assembly separate. For the crimpers, most crimping pliers on amazon will do the trick. Just make sure the pliers can handle 1.6 and 1.9 mm widths. Also, don't go nuts on a pair of strippers. I personally have a pair of [these](https://www.amazon.com/Stripper-Stranded-Klein-Tools-1003/dp/B000V6W5QU/ref=sr_1_59?crid=3C40FWK0G2Q9M&keywords=wire+strippers&qid=1686095615&sprefix=wire+strippers%2Caps%2C160&sr=8-59) and they're fine  
[2x 4 pos 2mm pitch JST-PH connectors](https://www.amazon.com/CQRobot-Connector-Terminal-Industrial-Integrated/dp/B0731MZCGF)    

For the 6x6x5 buttons, focus more on the 6x6 length x width than the 5mm height. [Packs of buttons](https://www.amazon.com/gp/product/B07C7211PJ/ref=ppx_yo_dt_b_search_asin_image?ie=UTF8&psc=1) can be gotten on amazon for a fair price but they can also be ordered individually from Digikey or McMaster Carr.   
[6x 6x6x5 momentary push-button switches (McMaster)](https://www.mcmaster.com/1821N11/)   

Digikey can be a bit overwhelming, hopefully [this link](https://www.digikey.com/en/products/filter/tactile-switches/197?s=N4IgjCBcpgzADFUBjKAzAhgGwM4FMAaEAeygG0QAWeANhtpAF0iAHAFyhAGU2AnASwB2AcxABfIgFYaAdiQhUkTLkIlyIAEyT4kmQA4mrDpG58hoiSAC0G%2BYr4BXVaUgVJTMZ6A) goes right to the search I used. In the Switches -> Tactile Switch section, use the search to set the Circuit to SPST-NO and the Outline to 6.0mm x 6.0mm   

This is the *exact* part I ordered and the board's tolerances were designed specifically for it.  
[USB Type B male to type B female extension](https://www.amazon.com/gp/product/B00S5WJ5RO/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)  

Dealer's choice on which flavor of choc switch to go with, I suggest staying in the 30-50gf range for actuation force.   
[12x kailh choc keyswitches](https://mkultra.click/choc-switches)   

This is the exact cable I use but honestly, any B to A cable will do fine.   
[Amazon Basics 6ft USB-A to USB-B cable](https://www.amazon.com/Amazon-Basics-External-Gold-Plated-Connectors/dp/B00NH11KIK/ref=sr_1_2?crid=8LI8RN92O9J4&keywords=Amazon%2BBasics%2BUSB-A%2Bto%2BUSB-B%2B2.0&qid=1686093715&s=electronics&sprefix=amazon%2Bbasics%2Busb-a%2Bto%2Busb-b%2B2.0%2B%2Celectronics%2C111&sr=1-2&th=1)   

For wiring between components I use ~22-24AWG wire. I generally go with PVC coated instead of silicone since its easier to get it to sit still. If you plan on being fancy and crimping ferrules onto your wire ends, I'd suggest going with 22 AWG since its easier to find ferrules for that gauge.    
[24 AWG Hookup Wire](https://www.amazon.com/gp/product/B073QHPGMC/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1)  

## Total Parts List
The parts listed here are mainly for reference and comparison so you can source your parts through a supplier that's more economically sound for you. The sources I list are mainly American suppliers so for anyone outside the continental US, shipping might make them insane choices.  


[1x PCB](https://www.amazon.com/Universal-Fighting-Compatible-preinstalled-Android-iOS/dp/B08H1TCFB1)  
[8x M3x4x5 heat-set inserts](https://dfh.fm/products/black-nickel-coated-threaded-heat-set-inserts?variant=43580471673054)   
[8x ~6mm M3](https://www.mcmaster.com/91294A126/)  
[12x 5mm M3](https://www.mcmaster.com/92005A114/)  
[8x 5mm M2](https://www.mcmaster.com/92005A019/)  
[3x 5 position 2.54 mm pitch screw terminals](https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/691210910005/11477521)  
[2x 4 pos 2mm pitch JST-PH connectors](https://www.amazon.com/CQRobot-Connector-Terminal-Industrial-Integrated/dp/B0731MZCGF)  
[6x 6x6x5 momentary push-button switches](https://www.mcmaster.com/1821N11/)  
[1x USB Type B male to type B female extension](https://www.amazon.com/gp/product/B00S5WJ5RO/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)  
[12x kailh choc keyswitches](https://mkultra.click/choc-switches)  
[1x USB-A to USB-B cable](https://www.amazon.com/Amazon-Basics-External-Gold-Plated-Connectors/dp/B00NH11KIK/ref=sr_1_2?crid=8LI8RN92O9J4&keywords=Amazon%2BBasics%2BUSB-A%2Bto%2BUSB-B%2B2.0&qid=1686093715&s=electronics&sprefix=amazon%2Bbasics%2Busb-a%2Bto%2Busb-b%2B2.0%2B%2Celectronics%2C111&sr=1-2&th=1)  
[Hookup wire](https://www.amazon.com/gp/product/B073QHPGMC/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1)  

## Credit

[6x6x5 pushbutton step file](https://www.mcmaster.com/1821N11/)  
[4pos terminal connector step file](https://www.phoenixcontact.com/en-us/products/printed-circuit-board-terminal-mpt-05-5-254-1725685)  
[Kailh choc switch step file](https://grabcad.com/library/kailh-choc-low-profile-switch-1)  
[USB Type B panel mount step file](https://grabcad.com/library/usb-type-b-panel-mount-1)  
[Kailh choc 1u keycap](https://grabcad.com/library/kailh-lp-choc-keycap-for-corne-1)  
