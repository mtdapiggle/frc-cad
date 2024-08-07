![image](https://github.com/user-attachments/assets/dbd7e4a8-6e01-4a87-9d1e-e9653c51e58a)# frc-cad
bad frc cadding (top tier frc cadders number one fear)

# session 1:
i wanted to make a full frc robot (that may look good on paper but will probably go badly in real life), without knowing how to (it's bound to go well.) i decided to start this by planning what kind of frc robot i wanted to make. after like 15 minute of pondering and looking at game animations, i chose 2020/2021, because it looks easy (probably isn't.) 
i then scoured chief delphi for different types of subsystems and pick the ones that i want/would be feasible for me to cad/would be effective
https://www.chiefdelphi.com/t/971-spartan-robotics-2020-2021-reveal-video/394078
this one is by 971, Spartan Robotics, but i can't really get a good idea of how their hopper kinda works, but their intake, indexing and shooting i can kinda understand.
https://www.chiefdelphi.com/t/frc-6328-mechanical-advantage-2020-2021-build-thread/370409/139 
this one is from 6328, Mechanical Advantage, and i can get a good picture of how it works, since they show cad pictures and i think have a cad file to look at. 
https://www.chiefdelphi.com/t/team-4414-hightide-2021-robot-onshore/392989/1
this one is from 4414, Hightide, and i don't know which robot is their main robot. i can see their intaking and shooting but not much of indexing/hoppers.
https://www.chiefdelphi.com/t/frc-95-the-grasshoppers-2024-build-thread/442176
this one is from 95, The Grasshoppers, and they provided an onshape link which helps me in seeing how their robot works. it also kinda takes a long time to load.
https://www.chiefdelphi.com/t/team-254-presents-dreadnought-2020-2021-technical-binder-q-a/395066/1
this one is from 254, The Cheezy Poofs, and a tech binder, where they explain how their robot works/how different subsystems work.
https://www.chiefdelphi.com/t/2910-ir-h-robot-design/391977/1
this one is from 2910, they have a grabcad i think, and they have a good picture of their robot, and i can see how their shooting, indexing and intaking works. 
https://www.citruscircuits.org/ccwp2020-2021.html
there's also 1678's cad release, they also cadded a bunch of other robots, so i can look at them if i need to check some things. 
i think that i'll be diong something like 2910's indexer, since 971's indexer is a bit tall. i also think that 6238's hopper design is good, since it looks simple and easy to do (watch as it's extremely hard) a bunch of these teams also used a shooter that could change the angle that it would shoot at, but i  think that's way above my skill level. maybe if i get better, i could do it, but i don't entirely know if i can, so i think i'll just be doing a fixed angle shooter. intaking is also quite interesting, i'm  not sure what i want to do for that just yet, but i think it'll be over the bumper, since through the bumper probably won't go too well for me, and i don't want to cut an entire section of a drivebase out (and i'm  not sure how swerve would go with it.)
also, i'll probably visit 254's tech binder quite a bit, since it goes into some detail about strategy n stuff.

# session 2:
ok so first thing that i have to do is make a drivebase, i also want to be able to change the size of the drivebase when i import it, although it isn't very useful since most frc teams will keep the same drivebase from year to year, and that you probably only need to cad the drivebase once, i just wanted to do it as an extra challenge/more pain. 
i wasn't sure how to make it to be changed, at first i thought it was variables but then i realised that i wouldn't be able to change the size if i was in another onshape document and attempting to import it in. 
i tried to search up how to make one, but it took me like 10 minutes straight because i had like no idea what to search up. i literally had to seach up synonyms for "change" or "adjust"
i searched up "how to configure parts in onshape" and it came up with what i needed. 
this link here:
https://cad.onshape.com/help/Content/configurations.htm
was really good because it told me how to use it, although i skim read it and didn't understand, only when i actually forced myself to read carefully (after 5 minutes) it kinda made sense. 
![image](https://github.com/user-attachments/assets/cd3c15eb-5591-41da-a91f-2ab9398f67fa)
i sketched this temporary drivebase tube, until i could figure out how to make it configurable. i started messing around in the configuration panel/table to see what can work, but i couldn't really get it to work. i forced myself to read through it a bit more and found this
![image](https://github.com/user-attachments/assets/46100400-aeaf-47b5-97e6-b398a849ab4c)
specifically the configuration variables, this was definitely what i needed. (i didn't look at the dropdown menus/dropup menus when i probably should have.) i then had to search up the maximum and minimum sizes of a drivebase, which i don't remember. it didn't give me an answer, so i had to look at the frc game manuals (which are really long)
![image](https://github.com/user-attachments/assets/2f59dc34-050a-40b6-b99e-c2c0b97eaf9b)
i found this, which i think means that the perimeter can't be larger than 304 cm or 120 inches. there is no minimum size from what i can tell, but i think it probably shouldn't be too small though. 
![image](https://github.com/user-attachments/assets/8f1b1e43-f666-4c6e-a258-f53c3001991e)
oof ok. i can't get it to automatically convert stuff for me.
![image](https://github.com/user-attachments/assets/17203213-ff53-473e-bd19-036e38c58542)
i didn't knkow what to do from here, since it didn't have anything about configuring features. 
ok, so i'm really dumb, i didn't realise that it was a variable that you put into things for it to work. i tried to subtract 214.6 mm from it (to account for swerve modules) but it said that i can't subtract.

# session 3:
i tried to subtract it when making the variable
![image](https://github.com/user-attachments/assets/74df74c0-af8f-4b67-921b-678658e31780)
it didn't entirely work. i checked the page about configurations and it didn't help. i could just input it as the correct length myself, but i want to be kinda lazy.
https://www.youtube.com/watch?v=S5oKJOz_JJo
i found this video, and i watched the entire thing, it seems that it is? possible to put expressions and stuff in variables, but i don't think it can work with the input variables.
![image](https://github.com/user-attachments/assets/9cde54f2-73d4-4363-b91e-4d1c84b71ff1)
i can do this in variable tables, but it just doesn't work for input variables
![image](https://github.com/user-attachments/assets/5f2672be-1430-43e3-a7c7-cf19520e674a)
what the flip... what am i meant to do...
![image](https://github.com/user-attachments/assets/fb847a2e-3bd0-44b5-b602-6ea15199c287)
WHAT. WHY. WHY DOES IT JUST RANODMLY WORKKKKKK
![image](https://github.com/user-attachments/assets/7ae11412-d464-4ab8-8df9-22aec94349e2)
ok so it doesn't just randomly work.
![image](https://github.com/user-attachments/assets/7c1876d8-d2b5-40bc-a586-de1ba69cb088)
ok well, after like the full hour of slowly losing my mind, i finally figured how to make it sorta work.
![image](https://github.com/user-attachments/assets/edb8d205-013b-4533-96e6-0bb387919690)
ok so it doesn't recognise it as a variable, weird.
![image](https://github.com/user-attachments/assets/8d2cd77b-a96a-4517-b7a2-33f7475f6cc4)
i moved it and now it's a variable. yipppeee.
![image](https://github.com/user-attachments/assets/f9ea67b6-e256-4161-a3ca-4c20d9072a6c)
ayeee it works !

# session 4:
now i needed a way to be able to make holes in the drivebase tubes that aren't oddly spaced out, since my worry with linear pattern is that it's going to be quite wacky. 
![image](https://github.com/user-attachments/assets/2ca0c0ae-1f7a-4be4-8bd8-f82d77ee4268)
i tried to make some kind of formula for it, but it doesn't really work. i think that's because it's a decimal number returned. i don't know how to not make it wacky, which sucks.
![image](https://github.com/user-attachments/assets/6702eeaa-6a51-41b7-be09-d75e3d6e455e)
so i gave in and just used the tube converter featurescript to do it.
![image](https://github.com/user-attachments/assets/ff163b63-093c-4235-bd0f-8cf13564668c)
everything  has been assembled... then i realised, i forgot the bumpers. i didn't really know how to formulate it, so uh yeah, that's a problem for later.

# session 5:
![image](https://github.com/user-attachments/assets/7f62e747-f954-4670-b7d2-5363fbbc5e8c)
i sketched the profile of the bumper, and now hda to try and come up with a formula or a way to make the bumpers change with the size of the drivebase. 
![image](https://github.com/user-attachments/assets/39cc5467-38c2-4c9c-99de-ef34076d82d0)
this should work.
![image](https://github.com/user-attachments/assets/a32c387c-f26b-43e4-83c5-1ae541cd8201)
something is wrong, and i also need to make the bumpers a bit higher.
![image](https://github.com/user-attachments/assets/bd275d1b-1b05-46d0-8d4e-da477373601f)
i don't know how to fix this. i probably need to reduce some dimensions, but i don't know by how much.
![image](https://github.com/user-attachments/assets/bcbbda00-8137-4b86-9172-338e0dc9d7b8)
this might work, but i'm not sure if it will.
![image](https://github.com/user-attachments/assets/11e9c2ce-f8a1-497b-94f3-b4d194cd63b3)
as expected, it didn't really work out well.
![image](https://github.com/user-attachments/assets/181451da-40f3-4ec1-95d5-c44f5b82e8bd)
ok so i got something big wrong, which is how i accounted for the swerve modules. i don't think i accounted for them correctly.
![image](https://github.com/user-attachments/assets/caf47710-b5ed-4ac5-a26e-2563ae334d46)
welp ok.
![image](https://github.com/user-attachments/assets/c9ee6ddf-1359-4432-9e52-60176b3dfaf8)
uh oh.
![image](https://github.com/user-attachments/assets/cc26291e-fb24-4f5e-89a6-3393e3949592)
now it fits nice and snug. (well i think that it would)

# session 6:
https://cad.onshape.com/documents/1a55ea4feea5b5a643d644af/w/624c779a72b46dcdaae9ccdb/e/882091ea1ff72d082defb0c9?configuration=Tube_Length%3D0.6%2Bmeter&renderMode=0&uiState=66b321c400147d2c44e0492e
here is the link to the configurable scuffed drivebase if you want it.
i then began work on 6328's hopper in a different document, because i wanted to keep the configurable drivebase as sort of a stand alone thing.
![image](https://github.com/user-attachments/assets/9f94c8f6-e3b9-4d1e-a918-52936dbf83d0)
i tried to insert the configurable drivebase, but... it doesn't work/???
![image](https://github.com/user-attachments/assets/82806d59-ab00-441a-bcaf-eaa7cdf05eeb)
uh... what's going on???
![image](https://github.com/user-attachments/assets/2718b73e-7850-43ee-a221-dc03e91b82b1)
why does it just suddenly work now??? i'm very confused.
![image](https://github.com/user-attachments/assets/2879e53e-8f62-4d8f-9f51-bc4b57edacda)
how do i give it edit permission
![image](https://github.com/user-attachments/assets/eec8c389-5b8b-4e86-a6f1-4f45d5cbf762)
this is what shows up when i click "show details". 
![image](https://github.com/user-attachments/assets/d0decc69-25a6-40f3-a7bc-3296bf5f95e3)
ohhhhhhhh ok
![image](https://github.com/user-attachments/assets/e93c4834-dc64-40dd-96a0-c762ed9271e2)
the bad thing is, is now i don't know how to make the permissions into edit.
![image](https://github.com/user-attachments/assets/6bc16ae5-4475-4f4f-8b51-b8779e8abf4c)
what ???
![image](https://github.com/user-attachments/assets/edc2911c-8be6-4a98-9065-f72305de27b0)
ok all i needed to do was make it versioned. AHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHAOSIFDJSALK;DFADKASDJFALSF;ASJF;ALSDJFASFAKSLFJA;LD

# session 7:
i realised that i had used the wrong configurations for the swerve drrive modules which will take at least 15 minutes to fix all of the fastens and the configs.
![image](https://github.com/user-attachments/assets/82189d2a-1a3b-4a04-ba14-2c08352fe0fd)
i also realised, that i had to adjust the height of the bumper again, since the configs had changed. i changed it, checked the rules and realised it had to be lower. i also decided to make a red and blue bumper configuration, and maybe a grey one for just any. 
![image](https://github.com/user-attachments/assets/d1e867e1-8e89-4204-a0b1-3b947758f598)
it looks like the tube goes slightly into the bumper, also generating the different coloured bumpers only changes it in the part studio, not the assembly.
![image](https://github.com/user-attachments/assets/64174072-03e4-4f9b-b012-18283a53aa5e)
just more things going wrong.
![image](https://github.com/user-attachments/assets/9c4fd717-0a8a-4e25-bf46-6de88f7733fe)
things are still going wrong.
![image](https://github.com/user-attachments/assets/ad6491b0-0f5c-4c0f-abf0-8491fa0b56f1)
why it no work !!!
![image](https://github.com/user-attachments/assets/e528332d-8ac3-4171-a803-f2d0a626fecc)
uhasdfajksf;ldsajflak;;fd
i have no idea on what's making it go wrong
![image](https://github.com/user-attachments/assets/11201636-fc2a-40e3-b4c6-1f050ba77644)
![image](https://github.com/user-attachments/assets/a117a4f9-59e1-46e7-9d49-6a279f4a644a)
WHATTTTT
![image](https://github.com/user-attachments/assets/8180d67a-95e6-4f31-ac1c-d8f2ccbbbf9f)
ok everything makes sense now.
![image](https://github.com/user-attachments/assets/481013e0-eadb-406b-8029-9420388283a8)
i extended it to 400, to check if it was a problem with the bumpers.
![image](https://github.com/user-attachments/assets/2467150b-22d4-4718-a92d-5c1e4b583e39)
HOW DID IT SHRINK???
![image](https://github.com/user-attachments/assets/723fa6cd-b869-45c1-90c9-c8c325ec8b12)
why does it still not work... i adjusted everything... WHY ISN'T IT WORKINGGGGG
![image](https://github.com/user-attachments/assets/7fbcc1bd-f0ff-4902-8377-8eaa90cbe72e)
