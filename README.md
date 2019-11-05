## Mdot's Custom Trails Guide
A primer to implementing custom trails on your sabers.

This guide will not cover how to make your model / import them into unity / etc. For more information on that see [angeliod0103's Guide](https://bs.assistant.moe/Sabers/)

# Custom Trail Script

-Select the RightSaber and LeftSaber game objects and add the Custom Trail script by clicking on the "Add Component" button in the inspector.

![addingscript](Images/addingscript.jpg)

-We'll only look at the left saber for now and copy everything over to the right saber later.

-The component should look something like this :

![script](Images/script.jpg)

-Point Start and Point End refer to the points on the saber where the trails will start and end

-The trail material will dictate what the trail actually looks like

-The Color Type refers to which color the trail will follow. If it's set to Left Saber, it will follow the color that the player has set for their left saber. If it's set to Custom colout it will override what the player has set and use the color that you set yourself in the next field

-The Length determines how long your trail will be. For most trails 20 is a bit too high, so chances are you will want to lower it, but feel free to experiment beforehand


