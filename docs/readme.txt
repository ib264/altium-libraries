Notes on location Dropbox\Research\Altium
While working with Bye-sah, I moved Altium work over to \Dropbox\Shared\Altium
As of 3/5/2019, all prior Altium work is now mowed back here
-> "PCO_related_designs" and "RPDN_related_designs" now contain most of my Cornell research designs
-> Removed "History", "__Previews", and logs from old designs to save space
"Components" have latest version of "CustomParts". Older project might use dated version of contained components


Useful Altium Hints and Shortcuts

1) Getting Started:
	Project -> Project Options -> ECO Generation: Add Rooms = Ignore Differences
	Storage Manager -> Change file names, etc
	Undo/Redo -> Ctrl+Z / Ctrl+Y
	Copy/Paste -> Ctrl+C / Ctrl+V
	Save -> Ctrl+S
	Select All -> Ctrl+A
	Find Similar Objects -> Select Matching
	Filter -> Clear Filter (Shift+C)

2) Schematic Editor
	Libraries (keep pinned)
	Libraries -> Project -> Add Library...(All Files)
	While dragging objects:
		Space -> Rotate 90 degrees
		X/Y -> Mirror around x/y axis
	Tools -> Annotate Schematics Quietly...
	Tools -> Update From Libraries...
	Tools -> Footprint Manager...
	Place -> Directives:
		Blanket (top left, bottom right, right click) -> Allows special rules for groups of nets
	Design -> Update <name>.PcbDoc
	
3) PCB Editor
	1/2/3 -> Board Planning Mode / 2D Layout mode / 3D Layout mode
	While dragging objects:
		L -> Flip on different to different side
		Space -> Rotate 90 degrees
	Q -> Toggle units (imperial/metric)
	M -> Move menu
	Shift+M -> Toggle insight lens
	View -> Flip Board
	Heads Up Display and Tracking
	Project -> Component Links: Synchronize components between schematic and PCB
	Tools -> Polygon Pours
	Tools -> Update From PCB Libraries...
	Design -> Rules...
	Design -> Layer Stack Manager
	Hide Layers/ Layer Sets
	
4) PCB Editor / Interactive Routing
	Ctrl+MouseButton1 -> Autocomplete connection
	"2" -> Add via without layer change
	"5" -> Toggle via pattern (for multi-trace routing)
	"+" or "-" -> Add via with layer change
	"SHIFT+R" -> Cycle through routing modes (ignore, avoid or push obstacle)
	"SHIFT+SPACEBAR" -> Cycle through routing styles (45/90, any angle, arc)
	".", ",", "SHIFT+,", "SHIFT+." -> Increase/decrease arc setback factor
	"SHIFT+E" -> Toggle hotspot snap
	"SHIFT+W" -> Routing width select
 
5) Component Editor

6) Footprint Editor