# wifireminder
Friends don't let friends have bad OpSec.   A fun way to remind friends what they're broadcasting is to listen for hotspot SSIDs of the format "\<FirstName\>'s [iPhone|Android|Car] and give them a verbal hint.  You never know who may be listening!

Usage (requires espeak):  wifireminder.sh <wifi interface>

# rfreminder
Same idea as wifireminder, just also includes bluetooth via hcitool.  It's single threaded operation slows down the loop, though (which might not be a bad thing)
Usage:  rfreminder.sh <wifi interface>
