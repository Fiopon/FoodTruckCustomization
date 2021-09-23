# Food Truck Customization
> Distributable pack to allow for creation of custom designs for the FoodTruck asset

------------
Want to make your own custom design for the FoodTrucks in VRChat worlds such as the Afterdark Arcade? Read below for a full how-to guide.

### Step One:
Download the [latest release](https://github.com/Fiopon/FoodTruckCustomization/releases "latest release") of the customization zip.

### Step Two:
If you have GIMP, skip to [step four](https://github.com/Fiopon/FoodTruckCustomization#step-four "step four").

You will want to open up `foodtruck_diffuse.png` in your preferred image editor, preferably one with the ability to multiply colors and use multiple layers. Add `foodtruck_customcolormult_PAINTJOB.png` and `foodtruck_customcolormult_TILES.png` into the editor, on layers above `foodtruck_diffuse.png`

### Step Three:
Recolor the `foodtruck_customcolormult_PAINTJOB.png` layer to whatever color you want the main color of the truck to be. Set this layer in your image editor to `multiply` so that the color transfers correctly. Repeat this step with the `foodtruck_customcolormult_TILES.png` layer to color the tiles on your design.

### Step Four:
If you do not have GIMP, skip to [step five](https://github.com/Fiopon/FoodTruckCustomization#step-five "step five").

Open `foodtruck_coloring_guide.xcf` in GIMP. There will be 3 layers named `BaseTexture`, `TilesColor` and `TruckColor` in the project. Take the bucket tool and select the color you want for the main body of the truck. Use the bucket tool on the `TruckColor` layer. Repeat this action for the `TilesColor` layer to color the tiles.

### Step Five:
Export the image as `foodtruck_diffuse.png` and then open the `foodtruck.obj` file with 3D Viewer (should be pre-installed on Windows 10 devices) to check the texture on the model. Feel free to switch back to your image editor and make changes.

### Step Six:
If you have GIMP, skip to [step eight](https://github.com/Fiopon/FoodTruckCustomization#step-eight "step eight").

Open `adverts_diffuse.png` in your image editor. Import `adverts_guide.png` as a layer above `adverts_diffuse.png` The red outlines show the edges of the visible space for your designs, add a new layer and fill in the sections as your please.

### Step Seven:
Once you are happy with your design, hide or delete the `adverts_guide.png` layer and set the layer you created your designs on to `multiply` mode.

### Step Eight:
If you do not have GIMP, skip to [step ten](https://github.com/Fiopon/FoodTruckCustomization#step-ten "step ten").

Open `adverts_guide.xcf` in GIMP. There will be 3 layers named `BaseTexture`, `VisibleAreas` and `AreaLabels` in the project. The red outlines on the `VisibleAreas` layer show what areas of the texture will be visible on the model. `AreaLabels` layer simply tells you which areas are for what part of the model. Add a new layer and create your design for each area.

### Step Nine:
Once you are happy with your design, hide or delete the `VisibleAreas` and `AreaLabels` layers, then set the layer you created your designs on to `multiply` mode.

### Step Ten:
Export the image as `adverts_diffuse.png` and then open the `foodtruck.obj` file with 3D Viewer (should be pre-installed on Windows 10 devices) to check the texture on the model. Feel free to switch back to your image editor and make changes.

### Step Eleven:
Take the new `foodtruck_diffuse.png` and `adverts_diffuse.png` textures you exported and rename them, adding your VRChat username to the beginning. Example: `fiopon_foodtruck_diffuse.png` and `fiopon_adverts_diffuse.png` (Please do not use spaces, thanks!)

### Step Twelve:
Add the 2 textures you created to a zip file and submit them in Discord.
