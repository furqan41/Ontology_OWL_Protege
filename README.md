# Ontology_OWL_Protege
**This the Assignment of AMBIENT INTELLIGENCE in  the ontology is which I have design the system by own, I have Integreated the sensore to build the smart system** 

The idea is about traffic system on the road which we see in our daily life, here I tried to make bit more intelligent (Smart traffic controlling &
 street lights on the road )

In the idea I have tried to create automatic traffice light timer adjustment  that means when when the traffic is normal the timer will run normally 
& when the traffic is excessive the the time will be less & and when there is emergency situation the signal will be TURN GREEN and these all thing will be
determined by RGB camera.

**So in my ontology for  this part I have a class called_ **traffic_light**_ in that class I have inserted the RGB camera which will determine the situation then I have three_subclasses of traffic_light named**
* for_Emergency (have instance Always_green)
* for_excssive_traffic (have Instance less_time_period)
* for_normal_traffic
in these subclasses I have inserted the timer which will be tragger by RGB_camera according to the situation so the RGB-camera with some algorithms determine the traffice stuation and control the timer of subclasses 


**The class Zebra_cross(have Instances pushButton_1 & pushButton_2 )**

In this Class I have inserted the timers and tried to delevop, when person Press the PushButton or button only from one side is pressed the timer will start normally to open the path but when adjacent also pressed at the sime time, the waiting will be less or timer will run fast

**CLASS FINE**

In the Class fine I tried to develop the actomatic fine system the this situation happens the car will be fined automatically with the help the tagID (each car has its unique tag number )
In ontology the fine class have two subclasse

* Overspeeding

in which I have inserted the accelerometer sensor which have the data property of interger, this will fine of 150 $
* RedlightVoilation

in this Class I also insterted the same RGB_camera that will determine the car ith help he TagID and fine it about 130 $

**The class streetLight**
 
here I tried to develop the automatic system  of street light which will turned on in the night and off in day light  for that I have inserted the LDR_sensor which will determine the intensity of the light and turn the lights ON & OFF
	
	
and I have also created a separate class called object in which i have define the  sub_class of person, vehicle and TagID (Tag  ), in this I also define the instance of thirteen vehicles which mean excessive traffic and the Timer period will be less  and for ambulanza the timer will be Always green and  car_1 have the tagID:121 , car_2 have tagiD:212, person_1 pushes button_1, person_2 pushes button_2 of of the zebracrossing
