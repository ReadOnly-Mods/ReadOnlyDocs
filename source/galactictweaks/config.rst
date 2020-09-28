==================
Configuration File
==================

.. WARNING::
	Documentation Not Finished!

------------------------------------------------------------------------------------------------------------

Default Configuation File
~~~~~~~~~~~~~~~~~~~~~~~~~

This configuration file was generated using GalacticTweaks-1.2.0 (Forge 2847):

.. code-block:: guess

	# Configuration file

	~CONFIG_VERSION: 3

	##########################################################################################################
	# compressor-enhancement
	#--------------------------------------------------------------------------------------------------------#
	# Adds Oredict ingots to compressor recipe table
	##########################################################################################################

	compressor-enhancement {
	    # Set to true if you want to register Compressor Fixes
	    B:compressorFix=false
	}


	##########################################################################################################
	# fix-icons
	#--------------------------------------------------------------------------------------------------------#
	# Fixes the Planet/Star icon sizes from More Planets & ZollernGalaxy
	##########################################################################################################

	fix-icons {
	    # Set to true to enable Fix Icons feature
	    # Only affects icons if enableNewGalaxyMap is enabled in 'Asmodeuscore/core.conf'
	    B:fixAsmodeusMapIcons=false
	}


	##########################################################################################################
	# music
	#--------------------------------------------------------------------------------------------------------#
	# Stops all custom music on Planets
	##########################################################################################################

	music {
	    # Set to true if you want to disable the music played on Galacticraft Planets
	    B:disableSpaceMusic=false
	}


	##########################################################################################################
	# new-galaxy
	#--------------------------------------------------------------------------------------------------------#
	# Move Duplicate Sol Planets to a new galaxy
	# THIS FEATURE WILL NOT BE EXTENDED OR ADDED TO IN FUTURE VERSIONS
	# ANY CRASHES OR BUGS RESULTING FROM THIS OPTION BEING ENABLED
	# SHOULD BE REPORTED TO THIS MODS ISSUE TRACKER NOT THE PLANETS ADDON DEV 
	# 
	# Use at your own discretion
	##########################################################################################################

	new-galaxy {
	    # Set to true if you want Seperate Addon Planets
	    # Note: AsmodeusCore, ExtraPlanets & GalaxySpace must be installed 
	    B:"00-Seperate Duplicate Planets"=false

	    # [valid: extraplanets | galaxyspace | none, default: none]
	    S:"01-Addon Planets To Move"=none
	}


	##########################################################################################################
	# overworld-comets
	#--------------------------------------------------------------------------------------------------------#
	# have comets also drop in the overworld - extending realism even further
	##########################################################################################################

	overworld-comets {
	    # Set to a value between 0.0 and 0.9 to decrease meteor spawn
	    D:overworldCometSpawnRate=1.0

	    # Set to true to enable comets in the Overworld
	    B:overworldComets=false
	}


	##########################################################################################################
	# space-breathing
	#--------------------------------------------------------------------------------------------------------#
	# Adds ability for passive mobs to beathe on other planets
	##########################################################################################################

	space-breathing {
	    # Set to true if you want all Passive Mobs to breathe in space
	    B:mobsBreatheInSpace=false
	}


	##########################################################################################################
	# space-race
	#--------------------------------------------------------------------------------------------------------#
	# Additional Features related to Galacticraft SpaceRace Teams
	##########################################################################################################

	space-race {
	    # Set to true if you want to enable features for Galacticraft SpaceRace
	    B:"Enable SpaceRace Feature"=false
	}


	##########################################################################################################
	# spawn-with-oxygen-equipment
	#--------------------------------------------------------------------------------------------------------#
	# Allows Players to Spawn With Oxygen Items Equipped
	##########################################################################################################

	spawn-with-oxygen-equipment {
	    # [default: false]
	    B:"00-Spawn With Oxygen-Gear"=false

	    # [valid: light | medium | heavy, default: light]
	    S:"01-Spawn With Oxygen Tank Tier"=light

	    # [valid: thermal | isothermal, default: thermal]
	    S:"01-Spawn With Thermal Armor"=thermal

	    # **False IF "00-Spawn With Oxygen-Gear" Is Disabled**
	    # [default: false] 
	    B:"02-Spawn With Frequency Module"=false

	    # **False IF "00-Spawn With Oxygen-Gear" Is Disabled**
	    # [default: false] 
	    B:"02-Spawn With Parachute"=false

	    # **False IF "00-Spawn With Oxygen-Gear" Is Disabled**
	    # [default: false]
	    B:"02-Spawn With Shield Controller"=false
	}