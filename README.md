# Lore friendly Cars
A collection of high rated lore friendly vehicles from GTA5-mods. This pack features a mixture of add-on, replace and tuning cars. Some also feature custom sounds.
* Only high quality models and sounds. 
* **Most** models run at <40 MiB of physical memory.
* Most handling files are lore friendly. Feel free to make a PR if you fix handling on one of the featured vehicles.

# Important ⚠️
* All credits to go the original creators of these vehicles. These vehicles may be removed from the pack if the owners will it.
* Treat all vehicles in this pack as the following: *Modifying this package and it's contents except the text data such as handling, meta files and mod-kit, uploading or hosting it elsewhere as is or in a modified state and selling, paywalling or monetizing in any shape or form is prohibited.*
* Most of these cannot be used as one of one's or as donator cars.

# Install
* Drag and drop
* Ensure Lorefriendly-Cars

# For use of sounds
* Drag [lf-cars-sounds] into your `resources` folder
* Ensure [lf-cars-sounds] in your server CFG

# Support
* I will not offer support on any of these vehicles, everything on my part is in the README. If you want to change any handling files (which for some it's needed), you need to configure it yourself.

# Credits
* All credits can be found in this sheet: [Credit Sheet - LDS LF-cars](https://docs.google.com/spreadsheets/d/1fwW5I7cjDeFstd8jkXQQjeMB15BTyOV-8nU6telg05s/edit?usp=sharing)

# To-do List
* Update handling to be a lore friendly standard.
* Make sure soundfiles work properly when provided.
* ~~Update README/Adding cars to dealerships to contain all vehicles~~.

# Adding cars to dealerships
* Add to `qb-core/shared/vehicles.lua`
```lua
-- Lore Vehicles

  -- albany
  { model = 'missile', name = '1932 Albany JSS Hawk Missile', brand = 'Albany', price = 70600, category = 'albany', type = 'automobile', shop = 'pdm' },

  -- bus
  { model = 'relaxer', name = 'Relaxer', brand = 'Brute', price = 108676, category = 'bus', type = 'automobile', shop = 'pdm' },

  -- compacts
  { model = 'brisket2', name = 'Brisket Rally', brand = 'Weeny', price = 1, category = 'compacts', type = 'automobile', shop = 'pdm' },
  { model = 'castella', name = 'Castella', brand = 'Shitzu', price = 1, category = 'compacts', type = 'automobile', shop = 'pdm' },
  { model = 'brisket', name = 'Brisket', brand = 'Weeny', price = 1, category = 'compacts', type = 'automobile', shop = 'pdm' },
  { model = 'issi8s', name = 'Issi Rally', brand = 'Weeny', price = 1, category = 'compacts', type = 'automobile', shop = 'pdm' },
  { model = 'penman', name = 'Penman', brand = 'Vapid', price = 1, category = 'compacts', type = 'automobile', shop = 'pdm' },
  { model = 'brisket3', name = 'Brisket Gasser', brand = 'Weeny', price = 1, category = 'compacts', type = 'automobile', shop = 'pdm' },
  { model = 'peanut', name = 'Peanut', brand = 'Weeny', price = 10000, category = 'compacts', type = 'automobile', shop = 'pdm' },
  { model = 'arias', name = 'Arias', brand = 'Bordeaux', price = 48296, category = 'compacts', type = 'automobile', shop = 'pdm' },
  { model = 'hotwee', name = 'Hotring Weevil', brand = 'BF', price = 89853, category = 'compacts', type = 'automobile', shop = 'pdm' },
  { model = 'eva', name = 'EVA', brand = 'Hijak', price = 134785, category = 'compacts', type = 'automobile', shop = 'pdm' },

  -- coupe
  { model = 'zr380c', name = 'ZR-380', brand = 'Annis', price = 90000, category = 'coupe', type = 'automobile', shop = 'pdm' },

  -- coupes
  { model = 'torrence', name = 'Torrence', brand = 'Vapid', price = 1, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'ingotc', name = 'Ingot VD90R', brand = 'Vulcar', price = 1, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'fagaloac', name = 'Fagaloa Coupe', brand = 'Vulcar', price = 1, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'superd3', name = 'Super Diamond S', brand = 'Enus', price = 1, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'sancyb4', name = 'Sancy B4', brand = 'Bordeaux', price = 1, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'seraph3', name = 'Seraph XS', brand = 'Übermacht', price = 1, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'schafter3rs', name = 'Schafter V12', brand = 'Benefactor', price = 1, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'scheisser', name = 'Scheisser', brand = 'Benefactor', price = 1, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'hachura', name = 'Hachura R', brand = 'Vulcar', price = 1, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'asteropers', name = 'Asterope RS', brand = 'Karin', price = 1, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'spritzer', name = 'Spritzer STR', brand = 'Benefactor', price = 87323, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'spritzerdtm', name = 'Spritzer DTM', brand = 'Benefactor', price = 87323, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'streiter2', name = 'Streiter', brand = 'Benefactor', price = 87825, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'clique2', name = 'Clique Deluxe', brand = 'Vapid', price = 117687, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'paragonxr', name = 'Paragon XR', brand = 'Enus', price = 152233, category = 'coupes', type = 'automobile', shop = 'pdm' },
  { model = 'sentinelsg4', name = 'Sentinel SG4', brand = 'Übermacht', price = 153918, category = 'coupes', type = 'automobile', shop = 'pdm' },

  -- motorcycles
  { model = 'kampfer', name = 'Kampfer', brand = 'Übermacht', price = 59955, category = 'motorcycles', type = 'motorcycles', shop = 'pdm' },
  { model = 'akumac', name = 'Akuma Classic', brand = 'Dinka', price = 83155, category = 'motorcycles', type = 'motorcycles', shop = 'pdm' },

  -- muscle
  { model = 'bcatctx', name = 'Bobcat CTX', brand = 'Vapid', price = 1, category = 'muscle', type = 'automobile', shop = 'pdm' },
  { model = 'recursion', name = 'Recursion', brand = 'Bravado', price = 1, category = 'muscle', type = 'automobile', shop = 'pdm' },
  { model = 'paradox', name = 'Paradox', brand = 'Willard', price = 47136, category = 'muscle', type = 'automobile', shop = 'pdm' },
  { model = 'paradox2', name = 'Paradox', brand = 'Willard', price = 47136, category = 'muscle', type = 'automobile', shop = 'pdm' },
  { model = 'torido', name = 'Torido', brand = 'Annis', price = 55081, category = 'muscle', type = 'automobile', shop = 'pdm' },
  { model = 'vulture', name = 'Vulture', brand = 'Bravado', price = 89024, category = 'muscle', type = 'automobile', shop = 'pdm' },
  { model = 'domc', name = 'Dominator Classic', brand = 'Vapid', price = 101292, category = 'muscle', type = 'automobile', shop = 'pdm' },
  { model = 'dominatorgtc', name = 'Dominator GTC', brand = 'Vapid', price = 115910, category = 'muscle', type = 'automobile', shop = 'pdm' },
  { model = 'gauntletc', name = 'Gauntlet Classic', brand = 'Bravado', price = 155969, category = 'muscle', type = 'automobile', shop = 'pdm' },
  { model = 'dukes4', name = 'Dukes Cobra', brand = 'Imponte', price = 181855, category = 'muscle', type = 'automobile', shop = 'pdm' },
  { model = 'gauntletstx', name = 'Gauntlet STX', brand = 'Bravado', price = 189784, category = 'muscle', type = 'automobile', shop = 'pdm' },

  -- offroad
  { model = 'l35r', name = 'Walton', brand = 'Declasse', price = 1, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'caracaran', name = 'Caracara', brand = 'Vapid', price = 1, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'kamswb', name = 'Kamacho SWB', brand = 'Canis', price = 1, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'sandstorm', name = 'Sandstorm', brand = 'Vapid', price = 1, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'mesaxl', name = 'Gator 4x4', brand = 'Canis', price = 1, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'l35l', name = 'Walton Bed', brand = 'Declasse', price = 1, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'restovig', name = 'Vigero Outlaw', brand = 'Declasse', price = 1, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'riata', name = 'Riata Monster', brand = 'Vapid', price = 1, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'sandstormxl', name = 'Sandstorm XL', brand = 'Vapid', price = 1, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'l35s', name = 'Walton Slambed', brand = 'Declasse', price = 1, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'ruinerafd', name = 'Ruiner UTE', brand = 'Imponte', price = 1, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'riata2', name = 'Riata', brand = 'Vapid', price = 1, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'trailw', name = 'Trailwilder', brand = 'Annis', price = 1, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'blazer6', name = 'Blazer Recon ATV', brand = 'Nagasaki', price = 45430, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'vigout', name = 'Vigero Outlaw', brand = 'Declasse', price = 74216, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'squaddier', name = 'Baller Raid', brand = 'Gallivanter', price = 85174, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'baller7r', name = 'Baller Raid', brand = 'Gallivanter', price = 94090, category = 'offroad', type = 'automobile', shop = 'pdm' },
  { model = 'gstyosemite1', name = 'Yosemite DRT', brand = 'Declasse', price = 177529, category = 'offroad', type = 'automobile', shop = 'pdm' },

  -- sedans
  { model = 'tulip2s', name = 'Tulip M-100', brand = 'Declasse', price = 1, category = 'sedans', type = 'automobile', shop = 'pdm' },
  { model = 'nebula2', name = 'Nebula', brand = 'Vulcar', price = 1, category = 'sedans', type = 'automobile', shop = 'pdm' },
  { model = 'oceanic', name = 'Oceanic', brand = 'Bravado', price = 1, category = 'sedans', type = 'automobile', shop = 'pdm' },
  { model = 'tahoma3', name = 'Second Hand Tahoma', brand = 'Classique', price = 1, category = 'sedans', type = 'automobile', shop = 'pdm' },
  { model = 'remusvert', name = 'Remus Cabrio', brand = 'Annis', price = 1, category = 'sedans', type = 'automobile', shop = 'pdm' },
  { model = 'tmprem', name = 'Premier 200 SS', brand = 'Declasse', price = 1, category = 'sedans', type = 'automobile', shop = 'pdm' },
  { model = 'primo3', name = 'Primo LX', brand = 'Albany', price = 1, category = 'sedans', type = 'automobile', shop = 'pdm' },
  { model = 'tahoma2', name = 'Tahoma', brand = 'Classique', price = 1, category = 'sedans', type = 'automobile', shop = 'pdm' },
  { model = 'dilettantedx', name = 'Dilettante DX', brand = 'Karin', price = 47413, category = 'sedans', type = 'automobile', shop = 'pdm' },
  { model = 'glendalelimo', name = 'Glendale Stretch', brand = 'Karin', price = 104695, category = 'sedans', type = 'automobile', shop = 'pdm' },
  { model = 'panorama', name = 'Panorama', brand = 'Classique', price = 115449, category = 'sedans', type = 'automobile', shop = 'pdm' },
  { model = 'elegant', name = 'Elegant', brand = 'Willard', price = 184411, category = 'sedans', type = 'automobile', shop = 'pdm' },
  { model = 'elegyheritage', name = 'Elegy Heritage', brand = 'Annis', price = 196066, category = 'sedans', type = 'automobile', shop = 'pdm' },

  -- sports
  { model = 'turismo2lm', name = 'Turismo LM', brand = 'Grotti', price = 1, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'm420', name = 'Monroe SOTW Edition', brand = 'Pegassi', price = 1, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'callista', name = 'Comet Callista', brand = 'Pfister', price = 1, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'auroras', name = 'Aurora Sport LHD', brand = 'Progen', price = 1, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'nerops', name = 'Nero Pur Sport', brand = 'Truffade', price = 1, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'auroras2', name = 'Aurora Sport RHD', brand = 'Progen', price = 1, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'sheavas', name = 'Sheava', brand = 'Emperor', price = 51554, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'meteor', name = 'Meteor', brand = 'Pfister', price = 80644, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'kawaii', name = 'Kawaii', brand = 'Annis', price = 82378, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'italigts', name = 'Itali GTS', brand = 'Grotti', price = 87538, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'coquette4c', name = 'Coquette D10 Widebody', brand = 'Invetero', price = 100584, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'buffalo4h', name = 'Buffalo Hellfire', brand = 'Bravado', price = 140174, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'raidenz', name = 'Raiden Z', brand = 'Coil', price = 141883, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'euros', name = 'Euros', brand = 'Annis', price = 187268, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'f620d', name = 'F620', brand = 'Ocelot', price = 216006, category = 'sports', type = 'automobile', shop = 'pdm' },
  { model = 'f620s2', name = 'F620 Sleeper', brand = 'Ocelot', price = 216006, category = 'sports', type = 'automobile', shop = 'pdm' },

  -- sportsclassics
  { model = 'stingersc', name = 'Stinger SC', brand = 'Grotti', price = 1, category = 'sportsclassics', type = 'automobile', shop = 'pdm' },
  { model = 'toreador2', name = 'Toreador', brand = 'Pegassi', price = 1, category = 'sportsclassics', type = 'automobile', shop = 'pdm' },
  { model = 'spzr250', name = 'ZR-250', brand = 'Annis', price = 1, category = 'sportsclassics', type = 'automobile', shop = 'pdm' },
  { model = 'feltzer9', name = 'Sterling', brand = 'Benefactor', price = 1, category = 'sportsclassics', type = 'automobile', shop = 'pdm' },
  { model = 'stardust', name = 'Stardust', brand = 'Pfister', price = 72573, category = 'sportsclassics', type = 'automobile', shop = 'pdm' },
  { model = 'cheetahfel', name = 'Cheetah Veloce', brand = 'Grotti', price = 191828, category = 'sportsclassics', type = 'automobile', shop = 'pdm' },

  -- suv
  { model = 'beretta', name = 'Beretta', brand = 'Übermacht', price = 1, category = 'suv', type = 'automobile', shop = 'pdm' },

  -- suvs
  { model = 'toros2', name = 'Toros', brand = 'Pegassi', price = 1, category = 'suvs', type = 'automobile', shop = 'pdm' },
  { model = 'peacemaker', name = 'Peacemaker', brand = 'Gallivanter', price = 1, category = 'suvs', type = 'automobile', shop = 'pdm' },
  { model = 'peacemaker2', name = 'Peacemaker Family Edition', brand = 'Gallivanter', price = 1, category = 'suvs', type = 'automobile', shop = 'pdm' },
  { model = 'peacemaker3', name = 'Peacemaker 6x6', brand = 'Gallivanter', price = 1, category = 'suvs', type = 'automobile', shop = 'pdm' },
  { model = 'atlas', name = 'Atlas', brand = 'Karin', price = 60339, category = 'suvs', type = 'automobile', shop = 'pdm' },
  { model = 'executioner', name = 'Executioner', brand = 'Vapid', price = 79419, category = 'suvs', type = 'automobile', shop = 'pdm' },

  -- truck
  { model = 'sbus2', name = 'School Bus', brand = 'Brute', price = 1, category = 'truck', type = 'automobile', shop = 'pdm' },
  { model = 'sbus3', name = 'Derby Bus', brand = 'Brute', price = 1, category = 'truck', type = 'automobile', shop = 'pdm' },
  { model = 'terabit', name = 'Terrorbyte Blitz', brand = 'Benefactor', price = 1, category = 'truck', type = 'automobile', shop = 'pdm' },

  -- tuner
  { model = 'playboy', name = 'Playboy', brand = 'Vapid', price = 1, category = 'tuner', type = 'automobile', shop = 'pdm' },
  { model = 'rh4', name = 'Elegy RH4', brand = 'Annis', price = 1, category = 'tuner', type = 'automobile', shop = 'pdm' },
  { model = 'hotringfr', name = 'Hotring Fortune', brand = 'Vapid', price = 1, category = 'tuner', type = 'automobile', shop = 'pdm' },
  { model = 'kriegerc', name = 'Krieger BPX-32B', brand = 'Benefactor', price = 1, category = 'tuner', type = 'automobile', shop = 'pdm' },
  { model = 'sunrise1', name = 'Sunrise R', brand = 'Maibatsu', price = 59060, category = 'tuner', type = 'automobile', shop = 'pdm' },
  { model = 'zion4', name = 'Zion Classic Custom', brand = 'Übermacht', price = 86000, category = 'tuner', type = 'automobile', shop = 'pdm' },
  { model = 'picadorexr', name = 'Picador EXR', brand = 'Cheval', price = 104636, category = 'tuner', type = 'automobile', shop = 'pdm' },
  { model = 'zr380s', name = 'ZR-380 Custom', brand = 'Annis', price = 120000, category = 'tuner', type = 'automobile', shop = 'pdm' },
  { model = 'roxanne', name = 'Roxanne', brand = 'Annis', price = 172427, category = 'tuner', type = 'automobile', shop = 'pdm' },
  { model = 'elegyrace', name = 'Elegy Race', brand = 'Annis', price = 310394, category = 'tuner', type = 'automobile', shop = 'pdm' },

  -- utility
  { model = 'benson2', name = 'Benson', brand = 'Vapid', price = 45430, category = 'utility', type = 'automobile', shop = 'pdm' },

  -- vans
  { model = 'cwagon', name = 'Compact Wagon', brand = 'Schyster', price = 1, category = 'vans', type = 'automobile', shop = 'pdm' },
  { model = 'morningstar', name = 'Morningstar', brand = 'Schyster', price = 1, category = 'vans', type = 'automobile', shop = 'pdm' },
  { model = 'nspeedo', name = 'Speedo Express', brand = 'Vapid', price = 54778, category = 'vans', type = 'automobile', shop = 'pdm' },
  { model = 'burritor', name = 'Burrito Racing', brand = 'Declasse', price = 121619, category = 'vans', type = 'automobile', shop = 'pdm' },
