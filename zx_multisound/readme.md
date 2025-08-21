Forked from https://github.com/UzixLS/zx-multisound  
Starting at a696ecd, skipping 63a2324 (GS refactor - broke GS for me) but incorporating the later 1ee608e, 35bb968 and 548d6ef.  
Additional (experimental) fix for https://github.com/UzixLS/zx-multisound/issues/11 (disabling SAA1099 via SW1.2 turns on an assumed TSFM legacy mode, which fixes the clicks in Ball Quest). See issue for details.  
Only 1MB variant tested, because that's the hardware I have.  

Quite frankly I have no idea why this works, as the clicking seems to be related to something else (FM/FMDAC enable - pulling the DACs fixes the clicking with the original firmware)
