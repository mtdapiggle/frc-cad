# frc-cad
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

# session 8:
why bumper break
![image](https://github.com/user-attachments/assets/101e91c1-7d6e-4e78-ab5a-0800a3a81977)
i adjusted the formula, and it still isn't right.
![image](https://github.com/user-attachments/assets/c518bf1a-9379-43dc-a56a-6dfc56de9aa5)
why won't this worrkkkkkkk.... after pondering this for like 10 minutes straight, i realised that it must be how the tube converter featurescript calculates holes and stuff. the length of the tube can change, but the positioning of the  holes won't change, unless it has enough space to add a hole, or it has too little space and removes a hole. i don't think there's really a way that i can change this, though.
![image](https://github.com/user-attachments/assets/27bcac86-6b4b-4c82-a1ac-0a7bfbfa7d92)
i may be able to tweak the pattern start and end margins and see if i cna make it work that way.
![image](https://github.com/user-attachments/assets/a5c71576-805b-4200-98b8-be7f8ee199eb)
OHHHHHH NOOOOOOOOOOOOOOOO
![image](https://github.com/user-attachments/assets/a5e5fdaf-5101-4532-94c8-afdca0189ab9)
luckily though, all i had to do was change the secondary axis of all of the fasten mates.
![image](https://github.com/user-attachments/assets/f3d79795-0c11-466d-8db1-5d4259b72029)
i think it's because i reduced the size too much, and now it's broken.
![image](https://github.com/user-attachments/assets/0ba5e955-bc20-4967-8c5a-14c7ad9152d9)
i don't think i can ever get it righttttttttt
i have no idea how to fix this, because of the way that the tube converter works, i don't think it's possible to make a configurable drivebase. i don't even think that it's possible, even with doing it normally. unless, an idea that i have works (which it probably won't.)
![image](https://github.com/user-attachments/assets/75a0f46c-8a6f-4e4f-ba0e-cd4c0fc8ee76)
so the plan was to section off an area, and then put some holes on it, that will always stay in the same place.
![image](https://github.com/user-attachments/assets/eb49904e-5899-443a-bbb8-a7fef7d5da43)
NOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO
it doesn't work...
![image](https://github.com/user-attachments/assets/7c9dab4c-10d6-48f4-b213-3d0b1a901907)
i added 7.5mm to try and neutralise the wackiness.
![image](https://github.com/user-attachments/assets/53debf0d-0e14-4086-9bd0-6f73e57f7677)
ok, now i need to test if other lengths work.
![image](https://github.com/user-attachments/assets/e6e52a56-96ba-4e6f-9cab-7d533580279b)
cmon surely nothing goes wrong.
![image](https://github.com/user-attachments/assets/b0915984-3045-4972-9760-1d352068e788)
uh what. oh wait it only changes when you insert it.
![image](https://github.com/user-attachments/assets/351db575-da45-4918-971e-408912ba4c47)
well that's no good. it's my bedtime, and i can't fix it right now. 

# session 9: 
i was thinking about how to make bumper colour changes when i went to sleep, although without being able to access onshape, i couldn't really test any of my things, or play around with settings and stuff. 
i had an idea to make an assembly configuration, which took the list input from the part studio
![image](https://github.com/user-attachments/assets/c40a1e41-76cb-4a87-b515-a744263a9781)
![image](https://github.com/user-attachments/assets/4a118765-4cc0-406d-bb6f-78893f188dc3)
it workkkkssssssss !!!!
i also went back to fix the holes that i couldn't fix before. 
![image](https://github.com/user-attachments/assets/4b593963-896c-41d8-ba0d-98277c341e21)
all i had to do was select the holes as exclude regions, because i think if tube converter sees any open area to place the center of a circle, it will. 
![image](https://github.com/user-attachments/assets/a3704c21-1bac-4f09-8573-09aef694aab1)
that's not good. 
![image](https://github.com/user-attachments/assets/f78d9b2a-01a5-4686-9564-b93f5bcee130)
well, ignoring that for now, the configurations work ! they are the correct size that i want them to be, which is really nice. 
![image](https://github.com/user-attachments/assets/8157745d-21fb-4e3b-ba1c-bc1341f85598)
ok so apparently the bumper thing was just a one off bug.
![image](https://github.com/user-attachments/assets/07e97532-3c54-44b5-9f60-7de225d4a91d)
ok so now i'm trying to work on a way to make the size of the drivebase configurable when you import it, because you can only configure the size of the tubes in the part studio, not the assembly, and the whole aim of this was to save time when making a drivebase. 
![image](https://github.com/user-attachments/assets/d3ea0d46-a6ec-4343-98b5-fecc8324bdaa)
it seems like assembly configuration variables don't show up in part studio variables. i can't even use it on sketch dimensions and stuff. 

# session 10:
i'm kinda confused on how i'm meant to do this.
![image](https://github.com/user-attachments/assets/7c221a51-a575-4fd5-801c-49a4b20c8d60)
NOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO..... 
well, it looks like i can't really make it configurable for the assembly, so i guess it'll stay that way. 
i changed the name of the document to configurable drrivebase tubes, because it seems more fitting that way.
https://cad.onshape.com/documents/1a55ea4feea5b5a643d644af/w/624c779a72b46dcdaae9ccdb/e/f824f45ba70116fe80c668a3
here's the document.
![image](https://github.com/user-attachments/assets/3eee0174-aef8-4e8b-97a1-fbfa616cb9be)
thattt'sss a bit low...
i fixed it quickly, and moved onto the hopper/indexing stuff. 
i wasn't really sure where i wanted to mount it so i just randomly put it somewhere on the drivebase.
![image](https://github.com/user-attachments/assets/9e4bf85a-332c-4248-b5e0-bf0d473e7b6b)
i sketched this shape out, and added some dimensions that i felt would look right. i also used https://www.reca.lc/belts to calculate belt distances for the pulleys n stuff. (the larger circles are the size of the pulleys, the smaller ones are for bearings.)

# session 11:
really on that cad grind rn, locking in.
i didn't really want to constrain the hopper to anything just yet, since i didn't know where i wanted to put my intake and stuff. 
![image](https://github.com/user-attachments/assets/0aed544f-37c9-47da-abbd-1b472d3048a8)
i sketched out teh extra features of the hopper. which are:
![image](https://github.com/user-attachments/assets/c103354b-b846-40e7-b8c4-bdae40efa691)
the blue bit, and the red part. i assume the red part is used to save weight on the hopper/use less material. the blue bit i think is to keep the pulleys in line with each other (as in, make sure that the pulleys don't fall out/go random places), and to stop the balls from going over the belt. 

# session 12:
i started this session out by sketching the path that i kinda want the ball to take. it's gonna be quite scuffed
![image](https://github.com/user-attachments/assets/ab0fb7f7-e6db-4432-b706-148dc9986f65)
ok so i wanted the balls to go over the bumper, and over the swerve modules so they don't get damaged. i then kinda followed 2910's way of indexing balls, by making it a bit of a snake.
![image](https://github.com/user-attachments/assets/81a6b378-461f-4f06-883d-291ba034b9d9)
the snake is quite scuffed, the line above the snake is the bottom of the trench run, which i would hopefully like to get under, but that may not be able to happen, unless i make an adjustable angle shooter (which is too hard for me, although i could look at examples)
![image](https://github.com/user-attachments/assets/0699435a-3964-4057-a8a8-4f751f43c1b1)
i then added an outline of how the indexer would look like. i also added a line for where the hopper stopped. 

![image](https://github.com/user-attachments/assets/0302ef43-faaf-4e0c-9ff0-98d86861ce45)
uhhhhh.... pretty sure it's meant to end?

# session 13:
i didn't entirely know where i wanted to go from here, so i just started making some gearboxes for the hopper/figuring out gear ratios n stuff.
i decided that high torque and low-medium rpm would probably be best for the belts, i looked up some gear sizes from https://wcproducts.com/collections/belts-chain-gears/products/aluminum-hex-bore-gears
i also needed the pitch diameter, but i realised that i could calculate it by dividing the gear tooth amount by 20, since 20 is the diametrical pitch (aka DP)(basically diametrical pitch is how many teeth per inch of diameter, so if it's 20 DP, and the gear has 40 teeth, its pitch diameter would be 2 inches, and yes it's in inches, but onshape automatically converts inches to mm, which is nice.) (pitch diameter is basically the area where the gear will mesh with another gear.)
i decided on 72:12 or 6:1, with the 12 tooth gear being the driving gear and the 72 tooth gear being driven. 
![image](https://github.com/user-attachments/assets/5504c04f-0a1b-4101-87df-029014323f41)
![image](https://github.com/user-attachments/assets/e96dce8e-074d-49f7-ab75-d97f61bc02a5)
i added holes for a neo v1.1 or v1, bearing holes for the gears, and holes for spacers and stuff. it's quite scuffed, but i feel like it'll do for now. i might also add part lightening later.

# session 14:
i started off by making a couple of belts, and then extruding the small part out.
![image](https://github.com/user-attachments/assets/6964becb-4536-45a2-94fe-c7575302b817)
![image](https://github.com/user-attachments/assets/f21ce225-346d-4a89-91a5-a42cccbb28ff)
then i tried making some part lightening ribs/where i wanted the ribs of the part lightening to be.
![image](https://github.com/user-attachments/assets/0185eee6-5543-48d2-b7da-07f0d435a09d)
i don't really like the look of this, because some things are just hanging off, and it didn't even follow all of my part lightening ribs. 
![image](https://github.com/user-attachments/assets/9ba60914-23c3-4523-903f-86d50e1cbe01)
surely it looks good, surely !
![image](https://github.com/user-attachments/assets/3b9775d5-36de-4c11-8b1a-1565dd3b4948)
it's pretty much the exact same, even though i added some more lines for ribs. this really confuses me right now.
![image](https://github.com/user-attachments/assets/fc20ac59-a206-4f3f-b480-1c5e55c3f10c)
btw, this is what it looks like right now. 
i have no idea how to fix this, so i just started to think about what areas i want fixed.
i wanted the area in the middle to be fixed. (the neo holes, and the bearing holes)
![image](https://github.com/user-attachments/assets/e87a44f1-51e0-4d78-a6e8-40376ee47a58)
yiiiiiipppppeeeeeee !!! although, there are a lot of problems right now. 
![image](https://github.com/user-attachments/assets/293e5aa0-da02-4e13-ae8e-a1e02dda953f)
aughaskjgdask;faskl;dfaslk;dj everything broke. ....j.sjafljaskdfjas;fd
![image](https://github.com/user-attachments/assets/a3f56e49-c62b-4e6f-9fca-45882ec28f00)
i had to manually click all of the lines, instead of selecting the sketch as the edges/lines of the thing.

# session 15:
![image](https://github.com/user-attachments/assets/d6215711-5ca4-4af7-acab-bc8e5a8a7e67)
i made a scuffed pulley system for the inside, so that the balls will get powered all the way through the system. i'm not sure if this will work, and it probbaly will interfere with the hopper in some way, but i put a lot of thought into the positioning of the pulleys, so that it (hopefully) won't interfere toooo much.
![image](https://github.com/user-attachments/assets/80a2e995-dcd3-4cf8-bcfc-30fe0c3abebd)
at the end, i also put some pulleys around the outside, to aid with powering it. i also added some holes for a neo v1.1 or v1, and decided to use a 60:12 gear ratio, since it would likely need a decent amount of torque, whilst the outer ones i think don't need too much torque. i may reduce the inner torque to like 50 or 40 or something, but for now it'll do. i also made the outline for a plate, and will do some part lightening on it. hopefully not as scuffed as last time. 

# session 16:
i'm having the craziest thunderstorm right now, so if i suddenly stop/don't do that much work this session, that probably means that i lost electricity, and have no more internet/wifi. 
anyways,
![image](https://github.com/user-attachments/assets/90b4b46f-b01f-4b8e-9f8f-8a807ddc2a81)
hole too close to edge, bad. 
![image](https://github.com/user-attachments/assets/346e426e-bfb6-4950-b9a5-00d645281eb2)
i used the normal constraint a bunch, which is kinda rare, since the normal constraint doesn't have that much uses in frc desinging.
![image](https://github.com/user-attachments/assets/bff2f1f1-21c8-472e-9614-ada5586907d0)
noooo the laggggggggg
![image](https://github.com/user-attachments/assets/f7c97d66-cd3a-430a-ad37-efb81ce25808)
why it not solve.
![image](https://github.com/user-attachments/assets/464d379c-b8c7-4aec-a41c-10df080af645)
i kinda wanna fill in some gaps, and maybe add some moer ribs.
![image](https://github.com/user-attachments/assets/67349373-72eb-4d3b-b4e0-88957d13c31d)
100% not scuffed
![image](https://github.com/user-attachments/assets/d8e3880a-30b9-4f2c-85a0-b0dc6c555e84)
that looks kinda  ugly now.
honestly i think diagonal lines would be nice, but might also clutte it too much, but i think it would be nice, but might clutte rtoo much, but nice.
![image](https://github.com/user-attachments/assets/526cd14e-ca27-4a33-8559-431d79aea2f8)
maybe just one moe line.
![image](https://github.com/user-attachments/assets/f59f0417-b71e-4ed1-915c-0ad70232a4c4)
peak.

# session 17:
i decided i want to put some lightening on the indexer sides, and maybe instead use polycarb or something to line the inside, because the metal can get quite heavy/lots of metal used. 
![image](https://github.com/user-attachments/assets/34223ee2-f1b3-4c76-84fa-25dbe997577d)
this is going to be extremely scuffed. i can already tell. 
i'm having insane problems with positioning all the ribs evenly. 
![image](https://github.com/user-attachments/assets/8a1f94c2-4e43-4f69-94c5-c13b5023988c)
what the scuffed...
i have no idea how to fix this. i went back and forth trying a bunch of different ideas to make it more even, and eventually, until like 40 minutes in i thought of a method that may? work
![image](https://github.com/user-attachments/assets/4c9d9d8e-f532-4c36-893b-58f347831be8)
SURELY THSI WORKS... PLEASEEEEE
![image](https://github.com/user-attachments/assets/4970e1ba-567b-4405-8842-6c4178526936)
ok uhhhh hmmm i think i need more ribs. i didn't think this through.
![image](https://github.com/user-attachments/assets/e68a0eaa-f6c3-4bea-9579-415ad415f04b)
surely nothing goes wrong.
![image](https://github.com/user-attachments/assets/d2e5879a-b8db-4c0c-b1f1-4fc1235075ad)
i probably should've looked at 2910's indexer part lightening, would've helped a lot more if i did that earlier. 
![image](https://github.com/user-attachments/assets/a4252b34-9835-4928-9367-094ceca900c9)
what the flip.
![image](https://github.com/user-attachments/assets/3021b151-9604-4614-8df9-97582a935e23)
IT'S SLIGHTLY OFFFFF AHHHHHHHHHHHHHHHHHHHHH
![image](https://github.com/user-attachments/assets/650cd0cd-b8dd-46e3-8929-5bf081146f67)
i decided to constrain all the points to lines.
![image](https://github.com/user-attachments/assets/b12c5c1b-b42d-4ad6-b870-c260a3f49247)
something... feels oddly wrong about it... i don't know what it is, but something just feels wrong...
![image](https://github.com/user-attachments/assets/670f0cca-a10a-4445-9429-27603d11ba4e)
i think that it's this big gap here. honestly i might put diagonal lines to cover some things, insetad of a bunch of vertical lines/horizontal.
![image](https://github.com/user-attachments/assets/a1165ba4-4cd1-449d-bc52-287c22433080)
looks kinda ugly.
![image](https://github.com/user-attachments/assets/3bf36580-13c8-49e0-9180-c2cc4292b56d)
ok maybe a bit too much. 
![image](https://github.com/user-attachments/assets/d6e96af6-8760-4a1d-9763-fa1b15318c87)
honestly i think i should leave it like this.
![image](https://github.com/user-attachments/assets/2823e5b4-778d-441e-9954-bf65c610387d)
tis a little too thick.
![image](https://github.com/user-attachments/assets/03453d44-9cd6-4ac6-890f-e4923aed17df)
i should stop making changes. 
![image](https://github.com/user-attachments/assets/f1db1f4e-dfb9-48ca-9689-19a7f10d21ed)
i think i submitted it a little too late (extremely late, but it's fine also it's like 11 pm for me)

# session 18: 
![image](https://github.com/user-attachments/assets/4bc25f66-f9e2-4eda-b536-dd02b901ef19)
i made the polycarb sheet for the inside, and made it transparent (yeah i know in the image it's not very transparent right now.)
since i didn't really know what to kinda do next, i decided to try and think of mounting options for this. 
i didn't really know how to mount this, considering how awkward it can be to mount the 2 surfaces, because they're perpendicular n stuff. 
i was thinking of running 2 tubes parallel to the indexer and then somehow mounting both the hopper and the indexer to it, but i'm not sure how to exactly do that. 
after like 20 minutes of spinning around in my chair and thinking about how to do it, i realised that i had forgotten about the 2910 cad. again.
![image](https://github.com/user-attachments/assets/10190cc0-7866-49b3-bceb-3c7c3daa0b39)
they had used the 2 tubes in parallel, and had some parts coming out of the indexer to mounnt to the tubes.
![image](https://github.com/user-attachments/assets/a61558ae-cfb5-4da6-b500-21f064f7b372)
i realised that there was a lot of space for me to extend the indexer. 
also a big problem with the parallel tubes, since i will make an over the bumper intake, the mounting of the parallel tubes can't be on the drivebase, or it'd be too low. i don't know how to really mount tubes higher without making it an extremely sketchy setup, that would probably break immediately.

# session 19:
i'll make an example of how sketchy it can be and explain some stuff. 
![image](https://github.com/user-attachments/assets/815ab1d8-2446-4380-8444-b5e121e76785)
so usually, there'd be a gusset here to mount the tube (and one on the  bottom), but when the tube's higher up like what i need to do
![image](https://github.com/user-attachments/assets/b426307e-580c-4fae-92a5-7e790c4641e0)
if it's something like up here, there isn't really a way that i can think of to mount the tube effectively, without some kind of scuffed setup, since it'd only be the bottom gusset supporting the tube.
i'd need to either extend the indexer mounts by 10 cm, which definitely isn't optimal, and the indexer is quite short compared to 2910's, since i'm using a hopper, so i have less area to make mounting points. looking at 6328's mounting of their hopper, 
![image](https://github.com/user-attachments/assets/c7547c8f-12a5-4e1b-b57b-d5fffd496b0e)
they bend their hopper downwards/angle it downwards, but i can't do that, since i'm using a swerve drivebase, which isn't as optimal since we'd have to bend it at a further point
which is:
![image](https://github.com/user-attachments/assets/cafa7e3b-bf35-4010-aa49-53ab0d064433)
i'd have to bend it across that red line, or it'd interfere with the swerve modules unless i mount the hopper even higher, which isn't good. not  only that, but it'll stuff up the belts and do some really, really wacky things. the reason why 2910 cna mount their parallel tubes so low, is because they have a through the bumper intake
![image](https://github.com/user-attachments/assets/60f74f61-6b3f-4816-a4c7-d0d4746c24e6)
basically meaning that they cut out a section of their bumper and use the area to intake balls. (you can't see the bumper because i hid it to see more things.)
so i tried researching how to mount them. it didn't yield any good results. 
![image](https://github.com/user-attachments/assets/3084af2e-1089-4603-a4f6-a203021c6d9f)
the only solution i cna think of right now is making a block on top/tube on the top of the drivebase, and then using gussets to connect the block to the side of the drivebase and the parallel tubes, but i'd probably be extremely scuffed and really, really weird.

# session 20:
aklafsjksadfk;laskfa;slfkasfdasfklsajdfsafklsajfasklfsdaf
i could use like 90 degree brackets to help mount things, but it can/will/maybe get a bit scuffed. 
i looked on andymark for some brackets that may work
![image](https://github.com/user-attachments/assets/d4570d76-650a-4590-9327-188ce7dec862)
this might? work
i was planning to mount the brackets on the side of the parallel tubes, and have the tube rest on top of the drivebase tubes. one major problem is...
![image](https://github.com/user-attachments/assets/315aa4d3-9d13-440b-901c-1f7e43a6ce5b)
the bracket is too thick and the holes are too small. 
so i had to look for more brackets. i couldn't find any other brackets that i could potentially use. 
i searched through other websites, and found absolutely nothing. sdalfjklsa;dfjsaklfjs viopaj fiawmesipjod vud fjajfmpiocquwmep,jsafijdcasmfiojaspoawe,jxc,jsd
the thing is, if i try to make my own bracket, it may not be strong enough, and it may not be machinable, but it's kinda my only choice. 
![image](https://github.com/user-attachments/assets/beb5c777-a026-4b06-b874-0fa7e502821a)
i made this bracket and called it the unmachinable part, because it probably is. i'd like it to mount on the sides of the tube and the bottom as well, just to secure the rigidity. i would also prefer if i could have like a triangle or some ribbing to help support it, but i know that isn't possible.
![image](https://github.com/user-attachments/assets/8ce49399-4fa5-4ec7-92c0-f3e7df575edc)
i decided that i wanted one mount at the front of the indexer and one at the back to help it. 

# session 21: 
i wanted the mounts to be more secure, so i expanded the amount of holes that it covers. 
![image](https://github.com/user-attachments/assets/ed84a916-110a-48d9-bb8b-0ff3e5222023)
expansion
![image](https://github.com/user-attachments/assets/be626b4c-e8cf-4d14-a8a0-acbdd7b0d769)
epic mounting (maybe not idk)
![image](https://github.com/user-attachments/assets/74ed87b9-cb43-4788-8a20-0898b187f9b7)
mmm that's kinda ugly..
![image](https://github.com/user-attachments/assets/c15e4214-a9c6-4dfd-acae-146ed16ddd7f)
also ugly
i didn't really know how to make it look  nicer. 
![image](https://github.com/user-attachments/assets/f4392fde-0512-4998-9544-d440296ead4b)
I'M A GENIUS. SURELY THIS DOESN'T LOOK BAD. 
![image](https://github.com/user-attachments/assets/d6284b88-338a-4208-99f2-894a8dd2aa06)
at 15 it's fine
![image](https://github.com/user-attachments/assets/1fa16e6a-45ae-4fdc-85dc-2ffc8b1d6e88)
but for some reason when i change it to 10, things break. 
![image](https://github.com/user-attachments/assets/6fcea12a-5702-45c8-935a-ae7af9d81cee)
i change this line to be perpendicular with the sloped line/angled line/line
![image](https://github.com/user-attachments/assets/7854ea10-23e5-4e3f-a717-be9d2ff4bd0a)
not good.
![image](https://github.com/user-attachments/assets/db6edaf6-b36c-44ac-8d76-5e8aa4e389aa)
even worse. 
![image](https://github.com/user-attachments/assets/ec2f17ce-3d9b-45bb-8f70-a32912f56f35)
not good either
![image](https://github.com/user-attachments/assets/db17e515-b9d3-45d1-a3fb-0a9d3f20e1c3)
by excluding this area it breaks
![image](https://github.com/user-attachments/assets/84a30c1a-6705-429e-9847-2c9bccfdafcf)
yiiipppppppeeeeeeeeee
![image](https://github.com/user-attachments/assets/d082b5f1-d6f3-4a63-9fed-d2757adf1a38)
i got started with the second mounting area. 

# session 22:
![image](https://github.com/user-attachments/assets/3a57d96a-2348-41ab-8e08-ca252abc9e9f)
i made a second mounting area and adjusted the holes, since earlier i felt like i made too many.
![image](https://github.com/user-attachments/assets/ea2dc97f-4ce6-4f58-b4a1-f2e7fa174cba)
oh no.
![image](https://github.com/user-attachments/assets/2d45afa1-fcf6-4539-98f6-21e5cd088fce)
i decided to repair this manually, so i can get the result that i want.
![image](https://github.com/user-attachments/assets/e9d66afc-c174-438f-a97b-38bb587758fa)
uhhhh..
![image](https://github.com/user-attachments/assets/5bbe55ab-bbbc-400d-a9ea-82cf33167b05)
oh ok.
![image](https://github.com/user-attachments/assets/ca79a04f-7e6b-4916-93bc-f95afb3baa77)
trust me this isn't scuffed
![image](https://github.com/user-attachments/assets/c41196d4-81ef-4098-9090-9f61aad3c6c7)
critical flaw
![image](https://github.com/user-attachments/assets/260df7bb-da9f-4810-ace6-7317e28b0ba1)
it'd never be scuffed !!! i swear !!
![image](https://github.com/user-attachments/assets/eaa00df8-8f29-4892-9ee2-8836f06f4f3e)
i realised i could skip some lines.
![image](https://github.com/user-attachments/assets/e51115b8-cc47-45e8-b4e6-7fed5fc74f8b)
epic !!!
now i decided to try and work on hopper mounting (note, try)
my current idea rn is standoffs, which will surely not be too bad, right? right???
mounting might be scuffed, but surely with standoffs it wonn't be (fajsdlkfsa;lfdjksajdfk;alsjfs;kdfljasdk;lajsdf;lkasjfd)

# session 23:
![Screenshot 2024-08-10 172454](https://github.com/user-attachments/assets/ae1c8ae4-f0dd-46b2-83d9-42bb45224a90)
aslkjfsakdjkfkjfaaks;;lksd;lkjadslkj;afd;lk;kdajfsafds
i just wanted the 2 lines to be equal.
![image](https://github.com/user-attachments/assets/8df82379-2d8b-4601-9550-fcd75000ad67)
looks horizontal, but it isn't.
![image](https://github.com/user-attachments/assets/77dd1ca8-4cdb-4d97-a607-9ba5230d76be)
i think i want to change these areas.
![image](https://github.com/user-attachments/assets/05ac6f60-0ddb-4839-aa77-d94b120e36b0)
ima have to redimension eveything.
![image](https://github.com/user-attachments/assets/7e2732fb-93cf-47f8-9af0-f6ad895bdd6c)
i tied to mirror some lines across, but it just isn't mirroring.
i think i found the problem. the mirror line isn't exactly in the middle of the drivebase. yes it's constrained to the origin, but the drivebase isn't on the origin. 
![image](https://github.com/user-attachments/assets/0a074a45-3edd-4dd0-bc73-7662889934bc)
ok it's fine ish now.
![image](https://github.com/user-attachments/assets/03e066fa-b5dc-4029-9504-0c0020d08e53)
the extrude broke wheni exited the sketch, meaning that the area isn't enclosed. 
![image](https://github.com/user-attachments/assets/321f9745-9726-417b-9e1a-02e8ed4cf48f)
found it
![image](https://github.com/user-attachments/assets/016836fb-7d9f-4503-b22d-1bf57af95d30)
i can barely do addition, but i don't think 99 + 99 = 187.
![image](https://github.com/user-attachments/assets/e4008bcd-ea58-4ff6-a61a-47a69757d6e3)
something's wrong here
i don't really know how to fix this, as everything has been defined. 
i had an epic idea like 5 minnutes later
![image](https://github.com/user-attachments/assets/eba14e76-cf93-4e50-89d2-aa298af88481)
i deleted the line and replaced it with a shorter line (wow) then mirrored it !!!
![image](https://github.com/user-attachments/assets/b34dc2ea-41c5-43c5-874f-6317247d97c8)
OHHHH NOOOOOOO
![image](https://github.com/user-attachments/assets/e63d2e4f-9561-4e88-9989-8fa7f5b2ccb4)
eveything is breaking.
![image](https://github.com/user-attachments/assets/9c79b08c-9487-419c-8f24-2f48a5a0678e)
everything is fine now.

# session 24:
now with everything ok/fine, i can move onto mounting the hopper.
![image](https://github.com/user-attachments/assets/de791d0f-490d-4dd9-b42f-fb7a69ed6fab)
i think i need more space.
![image](https://github.com/user-attachments/assets/f6d28b56-7003-40f7-8aca-36b1f1e430b9)
heck nah. 
ok so i reduced it to like a 2mm gap between the indexer plate and the hopper. surely it ends well. 
![image](https://github.com/user-attachments/assets/1bb60925-a839-4dde-8ae2-91433d6935f6)
epic. 
![image](https://github.com/user-attachments/assets/6bd91f2b-01d2-468d-a809-c4f5b6306f6b)
i turned the side of the hopper plate around, and the other things also turned around. i also had to use an offset on the hopper plate, so i would have enough space to use the gearbox. 
![image](https://github.com/user-attachments/assets/727a62d9-6bed-4367-bf6d-6b9a49e186d0)
also this doesn't look right. 
![image](https://github.com/user-attachments/assets/b9caad91-7042-4a55-871d-2e877d7d71f1)
i think i'll adjust the gearbox first, before moving onto hopper mounting, since at the start, i wanted to use standoffs to mount the gearbox, but now that i've figured out a mounting for a bunch of things, i think i want to fix it to the parallel tubes. 
now my problem is, is that i can't see where the parallel tubes are.
ok nvm i can measure things (i'm dumb)
![image](https://github.com/user-attachments/assets/02d3e9bf-109c-4026-9b65-1828ccc68234)
i'm extremely dumb (i forgot to take 25 mm off the measurement because of hole distances n stuff.)
![image](https://github.com/user-attachments/assets/6cd35f59-74a7-43cd-a2a2-2c23135fe511)
the holes don't line up, but that doesn't matter. (ok it probably does actually)
![image](https://github.com/user-attachments/assets/21b3fb34-e587-42c2-888c-7770e4e6112e)
NOOOOO WHAT HAPPENED
![image](https://github.com/user-attachments/assets/fddde603-fd49-4b0a-bd5f-38c334e57246)
hell nah
![image](https://github.com/user-attachments/assets/74e0c7aa-0f36-435c-87cb-4e4830f2bfa9)
i did the measurements, what went wrong here. 
![image](https://github.com/user-attachments/assets/fdfe3a97-b76f-4522-bc5d-e4b5f2b7f98c)
agrh that's also too close. 
![image](https://github.com/user-attachments/assets/79cb1bca-8a3c-4c69-84c7-557cd601ee83)
and now it's slightly off in a different axis. 
![image](https://github.com/user-attachments/assets/7ae40608-b1c0-4337-b29c-d0a7055fef5b)
YEAHHHHHHH
