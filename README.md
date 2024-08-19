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

# session 25 - the mystical 25 session mark:
uh so i hit 25 sessions. YIPPPPEEEE!!
![image](https://github.com/user-attachments/assets/77d35a40-7c33-4862-b50f-24a3cdde7d92)
NOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO
![image](https://github.com/user-attachments/assets/e45a381d-7a40-43f5-9025-7818c372d5a3)
NOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO ASHJFIDJWOAI DFKL;LAJSDLKFJ ASKLDJFLKDSAF
![image](https://github.com/user-attachments/assets/ea5169bc-6190-4779-80c2-beb2c8b65d17)
tis all fixed now. 
![image](https://github.com/user-attachments/assets/d6bbd106-888f-4e2e-99a1-4a66c96417ce)
but here is scuffed
i think i know the problem. the holes moved away from the center and it became scuffed. 
OHHH WAIT NO IT'S BECAUSE I SHRUNK THE PLATE DOWNNNNNN OHHHHHH AND THEN THE LINES PUSHED THE CIRCLE TO BE SMALLLLERRRRRRRR
![image](https://github.com/user-attachments/assets/58da7c4f-060b-4417-83e3-237291217c61)
it's better now.
![image](https://github.com/user-attachments/assets/3397c506-96b3-4c54-ae01-87ff0d3c0b69)
aw heck nah
![image](https://github.com/user-attachments/assets/5119ccd8-22d0-4340-968d-23123c78eccd)
aw heck nah (i was adjusting the size of the hopper again)
i was having a really hard time trying to make the hopper smaller, as the constraints were not going in my favour, and things were being quite wacky.
![image](https://github.com/user-attachments/assets/fcf8fb4e-fc67-40d4-9455-62894f296920)
i needed to somehow pull the hopper back.
never frekaing mind after like 20 minutes of being an absolute dumbass, i realised that i was changing the wrong dimensions. 
![image](https://github.com/user-attachments/assets/a9cce41d-3c83-4176-973c-13387d652247)
barely not good enough.
![image](https://github.com/user-attachments/assets/306d22ad-31c6-44fb-a436-7700a1a6db76)
and its fine now.

# session 26:
![image](https://github.com/user-attachments/assets/9c374054-9110-4736-a7a1-94886ef130fa)
i made the hopper smaller slightly more, to have more room.
![image](https://github.com/user-attachments/assets/a17ea61f-f463-4cb8-bd06-585fa6f17bc1)
the hole is lined up, but now there's not enough space. 
the thing is, i can't adjust the size of the area that i reserved for the mounting, because it's the correct size. 
![image](https://github.com/user-attachments/assets/6ac83b74-be9b-4bda-9f57-7ffe5f67866f)
i think i see the problem, the indexer sketch isn't exactly on the middle of the drivebase, it's on the front plane, but the drivebase isn't centered. 
![image](https://github.com/user-attachments/assets/9fe3afce-ae5d-413a-9927-abf0b542ec60)
this should work
![image](https://github.com/user-attachments/assets/3d904ebf-a530-4554-9310-4518c41662ec)
yey its fixed !!!
i also decided to clean up my sketches and extrudes, and naming them so i don't forget what is what. 
![image](https://github.com/user-attachments/assets/e87cd3ee-6e47-4b8c-b6a4-21ebae88bccc)
so i moved back to mounting, and i have a problem, which is that the red holes are smaller than the blue holes, because the swerve modules use (i think) #10-32 (imperial) bolts, whilst the drivebase has holes for M5 (metric) bolts, these two are different sizes, which means that it's going to be kinda scuffed, and the standoffs would need to be a different size as well. i didn't know how to really deal with this, since it could get kinda scuffed. 
like 10 minutes later i realised i'm so frekaing dumb. 
you can just drill holes.
i'm so dumb.
now i had to see what hole lined up on the hopper plate. 
i didn't realy know how to get the holes to line up/know where the holes were on the hopper, since there was no way for me to dimension and stuff. 
i could guess by using dimensions but i kinda wanna find a more efficient and faster way.
![image](https://github.com/user-attachments/assets/31ef86cd-5c2b-4811-b93b-2cc409cb4e60)
well i found it (it's the concentric constraint)
![image](https://github.com/user-attachments/assets/3ecdb1c5-2014-4731-9a8d-45e8e3b137c8)
epic. 

# session 27:
session 27ing
ok so i finished off the mounting holes. 
![image](https://github.com/user-attachments/assets/0a5bbc8f-9c0f-4a7e-b599-3bf79ea467b1)
epic.
looking at 2910's cad i can see that they have standoffs for the indexer, so i decided to model those in.
it was then that i also realised that i forgot to make holes for the indexer gearbox, since i thought i could use the equal constraint to constrain the size of the holes, and thought that there were holes for the gearbox. 
![image](https://github.com/user-attachments/assets/d4dbd3b9-f984-4f23-8b83-4edda30bbbd3)
there wasn't a lot of space to place any bolts/holes on the left side, because it was so filled up with other things.
i also realised that the holes i had made for the motor were wrong. yipppeeeee....
i had to search up the clearance holes for 10-32 bolts, but then i realised that i had a model of a neo motor, so i just measured it off of that. 
ok it isn't 10-32, i'm kinda dumb, it's probably 8-32. anyways.
![image](https://github.com/user-attachments/assets/b9985e4f-1bc8-4f65-9d66-413ae84214da)
that's not good.
![image](https://github.com/user-attachments/assets/5d4d5948-cc34-4341-b21e-4b00fc6c1649)
i expanded the size of the walls of the indexer, so that i would have more space to mount things. 
![image](https://github.com/user-attachments/assets/31d125f1-4f93-49a0-a37f-01a1db25ef3e)
i think i might have to remove these gaps. 
![image](https://github.com/user-attachments/assets/81dd8ba1-aeb4-4977-9f1c-f89af80279c4)
bruh why cna't i select this area 
![image](https://github.com/user-attachments/assets/9148a9d6-5840-497a-96d9-54d98e0b957c)
epic.
i think i want to make the gearbox larger.
it's gonna  be a pain because of how i constrained and dimensioned everythingkgskdlfjkalsdjf;saasd;f i regret making some wacky constraints. 
onshape is slowly dying on me, my internet sucks nad onshpae doesn't like it.
![image](https://github.com/user-attachments/assets/907dd1e6-caba-453b-8f1e-cbdb30435ae2)
i expanded it out.
![image](https://github.com/user-attachments/assets/b6e083c2-e130-4dff-9d63-21946bfc1994)
tis a  bit too much
![image](https://github.com/user-attachments/assets/8a78ef19-2543-4fa3-a13c-f27bb57d34dd)
uh oh.
![image](https://github.com/user-attachments/assets/69e31a5e-8015-4074-b46b-27a5f3d5dc4e)
somehow this hole got covered up.

# session 28: 
![image](https://github.com/user-attachments/assets/5d4fe918-a41a-4fa5-b928-17a2bd4d905c)
i'm really dumb. like literally room temperature iq. i didn't realise that i didn't need those holes on the right side, and that i probably don't need pocketing on the right side. i also need to make the holes on the top higher, so that they can actually have space to go into the indexer plate, or somewhere else. i don't know. 
![image](https://github.com/user-attachments/assets/15326dfa-f65f-46a5-9972-10b8367b920d)
looking at this, i think i also need moe holes on it, so it can be more secure. 
![image](https://github.com/user-attachments/assets/ef0235e2-56db-49e2-84b1-ce9b6d4aeccc)
epic. 
![image](https://github.com/user-attachments/assets/c6e97bb2-f595-4751-8e07-3e8a3a6aae68)
the gap here is too small, so i'm gonig to remove a rib or maybe move it. 
i was confused on why i couldn't move it much, even afte ermoving most of the constraints. (it was a vertical constraint from somewhere else)
asjdflaskfja;skfj;skldaf
![image](https://github.com/user-attachments/assets/4d942cc5-a5ca-4418-9668-13c5f5640c09)
ok cool good enough.
i realised that i hadn't filleted some edges yet, so i filleted them.
i decided to start on the shooter. 
i had to plan a bit for this one, since most of the shooters i've seen are adjustable angle shooters, which are harder to make.
i literally had to go to the 4th page of google, because i couldn't find anything. i didn't find anything on the 4th page
jkasdflkajdflj;alskdfjas;ldkfjsak;lfsajdf;klsafja;sfjkasdf
i honestly might make an adjustable angle shooter, but they confuse me too much.
i had no good ideas of how to make a fixed angle shoote. 
https://www.chiefdelphi.com/t/design-shooter/388925/16?page=2
well i found this, after putting chief delphi in what i searched. i'm (not) so smart
i read through the entire thing and it doesn't entirely tell me how to make a fixed angle shooter, but at least it helps. some people said that you would have to test it with prototypes to get the proper shooting angle, rpm of the motors and other things, whicih i can't really do because i'm working in cad, not real life. 

# session 29:
jalskdfja;sldfjasf;salkfjsaksad;fj
the cad grind
asjfdla;ksdjf;lksadfj
i didn't really know where to start off with the fixed angle shooter. 
i realised that i didn't knokw what angle that the fixed shoote would be at, so i had to find a cad of the 2021 field and look at wheer i wanted the obot to shoot from. i also read the 254 tech binder on strategy to sort of get a better understanding.
uh so when i was downloading the field cad, i realised that there was an onshape link to the field. yyyyyyyiiiiiiiiiiippppppppeeeeeeeeeeeeeeeeeeeeeee.
then i realised that it was the 2024 field, NOT THE 2021 FIELD
![image](https://github.com/user-attachments/assets/80cd623a-0955-4d2f-aa18-51dd4a6cd6aa)
i got scammed
![image](https://github.com/user-attachments/assets/fd3a3328-b702-4eee-9e5a-8ef48461d14e)
hmmm yes quite interesting.
i think i want the robot to shoot from position 4, since it probably would be consistent there, and it says power shot, so i think it can fire some good shots there. it's also perpendicular to the goal, so that can mean better angles to shoot into the outer and inner goal.
now i didn't really know how to get the angle that i wanted, considering that i might have to aim a bit higher, since the wheels probably won't be able to shoot it straight ahead. 
i decided to copy the document so that i can draw lines and stuff and see what angle i need it to be at. it's probably going to take a long time. (it only took 1 minute, phew.)
![image](https://github.com/user-attachments/assets/0cf6f12c-6acf-46bc-9a56-e850d04e89f9)
hmmmm ok
i just realised that i'm kinda (really) dumb i shouldn't measue from the floor. 
![image](https://github.com/user-attachments/assets/1ce4918f-1ee7-40f5-9133-18e8d0a70b5d)
ok cool, i went for 30 degrees. 
![image](https://github.com/user-attachments/assets/baf2a4c3-5a27-4ca6-822b-c5ab629635b2)
this should be enough space/area for me to work with.
![image](https://github.com/user-attachments/assets/7664eec3-7a08-4547-91f2-7d1e32cb4cd9)
i think i might have only one roller. this may have some results like spinning and stuff, but there's not much i can do. 

# session 30: 
i realised that i had forgotten to power some of the pulleys on the indexer, basically meaning that they would do absolutely nothing if i just left them like that. 
![image](https://github.com/user-attachments/assets/81ae33c5-c15b-4e38-9beb-1e020264e388)
UH WHAT. (turns out, i forgot to change it from inches to millimetres. epic.)
i also realised that i needed to lower the gear ratio for the outer pulleys on the indexer, since it's currently 60:12 and i want it to be kinda lower, something like 45:12 could work.
asjdfklfjasjdfklsafjska;fjsaklsajf;asd
this gearbox is going to become even more scuffed i swear... i'm slowly losing my mind.
![image](https://github.com/user-attachments/assets/ddb9bd87-e65e-447d-bc33-ce5afc48c3ec)
i decided to move the larger gear up, so i (might) have space to place a smaller gear towards the bottom. 
![image](https://github.com/user-attachments/assets/ca094cbd-5387-4002-960e-8d254f196507)
OHHHH NOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO
the worst part is, i can't really make it so that the gears are able to turn the right way, because it's either that the middle indexer belts are turning in the right direction, or it's the outside indexer belts that are going i nthe right direction.
ooo i think i have a good idea, since the 2 gears are so close to each other, i think i should make it so that the 60 tooth gear powers the 45 tooth gear and then everything would work. right?
.
.
.
5 minutes later
.
.
.
i'm so dumb for not realising this, but if i power the larger 60 tooth gear and then make it power the 45 tooth gear, the middle indexer belts wouldn't move because 2 of the pulleys would  be turning in opposite directions.
sjklafklsafjs;klafdjsakfjsaklfsjafask;f this all makes no sensenseee
i proceeded to spend the rest of the session just trying to think of ways to package this monstrosity, but i can't really come up with anything that i think would be effective. 

# session 31:
the thirty first session.
so i'm really dumb, and i forgot that 2910's cad exists. 
*sighs* ;slakdjfkajskldfjsa;fj;sklafjsad;lfjlskadfj;asfjksd
![image](https://github.com/user-attachments/assets/4219a231-f2ce-49b4-819d-7ee8ff790d51)
their gear setup looks like this on one side. 
![image](https://github.com/user-attachments/assets/a6c8a484-29ef-49ae-8ce8-7e6722458b2a)
and on the other side it looks like this. 
looking at these pulleys, i realise that i probably could reduce the gear ratio, but i'm not sure.
so i had to count some of the teeth of the pulleys, and it was extremely fun. some parts had their tooth count (only the gears) 
https://www.chiefdelphi.com/t/help-with-gear-ratio-calculations/136627/4
i found this thread, because i was having a hard time trying to calculate their gear ratio. 
![image](https://github.com/user-attachments/assets/2c0ad672-7ff7-440d-b264-8e6b47b84cdb)
mmm that's kinda high. 
actually wait, it's even higher  because i forgot to add the pulley ratios. it's more like 14:1, which is really, really high. how am i going to do that? i don't know. 
i spent even more time counting more teeth for pulleys, and the gear ratio for the outer indexer pulleys/belts/whatever is 1:1. 
seeing this makes it even harder to package it for me. 
i'm literally losing my mind...
i wanted to take a break from the hell that is the gear ratios, so i decided to adjust some things
![image](https://github.com/user-attachments/assets/a82eb52f-62b9-48e8-8a2c-ecbc32c0b519)
i adjusted the indexer mounting to be larger for more holes, but lots of things broke.
![image](https://github.com/user-attachments/assets/6f1769ca-ccd0-40cb-a05c-bee3238fe823)
i also made the parallel tube smaller, so uh yeah. 
![image](https://github.com/user-attachments/assets/18435e9c-d16b-4224-a5a3-db8cd62df323)
WHATTTT THE FLIPPPPP

# session 32:
![image](https://github.com/user-attachments/assets/34bee200-d56b-415c-a5ba-4b2312fc6e1b)
i managed to fix it all up. 
i also had to change all of the different shafts.
and then.
i decided to go back to hell (aka packaging a scuffed as hell gearbox)
after like 30 minutes of thinking over gear ratios, and debating if the 60 tooth gear is even needed, and wondering if i'm going insane, i eventually swapped to a 50 tooth gear, and then a 16 tooth gear to a 50 tooth gear, to get around 13:1 ratio, which is good enough to me to be honest. 
this is just going to be so scuffed...
i decided to tackle one thing at a time, and finish the gearing for the middle belts first, before moving onto the outer belts. 
![image](https://github.com/user-attachments/assets/96eae7c3-c4ea-4cc2-a170-f9b80731d45b)
it look sso weird now.
![image](https://github.com/user-attachments/assets/92d566dc-1b9d-4b0e-9d58-eb22cf81450f)
OH MY GOD SO MUCH RED.
![image](https://github.com/user-attachments/assets/b828670c-7909-4043-8d8b-1e1ae87a58da)
uh oh.
![image](https://github.com/user-attachments/assets/353d7919-c68b-4028-96bb-8ecfa6785dd8)
hmmmm still wacky
![image](https://github.com/user-attachments/assets/1ae4dbe5-e461-481a-92ae-e3da883f5b30)
i just realised that there arent enough holes for the neo.
![image](https://github.com/user-attachments/assets/38f52662-0fe5-468a-80a6-3ab334d9ae6f)
it says 6
![image](https://github.com/user-attachments/assets/9aa984f7-febe-4266-b909-96d1da6c2461)
but i put 8 ???
I CAN'T EVEN DELETE THE THING, WHAT.
onshape is straight up tweaking out on me.

# session 33: 
i reloaded the page to see if it'd fix but
![image](https://github.com/user-attachments/assets/1f8a5547-b0fb-4254-9a4e-ea40e4ea4b1c)
my god bro onshape is straight up dying right now.
ok so from what i can think right now, the motor has to spin clockwise from the side with the indexer plate, for the middle belst to work. 
i was originally going to power the outer belts through the 50 tooth, and then use belts to get it over to the outer belts then reduce it down to like 1:1. then i realised, that it probably isn't effective at all, and it'd probably be better for me to just use some different gears to pull it off. 
actually, now that i think about it, it may be possible to attach like a 16 tooth gear to the 50 tooth
oh wait nevermind, because it'd be 1.3333:1 in gear ratio.
wait, i can use pulleys.
i'm so dumb. i can just use pulleys to reduce it.
okie dokie, so i don't have enough space to attach a 16 tooth pulley to the 50 tooth, buuuutttttt
i could attach one to the 12 tooth pinion. maybe, just maybe, SURELY it works. 
16:12 is 4:3 or 1.3333333:1 in gear ratio... wait isn't that the same as the 50:16 uh well yes it kind of is, close enough in my opinion.
i decided to use a 42 tooth pulley, and an 18 tooth pulley that's a 18:42 ratio
then i realised, that pulleys don't calculate ratios the same way as gears do, so i decided to make the gear larger, to 20 tooth, and then  calculate things again. 
20:12 is 5:3 or 1.6666:1. i also decided to increase the pulley size from 18 to 24. that, surely will work, right???
i also realised that i cna move some holes into the corners. so i quickly moved some holes around. 
![image](https://github.com/user-attachments/assets/9c694508-972f-433e-8d46-6e26be061bcd)
epic.
ok, problem, if i use the 20 tooth gear on the 12 tooth gear, i won't have enough space to mount the motor, so i have to move some things around. 
wait i'm dumb, you don't have to use all 8 holes to mount the motor, you only need 4 to be safe.
uh, problem, the bearing hole itself is too big, and doesn't allow the 20 tooth gear to mesh with the 12 tooth gear. i realised that if i do some weird janky stuff, i can techinically mount the 50 tooth gear anywhere, so i moved it somewhere else. 
jfsalkdfjasklfjafd i hate gears and pulleys, why are they so confusing, why can't they just be this thing power that thing.

# session 34:
ok so, i started to do the pulleys. 
it's painful to adjust belt lengths and see what i need to get. 
![image](https://github.com/user-attachments/assets/813345e3-c5a5-4284-88e0-58bcfa9d2257)
what the abomination.
![image](https://github.com/user-attachments/assets/93129216-94c6-4827-acfc-0846343ab279)
average day where things go wrong.
![image](https://github.com/user-attachments/assets/c031b298-0ba3-44ad-b72c-b706ab9b6f72)
well everything is fixed now and done after 30 minutes... (why is this so slow)
![image](https://github.com/user-attachments/assets/7008db28-7a8f-4d3e-9ab8-daffef28d9a3)
i was getting some progress done with teh shooter, but i realised that i hadn't made the standoffs for the indexer. 
![image](https://github.com/user-attachments/assets/68c56319-ae4a-4473-969d-cad2bcaa4e6c)
hmmm that's a bit off.
![image](https://github.com/user-attachments/assets/1224277c-d711-4632-8d1b-0ebc47a7f6dc)
i gotta move it slightly more...
![image](https://github.com/user-attachments/assets/19e0d71b-61b9-4ae6-b5f8-fd320da3f607)
good enough.

# session 35:
i wanted to make some space on the ribs for the standoffs, so i had to make the circles on the indexer rib sketch
![image](https://github.com/user-attachments/assets/76f0c1bc-69d2-4076-9dc4-82609a961bc2)
epic.
![image](https://github.com/user-attachments/assets/a715d644-7ba4-4d6b-96ce-8bfb501ade1f)
uh so nothing changed. i think i have to change some of the settings. 
![image](https://github.com/user-attachments/assets/7b7bddf9-d2ab-4ea0-8940-52d828e22a2c)
that's.... maybe too much, the thing is, i can't change the rib size or it'd change the rib size for everything.
![image](https://github.com/user-attachments/assets/22c04fd4-1357-4dcd-8049-96ac1496f1cf)
i mean it's alright, but i think i want it to be larger.
![image](https://github.com/user-attachments/assets/a0fc78c3-4936-4d44-aec9-bdb6b3905304)
epic. 
![image](https://github.com/user-attachments/assets/d9e618d3-795e-4136-b5f3-b8215920f3d7)
ooo that's kinda scuffed. 
![image](https://github.com/user-attachments/assets/9d5fcfdc-0a5c-4540-a370-6d8e1ef112a5)
that's not good either. 
it's all fixed now. i think i want to adjust the bearing hole, or add something to  it so that it looks  better. 
![image](https://github.com/user-attachments/assets/a60f4ea8-d871-4a85-9249-f44d8d2fcd13)
why is this not a face. what???
![image](https://github.com/user-attachments/assets/0bfa4d50-6639-4d22-8a7d-4d277ad22819)
i think i might also put the bearing slightly away from the plate. 
![image](https://github.com/user-attachments/assets/e073eb42-388f-47fa-8260-091389af31c4)
uhhhhhh
![image](https://github.com/user-attachments/assets/29dbef7b-8a41-4ab5-8dd8-7d50f0ae3f55)
uhhhhh that don't look too good. 
![image](https://github.com/user-attachments/assets/5f792a90-3b9b-485b-b0f9-d3f1d239f3d2)
welp.
![image](https://github.com/user-attachments/assets/2c7b0205-3b34-4ebf-ad50-c8167b3cde8b)
epic.
![image](https://github.com/user-attachments/assets/f2ad1a7e-9053-48b5-adac-ed844007d7c3)
IT'S SO SMALL BUT IT ANNOYS ME SO MUCH... AHHHHHHHHHHHHHHHHHHHHHHHH
![image](https://github.com/user-attachments/assets/1e82da87-8442-4e4b-a07a-fbd1403e526a)
everything should be fine.
![image](https://github.com/user-attachments/assets/e02f8793-547e-42ec-8e06-0ab5e7f67281)
NOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO
![image](https://github.com/user-attachments/assets/9171bd31-c2b1-4697-9275-09124a7ab8ed)
well i fixed it, but idk how to really fillet this edge without it being scuffed. 
![Screenshot 2024-08-12 180040](https://github.com/user-attachments/assets/c7112859-ef19-4f18-918b-a8069e231ab2)
i had an idea to make some lines on where the fillet could be, and tried to make a fillet but it didn't work.
![image](https://github.com/user-attachments/assets/f535cc7c-56d4-4bd3-a0b9-6c38d98b49eb)
ok so i had to extend some  lines intead.

# session 36:
this is gonna be a short session because i gotta sleep soon. 
i kinda need to figure out a way to power the shooter, i think i'll do it through belts, although i think i want to look at some examples first, so i don't mess up like previous times.
![image](https://github.com/user-attachments/assets/f111181d-8a53-48b1-b6da-4b471b41e36b)
ok so 2910's shooter wheels are powered by 2 falcon 500 motors, which is one of the best/most powerful motors in FRC. their ' ratio is around 0.7:1 or 7:10, in simple terms, wheel go fast. 
![image](https://github.com/user-attachments/assets/bbef2a3e-3d28-4956-8164-fbcd1b22adc5)
254 also uses 2 falcon 500 motors, and it's a 1:1 ratio. 
![image](https://github.com/user-attachments/assets/2b087367-92cd-4bcb-8ebf-1907da15bec2)
6328 uses 2 neo motors, which are like middle of the road/pretty reliable and standard motors, and a gear ratio of 0.66:1 or 2:3
it's gonna be really hard to compress all of the motors and pulleys and stuff, holy this is going to be incredibly scuffed. 
![image](https://github.com/user-attachments/assets/a366f77b-df26-41aa-82f9-9ecc144a21d5)
i found this pulley for neos. it should suffice. 
![image](https://github.com/user-attachments/assets/02ad7cd6-4100-44f4-a2c7-0b0735c99980)
alkfjda;fl this gonna be so scuffed i swear.
![image](https://github.com/user-attachments/assets/e08dd877-aa9e-4ad5-a79f-d1c7a39db08e)
asdklfjalskfdjsa;dfjaslkd;fa yipppee

# session 37:
the 2 neo motors will be on opposite sides, meaning that i won't have to cad 2 areas on the gearbox for motors. 
i forgot that i hadn't made onen of the crucial parts of the indexer, the  bottom of it. without the bottom, the balls would just fall out. which isn't good.
![image](https://github.com/user-attachments/assets/e74e1d6c-1d6a-4b7a-8359-5089e8fe1745)
ok now that i look at this, uh... it looks quite scuffed. 
![image](https://github.com/user-attachments/assets/bfb56fe9-48fb-42f4-8dd3-2cfc4fc1a077)
better
anyways back to doing the bottom of the indexer.
![image](https://github.com/user-attachments/assets/f09d3de0-713a-4d1d-933a-12aa77e83e0a)
OHHHHH NOOOOOOOOO (i drew a new shape on the indexer sketch and it broke everything.)
![image](https://github.com/user-attachments/assets/4cc54f35-ee2f-45aa-bbd4-ea274b5c8e75)
it collides with the hopper a bit, then i realised that i could've just fused the hopper and the bottom of the indexer together, to make it more simple and easy. 
![image](https://github.com/user-attachments/assets/cf8db1f7-590a-445f-a9f2-7ad36e658b20)
epic.
![image](https://github.com/user-attachments/assets/7db7aaf3-3433-468b-9334-1acee4435387)
those holes are just slightlllyyyy off. 
![image](https://github.com/user-attachments/assets/d245a35d-2ec5-4e82-ada1-8404156330a2)
should be fine now.
![image](https://github.com/user-attachments/assets/f13ff08d-d9b4-4f0d-9f9d-f22f9ff09f85)
nevermind i added when i should've subtracted.
![image](https://github.com/user-attachments/assets/c5eee5a4-81f7-43d7-bf5f-af23ac7b8a64)
huh... what the flip. 
oh i think i took minimum or maximum distance insetad of center distance. 
![image](https://github.com/user-attachments/assets/5a21e844-6f34-4972-ba38-cfba510b0b77)
finallllyyyyyyy.
ok so, i think i have to move onto the intake now, since i think everything else has been done. i of course have to assemble everything together, which can take a while, but for now that's not what i have to do. i honestly also might make a belly pan (basically the bottom of the robot to make sure nothing falls off like electronics n stuff.) but since i won't be adding in all of the electronics, (probably only going to keep motors and stuff.)
my parents are asking me to do my schook work right now (i've been doing too much cad 😭)
ima go look at examples of intakes now. 
![image](https://github.com/user-attachments/assets/0759be7d-7fe3-4330-86ba-6407266daf7a)
2910's intake is deployed by pistons. it uses mecanums to center the  ball, then it takes it in using belts. 
![image](https://github.com/user-attachments/assets/48e5b0a8-9d79-4131-83f6-005a8e156b37)
6328's intake is just some rollers that intake the ball, and then  the hopper centers the balls. it's deployed using pistons
![image](https://github.com/user-attachments/assets/322b6665-5ad7-4393-be03-86477bd44f9e)
254 uses wheels to intake the ball and pistons to deploy.
![image](https://github.com/user-attachments/assets/33f6d44d-c324-48f1-9ed6-6ec23831ce7d)
1678 uses wheels to intake and pistons to deploy. i can't really understand what is going on, and how it works compared to the others because a bunuch of things are transparent/kinda transparent.
![image](https://github.com/user-attachments/assets/2bb4c2b0-aac0-498d-99e6-9db23ad0d771)
for 4414, i have no idea how their intake deploys, what i do know/what i can tell  is that they use wheels to intake. 

# session 38:
![image](https://github.com/user-attachments/assets/5291d8d0-1fab-4ec3-811d-a9f34b929668)
on the side of 4414's intake, i can see this thing. i think that there's like a pin or something that slides along the piece, but i'm not sure how it even retracts.
there's literally nothing attached to it, other than the intake.
i decided to watch some games that 4414 participated in 
https://www.youtube.com/watch?v=S78mJ4DjnDk
i watched this video, and i saw that the intake was able to stow all the way up, and then go downwards to intake. i have no idea how they do this, since the arm isn't connected to anything that can make it move. like HOW. HOW DOES IT MOVEEE.
https://www.youtube.com/watch?v=Sy9afD-bew8
this is their promotional video/robot reveal
![image](https://github.com/user-attachments/assets/56946fe3-56fb-4e5f-aacd-7fb19d5b27e6)
ohhhh so it moves through pistons
ok wait nevermind, that isn't the right robot (the 2020 and 2021 seasons were the same game, 2020 was cancelled due to covid)
i had to look for their 2021 robot.
https://www.youtube.com/watch?v=EjCz7m7TRaM 
ok so apparently the intake just doesn't move. that would've been nice to know. i gotta check the 2021 rules for frame perimeter, since i'm not sure how far that intake can extend over the bumpers. 
![image](https://github.com/user-attachments/assets/ddda58be-4a4b-4961-ba14-ab69d0ce4d3c)
hmmm ok 30 cm. that should be enough space. maybe?
ok yeah it should be, the diameter of the ball is around 18 cm.
i have no idea where i'm going to mount this, or how i'm going to start the intake.
i decided to start by sketching where the rollers/wheels would have to go. 
![image](https://github.com/user-attachments/assets/2c3b850a-2479-462a-830c-01cea9f0627e)
general sketch/outline.

# session 39: 
i think i want to increase the compression between the wheels and the ball. 
![image](https://github.com/user-attachments/assets/d384d57f-d740-4be0-86db-eb0ab281759d)
i think i want to figure out some belt stuff now, and then move onto mounting later on.
![image](https://github.com/user-attachments/assets/8dfd112a-a168-4dcd-bf24-e87133e0d978)
2910 uses a 24:16 ratio or 1.5:1 for their belts and wheels, basically wanting a bit of torque but not too much. 
![image](https://github.com/user-attachments/assets/c061a09a-3731-4cf4-92d1-ee3c4482407f)
4414 uses a 1:1 ratio. 
![image](https://github.com/user-attachments/assets/26f58b2e-9ab5-4540-a673-10f1cb304db7)
1678 has this setup (i'll count the gear teeth, maybe.)
(it goes across the entire robot to get to the intake)
uhh so they have a falcon 500 with a 14 tooth pinion which goes into a 52 tooth gear (52:14) and then it goes to a 1:1 ratio of pulleys
![image](https://github.com/user-attachments/assets/5d4f2c68-37a2-4909-a196-b446307b09e9)
![image](https://github.com/user-attachments/assets/ae27f4b6-280d-4ce0-a75a-824231650878)
and then it goes to these orange rope thingys, which i think is called polycord, i'm not sure how to calculate the ratio for this, so i'll calculate it as if it's a pulley, because it seems like it'd be calculated like a pulley. it's just 1:1 
all of the other pulleys in their intake is 1:1, so basically it's 52:14 for their intake. 
![image](https://github.com/user-attachments/assets/cbb67d74-af41-41bc-8fca-11df93a1a207)
i think i'll use these pulleys. 
![image](https://github.com/user-attachments/assets/8e45fb17-2ec4-42e2-a07c-3ce840386690)
so many circles...
![image](https://github.com/user-attachments/assets/68b9846a-2d71-4b64-a30b-78c948d59f6f)
oh no
![image](https://github.com/user-attachments/assets/7c668000-fda7-4322-aa71-a9090130ebf9)
taht might be a bit much
![image](https://github.com/user-attachments/assets/831e5ca6-3229-4c9c-a451-66049d7a211b)
this should be good enough. 
![image](https://github.com/user-attachments/assets/eab16091-79ac-4422-b7aa-31d89b26ab18)
i think i'll add some more belts over the top, to make sure that hte ball can't escape.

# session 40:
![image](https://github.com/user-attachments/assets/f1cde672-baad-4c8e-ae9c-c750a036d736)
okie dokie, now i need to make a frame for the intake and eventually mount it. 
![image](https://github.com/user-attachments/assets/963aaf8d-9051-48a0-8134-70a929cc7241)
i can already feel how scuffed i'm going to make this. 
![image](https://github.com/user-attachments/assets/0663aff8-c284-4f9e-bd8b-6e8e43a7150f)
i think i probably need to change a couple of things tbh. the mounting from the drrivebase to the first pulley is kinda scuffed, i think i also need to connect the mounting a bit to the 2nd belt/pulley
![image](https://github.com/user-attachments/assets/36034c0b-5263-4e3d-a46d-88d64a51a151)
i guess this kinda works, but i think i want to smoothen some things out.
![image](https://github.com/user-attachments/assets/6f93ef89-7021-4a64-8c49-eb3b1122314b)
it seems alright? ish, i feel like something just wrong about it, but i don't know what it is. 
![image](https://github.com/user-attachments/assets/27fb529c-21ff-493b-8694-eae90d9d6c99)
oh that's going into the swerve modules. 
i think i want to look at examples of intakes to see how they sort of shape their intake plates. 
![image](https://github.com/user-attachments/assets/ec55ad15-fd35-42ec-b41d-5a1418f20127)
4414 did this. the problem i have is that i don't know how to not mount the plates onto the drrivebase tubes, since that's like the only way i can/know how to do it. they mounted their intake plate somehow to their bumper backing (which is wood)
![image](https://github.com/user-attachments/assets/9a5090fd-e888-48dd-a8a3-f2d15516a1d7)
how did this happen.
![image](https://github.com/user-attachments/assets/ba512cbc-8e41-4180-a309-30898d9d0a3d)
why's everything breaking
i think it's just easier to delete them adn then redo it, instead of trying to fix it.
no matter what i do, i just can't seem to find the right shape for the plate.
fjlksjf;alsjfdasfjalsfkdals;fdjaskfjd this is slowly stressing me out.....sjdklfjsa;dfalksjsa;fdjaklsdf
![image](https://github.com/user-attachments/assets/271e4ada-4930-4eab-b613-5050acc7ad5a)
i think i might just make a large circle. 
![image](https://github.com/user-attachments/assets/454711af-beb5-4e99-ad95-3972d2f98110)
why do complex line things when you can do big circle
![image](https://github.com/user-attachments/assets/7d85326f-c135-49eb-a522-00bb30b942c9)
this is so peak
![image](https://github.com/user-attachments/assets/2cf6ba61-4d67-4d67-b01f-e859819f373b)
anddd it interferes with swerve modules. yiipeee.
![image](https://github.com/user-attachments/assets/f4c0534d-b80f-455b-aa36-f0321b575f61)
i feel like hte line that is dimensioned as 200 is being stretched out quite a bit, but there's not much i can do about it. it has to fit somehow.
![image](https://github.com/user-attachments/assets/72b5cfc7-0cab-44c2-a3d4-ed366d26905a)
aw heck nah
i managed to fix it
![image](https://github.com/user-attachments/assets/8982f162-509b-46a8-b6eb-0024782ba83d)
welp new problem.
![image](https://github.com/user-attachments/assets/b337888a-4f9d-49df-b37d-a2eb863bebc4)
the problem was literally this one small piece/area. why.

# session 41: 
![image](https://github.com/user-attachments/assets/dc57bfdc-080e-4dcf-9c10-48949d422dbc)
WAIT WHY DOES THIS HAVE CORNERS.
![image](https://github.com/user-attachments/assets/ce7a1c9e-f040-4209-895a-dc39436945f5)
ah wait nvm it's just because my graphics settings are on low, which makes circles do that.
hmmmmm well, time to figure out motor mounting, plate mounting, then it'll be onto assembly (aka the biggest pain ever)
i might do a bit of lightening on the plate, but if something hits it then it'll probably take a lot of damage, so i'll flip a coin on it. 
![image](https://github.com/user-attachments/assets/12cc523f-6ab1-42d6-9f7b-27e8a6aa9971)
nooooooo 😭 lightening my goat (i'm still going to do lightening anyways)
i think i'll do some lightening on the thicker areas, to make sure everything doesnt immediately explode the moment it gets hit. 
![image](https://github.com/user-attachments/assets/e1150a36-ea69-47d5-8d7a-ce9c1ee5fe26)
i think this might be good, not sure though.
![image](https://github.com/user-attachments/assets/ac47f64c-a089-4b80-a22e-dda7cf79a9a6)
ok so the external line doesn't work (i thought it would do it, but honestly it's kinda fair that it doesn't, since i didn't specify a face for it.)
![image](https://github.com/user-attachments/assets/f8c5bf28-dab8-422e-bb46-1bd130d724f8)
second problem is this
![image](https://github.com/user-attachments/assets/b11a19a7-28a6-4ba8-9f14-b7c83477e269)
some gaps are still left, even if i amp the wall thickness up by a lot.
![image](https://github.com/user-attachments/assets/1a754e87-07b7-4442-891d-197df74d0f75)
not scuffed, i don't know what you're talking about.
![image](https://github.com/user-attachments/assets/8583c902-716a-48eb-a5c4-02f05290ae73)
gotta fillet some edges first
![image](https://github.com/user-attachments/assets/38101856-d74a-4001-8596-21c011405e2a)
i gotta add some more ribs, adn fix up some of the ribs.
![image](https://github.com/user-attachments/assets/943817de-a9da-4ca2-a0c0-c428db882815)
i think i wanna adjust this a touch. 
![image](https://github.com/user-attachments/assets/ac9da8d1-3667-4a08-a405-a0022b19bb57)
lightly scuffed
![image](https://github.com/user-attachments/assets/e3d0a168-286c-4de8-9a58-2ca7bb18b985)
that actually kinda worked. ok so i guess imago focus on motor mounting. i'll probably do 1:1, or maybe something like 1.5:1 
ok what i might do is, because of scuffed bearing placements and stuff, i think i'll do a 12 teeth motor pinion, into a 24 tooth gear, and then use pulleys to reduce it.
![image](https://github.com/user-attachments/assets/d6cee47a-a2b1-4ed8-aff4-fccf1357c342)
that's scuffed.
i think i'm going to do a 30 tooth gear.
i decided on 42 tooth pulley to a 24 tooth pulley. 
![image](https://github.com/user-attachments/assets/4c6225f4-79bb-480d-a03f-daa2937f6778)
uhhhhh...
![image](https://github.com/user-attachments/assets/aaa1bf32-f2d4-4fc0-82c3-b0f493e04cb4)
ok cool.
![image](https://github.com/user-attachments/assets/158f0bcd-aa5d-4c18-af81-7162ee139814)
some things are brokennn

# session 42:
![image](https://github.com/user-attachments/assets/a809039a-96ad-4cb5-a830-cc45a20e9b09)
bruh it refuses to work. even if i try changinng wall thickness and rib thickness, it still doesn't work.
changing rib thickness to something really low like 0.1 mm makes the existing ribs smaller, but doesn't make any new ribs. changing wall thickness to someting low makes new ribs, but at the trade off of removing too much stuff. 
line 1000
i think i might just not change anything with it, and keep it like that. (not like i can change it much anyways.)
now i need to move onto plate mounting
this is going to be fun, because i didn't put any holes on the side of the drrivebase tubes, this is going to be 100% speculation on the hole patterning, but it doens't really matter since nobody's going to make this. ok, well maybe not 100% speculation, but around 30%.
![image](https://github.com/user-attachments/assets/717d15f4-15dd-4aab-b63d-ac087adcbcd0)
that should be good. ok, time to assemble i guess. 
![image](https://github.com/user-attachments/assets/76dfbeda-e2ba-425e-bf60-eb8fe5f79244)
and it broke.
i think i'm just going to remove the part lighten.
now, back to assembling.
right now it's such a pain to look at the amount of holes so i can mount things in the right spots. 
ok so i quickly realised that i hadn't made an area for me to mount the indexer gearbox on.
![image](https://github.com/user-attachments/assets/42287664-9576-4d06-9211-01adf2835ed3)
it's going alright.

# session 43:
more assembling i guess, there won't be much talking/typing, since assembling shouldn't have too many problems (hopefully.)
![Screenshot 2024-08-13 220114](https://github.com/user-attachments/assets/203e522e-9b3c-4f9d-996a-e949e4283d7a)
guess and check please save me
![image](https://github.com/user-attachments/assets/30b0a1b9-e6ae-4198-8c18-281b70f55dcb)
ok, problem i just realised, the ball may not go onto the hopper, or it may get stuck somewhere, because i was kinda dumb and didn't realise how far above the hopper is from the bumpers. 
![image](https://github.com/user-attachments/assets/e7430c84-5653-4bf4-88aa-ba8873d0f61e)
when i was checking for the holes for the gearbox on the hopper, i realised that they aren't aligned. 
![image](https://github.com/user-attachments/assets/30faa0cc-7f8e-4e06-94c2-95ddcda90b8d)
AW HELL NAH.
![image](https://github.com/user-attachments/assets/1aa33715-2c8c-42fc-a5f4-00af2e89d65a)
omg it was all misaligned in the part studiooooooooooooo.
i used the mirror tool for the tubes, but now i have to fix the flow-on effect.
![image](https://github.com/user-attachments/assets/f0a33ca0-f45a-4e35-a385-cfb34519a36c)
jlksdjfaslkdfjsadfl;asdjf;saldfjsadflkasdfjasldfkjaslkfjwioreuqwpoitueqwiotuqioweutwioetupwoqite

# session 43: (the second part)
(the second part)
![image](https://github.com/user-attachments/assets/79c73556-a587-4c21-b9bc-328be5571580)
the holes are now in the right area (or, well are horizontal to each other/vertical/idk)
now i just need to change some things.
![image](https://github.com/user-attachments/assets/1e1fab12-c87a-40e5-a8c1-00336d5b74a1)
i decided to make the plate wider, since things were becoming too small and too compacted.
![image](https://github.com/user-attachments/assets/b12b1dc7-7ec0-4da1-90fc-6bda2b03d4c5)
part lightening is a bit scuffed, and it's not lined up :(
uh so i minused the hole distance that was measured, instead of adding it. 
i'm smart like that. 
![image](https://github.com/user-attachments/assets/51f62e7a-8ed2-4fd2-8ac2-e49943f6ab01)
i added it, and now it's too large...
![image](https://github.com/user-attachments/assets/d917cbc5-738f-41ad-a26e-4a36e2e85428)
bruh...
i think i know the problem
the amount that i measured from the hole to hole distance was accurate, it's just that i had minused something before, and then replaced it with the new dimension/distance, basically making it longer because there is no longer the minus thing to balance it out.
![image](https://github.com/user-attachments/assets/3239ba99-aadf-43fc-86fa-8fafdb520fb3)
ok epic, time to change the part lightening.
![image](https://github.com/user-attachments/assets/0f2d9144-eb26-44b5-a262-2b74a87c8c06)
i think i might add some diagonal lines.
![image](https://github.com/user-attachments/assets/b385b598-c2fb-4964-8f15-749aff5de8b0)
this is PEAK.
i feel happy with this.
i think i'll feel happier when i complete assembly (it's gonna be a pain.)
![image](https://github.com/user-attachments/assets/b3395031-e3c5-4c31-bbe9-b445f45d273c)
OHHH WAIT NOOOOOOOOOOOOOOOOOOOOOO
![image](https://github.com/user-attachments/assets/723c8c69-f569-4bf2-92f7-dc799aba7c2e)
whathtatatatatatat
ok. i have a crazy idea.
i'm going to measure the distance between the tubes
and then use that for the measurement of the gearbox, instead of taking the measurements between the hole on the gearbox and the hole on the tube. 
![image](https://github.com/user-attachments/assets/dde016ca-9c5d-49d5-97e3-9a55a3485c53)
dude i'm so smart.

# session 44:
i looked in the arcade-help channel, and found out that i had to commit .stl/.step files every session this is going to be a pain, because i thought i only had to commit them at the end of the project.
oh well.
ima commit some stuff right now
i won't include stuff like belts or standoffs for now, since that'd be a pain to do, and you don't need like 10 different orientations of the same sized belt. 
![image](https://github.com/user-attachments/assets/f6f5d6da-c8cd-4b46-82ea-5fc8c04aa7a2)
where's the export button :(
![image](https://github.com/user-attachments/assets/bc883c14-2fc4-42fa-b648-2399c83d480b)
either i'm straight up blind, but i swear there's meant to be an export button.
![image](https://github.com/user-attachments/assets/b0d06abb-3cf8-49a3-a23e-e3f8da2d81b1)
well apparently i needed to right click the part name thingy.
anyways, time to go back to doing assembly
![image](https://github.com/user-attachments/assets/1cd6d928-5ad8-42a0-94ad-18a5577e2fa3)
NOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO
![image](https://github.com/user-attachments/assets/700aaeab-222c-446a-878c-83abe55f4681)
apparently only the fastened was the problem, but i can't seem to click on the tube's mate connector. 
ok nevermind, it's being fastened by fastened 22, i can just delete fastened 21. 
i decided to put bearings in all of the bearing holes now, and then work towards getting all the stuff on the shafts down.
![image](https://github.com/user-attachments/assets/a2f227a9-e91a-477b-8398-ebeec5e08153)
bearing.
there's so many bearings and bearing holes.. i feel like it'll take a year to get this all done. 
![image](https://github.com/user-attachments/assets/380dcd50-6d56-4489-a318-a8a2b5211634)
there's so many of them....
![image](https://github.com/user-attachments/assets/14ebb6d0-4f9a-492e-8c16-473359d45034)
OHHH WAIT NO I FORGOT ABOUT THE HOPPER BECAUSE I MADE IT HIDDENNNNN
asdfasdfsdafsadfsafasdsaf 
more.. clicking... asdfjaskldfjasklfd
![image](https://github.com/user-attachments/assets/1179925a-3554-44ae-a9f9-d5cbdf0e667a)
there's like no neo pinions... what..
i think i might use the 12t 20dp cim pinion, because it looks like it has a key like the neo. (btw a key is like a thing that allows the motor to spin things, because the motor's shaft is circular, if it doesn't have the key it just spins and doesn't do anything.)
![image](https://github.com/user-attachments/assets/c6c53a3c-b717-4c42-bd47-2c0870bd5be9)
and it fits perfectly.
![image](https://github.com/user-attachments/assets/b70f4686-00c4-47c3-a9b6-509a25dd64fc)
2 gears.

# session 45:
spinny
one thing i didn't account for with the 42 tooth pulleys, are that you have to put bearings in them for them to interface with the hex shaft. 
i searched for solutions to fix it
ok nevermind, you can use a versahub for it to work. (a versahub is like an adapter.)
![image](https://github.com/user-attachments/assets/b1140896-1a22-4e5e-9472-42a925a2157d)
can't really see it from this angle, but it fits.
![image](https://github.com/user-attachments/assets/506203d5-19ea-4cd1-88e6-89a529ed7d51)
it's all coming together.
i realised that i didn't make a lot of the different shafts that i would desperately need.
also while i'm in the part studio, i decided to change a couple of the structural things.
![image](https://github.com/user-attachments/assets/6852b0c0-4fcd-45c9-9b4e-1cf78fbb2943)
mmmm yes.
![image](https://github.com/user-attachments/assets/ec32acba-a1df-4d01-a1c6-b621e5d7474c)
today i find outu that you don't need a point, you can just select the edges of a circle and it'll put it in the middle.
ok, i think i've got all the shaft lengths, time to get back to assembling.
![image](https://github.com/user-attachments/assets/9514e0b5-4416-4c26-8ea5-265670dc0163)
oh man it's going to be fun trying to figure out which length of hex is the right length.
![image](https://github.com/user-attachments/assets/4bbcd066-9e22-4556-94f6-b5d8d0e36c0d)
ok so i underestimated the length that i needed.
ok nevermind, i clicked the wrong shaft length.
![image](https://github.com/user-attachments/assets/7236c077-b40e-4272-837b-e9f78cd46cee)
hmmmm it seems a bit short.
mmmm, yeah it was way too short, by a long shot. 6328 used around 100mm between their hopper and the pulley.
![image](https://github.com/user-attachments/assets/9fcb69af-5dd3-4426-a159-0a6ce93868fb)
now that feels too tall.
![image](https://github.com/user-attachments/assets/fdc69d26-28c8-4b90-b566-eae19d49335b)
well uhm... that's not entirely good. (6 seconds D:)
![image](https://github.com/user-attachments/assets/c2d1e742-6e55-4649-af56-d20b9dc10c1f)
that seems good.
![image](https://github.com/user-attachments/assets/a3a760bb-46cb-4903-a0bb-5f973916ad0b)
ooooo it's all coming together...
![image](https://github.com/user-attachments/assets/61360fa0-bfdc-4708-8e8c-477235c2dcc9)
i have to use 2 fasteneds here because the angle is scuffed, and i can't just turn the secondary axis to easily put it in.
![image](https://github.com/user-attachments/assets/b04d36e5-6c6c-4716-9fb6-a2a30c0e1d9e)
jaskldfjafklsadfjasfklsjdafklas;dfj i can't do it.
i don't know how to change the angle without guessing and checking...
so after like 10 minutes
![image](https://github.com/user-attachments/assets/a982bc77-4fdb-42f3-9dcd-2ca7a0221bcb)
i'm so smart (not)

# session 46:
it's session 46
![image](https://github.com/user-attachments/assets/d7312dd4-7c66-486f-9ee9-422feb89cc60)
ALSO OH MY GOD IT JUST KEEPS GOING UP...
![image](https://github.com/user-attachments/assets/5fcc962d-0db0-4cdd-a209-095d544751b5)
dude i'm going to  have my downloads absolutely FILLED with cad files of this, and each of em are going to be
![image](https://github.com/user-attachments/assets/26193526-8768-4bd3-8d33-3e776097fe6a)
THEY'RE GONNA BE LIKE 700 MB EACH.. (luckily i can delete them, but holy, my storage is only like 500 GB or something)
al;skjdfalskfjsaldf oh well.
not much i can do.
![image](https://github.com/user-attachments/assets/6a136e93-f716-41a1-a2e4-3de25b330bea)
also uh...
oh well, nothing i can do about it. 
![image](https://github.com/user-attachments/assets/c0adcb1e-cc0d-4549-bfc1-07d6ce01e7f3)
ok, uh i'm kinda dumb.
![image](https://github.com/user-attachments/assets/d0137122-defa-4d55-9682-e9db3d03b14d)
ok well i tried.
![image](https://github.com/user-attachments/assets/4443667d-b12f-4423-9596-6f1cd901a2c5)
that's... not going to work.
![image](https://github.com/user-attachments/assets/4d1669b0-39bc-4a82-b4f9-2bb5c86f1713)
time to guess and check.
![image](https://github.com/user-attachments/assets/622def28-37a5-4df4-a1ab-51e94f7872be)
i mean if nobody looks tooooo closely, it's fine.
![image](https://github.com/user-attachments/assets/108d3dbd-1734-468d-9e23-45557da4150a)
why's it misaligned....
time for more guessing and checking.
![image](https://github.com/user-attachments/assets/b8b1e00b-1f14-497d-b650-b50389e917a1)
alright cool.
![image](https://github.com/user-attachments/assets/83fac5f9-b214-4110-a0a0-5a839895b4b2)
it's still slightly off.
![image](https://github.com/user-attachments/assets/3623ca79-931c-4252-bd08-733040cbd2eb)
yep things are breaking.
![image](https://github.com/user-attachments/assets/52dcc97f-3c37-481e-ae56-4a1a1c19b1e9)
and it's not even aligned.
![image](https://github.com/user-attachments/assets/9939bcd2-9738-42fa-b6c0-ce96aa8d3576)
ok so the problem was that i had mounted the gearbox on the wrong hole. time to revert some things.
![image](https://github.com/user-attachments/assets/ac696c28-411d-4f50-ab4c-7ad704672f0e)
cool close enough.
![image](https://github.com/user-attachments/assets/154fa139-00dc-40aa-a33f-0df5e01bb949)
epic.

# session 47
no colon this time
![image](https://github.com/user-attachments/assets/5bc23097-efe0-44ff-8c5f-e41309172f83)
ok so there's some things wrong here. the difference between the 2 sides are quite apparent. (right side has the orange hex shaft being shorter/lower, and the grey one being a too high up, as nothing sticks out from the bottom.) i'm kinda confused on why this is happening, so i checked the fasteneds associated with the hex shafts and the thing going across the top.
![image](https://github.com/user-attachments/assets/9e95207a-d553-4c2a-a268-1d10a3862b93)
ok, so the problem was that i had no offset on the fasten for the thing going across the top. 
i also had fastened the grey hex shaft to the wrong side of the bearing.
![image](https://github.com/user-attachments/assets/d3963752-dd6f-4299-8dae-82bd999c4bac)
i fastened it to the top, when i should've fastened it to the bottom.
![image](https://github.com/user-attachments/assets/442de034-2ccd-474e-a694-8d7d85aa3cc4)
all pulleys for the gearbox and stuff are in place.
![image](https://github.com/user-attachments/assets/b3e482a3-9b0e-4982-971f-392e4c674faf)
the pulleys are in place. 
![image](https://github.com/user-attachments/assets/5bdaa4fe-7f56-4ff6-af14-11ad65d49b64)
whar. i thought i selected the right belt. ok turns out that i did select the right belt, but the problem is, the mate connectors are kinda scuffed.
![image](https://github.com/user-attachments/assets/8337cbe4-d94b-408a-8049-a3bced00471f)
hmmmmmmmmm
![image](https://github.com/user-attachments/assets/88989200-1d19-4912-adbb-a79e8b03027b)
had to do some guess and checking, i guess it works.
i can feel my computer slowly dying as it tries to render stuff in onshape. i can feel the lag.
![image](https://github.com/user-attachments/assets/90fbd6af-b7eb-431c-bdb6-dd32a909fdb4)
progressssss !!! i'm quite proud of my progress right now.
time to do some mounting for the hopper.
![image](https://github.com/user-attachments/assets/7216c56b-bd43-49ab-91b1-1fd56f36e6ae)
uh wrong shaft :(
![image](https://github.com/user-attachments/assets/aa763be3-61a6-4c68-8f71-ef4e35037c48)
uh too long.
whilst i was doing all of this, i realised that the mounting for the parallel tube is kinda weak. i can't use the L bracket beacuse number one, there's only going to be one hole that attachs the bracket to the tube. so i realised, that i'm kinda dumb, because i can put 2 T gussets on the top and the bottom of the parallel tube, and some 25 by 25 tubes to help mount the T gussets. i will still let the parallel tube to rest on the drivebase.
![image](https://github.com/user-attachments/assets/f4c31c70-e4d9-4776-b62c-5a67ad21927e)
alright epic.
![image](https://github.com/user-attachments/assets/f9cb04a8-0c98-436e-9bb7-0f01818a583a)
how'd this become unconstrained.
![image](https://github.com/user-attachments/assets/013d6d57-28c2-4193-8654-4e341a363aad)
ah right i forgot some holes.
![image](https://github.com/user-attachments/assets/f6233c68-2df9-4ba1-92df-ab7dcd96ed4a)
WAIT THE TUBE IS NOT ALIGNED. WHAT. WAIT WHAT. HOLD UP, WAITTTTT.
![image](https://github.com/user-attachments/assets/5aa50113-59ce-4f7a-a868-5bb739b85ddd)
i think i might extend the t gusset, but that's for later, the tube is the current problem.

![image](https://github.com/user-attachments/assets/94745129-647c-4b85-bf52-3127a0f309b8)
hmmmm ok.
![image](https://github.com/user-attachments/assets/4bfbbf92-0a15-4fbc-a5d2-a17731c9c904)
uh what.
![image](https://github.com/user-attachments/assets/2af694af-be4b-484f-8400-fba1cb40caad)
so many numbers.
![image](https://github.com/user-attachments/assets/63c26382-e381-4d25-bf67-6c0688458217)
WHATTTTT
![image](https://github.com/user-attachments/assets/2c06e413-cc7b-46d2-8881-d91f8a03022c)
YESSSSSSSS (i just had to minus it.)
![image](https://github.com/user-attachments/assets/42f7e0a3-6c28-4d26-a7f3-16f5950878a0)
balling.
![image](https://github.com/user-attachments/assets/cf26d8e9-dcaa-417c-9d63-274dead61b66)
ah right, i didn't take into account the standoffs. yeah i'm pretty (dumb) smart
i kinda need the t gussets but i also need the standoffs.
![image](https://github.com/user-attachments/assets/9ce1a185-d134-4e36-9b59-7653e6ac6e9c)
6328 uses only 3 standoffs... and their hopper is 476mm wide.
mine is 550 mm wide.
surely it's fine, right???
![image](https://github.com/user-attachments/assets/b914e36f-1374-4789-9b56-86fb675384ce)
argh i gotta go to sleep now, but i think i'm going pretty well.

# session 48:
hmmmm ok, so i think that i need might need to find a way to mount the standoffs, but i'm not sure how to.
![image](https://github.com/user-attachments/assets/dc38ce71-081c-49db-bec5-929d04340e56)
epic. i don't want to reduce the size of the t gussets, since i still want some strength, and i don't want to mount the standoffs to the gussets, since it might be kinda scuffed. 
![image](https://github.com/user-attachments/assets/62db832f-f159-465b-ae6d-af0355f30cd8)
i could mount them to teh swerve modules, but they might be too close to the other standoffs. 
so it turns out their center distance between their hopper standoffs is around 225mm.
mine is around 236mm. i think it's fine to be honest. 
![image](https://github.com/user-attachments/assets/e9e5835b-a198-4c4d-bc3c-3770d860da86)
epic.
![image](https://github.com/user-attachments/assets/f3b81d6e-e3b1-4278-923e-bb78a6426202)
epic.
i realised that once again, i had forgotten to add some of the shafts that i need, like the gearbox shafts on the indexer.
![image](https://github.com/user-attachments/assets/ffef0555-f573-41bb-92e6-f37ae51a2cd7)
some things added in, and some lengths changed.
![image](https://github.com/user-attachments/assets/5f073f58-e35c-4668-9439-f43584de74ee)
it's all coming together.

# session 49:
lately i've been behind on my commits, since i'd started to cad during the time and then make commits later. 
so i've attempted to cut back on the cadding and work on commits.
![image](https://github.com/user-attachments/assets/523ccd04-fcee-4de7-a890-d22c569d0e95)
ahhhh ok i should've expected that. uhm... i think i have to adjust some things. i think this will only be a problem when it enters the indexer, since it'll have to go over a big bump, and then go into the indexer which it might not be able to. 
alsdfjals;jdfkljfas;fd
![image](https://github.com/user-attachments/assets/90f532c6-f8a4-4cb3-b4f8-81b82c20e505)
this is where the pulley would be at the most extreme level.
it also means i have to adjust some pulley and belt sizes.
asdfjdsakljsaf;ksladjfa;sldfjk;asdf
![image](https://github.com/user-attachments/assets/a351c3cc-1d55-4399-a1d0-da1d28e48fc5)
hmmmm that might be a bit much...
![image](https://github.com/user-attachments/assets/27a5c630-d729-48c2-a64d-c299e52cd45e)
i had to try and adjust some things in the gearbox to try and fit things in. 
![image](https://github.com/user-attachments/assets/b356e3bc-f80f-4e0b-8a35-ee4f5174c5e7)
i pushed the indexer middle gearbox pulley stuff downwards, so that they would be able to push the balls into the indexer much, much easier.
alright, i might also adjust the size of the indexer as well, and i will also have to add things to the indexer plate.
![image](https://github.com/user-attachments/assets/d093eec3-c851-43a1-87d8-1bd539fbedb0)
the mount has been created.
![image](https://github.com/user-attachments/assets/f38eb835-694e-44ca-a530-bcad1ce3a169)
hmmmm ok.
![image](https://github.com/user-attachments/assets/b0124eae-3879-409d-a8af-0c1af71c1def)
everything's breaking.
![image](https://github.com/user-attachments/assets/0e646f83-f8d4-4c3a-a604-a098224887fd)
oh god everything's breaking... asdfmlsdafkjsafdsaklfdjsdal;f
![image](https://github.com/user-attachments/assets/02875973-796b-449a-8d06-fde568c88852)
this is so scuffed. i need to fillet a bunch of things now.
![image](https://github.com/user-attachments/assets/42015df6-3c26-4d6d-a975-754de80ff22c)
i might as well fill this in.
![image](https://github.com/user-attachments/assets/c85e972c-3f9c-46bc-b193-427b9cc6d1d2)
close enough.

![image](https://github.com/user-attachments/assets/3c6d8144-b654-42bb-8aad-6faef1e0f06b)
good enough.
things are breaking everywhere in the assembly. 
![image](https://github.com/user-attachments/assets/1c322f2b-11c9-4300-85db-32a52cece46d)
there's a flat line that i need to fix.
![image](https://github.com/user-attachments/assets/e1e20fc4-f9f8-47ec-9923-50e26e42e563)
wuhh..

# session 50:
![image](https://github.com/user-attachments/assets/9f97d94b-f9fd-4677-bcf7-aaa1d1981fc6)
i decided to just make an exclude region to fix it instead.
![image](https://github.com/user-attachments/assets/94706e76-0227-4fad-b224-8039212f2c14)
oh no....
the motors are clipping into each other.
the bad problem is, i don't remember what pulleys i used for the motor to the shooter, so i can't really calculate the distances.
i had to look through my sessions to find it. uh...
so in session 36 i decided on a 30 t 9mm wide 5mm htd pulley. ok.
![image](https://github.com/user-attachments/assets/c303cea3-bab8-41ee-b0e8-d0f66e3b4a78)
ok 115 t belt it is. 
![image](https://github.com/user-attachments/assets/803ffad9-a2da-40c0-aeb1-8926227ba3fb)
more problems. sigh.
![image](https://github.com/user-attachments/assets/9c283de7-7a56-4aef-a548-12991dc13b92)
what the scuffed.
tis fixed now.
![image](https://github.com/user-attachments/assets/bc704c59-0eec-4d09-90c5-41c24a8b40fb)
ok i think i need to reduce the length of the part that comes out of the hopper.
![image](https://github.com/user-attachments/assets/de3be2b9-110d-41cb-9426-9d1b2a419a0f)
hmmm need to reduce more.
![image](https://github.com/user-attachments/assets/ccab3339-c1e2-457d-bd22-223d8b34d641)
i need to reduce it even more somehow.
![image](https://github.com/user-attachments/assets/5d0509f2-9b18-4429-ab85-e5332eb5f9f3)
actually, i might change it a bit to make it a bit cooler. hold up. 
![image](https://github.com/user-attachments/assets/165ff5df-0a8d-4235-9be5-6365e2aa3c70)
epic.
![image](https://github.com/user-attachments/assets/af44c066-79e5-439e-98dd-9765bbb78fde)
gotta reduce it slightly more.
![image](https://github.com/user-attachments/assets/39cb5e64-77e8-4b43-ab92-a9e7521d4c2c)
ain't no way it's off center. i think that the pulley is off center.
![image](https://github.com/user-attachments/assets/a0d97ab0-027c-485b-af76-9fc10b72a0cd)
i minused when i should've added. 
also, uh i think i need to make it wider just to make it 100% sure that it can fit. 
![image](https://github.com/user-attachments/assets/65dc12a1-8cb9-4809-a314-6da1b5ce2fcf)
tis getting there.
![image](https://github.com/user-attachments/assets/78920b13-43ef-498a-a892-d31cd896a2e3)
hmmmm yes.

# session 51:
i was about to get back on the assembly grind, but then i realised that i had forgotten some belts.
![image](https://github.com/user-attachments/assets/7dfcc443-2b98-46dc-b7cc-d679630660f9)
i forgot what pulley i used here. ok so i don't think i ever decided on a pulley on teh shooter, so i'm going to go with something like 42 t pulley.
![image](https://github.com/user-attachments/assets/99676fc3-ae34-4678-a7ac-60c67eafb3b7)
why it no work.
ok wait i think it's because they're not on the same plane.
![image](https://github.com/user-attachments/assets/f1706095-7574-44d2-ab83-0010dc9e8495)
also i double checked, it's going to be a 125 tooth belt. i think i inputted the wrong settings
ok time to hop back on the assembly grind
![image](https://github.com/user-attachments/assets/2091c391-f9b8-414d-bc4e-0defb59b0b95)
yeah that's definitely a belt (i think)
![image](https://github.com/user-attachments/assets/3dcd917a-c323-45d4-9af5-3d740b44f616)
wait where did the versahub go
![image](https://github.com/user-attachments/assets/b0426b67-e6e5-4a94-9337-a72923f43d8e)
WHAT HAPPENED HERE...
![image](https://github.com/user-attachments/assets/6f8a947c-ab38-4cb6-a91e-788c46197d12)
OHHHHH NOOOOOOO (i somehow clicked the hex shaft and thought that nothing went wrong, i think it's because i think i tried to pan around the model, somehow left clicking.)
![image](https://github.com/user-attachments/assets/066fc849-4ef9-4f56-9eef-67823f820ec0)
guess and check goes crazy.
![image](https://github.com/user-attachments/assets/a34148ba-591b-486b-b356-9497af0017e0)
epic. 
i think i want to change the colours of the plates to make them look cooler, and then i'll go back to the assembly grind.
i think i want a grey colour of sorts. 
![image](https://github.com/user-attachments/assets/138c639c-05f6-439e-b76e-81e93f96bddb)
ok so i realised that i needed to extend this shaft, because i need to add the pulley.
![image](https://github.com/user-attachments/assets/eb414fae-ad3f-4a32-94c0-2bd057c0508f)
hmmmm that's short... ok, so i realised that i didn't account for the thickness of the plates. rookie mistake :(
i had to adjust some of the other shaft lengths because they were also slightly short. 
![image](https://github.com/user-attachments/assets/130b1ba9-2eca-4b9c-9f6e-936d78accbcd)
ok maybeeee i shouldn't have fastened the pulley to the belt. 
![image](https://github.com/user-attachments/assets/5935982d-b56e-40b9-a19a-7f9c520af8b6)
hmmmmm
![image](https://github.com/user-attachments/assets/2c2035d2-e6a5-4219-922c-8fffd25193b0)
mmmm yeah things are breaking now...
![image](https://github.com/user-attachments/assets/cbfddc4a-eb1b-41a7-a2ce-efbcb3567372)
i tried to use slider but it doesn't really work out.
![image](https://github.com/user-attachments/assets/0ac011f5-b326-48fa-bc7f-f3a2ab4c2691)
well cylindrical works.
![image](https://github.com/user-attachments/assets/238e662b-819a-408e-acf2-c6bb8957dd9e)
oh no it's all unaligned.
![image](https://github.com/user-attachments/assets/ad1af2ef-90a6-40c5-9685-94efe906acea)
oh no.
![image](https://github.com/user-attachments/assets/4ba085a2-9a7b-49ff-9b35-8ab28e2a03ec)
the shafts seem to not be symmetrical.
ok so it was fixable  by adjusting it to its original length, because i had placed the shaft starting on the edge of the indexer plate, and not in the middle or something. idk
![image](https://github.com/user-attachments/assets/34317521-2da1-4548-899e-a8a646393e3e)
oh no.
![image](https://github.com/user-attachments/assets/ee04a06a-ebb1-4e0c-9915-d4d9323eca8c)
ok so apparently cylindrical doesn't work.
i have no idea how to fix this.

# session 52:
the thing is, if i don't get the exact position that it needs to be in, everything breaks. i can't just do guess and check and pray that it works because revolute allows things to spin.
![image](https://github.com/user-attachments/assets/d6502b50-05b0-4d57-b1f6-6dbcb022206c)
ok so i tried to get all of the belts into the middle, but it isn't working.
![image](https://github.com/user-attachments/assets/57a08c7a-09a6-4e6d-ac94-0196eee96080)
that looks like its in the middle now.
![image](https://github.com/user-attachments/assets/b1ca641a-9cb2-46b5-9341-43e1b203f9fe)
bruh i thought it'd work
ok nevermind it turns out that i forgot to add the half of the width of the pulley. 
![image](https://github.com/user-attachments/assets/9b26cedd-d254-4667-8853-cfa73270f209)
asdfjasklfjaskdfjasd;fkf doesn't look very centered to me. 
argh i think i forgot to account for the flange on the bearingsssssss.
![image](https://github.com/user-attachments/assets/fcc13873-70c5-47bc-96ad-297701452e65)
that was 100% the problem. now i need to account for flanges on the other shafts to make all of the pulleys lined up.
onshape has turned into a lag fest. it's so darn laggy now. 
![image](https://github.com/user-attachments/assets/a88e221a-ba79-49a0-a301-4fec1174638b)
it still doesn't look symmetrical...
it's off by 2 mm.
ok wait nevermind it's off by 4 mm.
![image](https://github.com/user-attachments/assets/dd362093-b9b2-4bf3-9557-874589164406)
what.
i don't know why this is happening.
![image](https://github.com/user-attachments/assets/72709d07-7e22-4564-bd94-ec5e00975f03)
it's meant to be 12 mm....
asdfsadfsadfsadfasdfasdf
why cad no working
why cad so confusing
why cad
cad why
asdklfjas;kldfjsa;kldfjsda;f[ioeqwvteqwvtepwuioqvupwqoemvtuqpwoievmtuqpwioemvtupwoeqvt
![image](https://github.com/user-attachments/assets/ac9c0bf4-c143-416a-bd4a-84b99a4878d1)
what. the bearing slightly clips into the indexer plate. sfdasfdasfdasfdasfdasfdafdassfdasfda
how did i not realise this. 
akslfdjslfdj it's such a small thing
that i didn't realise
safdasfdasfdsafddffd
![image](https://github.com/user-attachments/assets/f5e732c0-0adb-4d90-8a18-83a370c83f9b)
it's...
fixed...
i'm free (for now)
i wish there was a way to see what mates are associated with a part, because it's hell to sift through the 80 ish mates to find out which one is the one that i need. 
argh. things aren't working. i've tried pretty much every mate that i think could work. planar doesn't work. 
![image](https://github.com/user-attachments/assets/80e77089-cc95-46d0-b5e1-9019532bad6c)
hold up this might work.
i've never used parallel before (or a bunch of other mates before) so uhhhhhhhh interesting. i think that i have to make the shaft at a certain degree so that the belt will go to the pulley.
![image](https://github.com/user-attachments/assets/35b85c7e-0446-4791-b674-07702bd3f56c)
what the flip is going onnnnn

# session 53: 
okay so i think i need to adjust the mates and the shaft
i need to spin it so that it can work.
i love guessing and checking (it takes like 10 seconds each time i want to check if it works, since there's so much stuff in the assembly right now 😭 and it takes like 10 seconds between when i press a number key and when it shows up on screen (fun.))
wait i have an idea
what if i make it parallel to the edge of the indexer plate, since i only used a direct line from each pulley to link them together, surely it means that the belt will be on the pulley, right?
![image](https://github.com/user-attachments/assets/6800ea66-c1ea-4c65-b66b-40fd0d54d783)
YESSSSSSSSS I DIDN'T NEED TO TURN THE SHAFT LET'SSS GOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO
LET'S FREAKING GOOOOOOOO
HELL YEAH
SCREW GUESS AND CHECKING
WOOOOOOOOOOOOOOOOOOOOOO
ok i gotta calm down
okie dokie, time to adjust all of the other belts. 
![image](https://github.com/user-attachments/assets/90e86eea-7da9-4421-b731-1504a3f84f85)
WAITTTT WHY DIDN'T IT WORKKKKKKKK MAN....
![image](https://github.com/user-attachments/assets/e2d920a3-f890-41bb-8164-8b5f0ef8ba76)
guess and checking for the win!!!
![image](https://github.com/user-attachments/assets/831e685a-5194-4020-a2cb-905e50733b95)
guessing and checking fixed nothing. the ups and downs of cadding, except it's only the down for me. 
i have no idea how to fix this now. i've tried EVERY single mate, regardless if i think it works or not. 
asjdfklafdklasjfdasdf
what shall i do
there's nothing i can do
i must think
hmmmmm (for like 20 minutes straight)
i decided to listen to some music to help restore some of my sanity.
WAIT. i have a brilliant idea.
what if i fasten the belts to the indexer plate, which doesn't move and always will stay the same.
i'm smort
(probably not)
![image](https://github.com/user-attachments/assets/2c0c40d4-c54f-411f-ad91-933080104abb)
i had to hide some bearings so i can use the mates. 
![image](https://github.com/user-attachments/assets/ce726d57-33cb-4749-8b36-67a696bc182b)
i thought i'd need some kind of offset like the width of the pulley + 7.5, since 7.5 is half of the width of the belt, but apparently i didn't.
![image](https://github.com/user-attachments/assets/1e3c0197-26b6-49a4-aa05-d5ee8a13a433)
and there we have it. uhhhhhh yeah it's something. 

# session 54: 
![image](https://github.com/user-attachments/assets/326bb5e4-e347-4d46-9cae-ac2c581950cd)
i promptly realised that there's nothing stopping the ball from just flying out of the indexer in this area. i'm not sure how you can mount it as 90 degree angles aren't necessarily the greatest thing to cnc so ...
i didn't really know how to do it, so i looked at 2910's indexer and see how they fixed it. 
![image](https://github.com/user-attachments/assets/febd9bb6-5c51-48b5-9ce6-e9f3512d6ef5)
ok, so they did it by avoiding the problem and having a longer indexer. i've pretty much locked in the size of the indexer, so i don't really want to change that. 
i don't really know how to go about this. 
sighs.
hmmmmmmmmmmmmgklfdajgklsfghskladjgas;kljdfafd
![image](https://github.com/user-attachments/assets/594695c8-2fdd-43d6-b187-b946f59f63b8)
actually, i have a bit of an idea.
i could use belts to ferry it over, but i also will have to adjust pulley locations. 
i think it might be fine to pull off, my only concern is stressing out the motors. 
![image](https://github.com/user-attachments/assets/a5b61474-6994-449f-aeb9-800f79a7db6b)
argh i can't see the constraints, even though i have the "Show Constraints" thingy checked. what. 
![image](https://github.com/user-attachments/assets/95251ee4-ecf2-47e4-bdf4-1920647205ab)
all i see is small lines that probably point to the constraints, but i can't click on them or anything.
i searched it up and couldnn't really find anything about it.
![image](https://github.com/user-attachments/assets/f93e477e-7f35-45c2-933b-660128fd4518)
i decided to clear my cache (which is probably the problem) 
and it works now. 
![image](https://github.com/user-attachments/assets/a8505eda-5482-4eb2-bb2f-3914b1eeed62)
surely this works.
also i realised that i could just use standoffs to block the ball, and maybe put some rollers that aren't attached to the shaft. 
![image](https://github.com/user-attachments/assets/39c7b342-a0fb-4566-a2b9-c379f09dd714)
ok time to reduce the fillet.
![image](https://github.com/user-attachments/assets/ebb8c7cf-2c8c-4f5a-be6f-d69452725b6f)
scuffed.
![image](https://github.com/user-attachments/assets/4bdaba24-5f9f-4e57-b715-36bdc3258eed)
what the scuffed setup

# session 54:
![image](https://github.com/user-attachments/assets/c4b645e3-b8ef-402c-a32a-054501f4a596)
what it looks like if i didn't add it in
![image](https://github.com/user-attachments/assets/c583bbcc-c64b-420b-856a-23fd71be7642)
what it looks like if i added it in (i did)
one is significantly better looking than the other. 
![image](https://github.com/user-attachments/assets/ea6dc02c-2f97-401d-9a35-d35ba89e7974)
oh no.
i just deleted the constraints and then the dimension, adn kept it the same. 
![image](https://github.com/user-attachments/assets/96d9bd52-4301-4616-8bf2-6656ac944357)
i put a 4" diameter circle to make sure that it won't interfere with the wheels. 
i might make some kind of roller that attaches to the shaft at the top, but the shaft at the top doesn't spin at all, but the roller won't be securely attached to the shaft. 
![image](https://github.com/user-attachments/assets/7557e5be-6637-460d-9f39-1a05c5fb427d)
epic.
![image](https://github.com/user-attachments/assets/a40d4fe3-f80a-47cb-bcf0-fcebdebcfff5)
i gotta move this pulley.
![image](https://github.com/user-attachments/assets/1584aa4f-7fb4-439f-be2d-bac8553bb0ce)
miscalculation
![image](https://github.com/user-attachments/assets/74e7f320-8c93-426a-87d5-e897e804c801)
i might make it a bit larger due to it being slightly close. 
![image](https://github.com/user-attachments/assets/d1c924d0-e848-417d-ad27-7a1f20cb7d1f)
epic. 
![image](https://github.com/user-attachments/assets/556a4249-0a25-48dc-af73-c683d75d595e)
had to make a new shaft.
![image](https://github.com/user-attachments/assets/e627f18e-a81e-4fa4-962b-b59a82f0cdf6)
![image](https://github.com/user-attachments/assets/6e4bf34d-e626-42d9-8b2d-043e0c5efa3f)
top tier moments were i forget to make a bottom for the shooter. (funny)
![image](https://github.com/user-attachments/assets/60cd8aff-d858-4c37-b8d7-68e1bebbeb1d)
uhhhhhhhhhhhhhhhhhhhhhhhhhh
![image](https://github.com/user-attachments/assets/d2bffc50-e6fd-44d6-94be-304e15859d0f)
uhhhhhhh
![image](https://github.com/user-attachments/assets/7cf81f4c-84bd-4798-abb5-f90606ff3e7f)
scuffed.
![image](https://github.com/user-attachments/assets/cccef236-7d38-4c20-a583-3b2c26b3ccb9)
standoffs please save me.
![image](https://github.com/user-attachments/assets/e7e40d6e-8194-492d-a986-6372aba401ee)
epic.


# session 55:
assembly grind.
![image](https://github.com/user-attachments/assets/e2c7fe7b-6764-4005-835b-a967d698bd20)
it feels impossible to click the center mate connector. how did i do it earlier?
i think i figured out the technique, you have to move your mouse cursor onto the face, and then the millisecond that your mouse enters the face, you have to stop moving your mouse, or the mate connector won't be in the center.
![image](https://github.com/user-attachments/assets/28a904ae-365a-42f0-8644-93804b6b8eea)
epic.
![image](https://github.com/user-attachments/assets/cf18a5ae-5647-4009-8c73-2112f1976dae)
i think i want 2-3 4 inch wheels and 2 flywheels. 
![image](https://github.com/user-attachments/assets/6b2031fa-f180-4cfb-8584-a6e92c2cbcd3)
uhhhhhh what's the difference between these...
![image](https://github.com/user-attachments/assets/e58aa59e-60f3-49cb-83d2-cc4037b73334)
idk what this means 
![image](https://github.com/user-attachments/assets/d9609673-9175-47ed-acfe-ee2d877c41fc)
hmmmmm ok, but what's the durometer
![image](https://github.com/user-attachments/assets/53ea7055-3491-48a8-9a0b-e867cab85448)
ohhhhhhhhhhhhhhhhhhhhhhhhhh
i see
ok uhhhhhh as i'm looking at other team's shooters, they also have another roller on the bottom/top/other side of the driven rollers/rollers that spin. 
asfjskldafj;sklafjskla;jfdksla;jfsa;fklasjdf
i also need 2.5 inch wheel or something.
![image](https://github.com/user-attachments/assets/7597cf35-e2fc-4fd1-afb5-2e97787fa875)
i think i imght reduce the size of the shooter. 
![image](https://github.com/user-attachments/assets/b4870545-91de-4be4-8f90-fc73d66add91)
oh no. 
![image](https://github.com/user-attachments/assets/dbbe9d16-5621-4249-96c6-616d00844b09)
that standoff hole is too close. 
and then i realised that i can't just put the wheel/roller there, because it'd have to go over a large bump to get there. 
![image](https://github.com/user-attachments/assets/84146976-d20b-4dab-9314-118c216a3111)
i was making the mount when i realisedd that i had forgotten to make a buffer zone for the bearings. 
![image](https://github.com/user-attachments/assets/494fb46f-08aa-449e-a552-6d8c7d6001a5)
ok cool.
![image](https://github.com/user-attachments/assets/7e6326c0-091b-4bd4-9872-69b265972455)
the extrude and sketch stuffed fixed itself, but not really.
![image](https://github.com/user-attachments/assets/b35e867d-3fd3-47b0-8e60-de6f16642cfc)
hmmmm yes. 
![image](https://github.com/user-attachments/assets/a9a96adf-9fe3-4791-a2ff-6e132244b19d)
that's wayyy too close to the neo motors. 
![image](https://github.com/user-attachments/assets/eda588a0-df38-49dd-abbf-bfc8599fed49)
i thought that this works but it doesn't. 
![image](https://github.com/user-attachments/assets/d23f9121-ac00-4600-b9c9-3b9e9c89dfa1)
it was because i screwed myself over by putting the minus sign, and i should've added the 12.7 because i had put the minus sign over everything/in the outer brackets. 

# session 56: 
![image](https://github.com/user-attachments/assets/5234cc88-42c1-42b2-8334-ab0ba1066548)
i was like 3/4 of the way through fastening all of the wheels on the bottom roller, when i realised that i was meant to be fastening them to the top roller. yippppeeeeee !
![image](https://github.com/user-attachments/assets/3fc48dbd-ec2d-42d1-932f-3b8944b61428)
luckily, since i fastened everything to the middle wheel, all i had to do was change the position of the middle wheel, and everything else follows. 
epic !!! i love making good decisions about fastening and stuff and cad and maybe not so great decisions but yeah !!!
![image](https://github.com/user-attachments/assets/944290ad-22f3-45a7-a669-ba337319677c)
i think i have some space in here to pop in some pulleys, but i gotta make the belt first. 
![image](https://github.com/user-attachments/assets/840e6a62-6f95-4d0f-a61f-a3c0477765c9)
i forgot to change the thickness of the belt. 
![image](https://github.com/user-attachments/assets/6a8d6f6c-2746-4e85-8501-028fbb53dd37)
there's only one 2.5 inch wheel. i might opt for something like 2 inch. 

![image](https://github.com/user-attachments/assets/34814240-7922-4677-b4f3-2e669b6e78be)
it's allll coming together now !!!
![image](https://github.com/user-attachments/assets/e091f99e-6b42-4de2-a769-5289116bb321)
i'm gonna work on the gearbox stuff now. 
![image](https://github.com/user-attachments/assets/62b4ca47-72ea-4d94-9a26-41401a91d6e8)
oh no.
![image](https://github.com/user-attachments/assets/2a7b6e59-9ef5-499b-a47d-48fe1ff4f8a6)
man idk how to package all of this, there's like no room to move anythiing. like what am i meant to do ???
jaskdfjaskldfjsa;kldfjas;ldfkjas;fkdlksafd
like if i move the motor up, i won't be able to mount it there, because the flange of the bearing will interefere with mounting. if i move it down, well then i can't make the lower bearing work. 
i can't move the gear because it has to be tangent with the 16 tooth gear on the pulley, so that it will be close enough on the other side of the gearbox. 
i can't move the other gear because then it'd start going into the indexer plate, and that's not good. 
i have no idea what to do, because i've basically locked in all of the gear sizes and ratios and stuff. i can't simply just expand the gearbox, because the bearing would interfere with the indexer plate
after like 30 minutes of contemplation and trying to work it out, i just deciedd to do something else. 
![image](https://github.com/user-attachments/assets/fa16d20f-fe3c-4424-a695-32eda0f3036e)
why is this here.
ima go fix this
it's fixed.
![image](https://github.com/user-attachments/assets/b9b2f9f0-7bce-41dd-8184-928fbee60f35)
now i wanna change this up somehow.

# session 58: 
okie dokie, so i wanna move the position of the standoffs a bit. 
![image](https://github.com/user-attachments/assets/e9e5ed99-e1e6-4fba-b532-4dff29d9e1e2)
it has been moved. 
![image](https://github.com/user-attachments/assets/59c9c3a1-77fe-4be3-8e69-09773b3a791c)
asjdfklsadfj;klasfjdasdfkljasdf i don't think anything can work at this rate. there seems to be like no way to move it. the gears are at their farthest distance from the motor, or at least as spread out as possible, and it doesn't work out.
![image](https://github.com/user-attachments/assets/a8907075-9a2b-4f0f-95b8-38a765b51682)
the blue construction circle is marking where the neo motor's footprint is/the size of the neo's footprint. as you can tell, it's pretty much unfixable. there's like nothing i can do. 
the thing is, i HAVE to fix it, or the robot cad wouldn't really function as an actual robobt you can build and make for the 2021 season. although yes, nobody would build it, i would like to get it functioning. 
ajsdkfljasd;lkfjsa;dfkjas;kdlfjasdf;lkajs;dfkjasdlf;kj
sigh.
i think ima postpone it for now. 
![image](https://github.com/user-attachments/assets/4bd3d687-f95d-44b7-8c48-45ba093701d7)
hmmmm ok that's not good.
i think i might work on the intake first. 
![image](https://github.com/user-attachments/assets/45c64200-a392-4fde-b750-b28eed5e1b7b)
arghghghgh the fastened broke and the pulley is scuffed..... asjdfklajsfkdljsd;fa;klsjdfas;lkdfjasdflk
and i can't fix it until i fix the gearbox issues...well ok, i'm just going to work on assembling the intake now. 
![image](https://github.com/user-attachments/assets/2796d93b-4cfe-49ef-86c1-dd2305ff9c74)
oh. well flip. that's...
not
good.
surely this one is easier to work out than the gearbox, i have lots of space !
ok so i decided to just power the intake directly from the neo using  belts, maybe havingn some kind of reduction. 
even worse, i can't even pull up the store page of VEX, since all of the memory is being taken up by onshape
![image](https://github.com/user-attachments/assets/258716e5-f7b4-4260-96d7-38f8505c3750)
i tried to reload the page, but it isn't working. even uploading images to github takes over 20 seconds...
ok, so i think i might want to do a 30 tooth pulley into a 42 tooth pulley. it might work, it might not, idk. 

# session 59:
asjdlkfjsadflkasjf;alksdjfad
![image](https://github.com/user-attachments/assets/db158083-8a91-4ed7-91d7-9d57e83339d8)
ok, so, as you can see in the image, i have selected the 24 inch long 1/2in hex shaft
![image](https://github.com/user-attachments/assets/b696bb69-d4ac-42c0-a696-e23f1c1f0c28)
as you can see in this image, it exists. 
I CAN'T FIND  IT WHEN I TRY TO INSERT IT INTO THE ASSEMBLY
ok nevermind i'm just blind. 
![image](https://github.com/user-attachments/assets/7695ac35-d0b6-4c6b-ad47-ae380726c74d)
anyways i  have a few problems. 
![image](https://github.com/user-attachments/assets/715accd1-c282-433a-a5b4-6b9eeb0e8576)
ok maybe add one more thing to that list.
i think the problem is that i set the bearings  on revolute, and then i connected stuff like the thing on top and the belt to the bearings/the pulley that spins with the bearing. 
another problem is not being abel to find which mate is the one associated with the thing. 
![image](https://github.com/user-attachments/assets/b97c59ef-60c7-4491-8103-01492b21f1f5)
i flipped on the show mates mode, but it doesn't entirely work out, and i can't find the mate in the sidebar.
hell i'm not even sure if the thing is mated to anything. 
kfaskdal;fka'sdfk
this is all stressing me out because i just can't find the mate, and i need to fill up the quota for the hour.
ok, so from what i can tell, the thing isn't mated directly to anything.
![image](https://github.com/user-attachments/assets/6256628c-e71c-417f-9935-464b50f4966c)
lots of things are breaking. 
argh it's so slow to do things.
onshape is taking like 4 GB of my ram.
i can feel my head hurtinggggg
![image](https://github.com/user-attachments/assets/1672a220-5789-4d89-9d3d-76f6740f0557)
uhuhuhajfsdklfjasd;lfkjasdf
well
it 
FINALLY
is
fixed
man it feels good

# session 60:
![image](https://github.com/user-attachments/assets/b419a059-9a78-43e5-9669-9cdd2e71d8b4)
whaddaflip.
i thought there was a problem with some of the parts, but it's just a mate connector problem
aka fun.
aka hell
i had to make another shaft before assembling the intake. 
![image](https://github.com/user-attachments/assets/c00bbc9a-fc35-4831-83c2-7214830fbca0)
![image](https://github.com/user-attachments/assets/2ec84a46-e07b-428e-9624-32ee07e6aedc)
one set of pulleys fixed.
![image](https://github.com/user-attachments/assets/fbfedeb6-f4d1-41d2-9345-955f9f0d4dbc)
oh god there's so many parts.
![image](https://github.com/user-attachments/assets/7a19fdba-9e4e-488d-9799-493f1ac3ac2c)
WHATTTTTT.
uh so i forgot the reverse button thingy. my bad. 
![image](https://github.com/user-attachments/assets/8cf1d61f-8013-4b0c-bdc8-a718f3806ea5)
uh what's going on. 
![image](https://github.com/user-attachments/assets/afabc214-af7b-43ab-8a35-3ede15b3f0aa)
is this a lot ???
![image](https://github.com/user-attachments/assets/fa7f425f-15a9-40f0-bbdb-2e6cf7695dc4)
ohhhhh nooooooooooo ....
that's 2910's cad.
mine has almmost quintupled the amount of primitives... no wonder my computer was suffering.
![image](https://github.com/user-attachments/assets/6316e8ce-d728-4915-a6b1-0cb166cb1556)
hmmm ok from what i can see, the rollers might get too close to the hopper, or it could make the balls go to some funky places. i think it's fine though, if i put large enouch wheels.
![image](https://github.com/user-attachments/assets/936a5c50-f93d-46f4-8242-26586fff9af3)
i decided to go with 3 inch wheels for the last roller, and hten 2 inch for the other ones. 
![image](https://github.com/user-attachments/assets/29cb7bd1-8699-4d9b-9729-429ce312fc6f)
one roller set completed, time to put on some pulleys. 
now uhhhh i forgot what kind of pulleys i used. 
ok so it's 24 tooth pulleys
ok
so
uh
assembling time
yeah !!!
![image](https://github.com/user-attachments/assets/a38e6c4f-a9ab-4527-a9c7-26f7850c71d2)
linear pattern my goat right now. 
![image](https://github.com/user-attachments/assets/82c1ed49-da98-4b2f-a16b-24726b711218)
slightly off centre.
![image](https://github.com/user-attachments/assets/f96348be-6724-4b0e-a3f6-aff48b68e655)
perfect. 
![image](https://github.com/user-attachments/assets/c8675434-d694-4c7a-93c5-d577c1635ff5)
ok so i just realised that the 2 inch wheels are around half the width of the 3 inch wheels. i think i can account for that by doubling up on the wheels. 
![image](https://github.com/user-attachments/assets/0cba572b-1860-49d5-bfe9-694bbb2a4dd3)
tis all coming together. 
![image](https://github.com/user-attachments/assets/bf6298b0-12b4-419e-baac-99ac0fd2b4be)
epic.

# session 61: 
i quickly finished up on the intake.
![image](https://github.com/user-attachments/assets/64295893-65a8-4061-8a79-33c4767e7602)
i feel quite proud of what i've done so far, but i still had one thing to solve. the motor placement. 
i think i'm just going to do everything i can to avoid doing the motor.
![image](https://github.com/user-attachments/assets/777d4388-6f06-4c03-8255-8112a0bd77b1)
ajSDFKASLK;FDJASZJCXVOIJSAI SOPDJAWPOIEJCSPX
that motor annoys me.
i think i need longer shafts for the gearbox. 
![Screenshot 2024-08-19 100519](https://github.com/user-attachments/assets/b0fcb591-27b1-4a99-a7b8-cad3c6492514)
i found out that there aren no 16 tooth gears for ½ inch hex shafts, so i decided to just swap to an 18 tooth gear. 
this means that it’s roughly a 11.5:1 reduction, aka not enough. 
asjdfalkdfkasjdf;asjfdf
hmmmmm
i decided to use a 56:12 adn then to a 50:18, resulting in around 13:1, which could work, but it kinda messes up the entire system i have running already.
![Screenshot 2024-08-19 102856](https://github.com/user-attachments/assets/80721b34-4ea7-4e49-8470-8cb8f9ee3c71)
hmmmm ok
that’s my original reduction for the outer indexer pulleys. 
this is like a rough idea of what the reduction is, it’ll be good enough. 
![Screenshot 2024-08-19 103135](https://github.com/user-attachments/assets/3e782140-709d-4cce-a684-d25aaf891d77)
this makes it slightly faster, but that’s fine. 
![Screenshot 2024-08-19 103309](https://github.com/user-attachments/assets/0ff3c15d-89ff-4e0f-afeb-b9251bfc7437)
i think this can work. 
time to modify the sketch for the indexer inner gearbox. 
![Screenshot 2024-08-19 103721](https://github.com/user-attachments/assets/817841f2-dcb2-46fb-88e6-d2d3b351b49e)
it has been modified. 
onshape is tearing through my battery right now, i'm on 50% after like 2 hours of work... (battery saver was on the ENTIRE time)
usually i cad at home, where my laptop is always linked to a power supply.
but holy. 
![image](https://github.com/user-attachments/assets/718a05b3-38c1-41d0-b29b-7251620ef1d7)
the 18 tooth pulley is nearly the same size as the bearings. 
also, if i use the 24 tooth pulley the reduction is like 2.8:1 
which could work. but i need speeeed 

anyways so 
![image](https://github.com/user-attachments/assets/6f9c4ec1-1fa0-46b5-978a-57ae8bbba943)
small problem, i can't find the 18 tooth pulley. 
i think i could just... decide to get the .step file from the manufacturer. 
but there' s abunch of unnamed stuff that doesn't have any tooth amounts. 
arg i don't wanna check them
i'm just going to import the step file. 

![image](https://github.com/user-attachments/assets/0bcd0672-9660-4dc6-9954-cf3aa7174c7c)
taht doens' tlook good...
