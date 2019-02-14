# TXn - Eurorack Fixed Panner/Mixer

The TELEXn (TXn) is a 2HP Remix of Jesper Särnesjö's open source module "nearness". Nearness is an ingenious module that you absolutely need in your rig. This remix compresses the original 3HP module into 2HP. You really can't go wrong with either one.

<img src="https://cdn.shopify.com/s/files/1/1856/2693/products/TXn_top-back_740x.jpg?v=1549508476" alt="TXn" width="400"/>

## What it Does

The module mixes and pans seven inputs to two outputs. There is an output at the top and bottom of the panel. Between these outputs are the seven inputs. These patch points correspond to panning positions between the two outputs. The closer you are to an output, the louder your signal will be there (and the quieter it will be in the corresponding output).

## How the TXn is Different from the 3HP Nearness

Again - all of the credit belongs with the original [Nearness Module](https://github.com/bpcmusic/nearness). The TXn is simply a reduced-form-factor version. A few changes needed to be made in order to accomplish this:

* The TXn is 1HP Smaller than Nearness (2HP vs 3HP).
* The TXn has a Power Section that is Different than the One on Nearness.
* The two boards on the TXn are oriented 90 degrees from each other (which can be tricky to solder).
* The TXn has a 1x5 power connector that hangs off the back of the module; its 6dB pad jumper connectors also hang off the back of the module.
* The TXn requires that the jacks be slightly raised off the top board in order to avoid electrical contact with the headers positioned underneath them. In fact, you will need to make sure you trim the headers flush with the top of the board priod to soldering. This is a real PITA, btw.

That's it.

If you are thinking you'd like to DIY a Nearness - it is highly recommended to consider building the 3HP version. It is much easier to solder and assemble.

## Module Specifications

* +12V: 25 mA  
* -12V: 26 mA  
* +5V: 0 mA  
* 2HP Width 
* 19mm Depth

## Folders & Files Explained

* **assistive**: 
	* ```TXn Build Guide.pdf``` - a PDF build guide to walk your through component-level placement
	* ```TXn Assembler.svg``` - little laser-cut forms to hold your boards together when soldering the 90 degree angle.
	* ```TXn Frame``` - a 3D printed frame to hold multiple TXn at a time
	* ```TXn Stencil Frame``` - a 3D printed stencil frame to hold the TXn in place while applying solder paste
	* ```TXn Stencil.svg``` - the solder paste stencil for laser cutting
	
* **board**
	* ```gerbers``` - the gerbers files (and Eagle files) for the top and bottom boards
	* ```images``` - image rederings of the boards
	* ```TXn_v1.2.brd/sch``` - the master Eagle file for the TXn
	
* **extras**
	* ```instructions.docx``` - the instructions delivered with the pre-built module
	* ```txn_mix_diagram.ai/svg``` - a digram of the module's mix behavior (used in the instructions file)
	
* **panel**
	* ```metalphoto``` - the individual files used for the creation of the metalphoto panel in the retail version
	* ```TXn.ai/svg``` - the panel files
	* ```TXn_lg.png``` - a big version of the panel
	* ```TXn_mp.zip``` - the archive sent for fabrication
	* ```TXn_sm.png``` - a small photo of the panel

* ```TXn BOM.csv``` - the BOM for this version of the TXb.

## Links

Nearness can be found in this repository:

* [Nearness Repository](https://github.com/bpcmusic/nearness)

Visit the TXn on Modular Grid:

* [Modular Grid](https://www.modulargrid.net/e/other-unknown-telexn)

Pre-built TXn are occasionally made availalbe for purchase here:

* [store.bpcmusic.com](https://store.bpcmusic.com/products/telexn?variant=5636075159583)

## License

[CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/)

