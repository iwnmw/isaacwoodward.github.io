# Origami Drone (Senior Design Project)

For my senior design project as an undergraduate at UMKC, I led a team of 4 mechanical engineers in continuing a previous team's design of a shape changing drone capable of transitioning between vertical takeoff and landing (VTOL) and fixed wing (FW) flight modes. We had only a semester for the project, but we were able to make a good amount of progress, and I was able to get experience in mechatronics, testing and debugging of robotic systems, and leadership.

<!-- Introduction of the Drone Itself -->
<div style="display:flex; gap:20px; margin-bottom:30px; align-items:stretch;">
  
  <!-- Text -->
  <div style="flex:1; min-width:0;">
  <p>
    The overall objective was to create a tricopter shape-changing drone that begins with its wings folded into a tetrahedral shape. In this folded configuration, the drone is capable of VTOL flight. Then, mid-flight, the drone can unfold its wings and rotate its rotors to a forward position in order to enter a FW flight mode. A previous time working on the project had succeeded in creating and flying a tricopter framework on which to add other functionalities, but none of the flap unfolding/rotor rotation functionalities had been designed, built, or integrated into the drone's control system yet. Our team's goal was to design and integrate all mechanical functions of the drone, including the flap actuation and rotor tilt. If possible, a full flight test demonstrating the VTOL-FW transition was desired, but due to various reasons that will be discussed later, a full transition test like this was not reached. 
  </p>
  </div>

  <!-- Image -->
  <div style="
    flex: 0 0 45%; 
    max-width: 45%; 
    display:flex; 
    justify-content:center; 
    align-items: center;
    flex-direction:column;
    ">
   <img src="../assets/images/Pre FT 5 Stands.jpg"
      style="width:100%; height:auto; border-radius:8px; border:1px solid #ddd;">
    <p style="text-align:center; font-size:0.9em; color:#666; margin-top:8px">
      Figure 1. Redesigned Tricopter Drone with Rotor Tilt System
    </p>
  </div>
</div>

<!-- Successful VTOL Flight -->
