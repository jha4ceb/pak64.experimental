Download links:
Pak64.Experimental (pakset only -- NB requires Simutrans-Experimental)
Pak64.Experimental + Simutrans-Experimental
Sources

Pak64.experimental is a modified branch of pak64 which implements the features of Simutrans-Experimental. Currently many of the features of Simutrans-Experimental are hard to access, because they require a compatible pakset---and there are not enough compatible paksets available (though there are some!). These features, which are included in this pakset, include the following: 

-- Tilting trains
-- Comfort ratings
-- Catering vehicles
-- Bi-directional trains (i.e. trains that can be driven from either end)
-- Liveries
-- Overcrowding on passenger vehicles
-- Way constraints
-- Increase in maintenance for obsolete vehicles
-- Fixed maintenance costs
-- Industrial obsolescence
-- Realistic loading times (to come with Experimental 10.0)

http://forum.simutrans.com/index.php?topic=1959.0 for more

Pak64.Experimental aims to make it easy for players to take advantage of these features by providing an Experimental-optimised. At the basic level, pak64.exp is just a branch of pak64 with the above features enabled. 

As well as making Experimental more accessible to players, Pak64.Experimental also aims to aid developers by providing (another) stable pakset-environment in which to test new Experimental features. All new Experimental features will be enabled here in order to further aid development of Simutrans-Experimental.

On another level, pak64.exp aims to be to pak64 what Simutrans-Experimental is to Simutrans: an environment where new (or old) features can be tried out for size, and a version where ideas which are too radical for the trunk can be made available to players.


CHANGES FROM PAK.64 (so far)

-- Change in vehicle data to implement the above features
-- Change in industry data to allow for industrial obsolescence
-- Changes to ground textures (to give the pakset its own distinctive feel)
-- A few new vehicles to fill in some gaps in time timeline 
-- A few new buildings (mostly modified versions of open-source pak128 files)
-- Various small changes to building "chance" parameters



TO-DO LIST
-- Incorporate Experimental features as they are designed. Ongoing. Upgrading vehicles, for instance, is not yet implemented.
-- Tweak existing changes. At the moment vehicle data has been updated in a very haphazard manner. More attention will be required to get the values right.
-- Balancing. Experimental's changes will no doubt require changing some of the settings to allow for balanced economic features. This will require testing.
-- Expand the set of passenger vehicles.
-- Further environmental changes (e.g. ground objects)


NB. pak64 saves CAN be loaded in pak64 experimental. However, pak64.experimental comes bundled with the "food" industry chain, which will cause conflict if you haven't been using it.
