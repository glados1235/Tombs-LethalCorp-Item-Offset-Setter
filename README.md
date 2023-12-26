# Tombs-LethalCorp-Item-Offset-Setter
I made This very simple tool to make setting item offsets for your created items easy as moving it into position and clicking a button!


to use this simply import the unity package into your [Project Template](https://github.com/EvaisaDev/LethalCompanyUnityTemplate) and open the OffsetScene that is included.


then drag the prefab of your item into the main Hierarchy and **NOT** in the **ScavengerModelArmsOnly** item, this makes sure your prefab is world-scaled and the correct size.


you then drag the prefab under the **LocalItemHolder** empty under the **Sholder.R > Hand.R** bone chain, there is a capsule there called **TemplateItem** for reference. after your prefab is under the **LocalItemHolder** zero its **Position** and **Rotation** then move it to where you want on the hand! once it's positioned to your liking open the **"Tombs LethalCorp Item Offset Setter"** wizard tool from the **Tools** menu in the top **Menu Bar**.


drag in your prefab into the **Source Object** box and drag your Item into the **Target Item** box, then simply press **Set Position and Rotation**!


that should be it, keep in mind the rotation values **MAY** have different numbers due to the quaternion conversion but they will result in the same rotation in game.

keep in mind this asset relies on both the [LethalCompanyUnityTemplate](https://github.com/EvaisaDev/LethalCompanyUnityTemplate) and that you have used [AssetRipper](https://github.com/AssetRipper/AssetRipper) on the base game to retrieve the game assets otherwise there may be missing meshes/textures in unity!
