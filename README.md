# Spider Evolution Simulator

> The original project by @carykh can be found [here](https://github.com/carykh/SpiderEvoSim).

Spider Evolution Simulator is a simulator of how spiders evolve based on danger-sensing tactics.

## Story

You're a hotel manager, and you have tenants who live in your hotel, but there's a major problem; Spiders! The spiders are all over the walls, and since the tenants are [arachnophobic](https://en.wikipedia.org/wiki/Arachnophobia), you need to find a way to exterminate them quick without having to shut down the hotel! Thankfully, you have a team of scientists who have created a special swatter technology that can exterminate these spiders quick. But watch out, because these spiders can learn and grow to get used to the swatters! 

## Running

This project built in [Processing](https://processing.org/) (specifically Processing 4), so you will need to [download Processing](https://processing.org/download) first before you do anything.

### Steps

> [!IMPORTANT]
> Make sure you have downloaded and installed [Processing 4](https://processing.org/download) beforehand, or else you will not be able to run the project.

1. Open the Processing 4 executable file.
2. ***Select the [`SpiderEvoSim`](/SpiderEvoSim.pde) file in Processing.*** <!-- I may come out as mean for saying this, but I can't get over how important this step is! Many people choose to open the room.pde file instead of the main SpiderEvoSim.pde! There's issues all over the original repo about it, and I feel bad that one guy [@hefnar] has to repeat himself in several of the issues related to this. -->
3. Run using the button

## Help!

### `No library found for processing.sound`

This can be fixed by installing the Sound library from the Contribution Manager.

1. Go to the "**S**ketch" menu
2. Select the "**I**mport Library..." menu
3. Select the "**M**anage Libraries..." menu
4. Search for "Sound" in the "Libraries" tab, and select the "**Sound**" library by "The Processing Foundation"
5. Press the Install button
6. Wait for it to download and install, and you're done!

### `String` / `ArrayList` / (some other) class is missing

Make sure you installed Processing 4 properly. Sometimes they won't install with the fundamental libraries. ("x"/"executable" permission is missing)
