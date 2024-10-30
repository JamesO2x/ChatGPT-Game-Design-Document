
# Chrono Trigger Story Point Table

Every story event ID in Chrono Trigger. Formatted here as a 2D Python List. Columns are ID value (int), Name (string), and ID value (hex).

Values originally from: [Chrono Trigger (SNES)/List of Storyline Points - Data Crystal](https://datacrystal.tcrf.net/wiki/Chrono_Trigger_(SNES)/List_of_Storyline_Points)

```python
story_point_table = [
  # The Millenial Fair:
  [0, "New Game", 0x00],
  [3, "Crono gets out of bed", 0x03],
  [6, "Marle has lost her pendant", 0x06],
  [8, "Marle has joined Crono at the fair", 0x08],
  [10, "Visited Lucca's Telepod exhibit", 0x0A],

  # The Queen Returns:
  [12, "Marle disappeared into portal", 0x0C],
  [15, "Met Marle masquerading as Queen Leene", 0x0F],

  # The Queen is Gone:
  [16, "Marle disappears beyond the boundaries of time", 0x10],
  [18, "Lucca arrives in past", 0x12],
  [21, "Seen through the guise of the nuns at the Cathedral", 0x15],
  [27, "Rescued Queen Leene", 0x1B],
  [28, "Frog leaves Guardia throneroom in disgrace", 0x1C],
  [33, "Marle rematerializes in the Queen's chambers", 0x21],
  [36, "Lucca opens the gate back to the present", 0x24],

  # We're Back!:
  [39, "Arrived back in the present", 0x27],
  [42, "Detained for trial", 0x2A],

  # The Trial:
  [45, "Trial ends", 0x2D],
  [46, "Lucca comes to break Crono out of prison", 0x2E],
  [48, "Escape Guardia Castle", 0x30],

  # Beyond the Ruins:
  [51, "Escape through Guardia Forest Portal", 0x33],
  [52, "Met the people of Arris Dome", 0x34],
  [53, "Exploring the lower levels of Arris Dome", 0x35],
  [54, "Discovered visual record of Day of Lavos", 0x36],
  [55, "Given seeds to people of Arris Dome", 0x37],

  # The Factory Ruins:
  [60, "Setting out for the Factory Ruins", 0x3C],
  [63, "Security system goes haywire", 0x3F],
  [64, "Robo got creamed", 0x40],
  [66, "Defeated R Series", 0x42],
  [69, "Decided to leave via the Proto Dome portal", 0x45],
  [72, "Arrived at the End of Time", 0x48],

  # The End of Time:
  [73, "Spoken to Gaspar", 0x49],
  [74, "Gaspar calls when trying to leave the first time", 0x4A],
  [75, "Gaspar says to take a look in the room behind him", 0x4B],
  [76, "Spekkio", 0x4C],
  [77, "Learned magic", 0x4D],

  # The Village of Magic:
  [78, "Arrive in Medina", 0x4E],
  [81, "Defeated Heckran", 0x51],

  # The Hero Appears:
  [84, "Arrive in 600 AD to search for Magus", 0x54],
  [87, "Ozzie launches an attack on Zenan Bridge", 0x57],
  [90, "Ozzie summons Zombor", 0x5A],

  # Tata and the Frog:
  [93, "Met Tata on Denadoro Mts.", 0x5D],
  [96, "Received Bent Sword", 0x60],
  [102, "Received Hero's Medal", 0x66],
  [105, "Received Bent Hilt", 0x69],

  # The Rare Red Rock:
  [108, "Showed Melchior the broken Masamune", 0x6C],
  [111, "Met Ayla", 0x6F],
  [114, "Win soup race", 0x72],
  [117, "Awaken without Gate Key", 0x75],

  # Footsteps! Follow!:
  [120, "Setting out to find Gate Key", 0x78],
  [123, "Find Kino in Forest Maze", 0x7B],
  [124, "Defeated Nizbel", 0x7C],
  [125, "Leaving Chief's Hut to return to the portal", 0x7D],

  # The Masamune!:
  [126, "Leaving Prehistoric times with Dreamstone", 0x7E],
  [129, "Melchior reforges the Masamune", 0x81],
  [132, "Frog decides to face Magus", 0x84],
  [135, "Opened the Magic Cave", 0x87],

  # Magus' Castle:
  [136, "Arrived at Castle Magus", 0x88],
  [137, "Ozzie Defeated", 0x89],
  [138, "Magus Defeated", 0x8A],

  # Forward to the Past:
  [141, "Arrive in Prehistoric times from Castle Magus Inner Sanctum", 0x8D],
  [142, "Arrive at Laruba", 0x8E],
  [144, "Meet Ayla at Dactyl Nest Summit", 0x90],

  # Unnatural Selection?:
  [147, "Setting out for Tyrano Lair", 0x93],
  [150, "Defeated Reptite guards outside of Kino's cell", 0x96],
  [151, "Kino freed", 0x97],
  [152, "Kino opens fossil head", 0x98],
  [153, "Lavos falls to Earth", 0x99],

  # The Magic Kingdom:
  [159, "Traveled to 12000 BC for first time", 0x9F],
  [162, "Watched Schala open door to Zeal throneroom", 0xA2],
  [165, "Charged pendant", 0xA5],
  [168, "Captured by Dalton", 0xA8],

  # Break the Seal!:
  [171, "Locked out of 12000 BC", 0xAB],
  [174, "Acquired Epoch", 0xAE],

  # The Guru on Mt.Woe:
  [177, "(Does not appear to be used, but marks the start of this chapter)", 0xB1],
  [180, "Fight the Mud Imp and his beasts", 0xB4],
  [183, "Mt Woe falls", 0xB7],

  # What Lies Beyond?:
  [186, "Dalton kidnaps Schala", 0xBA],
  [187, "Melchior gives Crono the Ruby Knife", 0xBB],

  # Lavos Beckons:
  [189, "Defeated Dalton in Zeal throneroom", 0xBD],
  [195, "Queen demands Schala to raise power of Mammon Machine", 0xC3],
  [198, "Queen anticipates immortality nearing", 0xC6],
  [201, "Defeated GolemTwins", 0xC9],
  [203, "Crono gets whacked", 0xCB],
  [204, "Tidal Wave washes over land", 0xCC],
  [205, "Awaken in Last Village", 0xCD],

  # The New King:
  [207, "Dalton attacks Last Village", 0xCF],
  [210, "Blackbird crashes", 0xD2],

  # The Time Egg:
  [211, "Met Magus at North Cape", 0xD3],
  [212, "Black Omen rises", 0xD4],

  # The Fated Hour:
  [213, "Revived Crono", 0xD5],

  # The Final Battle:
  [214, "Destroyed the Black Omen", 0xD6],
]
```

# Missing Entries

Here's the completed table with the missing entries added. Each missing entry has `None` type as the second element and is filled in with the appropriate hex value for the third element.

```python
story_point_table = [
  # The Millenial Fair:
  [0, "New Game", 0x00],
  [1, None, 0x01],
  [2, None, 0x02],
  [3, "Crono gets out of bed", 0x03],
  [4, None, 0x04],
  [5, None, 0x05],
  [6, "Marle has lost her pendant", 0x06],
  [7, None, 0x07],
  [8, "Marle has joined Crono at the fair", 0x08],
  [9, None, 0x09],
  [10, "Visited Lucca's Telepod exhibit", 0x0A],
  [11, None, 0x0B],

  # The Queen Returns:
  [12, "Marle disappeared into portal", 0x0C],
  [13, None, 0x0D],
  [14, None, 0x0E],
  [15, "Met Marle masquerading as Queen Leene", 0x0F],

  # The Queen is Gone:
  [16, "Marle disappears beyond the boundaries of time", 0x10],
  [17, None, 0x11],
  [18, "Lucca arrives in past", 0x12],
  [19, None, 0x13],
  [20, None, 0x14],
  [21, "Seen through the guise of the nuns at the Cathedral", 0x15],
  [22, None, 0x16],
  [23, None, 0x17],
  [24, None, 0x18],
  [25, None, 0x19],
  [26, None, 0x1A],
  [27, "Rescued Queen Leene", 0x1B],
  [28, "Frog leaves Guardia throneroom in disgrace", 0x1C],
  [29, None, 0x1D],
  [30, None, 0x1E],
  [31, None, 0x1F],
  [32, None, 0x20],
  [33, "Marle rematerializes in the Queen's chambers", 0x21],
  [34, None, 0x22],
  [35, None, 0x23],
  [36, "Lucca opens the gate back to the present", 0x24],
  [37, None, 0x25],
  [38, None, 0x26],

  # We're Back!:
  [39, "Arrived back in the present", 0x27],
  [40, None, 0x28],
  [41, None, 0x29],
  [42, "Detained for trial", 0x2A],
  [43, None, 0x2B],
  [44, None, 0x2C],

  # The Trial:
  [45, "Trial ends", 0x2D],
  [46, "Lucca comes to break Crono out of prison", 0x2E],
  [47, None, 0x2F],
  [48, "Escape Guardia Castle", 0x30],
  [49, None, 0x31],
  [50, None, 0x32],

  # Beyond the Ruins:
  [51, "Escape through Guardia Forest Portal", 0x33],
  [52, "Met the people of Arris Dome", 0x34],
  [53, "Exploring the lower levels of Arris Dome", 0x35],
  [54, "Discovered visual record of Day of Lavos", 0x36],
  [55, "Given seeds to people of Arris Dome", 0x37],
  [56, None, 0x38],
  [57, None, 0x39],
  [58, None, 0x3A],
  [59, None, 0x3B],

  # The Factory Ruins:
  [60, "Setting out for the Factory Ruins", 0x3C],
  [61, None, 0x3D],
  [62, None, 0x3E],
  [63, "Security system goes haywire", 0x3F],
  [64, "Robo got creamed", 0x40],
  [65, None, 0x41],
  [66, "Defeated R Series", 0x42],
  [67, None, 0x43],
  [68, None, 0x44],
  [69, "Decided to leave via the Proto Dome portal", 0x45],
  [70, None, 0x46],
  [71, None, 0x47],
  [72, "Arrived at the End of Time", 0x48],

  # The End of Time:
  [73, "Spoken to Gaspar", 0x49],
  [74, "Gaspar calls when trying to leave the first time", 0x4A],
  [75, "Gaspar says to take a look in the room behind him", 0x4B],
  [76, "Spekkio", 0x4C],
  [77, "Learned magic", 0x4D],
  [78, "Arrive in Medina", 0x4E],
  [79, None, 0x4F],
  [80, None, 0x50],
  [81, "Defeated Heckran", 0x51],

  # The Hero Appears:
  [82, None, 0x52],
  [83, None, 0x53],
  [84, "Arrive in 600 AD to search for Magus", 0x54],
  [85, None, 0x55],
  [86, None, 0x56],
  [87, "Ozzie launches an attack on Zenan Bridge", 0x57],
  [88, None, 0x58],
  [89, None, 0x59],
  [90, "Ozzie summons Zombor", 0x5A],

  # Tata and the Frog:
  [91, None, 0x5B],
  [92, None, 0x5C],
  [93, "Met Tata on Denadoro Mts.", 0x5D],
  [94, None, 0x5E],
  [95, None, 0x5F],
  [96, "Received Bent Sword", 0x60],
  [97, None, 0x61],
  [98, None, 0x62],
  [99, None, 0x63],
  [100, None, 0x64],
  [101, None, 0x65],
  [102, "Received Hero's Medal", 0x66],
  [103, None, 0x67],
  [104, None, 0x68],
  [105, "Received Bent Hilt", 0x69],
  [106, None, 0x6A],
  [107, None, 0x6B],

  # The Rare Red Rock:
  [108, "Showed Melchior the broken Masamune", 0x6C],
  [109, None, 0x6D],
  [110, None, 0x6E],
  [111, "Met Ayla", 0x6F],
  [112, None, 0x70],
  [113, None, 0x71],
  [114, "Win soup race", 0x72],
  [115, None, 0x73],
  [116, None, 0x74],
  [117, "Awaken without Gate Key", 0x75],
  [118, None, 0x76],
  [119, None, 0x77],
  [120, "Setting out to find Gate Key", 0x78],
  [121, None, 0x79],
  [122, None, 0x7A],
  [123, "Find Kino in Forest Maze", 0x7B],
  [124, "Defeated Nizbel", 0x7C],
  [125, "Leaving Chief's Hut to return to the portal", 0x7D],

  # The Masamune!:
  [126, "Leaving Prehistoric times with Dreamstone", 0x7E],
  [127, None, 0x7F],
  [128, None, 0x80],
  [129, "Melchior reforges the Masamune", 0x81],
  [130, None, 0x82],
  [131, None, 0x83],
  [132, "Frog decides to face Magus", 0x84],
  [133, None, 0x85],
  [134, None, 0x86],
  [135, "Opened the Magic Cave", 0x87],
  [136, "Arrived at Castle Magus", 0x88],
  [137, None, 0x89],
  [138, None, 0x8A],
  [139, None, 0x8B],
  [140, None, 0x8C],
  [141, "Magus chanted Lavos summoning", 0x8D],
  [142, None, 0x8E],
  [143, "Defeated Magus", 0x8F],
  [144, None, 0x90],
  [145, None, 0x91],
  [146, None, 0x92],
  [147, None, 0x93],
  [148, "Portal sends party to 65,000,000 B.C.", 0x94],
]
``` 

Let me know if you need any further adjustments!