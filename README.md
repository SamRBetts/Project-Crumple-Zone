# Project-Crumble-Zone

Welcome to all version-controlled CAD for the ME capstone CanSat project!

Guidelines: 
<ul>
<li>Every assembly lives in a similarly-named folder containing itself + everything needed to construct it; this may include more assembly folders</li>
<li>Anything that is made from a single piece of material or single off-the-shelf component is a SLDPRT, anything else is a SLDASM</li>
<li>If you need a stock part, copy it or add it to the Github stock parts repo</li>
<li>Make subassemblies when a set of parts logically functions together; at minimum, anything that is glued together should be its own assembly, and anything that will be handled as a unit should be its own assembly (ex: the avbay should be one assembly) </li>
<li>File names should be snake case (like_this), folder names should be upper camel case (LikeThis)</li>
<li>Shared interface parts like couplers and screws should belong to the assembly that they are permanently attached to first; if it’s not obvious which side they should belong to, they should belong to the overarching assembly</li>
</ul>
