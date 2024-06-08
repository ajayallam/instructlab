Training Doc TO Locomotive Operator FAQ v2.1.docx
This document is intended to cover frequently asked questions and does not supersede any current CSX
Operating Rules or Procedures, if this document is in-conflict with a rule, the rule will govern.

Questions about the TO Helpdesk:
Q: What is the Helpdesk Phone Number?
 321-435-7436 is the direct number and does not require you to select any options
 The toll free # is: 800-825-7990; You need to select the options to reach the TO Helpdesk
Q: What can the TO Helpdesk do?
 If you call prior to boarding the train, they can ping the locomotive to ensure that it is
communicating, and make sure the trip is in the system
 Build a trip, if the trip data is not present
 Correct the consist to reflect the correct power for the train
 During an initialization, can let you know if a unit is downloading track databases
Q: What can’t the TO Helpdesk do?
 Edit or change speed restrictions
Questions about Initialization:
Q: When I attempt to engage TO, sometimes it takes longer than 5 minutes and fails to initialize
(times out), what do I do?
1. If PTC Comm. Breaker is available on unit, ensure it is turned “ON” (found on the engine control
panel) to engage locomotive communications.
2. Try engaging TO again, a minimum of three attempts is suggested if conditions permit.
3. If no initialization is possible fill out a trouble report, provide as many details as possible, such as
number of attempts, and any information provided by the helpdesk, etc.
Discussion:
If there is No “Trip Optimizer” button at all, make sure the reverser is centered and the throttle is in idle.
(If the reverser is not centered or if throttle is other than idle TO will not initialize).
If there is a button present, but TO times out, one possible reason is the locomotive is not
communicating through satellite or the cell tower.
 Check the status of the PTC Comm. Breaker
Another possibility is that the unit is downloading the TO databases from the server. This can take
longer than five minutes if many databases are needed, or the connection is poor.
The helpdesk has the ability to tell which condition is the problem.
NOTE: To help get trip inits more reliable, try the Trip init as soon as you get into the cab as this will allow
for more time to download track databases.
Training Doc TO Locomotive Operator FAQ v2.1.docx
This document is intended to cover frequently asked questions and does not supersede any current CSX
Operating Rules or Procedures, if this document is in-conflict with a rule, the rule will govern.
Version 2.1 Page 2 Effective April 1, 2016
NOTE: If you move the train, the Trip Init process continues in the background, so databases will
download. When you get stopped, a second trip init will initialize quickly as the databases are already
loaded.
NOTE: Once stopped, you can try to initialize TO within 35 miles from Originating Terminal. If the
original communications problem was location specific, TO may be capable of initializing at this point.
Q: I am on a TO unit, and NO Trip Optimizer button is present, OR When a Train ID is entered, the
“New Trip” Key does not appear, what do I do?
 Fill out a trouble report for this unit; indicate the type of problem observed.
Note: This indicates that the locomotive computer systems are not communicating correctly and TO will
not be available for this trip.
Q: If the locomotive numbers on TO screen do not match the actual consist, what do I do?
1. You must change them to match your train by selecting the “Change Locomotive” Option on the
Train Setup Screen,
2. Ensure the correct locomotive Road Number and Isolate/Run Setting is set for each locomotive,
and
3. Ensure the locomotives are in the correct position within the train, which is critically important
for Distributed Power Trains.
Discussion:
TO builds a plan based on the exact type and number of locomotives in the train. If TO believes the
consist has two EVO Units, it makes a completely different plan than it would make for two Dash-8s and
an SD-50.
Note: For DP trains, not setting the locomotive types and positions correctly will also cause TO to not run
as planned. With newer TO software, it will automatically end auto control and make you take manual
control if the DP Train is not setup correctly.
Q: I am on a recrew relieving the original crew on line of road, should I continue the trip from the
previous crew?
1. No, Hit the “End Trip” button,
2. Initiate a new trip from your current location (TO should be able to create a new trip on your
current track segment with updated speed restrictions),
3. Carefully review the data supplied by TO, and
4. Update the Consist and Locomotive information (as normally be done for a new trip)
Note: This will not work if you are within 35 miles of the end of the trip, in those cases, just end the Trip.
Q: I am a recrew that has been assigned a new train ID, and am not at the origination point. Will I be
able to start a new Trip Optimizer Trip?
 Yes, with the assistance of the Helpdesk when:
