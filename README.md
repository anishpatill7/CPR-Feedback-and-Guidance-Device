<h1 align="center">CPR Feedback and Guidance Device</h1>
<h1 align="center">Semester V Mini Project 2021</h1>

<h3 align="left">Introduction:</h3>
<h4 align="left"> Cardiopulmonary Resuscitation or CPR is when a person performs chest compressions and breathing into a patient who has no pulse or who isn’t breathing.
Chest compressions combined with breathing into the patient will carry the now oxygenated blood throughout the body and into the brain. A CPR feedback device is a an instrumented directive feedback device which measures compression rate, depth, and provides real-time  visual feedback on these critical CPR skills. </h4>

<h3 align="left">Components:</h3>
<h4 align="left">
1. Arduino Uno <br>
2. LCD Panel <br>
3. Force sensors <br>
4. Resistors and Potentiometer <br>
5. LED and Button <br> <h4>
  
<h3 align="left">Block Diagram:</h3>

  
<h3 align="left">Working:</h3>
<h4 align="left">Step 1<h4>
  <h5 align="left">Place the force sensor on the patients chest. The compression force will measured by the sensor. It will calculate the pressure and signal by switching on either the green or red light.
If the pressure is less than 500 then, Green LED will turn ON.
If the pressure is greater than 500
then, Red LED will turn ON. <h5>
<h4 align="left">Step 2<h4>
  <h5 align="left">When the CPR begins the Time count starts till it reaches 30 compressions for a single cycle.
The LCD will display GOOD as its output message if the BPM range is between 100 to 120.
BMP can be calculated by the following formula
BPM count = 30 / Total Time
BPM = BPM count x 60 <h5>
<h4 align="left">Step 3<h4>
  <h5 align="left">After every cycle the LCD panel displays the Total Time and BPM Rate.
After 5 cycles the device will get reset to the original settings.
To maintain good CPR practice the BPM range and compression force must be maintained at all times. <h5>
    
<h3 align="left">Outcome:</h3>
<h4 align="left"> Due to its compact and easy to use features the CPR Feedback Device can save many lives. 
The device can be used to educate and train medical students and public to help them perform CPR in case of medical emergencies.
The guided instructions of the device helps the rescuer to perform accurate CPR compressions which increases the performance. </h4>

<br><br><h4 align="center">Thank You!</h4> 
