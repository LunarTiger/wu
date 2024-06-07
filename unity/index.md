<section>
	<h1>How to become a World Builder in Altspace Using Unity</h1>
	<p>Updated Jan 13th 2020</p>
	<div class="holder">
		<p>The official guide is <a href="https://help.altvr.com/hc/en-us/articles/115003528693-How-can-I-create-content-in-AltspaceVR-" target='_blank'>here</a>, but below is a simplified walk through and a few hints and tips.<br />This isn't a guide how to create content for your scene, it's just how to set up Unity for use in Altspace and Upload a World.</p>
	</div>
	<button class="collapsible" id="need" data-parent="need" data-child="need-child">You will need</button>
		<div id="need-child" class="innertext" data-parent="need">
			<p>An Altspace account and the Altspace client installed on PC or VR headset</p>
			<p>A "Discord" account.</p>
			<p>PC or Laptop capable of running Unity.</p>
			<p>Unity HUB and the same version of Unity as Used by Altspace.</p>
			<p>The Unity to Altspace Uploader tool.</p>
		</div>
	<button class="collapsible" id="tools" data-parent="tools" data-child="tools-child">1) Enable the extra builder tools for the Altvr.com website</button>
		<div id="tools-child" class="innertext" data-parent="tools">
			<p>First you should get included in the "Allow List", The proper way is to join the Discord channel "Official AltspaceVR",<br />
			The Easiest way to find it that is to enter "Official AltspaceVR Discord" in a web search engine.<br />
			When you have joined that Discord, look for "GENERAL Community" / "world-building" Give your Altspace username and ask to be included in the "allow list"<br />
			After you are included you will see extra building tools in the "More" button when you log in to you <a href="https://altvr.com/" target='_blank'>altvr.com</a> account using the same login details you use for the game.</p>
			<p>You might also want to enable "Early Access Program" to enable more features, these can change from time to time.<br />
			<a href="https://help.altvr.com/hc/en-us/articles/360015270793-What-is-the-Early-Access-Program-" target='_blank'>More info</a></p>
		</div>
	<button class="collapsible" id="install" data-parent="install" data-child="install-child">2) Get Unity installed on your PC</button>
		<div id="install-child" class="innertext" data-parent="install">
			<p>Download and install the "<a href="https://unity3d.com/get-unity/download" target='_blank'>Unity HUB</a>"<br />
			Run the Hub and click on "Installs" on the left side. Click ADD<br />
			The version we want might no be on the list showed, so click "download archive" to see the full list<br />
			Look for the Unity Version that matches Altspace (Current version : Unity 2019.2.12)<br />
			Click on the button that says "Unity Hub".<br />
			Make sure "Android Build Support" is ticked and click Install</p>
			<p>The Hub allows you to easy install multiple versions of Unity, and easily load projects.</p>
			<p>[Tip] I suggest making neat organised folders on your preferred storage device, like /UnityProjects2019 etc.</p>
		</div>
	<button class="collapsible" id="creating" data-parent="creating" data-child="creating-child">3) Creating a New project and adding the Uploader</button>
		<div id="creating-child" class="innertext" data-parent="creating">
			<p><a href="https://altvr.com/download-latest-unity-uploader/" target='_blank'>Download the latest Uploader tool</a><br />
			I suggest copying this to your Unity2019 folder for easy access, you need to add this tool to every project you create.<br />
			The Current version is "Uploader-0.8.6.unity package"</p>
			<p>To create a new project, Open Unity Hub and click NEW (Click the down arrow to select a specific version if you have multiple unity versions)<br />
			Enter a Project name and select the Location you want the project to save (Where you created your /UnityProjects2019).<br />
			"3D" templates should auto select. If not click "3D", then click "Create"</p>
			<p>[Tip] You can also just click Unity itself from the desktop icon to load or create a new project, but using the HUB is good practice and is very useful for opening existing or imported projects (See below for opening existing or imported projects)</p>
			<p>The first time you use Unity you should check to see the build settings are correct.<br />
			Hit "Control+Shift+b" to open the Build settings menu and check that "PC, Mac & Linux Standalone" has the Unity logo placed to the right. If not, select it and click the "Switch Platform" button. Unity should remember this from now on.</p>
			<p>The first thing you should do with a Unity project for Altspace is add the Unity Uploader, to do this Right Click anywhere in the gray are of the lower mid panel (should say assets by default) and select "Import Package/Custom Package" and navigate where you saved "Uploader-0.8.5.unity package", the click "All" and then click "import!. You should get a dialogue box asking if you want to reload or ignore the scene, you can select ignore as we haven't created a scene yet.<br />
			You can add the uploader to old projects too, but make sure you backup the project folder in case anything goes wrong. (backup by copying the project folder to another folder, or creating a compressed archive file of it like zip, rar.)</p>
			<p>[HUGE TIP] ALWAYS BACK UP A PROJECT before you continue work on it, and do them during editing sessions too, you will have to close Unity to do this, but you will be super annoyed if you spend hours working on a project then break it without backing up. Saving scenes and projects from within Unity won't save you from accidentally breaking your Scene, I and plenty of users have broken scenes often as it's easy to do!"</p>
		</div>
	<button class="collapsible" id="uploading" data-parent="uploading" data-child="uploading-child">4) Uploading your project Template to Altspace</button>
		<div id="uploading-child" class="innertext" data-parent="uploading">
			<p>So OK, you've created a wonderful scene (or a simple one which is a good idea for your first project) and you want to Upload and share it with everyone</p>
			<p>First you need to login to your account on the altvr.com website and then navigate to the "More" button and select "Templates", and Click the "Create" button<br />
			Enter the name you want to project to be called, it can be anything you like but try to help yourself later by using a memorable name<br />
			Select an Image to be displayed when selecting the Template, this is very helpful to jog your memory later by having an actual image of your template.<br />
			We are supposed to use 1920x1080 resolution images, but 1024 or even 512 seem OK to me and scale OK<br />
			Entering description is and tag is optional, but could be helpful later</p>
			<p>Now click "CREATE TEMPLATE" and the blank template is now ready to upload to from UNITY</p>
			<p>Back in Unity with your Project, click on the top tool bar Tab "AltspaceVR/Build Settings"<br />
			Enter Your Login detail (same as the Altspace client and Website)<br />
			Click "Remember Login Credentials" So you wont have to login with this project again.</p>
			<p>Makes sure Template is highlighted, Not Kit (Kit uploading is completely different than template uploading</p>
			<p>Click "Load your Templates" and the templates you have created on Altvr.com will show.<br />
			Select the template you wish to upload to (The one you just created for e, g,)<br />
			Makes sure both "Build for Windows" and "Build for "Android" are ticked<br />
			Now Finally click on "Build & Upload"<br />
			It may take some time for the build be created and then uploaded. You can check on the Altvr.com website, look at the template, at the bottom check under where it says "Uploads" and it should say how many  and when the template was created for both Android and PC. If they are missing, or say 0 MB the upload has failed.</p>
			<p>[TIP, long but important] The PC and android builds are built separately, although they are both uploaded and stored in the Same Template on the Altvr servers.<br />
			The Android version has to convert the material shaders to display properly, and this is also why it takes a long time to Build before Uploading.<br />
			You can modify a project and upload and build only the android or PC builds separately. This allows us to make a project that's more optimized for android without compromising the PC build. I personally like to create a PC version of the project first, upload that as Windows only, then make a copy the Project folder and rename it by extending the name _Mob. I can then freely change the shaders to mobile friendly shaders, and reduce the size of any image textures without effecting the project I upload for PC.</p>
			<p>Remember once you make 2 different projects, any modifications you do later will have to be replicated in both projects.<br />
			Make sure you carefully select Build for mobile or PC accordingly. You wouldn't want to over write your PC only upload by accidentally having Android and Windows ticked on the uploader when you only want to upload the Android project.</p>
		</div>
	<button class="collapsible" id="world" data-parent="world" data-child="world-child">5) Creating a world to show off your Template</button>
		<div id="world-child" class="innertext" data-parent="world">
			<p>On the AltVR website click "More/Worlds" and select "My Worlds"<br />
			If you haven't created a Universe, do so now, Worlds are created in Universes<br />
			Create a name for your Universe (its just like a folder) everything else is optional, and you can add an image or not.</p>
			<p>Now when you click "More/Worlds" and select worlds you will see your created Universe, click that and you can Click on "Create World"</p>
			<p>Create the Name, again, call it anything you like, but think about it a little, it's helpful later when you have lots of worlds.</p>
			<p>Description is what the Users will see when they look at your world from the menu or website. Sell your World in words here!</p>
			<p>Image: Make sure to add an image this time, the image should 1090x1080, it can be other sizes as it Will resize, but AltVR wont featured it, a screen shot from your project is always nice as the World Image. Look at other Worlds images for inspiration.</p>
			<p>Private: click if you only want user that you have added to the ALLOW List to enter.<br />
			Unlisted: Click if you don't want your world showing up in the menu when users search for worlds.</p>
			<p>In VR Section (I don't want to flood this guide with advanced features but this is a nice tip)<br />
			You can add special abilities to joined users who join your world<br />
			E.g.<br />
			Default Contextual Roles: pilot<br />
			This gives users the ability to enable fly or use the Fly Tool if the have two controllers</p>
			<p>Default Contextual Roles: megaphone_only, pilot<br />
			As well as pilot, we can enable them to use the megaphone, this can be an annoyance!</p>
			<p>Now Select the Template you wish to use for your World, There's a pictorial list of Template, You uploaded Template will be there, click it to select.</p>
			<p>FINALY!  Click on "Create World"</p>
			<p>Now go into Altspace, In the main menu select "Worlds", "My Worlds" and admire your great work!</p>
		</div>
	<hr />
	<h1>A few Extra Tips to help create Worlds</h1>
	<div class="holder">
		<p>Its very tempting to add everything you find that's amazing on the Asset store or other sources of models and scenes into Altspace BUT!<br />
		Unity is a pretty optimized game engine, but it still has a lot of limitations. You have to careful not to overload users with huge mesh and textures.<br />
		This is especially so with mobile users (GearVR, Go & Quest). Altvr have guidelines that are pretty tight if you want a World featured, however you can freely break these guidelines and find a world is still playable for many users. It's wise to check the FPS with an Oculus GO or Quest and use that to guide you. AltVR wants you to keep above 70 FPS to feature for an event, but for other use try to keep above 50, 40 is going to be bad if you have more than a handfull of users.<br />
		If you are PC based or haven't got a mobile HMD, ask someone with a Quest to check for you. In the Game menu select "Display" and "show Oculus FPS".</p>
	</div>
	<button class="collapsible" id="noscript" data-parent="noscript" data-child="noscript-child">Altspace Does Not Allow Scripting!!!</button>
		<div id="noscript-child" class="innertext" data-parent="noscript">
			<p>I know this is super sad, most people into Unity get excited about making dynamic scripts to make GAMES!<br />
			And scipting would greatly benefit Altspace content and it's users, but the servers interrogate the Uploads and generaly reject any Templates with Scripting.</p>
		</div>
	<button class="collapsible" id="optimisation" data-parent="optimisation" data-child="optimisation-child">A Word on Optimisation</button>
		<div id="optimisation-child" class="innertext" data-parent="optimisation">
			<p>It's the most important strategy any World Builder should consider!</p>
			<p>One of the most effective optimizations is texture size, these are the images added to materials to apply to your models.</p>
			<p>Try to keep them under 2k resolution (2048x2048) for PC, and Under 1k (1024x1024) for Android.<br />
			I would suggest going down in size till you can't bear how pixelated the texture looks on your models.<br />
			Even if a texture looks pixelated close up, it might look fine from a users typical position.</p>
			<p>Keep the pixel size (resolution of the image) to a power of two,<br />
			(e.i. value doubles evey iteration: 1,2,4,8,16,32,64,128,248,512,1024,2048,4096 etc.)<br />
			The way Unity assigns memory for an image is to allocate a block, it will fit a block to fit your image in Power of two<br />
			So if you have a image with a resolution of 1000x900, Unity will allocate 1024x1024 in memory.</p>
			<p>If you have an image of 1025x1024 it will allocate the next power of two, 2048x1024!<br />
			You should therefore resize that image to 1024x1024.</p>
			<p>Resize all of your images down to fit neatly into a power of two, no matter what the ratio of the image is.<br />
			Any image ratio can be restored by stretching the object in your Unity scene that has the material applied.</p>
			<p>Always scale down, not up. And remember the power of two can be different per axis.<br />
			(e.g. Image = 1300x650, I would resize that to 1024x512)</p>
			<p>It's common to have a PC Texture 2048x512 and downsize the Android version 1024x512, or even 1024x256.</p>
		</div>
	<button class="collapsible" id="opening" data-parent="opening" data-child="opening-child">Opening Existing or Imported Projects</button>
		<div id="opening-child" class="innertext" data-parent="opening">
			<p>Always use the HUB to open an Imported, Ripped or Older Unity project that isn't on the list when you start Unity.</p>
			<p>In the HUB click "ADD" and navigate to the project folder that contains the "Assets" folder, dont navigate into the Assets folder itself.<br />
			Click "Select folder". The in HUB select the version of Unity to open the project if its not already set.<br />
			Just Click on the project name in the HUB to load the project.</p>
		</div>
	<button class="collapsible" id="colliders" data-parent="colliders" data-child="colliders-child">Nav Mesh and Colliders</button>
		<div id="colliders-child" class="innertext" data-parent="colliders">
			<p>Often your Imported 3D Objects won't have a collider, or Nav Mesh selected.</p>
			<h2>Collider</h2>
			<p>If you want an Avatar not be able to walk through a wall, or not fall through a floor, or stand on an object (for example), you would want to add a "collider" to that object. You can either attach a "Mesh Collider" on an object which attaches a collider to every facet (polygon face) of the Object, this can be very costly to performance if your object is highly detailed. Or you can create simple geometry in Unity or your 3D visualization software like Blender to add to your scene, and then add a collider to it.</p> 
			<p>If your Floor or walls (for example) are just a simple plane's or Quads that are detached from the rest of the the model (Selectable by themselves), you may as well just attach a "Mesh Collider to them", But if they are part of a much more detailed object you should instead create a "Quad" and add a Mesh Collider to it. Then turn off Mesh rendering so the object is not visable, but the collider will still work.</p>
			<h3>To Create A Quad</h3>
			<p>A Quad is a simple Square object made from two triangles<br />
			In the Hierarchy Window, Right Click and select "3D Object" and then "Quad"<br />
			In the Inspector panel Change the X Rotation to 90 to Aim the face Upwards, or alter for what ever angle you want.<br />
			You can use the Widget with Arrows in the Scene Window, or manualy type in the Inspector Panel to set Position, Rotation and Scale<br />
			The Quad Automatically adds a mesh Collider, You just have to Untick "Mesh Renderer" to make it not visable.</p>
			<h3>To attach a Collider</h3>
			<p>Select an Object in the "Hierarchy Window", The look at the "Inspector Window", At the Bottom click "Add Component"<br />
			Select "Physics/Mesh Collider"</p>
			<h2>Nav Mesh</h2>
			<p>Nav Mesh is Layer applied to the Object that tells Unity if the Object is navigable, If you want Players to use their Cursors to Telport, you can to make sure to switch the Mesh Layer from "Default" to "Nav Mesh". If you Teleport on to an Object that is not Nav Mesh, it will just send the Avatar to 0.0.0 in the scene.</p>
			<p>To Set Nav Mesh on: Select an Object in the Hierarchy Window, then look at the Inspector Window for "Layer" The drop down list should contain "14.Nav Mesh"<br />
			You can change this to Default if you wont to dissable Teleporting.</p>
		</div>
	<button class="collapsible" id="shaders" data-parent="shaders" data-child="shaders-child">Shaders</button>
		<div id="shaders-child" class="innertext" data-parent="shaders">
			<p>Materials use a selectable "Shader" to attach Textures and add effects.<br />
			Unity automaticaly selects "Standard" Shader When you create a Material, But Standard does not mean Simple!<br />
			The more features a Shader offers, the most costly the performance, And "Standard shader offers a lot of features.<br />
			Most of the features would not be required on your object, Such as "Specular Highlights" or "Reflections" which are enabled by default. It also has slots for multiple types of textures to create complex material effects.</p>
			<p>The problem with Standard shader is that all this complexity requires a lot more processing by the VR Headset, and you will most likely not require the effects anyway. There's a drop down list of Shaders, In that list are a selection under "Mobile". The Mobile VertexLit Shader is very simple and thus much more performant.</p>
			<p>You might require more features, so always study what Shader gives you the functionaly your require, and no more.<br />
			Shaders require a guide on ther own to explain all the features, there's good guides online if you search "Unity Shaders"<br />
			Shaders can be imported from the "Asset Store", but ones with additional Scripting will be rejected if you upload them to Altspace.</p>
			<p>Inbuilt Shaders (Just a few optimal performers, great for mobile)<br />
			&nbsp;&nbsp;-Unlit Color = very performat, great for objects not effected by scene lighting, like Lit light bulbs.<br />
			&nbsp;&nbsp;-Unlit Texture = As above but allows a simple Albedo Texture, Nice for lit Signs.<br />
			&nbsp;&nbsp;-Mobile/VertexLit = As above, but by lit by the scene lights.<br />
			&nbsp;&nbsp;-Legacy Shaders/Diffuse = My fav!, It allows a texture and a color tint. Great for darkening with grey colors too.</p>
		</div>
	<button class="collapsible" id="faq" data-parent="faq" data-child="faq-child">FAQ</button>
		<div id="faq-child" class="innertext" data-parent="faq">
			<p>I will create an FAQ and add it here for other common issues as you make me aware of them.<br />
			If you want any general advice for World Building don't hesitate to ask for Help on the Discord channel.<br />
			If you have any specific questions about this guide, Message me on Discord. My User ID is: <a href="https://discordapp.com/users/339873153750925316" target="_blank" id="discord" data-parent="faq">Andy Wood#9633</a></p>
		</div>
	<hr />
	<div class="holder">
		<p>This page was made possible by the efforts of Andy Wood. The original document this was based on is avaliable <a href="https://github.com/DjVivid/Altspace-Creation/blob/master/How%20to%20Use%20Unity%20Uploader%20for%20Altspace.txt" target='_blank'>here</a></p>
	</div>
</section>
<script src="/assets/js/collapsible.js"></script>