A. The re-crew occurs at a location within 35 miles of the origin, or
B. Within 35 miles of a crew change location
Q: My train has been rerouted before I initiate the trip what do I do?
Training Doc TO Locomotive Operator FAQ v2.1.docx
This document is intended to cover frequently asked questions and does not supersede any current CSX
Operating Rules or Procedures, if this document is in-conflict with a rule, the rule will govern.
Version 2.1 Page 3 Effective April 1, 2016
 Call the Helpdesk and have them check your trip, they can adjust the destination if your new
destination is on TO track.
Q: If I get a Dispatcher Message that does not contain both a speed and milepost combination at a
given location, will TO control for this speed reduction?
 No, TO does not currently plan for speed changes that do not have an associated milepost.
 In these areas you must transition to Manual Control
Discussion:
This restriction doesn’t contain any Mile Post Information, so TO wouldn’t know where to apply.
Questions about the Trip:
Q: Why did TO kick me out of or fail to offer auto control?
This could be caused by:
A. Incorrect train consist information, or
B. Incorrect locomotive information relating to locomotives in the train, cut in/cut out, etc, or
C. A locomotive fault issue caused by the health of the locomotives in the consist, that may or
may not be visible to the locomotive operator
Discussion:
The train consist and locomotive information can only be changed when the train is stopped.
Locomotive faults that impact dynamic braking or reduce tractive effort will disable TO. Also, TO detects
Train-line faults from trailing units and these can prevent Auto Operation. Further, a bad MU cable can
create fault conditions that TO will detect.
Q: After initialization, when do I need to update the consist or locomotive information?
A. When there is any change to the status of the locomotive consist, such as isolating or placing a
unit on-line, or
B. If there is any change to the train, such as picking up or setting out cars
Q: What should I do if a locomotive is under-loading?
1. Continue to run TO as normal, (if the problem is severe enough, TO will prompt Manual
Control),
2. Fill out the locomotive operator’s work report, and
3. Report the incident on the locomotive to the mechanical desk.
Discussion:
TO will continue to function with an under-loading problem until the problem becomes severe enough
that TO is not able to run to the plan at that time TO will move to “Manual Control Only”.
Training Doc TO Locomotive Operator FAQ v2.1.docx
This document is intended to cover frequently asked questions and does not supersede any current CSX
Operating Rules or Procedures, if this document is in-conflict with a rule, the rule will govern.
Version 2.1 Page 4 Effective April 1, 2016
 If the train can continue without the problem unit online, isolate it, update the Train Setup
Screen with the change to the locomotive configuration. TO will re-plan, and Auto will become
available.
 Otherwise, run in Manual
Q: How do I know what TO’s plan is for the upcoming track?
 TO shows its exact plan for the next 5-Miles on the rolling map. Looking at the rolling map will
show:
1. The permanent and temporary speed restrictions for the next 5 miles, and
2. TO’s speed plan for the train.
Note: The information shown will be for the track the train is currently on. The information will update
when a re-plan occurs after the “What Track” prompt. When in Auto, TO should keep the train speed on
the plan line as it operates. TO’s plan will not always be maximum authorized speed or current track
speed.
Q: The “Auto Available” prompt appears on the screen, should I immediately engage Auto?
 No, consideration must always be taken for operational and track conditions prior to engaging
TO. The 5-mile look-ahead on the rolling map shows TO’s plan. TO will accelerate or decelerate
the train to match the plan shown as soon as auto is engaged.
Discussion:
 When leaving a siding, if TO does not know the train was on the siding, it then does not know to
control the train for the siding’s speed restrictions. TO should not be engaged until you are fully
clear of the siding.
 When accelerating the train from a stop, TO will allow auto operation as soon as the train is
running above 12 MPH in any location that is not a manual zone. Upcoming track, grade or
restrictions may make manual operation the more appropriate action.
 If a restriction has been abolished, the train must be operated in manual through the limits of
