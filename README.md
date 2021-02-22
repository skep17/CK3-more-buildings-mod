# CK3-more-buildings-mod
This mod sets 10 building slots for baronies in the game, both county capitals and others. To avoid UI stretching and overlapping there's a scroll bar added and fit in the window. Only 4 slots space appears at a time.

You should put the main folder and .mod file here: C:\Users\< you user here withouth <> >\Documents\Paradox Interactive\Crusader Kings III\mod

Uniqueness of this mod is that it offers scrollbar to give more than vanilla game slots and prevent any bizarre GUI. 10 slots are just personally selected, you can change the number in more_buildings\common\defines\more_buildings.txt the file should look like this:


NProvince = {
	BASE_SUPPLY_LIMIT = 2000					# The unmodified base supply limit of a province
	BARONY_BUILDING_SLOTS = 11
	COUNTY_BUILDING_SLOTS = 11
	SUPPLY_PER_DEVELOPMENT = 150				# Each development adds this much sto the supply limit
	ACROSS_WATER_PROVINCE_MAX_DISTANCE = 2		# Maximum number of (traversable) water provinces between provinces to be considered "connected across water"
}


Here you can change:

BARONY_BUILDING_SLOTS = 11 representing regular barony slots
COUNTY_BUILDING_SLOTS = 11 representing county capital barony slots, in the vanilla game more than regular barony

just keep in mind to put 1 bigger number that you desire after = sign ( 11 means that it will be 10 slots in the game )
