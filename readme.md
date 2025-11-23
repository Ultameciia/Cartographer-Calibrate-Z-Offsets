This is a macro I've thrown together to calibrate your Z offsets using cartographer. There's a couple things to modify for your setup. 

In CARTO_OFFSET_PROBE you need to adjust it to your number of tools. The one I'm uploading here has 4 tools. You can just comment out the tools you don't need, or add if you have more. 
Do the same in CARTO_SAVE_RAW and CARTO_CALIBRATE_Z_OFFSETS. 


Feel free to make this cleaner (but pls share it with me if you do). I had hell trying to do this recursively or all within one macro due to how klipper saves the state of a variable. 
