Zaxour's Remix Multiout (pads in same order as NESRGB): https://github.com/zaxour/NESRGB_Multiout

EasyEDA Link: https://easyeda.com/fragolroc/ft-av-multiout

Gerber files for current FragolTech AV Multiout boards.

MONO boards have left and right pins internally bridged. If used for NESRGB installs, you will only need one wire connected to either the left or right audio pad. Sound will come out both channels of the multiout.

JUMPER boards have a jumper (J1) that will bridge Left and Right audio. Leaving the jumper open allows you to hook up separate Left and Right channels.

Ground pads/pins are internally bridged. This ensures proper grounding regardless of what cables you use. It has been observed that some video cables do not have ground hooked up to both ground pins of the mulitout connector. This multiout board helps ensure you have proper grounding even if your cables do not.
