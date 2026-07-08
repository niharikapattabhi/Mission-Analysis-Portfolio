Day 1 notes QnA:
  What is Mission Analysis?
  Mission analysis is determining whether a mission is physically possible, technically achievable, 
  operationally feasible and efficient while meeting all engineering requirements and constraints.
  It is the complete end-to-end planning of a mission, its components and their lifetimes with respect
  to the budgets associated with each system and subsystem.
  
  Why is GMAT only a tool?
  GMAT or NASA's General Mission Analysis Tool produces outputs based on what information is being
  fed into the system. It basically functions like a calculator. It cannot derive any mission related
  information on its own, it will only help simulate the mission based on information that is already
  known and being input and then using certain algorithms to help predict later stages. GMAT is only
  a tool, the user is the engineer.
  
  What is a state vector?
  State vector contains information regarding the current position and velocity of a spacecraft at
  any given instant. This tells us where the spacecraft currently is and where it is possible headed
  to be able to trace its path both backward and forward. All other information regarding a spacecraft's
  trajectory and orbit can be determined from the knowledge of the state vector.
  
  Why are six numbers sufficient to define the spacecraft state in classical mechanics?
  The six numbers within the state vector are 3 coordinates of position x, y, z and 3 velocity directions
  v_x, v_y, v_z. These six numbers tell us where the spacecraft currently is and where it is headed and 
  at what speed.
  
  Why is altitude alone insufficient to describe an orbit?
  Altitude alone is not enough to describe an orbit because a spacecraft at a certain height at that
  instant can be following any trajectory or orbit. It could be in a elliptical or circular orbit, it 
  could be geo or sun synchronous, or even in an escape trajectory. This is why it is necessary to know
  the satellites' state vectors.

Day 1 Interview Qs:
  What is the difference between a trajectory and an orbit?
  A trajectory is the path followed by the spacecraft. A trajectory that repeats itself around a
  central body is an orbit.
  
  Why do mission analysts care about the epoch?
  State Vector is one of the most important pieces of information a mission analyst can have regarding
  a spacecraft. It tells us about the position and velocity at a certain time instant so that one can
  determine what path the spacecraft might have been following and what path it is headed on. That
  current instant of time is called Epoch. A mission analyst should know when the given state vector
  is from.
  
  Why can't altitude alone define a spacecraft's motion?
  Altitude alone does not give us enough information about a satellite's whereabouts. To know the
  exact orbit it is in or the trajectory it is following, information of the state vector is required.
  
  What information is required to predict a spacecraft's future position?
  A spaecraft's future position can be determined by knowing the state vector (position and velocity)
  and epoch.
  
  Why should an engineer validate GMAT outputs instead of accepting them blindly?
  GMAT outputs are based on multiple factors such as the inputs and methodology chosen for a certain
  calculation to take place. Any mishap among those can produce different results than expected. GMAT
  is just a tool, it will only do what it is told to, therefore, it is important for the user to
  crosscheck any results produced. 
