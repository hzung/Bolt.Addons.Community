

# Bolt.Addons.Community
A community-driven project for extending Unity Bolt with custom nodes, types, and helpers.

Development is open to the community.


#### Why Bolt.Addons.Community and not Bolt.Community.Addons?  
While the latter flows off of the tongue more naturally, this project aims to be part of a larger ecosystem of addons and so aims for the former.  If auto-adding custom types from namespaces becomes a supported feature of Bolt, Bolt.Addons.X is preferable.

> [Direct Download (requires matching Bolt version)](https://github.com/RealityStop/Bolt.Addons.Community/releases/)



----------

# Installing

To import the addons, open Packages/manifest.json and add this line under dependencies:

	"dev.bolt.addons": "https://github.com/RealityStop/Bolt.Addons.Community.git"
	
Then, use the Tools menu to Build Unit Options, and they're ready to go!  Once you've rebuilt your unit options, the new nodes will be available for use.

> **Important**: if updating from a pre-3.0 version, please *DELETE* any Bolt.Addons.Community dll files.  By default these were placed in your *Plugins* folder.

# Updating
To update GoCS, open Packages/manifest.json and remove the dev.bolt.addons entry under lock at the end of the file.


----------


### What's included
There are two sets of units currently delivered:

> ### Bolt.Addons.Community

/Variables
 - **Increment Variable**
 - **Decrement Variable**
 - **Plus Equals**

/Events
 - **On Every X Seconds**
 - **On Variable Changed**
 - **Manual Event**
 - **Defined Event**
 - **Trigger Defined Event**
 - **Global Event**
 - **Trigger Global Event**

/Documentation
 - **Todo**
 - **Some Value**
 - **Stuff Happens**
 - **Comment**

/Collections
 - **Random Numbers**

/Control
 - **Branch (Params)**
 - **Gate**
 - **Edge Trigger**
 - **Change Detect**
 - **DoOnce**

/Logic
 - **Latch**
 - **Polarity**
 - **Between**
 - **Logic (Params)**
 - **Log**

/Math
 - **Math Op**
 - 
	 /Functions  (Still in testing, feel free to make suggestions, though!)
	 - **Decay**
	 - **Exponential**
	 - **Linear**
	 - **Logarithmic**
	 - **Reverse Linear**
	 - **Sigmoid**



## Current contributors (aka who to blame)
 - *Reality.Stop()
 - *JasonJamesLASM
 - Necka
 - AFoolsDuty
 - Eka
 - Silence
