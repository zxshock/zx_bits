# zx_bits
Smaller projects, output or conclusions not worth their own repo

zx_multisound - fork of the firmware, addressing clicking issues in TS(FM) mode based on an older firmware as GS didn't work for me with the current version - see https://github.com/UzixLS/zx-multisound/issues/11 & https://github.com/UzixLS/zx-multisound/issues/10  
dkjoyprg3.tap - alternative programmer for DK'Tronics programmable joystick interface made in Boriel BASIC. 48K only, OTLA-ing works on real hardware (but somehow fails in Fuse).  
dkjoyprg5.tap - As above, but with additional, optional Reset or testmode after programming. Includes Easter Egg. Slightly re-arranged layout.  
dkjoyprg6.tap - As above, but now shows active key of the keyboard matrix in testmode.  
done_dkjoyprg7.tap - As above, but with UDGs for Enter/Space in testmode. Likely the final version.  
Extensively tested on my perfboard variant of said interface based on this schematic (used 2114 SRAMs instead of 6116): https://hardware.speccy.org/hardware/JoystickProgramable-dktronics/esquemas-i.html
