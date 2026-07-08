Day 1 notes QnA:

  1) What is Mission Analysis?
  Mission analysis is determining whether a mission is physically possible, technically achievable, 
  operationally feasible and efficient while meeting all engineering requirements and constraints.
  It is the complete end-to-end planning of a mission, its components and their lifetimes with respect
  to the budgets associated with each system and subsystem.
  
  2) Why is GMAT only a tool?
  GMAT or NASA's General Mission Analysis Tool produces outputs based on what information is being
  fed into the system. It basically functions like a calculator. It cannot derive any mission related
  information on its own, it will only help simulate the mission based on information that is already
  known and being input and then using certain algorithms to help predict later stages. GMAT is only
  a tool, the user is the engineer.
  
  3) What is a state vector?
  State vector contains information regarding the current position and velocity of a spacecraft at
  any given instant. This tells us where the spacecraft currently is and where it is possible headed
  to be able to trace its path both backward and forward. All other information regarding a spacecraft's
  trajectory and orbit can be determined from the knowledge of the state vector.
  
  4) Why are six numbers sufficient to define the spacecraft state in classical mechanics?
  The six numbers within the state vector are 3 coordinates of position x, y, z and 3 velocity directions
  v_x, v_y, v_z. These six numbers tell us where the spacecraft currently is and where it is headed and 
  at what speed.
  
  5) Why is altitude alone insufficient to describe an orbit?
  Altitude alone is not enough to describe an orbit because a spacecraft at a certain height at that
  instant can be following any trajectory or orbit. It could be in a elliptical or circular orbit, it 
  could be geo or sun synchronous, or even in an escape trajectory. This is why it is necessary to know
  the satellites' state vectors.

Day 1 Interview Qs:
 
  1) What is the difference between a trajectory and an orbit?
  A trajectory is the path followed by the spacecraft. A trajectory that repeats itself around a
  central body is an orbit.
  
  2) Why do mission analysts care about the epoch?
  State Vector is one of the most important pieces of information a mission analyst can have regarding
  a spacecraft. It tells us about the position and velocity at a certain time instant so that one can
  determine what path the spacecraft might have been following and what path it is headed on. That
  current instant of time is called Epoch. A mission analyst should know when the given state vector
  is from.
  
  3) Why can't altitude alone define a spacecraft's motion?
  Altitude alone does not give us enough information about a satellite's whereabouts. To know the
  exact orbit it is in or the trajectory it is following, information of the state vector is required.
  
  4) What information is required to predict a spacecraft's future position?
  A spaecraft's future position can be determined by knowing the state vector (position and velocity)
  and epoch.
  
  5) Why should an engineer validate GMAT outputs instead of accepting them blindly?
  GMAT outputs are based on multiple factors such as the inputs and methodology chosen for a certain
  calculation to take place. Any mishap among those can produce different results than expected. GMAT
  is just a tool, it will only do what it is told to, therefore, it is important for the user to
  crosscheck any results produced.

Evaluation and Feedback:

->  "components and their lifetimes"
    A mission analyst usually doesn't directly determine component lifetimes—that's more the
    responsibility of subsystem engineers (thermal, power, structures, etc.). Mission analysis
    those constraints rather than owning them.
    "...while considering spacecraft performance, operational constraints, environmental effects,
    mission timelines, and available resources."
    
-> "information already known"
    change to "engineering assumptions"

-> "possibly headed"
    The velocity vector tells us exactly how the spacecraft is moving at that instant.
    Future motion depends on the forces acting on it.
    "...describes the spacecraft's instantaneous position and velocity."

-> "six numbers tell us..."
    "Under classical Newtonian mechanics, the equations of motion are second-order differential
    equations. By expressing them as six first-order equations (three positions and three
    velocities), the spacecraft's future motion becomes uniquely determined once the acting forces
    are known."
  
-> Why epoch?
    The spacecraft is moving.
    The state vector changes continuously.
    Without the epoch...
    the state vector becomes meaningless.
    "A state vector is only valid at a specific instant in time. Since spacecraft motion is
    continuous, the epoch tells us exactly when the reported position and velocity were true,
    allowing accurate propagation and comparison with observations."

-> Future position?
    You need
    - state vector
    - epoch
    - force model
    Without forces...
    you can't propagate.

-> Writing Feedback

     1) Instead of "GMAT outputs are based on multiple factors such as the inputs and methodology
      chosen for a certain calculation to take place."
      Write:
      "GMAT results depend entirely on the assumptions, models, and inputs selected by the user. An
      incorrect force model, initial state, or numerical configuration can produce misleading
      results. Therefore, engineers must verify that the simulation accurately represents the
      intended mission before relying on its outputs."

      2) "to be able to determine" - "to determine"

      3) "information regarding" - "information about"

      4) "help simulate" - "simulate"

      5) "at any given instant" - " at a given instant"