the abolished restriction.
Q: I am approaching a speed restriction or reduction, and I am concerned how TO is planning and
controlling the speed, what do I do?
1. Take manual control when:
A. Prompted to do so by TO, or
B. Train speed gets above the plan speed, or
C. Experience tells you that the train will not slow and stay on the plan
2. Fill out a trouble report for this location so a further investigation of this area can be conducted
Discussion:
Other times manual control should be considered:
A. On signals less than clear, or
B. Wheel slip is occurring on the consist due to contaminated rail or other conditions, or
C. Any restriction that requires 10 MPH operation, TO will require Manual Control if train
speed drops below 9 MPH, or
Training Doc TO Locomotive Operator FAQ v2.1.docx
This document is intended to cover frequently asked questions and does not supersede any current CSX
Operating Rules or Procedures, if this document is in-conflict with a rule, the rule will govern.
Version 2.1 Page 5 Effective April 1, 2016
D. If you are less than 2 miles from a restriction, engaging auto may cause it to accelerate the
train to match the plan speed, and then decelerate back for the restriction, or
E. If you have locomotive issues, such as dynamic brake problems, surging, etc.
Q: When is Manual Control required?
Manual Control is required when:
A. Operating on a signal that requires the train to operate prepared to stop at the next signal, or
B. Anytime the route to be taken beyond the next signal is not known, or
C. When approaching work authorities until clear of the work limits, unless cleared all the way
through the limits, or
D. A train that experiences an emergency in motion must be operated in manual for at least one
train length in order to comply with Operating Rules, or
E. Until trained and authorized to run TO by your Road Foreman
Questions about Train Handling:
Q: When does TO prompt for “Which Track”?
 The prompt distance should allow the intermediate signal to be seen. If the signal can’t be seen,
fill out a trouble report indicating the control point so the prompt location can be adjusted.
Discussion:
TO only prompts at Control Point that leads to the destination of this trip. There will not be a prompt at
a diverging control point that will lead to a different destination.
Q: How long do I have to respond after TO prompts for “Which Track” before TO kicks out to “Manual
Only”?
1. After the prompt the operator has 30 seconds to respond or transition to Manual Control.
Note: If you do not know the answer to the prompt, put the train in Manual Control
2. After 30 seconds, the system will prompt the operator “Manual Control Required” and start an
additional 30 second timer
Note: Failure to respond to the “Manual Control Required” prompt within 30 seconds will result in a
forced-idle condition in motoring train will maintain dynamic brake level in braking
Q: Why does TO run under the posted speed on an uphill grade when I would normally be in #8
throttle?
 TO makes and follows a fuel conserving plan, and as it goes uphill, it regulates the throttle to
keep the train speed on the planned speed line.
Discussion:
TO creates a minimum time plan for a given trip, following all operating rules and procedures, avoiding
air brake when possible. It then adds 1% to this minimum time plan (so if a run takes 8 hours, TO adds
4.8 minutes to this time). TO then re-plans the trip and applies the 4.8 minutes in the best locations to
save fuel. For example, using momentum for cresting grades, or between two adjacent restrictions, TO
will run slightly below the authorized speed and save fuel. 
Training Doc TO Locomotive Operator FAQ v2.1.docx
This document is intended to cover frequently asked questions and does not supersede any current CSX
Operating Rules or Procedures, if this document is in-conflict with a rule, the rule will govern.
Version 2.1 Page 6 Effective April 1, 2016
Q: If I lose a locomotive mid-trip how will Trip Optimizer re-program the remainder of my trip?
 Use the “Train Setup” screen and set the effected locomotive to “Isolated”, this will cause TO to
re-plan the trip without that locomotive’s tractive and dynamic braking effort.
Discussion:
TO will detect the change in train performance due to the locomotive failing and may transition to
Manual Control operation. TO may stay in Manual Control until the Train Setup is updated.
Q: I am issued EC-1s by the train dispatcher in-route that requires me to operate at less than the
maximum speed permitted, what should I do?
1. TO must be operated in Manual Control for:
A. Speed restrictions, or
B. False/partial activations, or
C. Working limits, or
D. Locations affected by the EC-1s.
Note: The TO screen and TO plan will not update with the data in the EC-1s after the trip initialization is
made
Q: What do I do for a Heat or Weather Restriction?
 Use the TO function for applying Heat or Weather to the TO Plan
Note: Heat or Weather Restriction can be applied while moving, use the “Restriction” Screen.