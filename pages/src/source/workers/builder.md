---
type: worker
worker: builder
layout: worker
---
{% infobox_worker %}
The Builder is the **MOST** important worker in your colony. As long as you provide the Builder with all the resources they ask for, they will build and upgrade all of your town buildings, workers' huts, decorations, and your personal schematics.

## Building A Hut/Schematic
**Before you build *any* building, you need to build the Builder's Hut. If the Builder’s Hut isn't built, the Builder cannot build any other building.**
Buildings are constructed after the hut block/schematic is placed using the Building Tool and the green checkmark clicked. If it is a hut, you must right-click on the hut block, click Build Options, and then click Build Building. Only then will a build request be created (indicated in chat). An available Builder will accept the request (also noted in chat), and head off to clear the land and start building. They will stop building if they run out of materials and will then head back to their hut and request more.

## Notes
- The Builder will not start another build assignment until they have finished the current one.
- The Builder can *ONLY* upgrade other huts to the level of their Builder’s Hut. Upgrade the Builder’s Hut to further upgrade other buildings.
- You can rearrange the priority and cancel the build requests in the <a href="../../source/buildings/townhall">Town Hall</a> GUI under the Work Orders symbol (!).
- The Builder will collect most  blocks they remove and deposit them in their hut inventory and any racks in their hut. However, some blocks (e.g., ore blocks and glass) will be lost, as well as item drops that are not picked up in time.

If you see the Builder has not finished building/upgrading any build order and they aren't asking for any materials, go to the Builder’s Hut and recall the Builder and wait a bit to see what they need. You can also go to page 2 of the Builder’s Hut GUI and check the list of materials required. Any material in the list that is missing will be in red.

If a build request is created but no Builder starts building, the building may be out of their range (which is 100 blocks from their hut). Cancel the build order, then go to Build Options of the hut you want to be built and manually assign a Builder (top right).

If the build order is within their range and they still aren't building it, check if you've set them to Manual on the third page of their hut GUI. If you have, you'll need to choose build orders for them yourself (also in the third page of their hut GUI).

The higher a Builder's Adaptability skill, the faster they'll place blocks. Similarly, the higher their Athletics skill, the faster they'll break blocks.
{% endinfobox_worker %}

## Build Options Details

### Before Hut is built

{% content_block image="../../assets/images/gui/newbuild.png" image_alt="New build GUI" cols=6 %}
- **Schematic style:** Here you can verify the style of schematics you have currently. You can change the style, but it's not recommended that you change it since it will most likely be in a different position.
- **Builder:** Here is where you can choose what {% worker_link builder %} you want on the project. If the hut is out of your {% building builder %} range, this is where you can manually assign one.
- **List:** This is the list of resources that the Builder will need for the schematic style selected.
- **Repair:** Not needed, as the building hasn't been built yet.
- **Build Building:** This is where you tell the Builder to build the building with the style selected.
{% endcontent_block %}

### After Hut is built

{% content_block image="../../assets/images/gui/upgradebuild.png" image_alt="Upgrade build GUI" cols=6 %}
- **Schematic style:** Here you can verify the style of schematics you have currently. You can change the style, but it's not recommended that you change it since it will most likely be in a different position.
- **Builder:** Here is where you can choose what {% worker_link builder %} you want on the project. If the hut is out of your {% building builder %} range, this is where you can manually assign one.
- **List:** This is the list of resources that the Builder will need for the schematic style selected.
- **Repair:** This is to repair a building according to its schematic. This will remove any changes that a player has made to the current building.
- **Upgrade:** When you are ready to upgrade to the next level. Upgrading will come with benefits, like more furnaces for a {% building_link smeltery %} to use.
- **Deconstruct:** To deconstruct the building. After the Builder is done breaking the building, click the Pick Up button, which will appear where the Deconstruct button was. You will get the building's hut block, which will keep its current level. This is so you can place it somewhere else using the [build tool](../../source/items/buildtool).
{% endcontent_block %}
