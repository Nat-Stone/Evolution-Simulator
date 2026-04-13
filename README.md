# Evolution-Simulator
This evolution simulator begins with creatures with random attributes, but the fittest creatures become more prominant due to natural selection. Creatures can be selected to view their information, and simulation settings can be modified as variables in the code.

Press "p" to pause
Click creature to view their attributes
  "Energy" is a creature's energy, which is consumed through movement, turning, vision, and birth
  "Health" is a creature's health, which is consumed after energy is depleted
  "Max Health" is the maximum health a creature can have, which is proportional to the square of size
  "Color" is a creature's rgb color
  "Size" is a creature's size, which is proprtional to the rate of energy consumption due to movement and the square root of max health
  "Speed" is a creature's movement speed, which is proprtional to the square root of the rate of energy consumption due to movement
  "Angular Speed" is a creature angular speed, which is proprtional to the square root of the rate of energy consumption due to turning
  "Birth Energy" is the ammount of energy transfered to children
  "Birth Factor" is the ratio between a creature's minimum energy needed to give birth and the energy it transfers upon giving birth
  "Sight Distance" is the distance a creature can see, which is proportional to the square root of the rate of energy consumption due to vision
  "Sign Angle" is the angular width of a creature's vision, which is proportional to the rate of energy consumption due to vision
  "Angle Weight" is how heavily a creature prioritizes moving forward over turning, with target score (which a creature minimizes) being calculated as {Target Distance} + {Target Angular Distance} * {Angle Weight}
  "Heal Energy" is the minimum energy at which a creature will convert energy to health
  "Healing Rate" is the rate (energy / time) at which a creature converts energy to health, with lower rates being more energy-efficient
