# Chocbox

The objective of this project was to create a stickless controller with a low height body. To achieve this I swapped from standard buttons to instead using a PCB housing choc switches and 3d printed buttons designed to slot into them.

I chose choc switches since their design holds a 3d printed button much more securely than an mx switch while also being easier to print.

Refer to the [OnShape project](https://cad.onshape.com/documents/75e113c9407cf422c65e0889/v/b19a7fb4bdb8a6e4af42e747/e/7d5beb43c80cf76b58155f77?renderMode=0&uiState=64277b0d6e2bbc2d59b42c88) to see what assembly roughly looks like. Please feel free to clone the project and change it however it suits you.

[The buttons were also designed in OnShape](https://cad.onshape.com/documents/3c28af6b43d2c4966163a2e3/w/c3540472dc935fdd22f11141/e/71cabcc9b349a1862c93366c?renderMode=0&uiState=64277b5fd101cb2a61f906aa). Same thing, please clone it and change it to suit your needs.

The drawings I used to order the top and bottom plate are in the drawings directory. I recommend SendCutSend if you choose to order your own. They work fast and their prices are reasonable for what you get.

The kicad projects that define the PCBs are in the PCB directory. Please try not to judge too harshly, I'm an amateur at best when it comes to PCB design. For anyone that wants to learn, the [PCB Design Guide by AI03](https://wiki.ai03.com/books/pcb-design/page/pcb-guide-part-1---preparations) is a great resource for the basics. The produced gerbers are also housed with each board's project. JLPCB is a great service to order these from.

Feel free to raise an issue through the repo for any questions/concerns.

## Specifics

The boards for the main buttons and cardinals use 2.54mm pitch connectors. Screw terminals are great as are JST connectors.

The small boards for the control buttons and L3/R3 use 2mm pitch connectors. I designed them with JST-PH connectors in mind.

The 3d printed center pieces are intended to have brass inserts sunk into them to attach the top and bottom plates. I ended up getting a bulk pack off Amazon and used two inserts per hole (top and bottom).

Likewise, the 6x6x5 pushbuttons can also be sourced from Amazon pretty inexpensively.

All holes in the project are intended for M3 screws.

## Credit

[6x6x5 pushbutton step file](https://www.mcmaster.com/1821N11/)  
[4pos terminal connector step file](https://www.phoenixcontact.com/en-us/products/printed-circuit-board-terminal-mpt-05-5-254-1725685)  
[Kailh choc switch step file](https://grabcad.com/library/kailh-choc-low-profile-switch-1)  
[USB Type B panel mount step file](https://grabcad.com/library/usb-type-b-panel-mount-1)  
[Kailh choc 1u keycap](https://grabcad.com/library/kailh-lp-choc-keycap-for-corne-1)  
