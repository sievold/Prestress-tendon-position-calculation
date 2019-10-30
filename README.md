# Prestress-tendon-position-calculation
# Input values in only the fields between F8 and M8
# Span and desired position from midpoint along span takes inputs in feet, all other measurements are in millimeters
# From the midspan upto the point 4*span/10 from the midspan, the tendon follows the curve y = a * (x^2)
# From the 4*span/10 position upto the endspan, the tendon position is linearly interpolated
# The tendon position at the centreline (y0) and the endspan(h1) must be known for this excel to be useful
# The diagrams are not to scale
#The necessary code is hidden behind the beam duct profile graph and the rectangle group object with the beam section graphs
