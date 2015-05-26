# Lessons Learned from CPS and Cable Analysis
--
## Cable mechanical properties are...
--
<!-- .slide: data-background="media/img/magic.jpg" -->
## ...not well understood.

--
For installation, storm and fatigue analysis we care about:
## Bending stiffness

Note:
Is the key input. It defines the structure's resistance to bending loads.
It feeds into weather windows.
--

## In practice bend stiffness depends on:
- curvature and rate-of-change of curvature
- tension
- temperature

<img data-src="media/img/cable_ei1.png">

Note:
The curve shown is the simple way of expressing the real bending behaviour of cables.
--

### Most cable suppliers define bend stiffness like this:

--

| Cable Property | Value |  Units  |
|:--------------:|:-----:|:-------:|
| Bend stiffness |  1.5  | $kNm^2$ |

--
<!-- .slide: data-background="media/img/facepalm.jpg" -->
--
### Most, not all. Some do this:
--

| Cable Property | Value |  Units  |
|:--------------:|:-----:|:-------:|
| Bend stiffness |  1.5 or 15  | $kNm^2$ |
--
### or
--

| Cable Property | Value |  Units  |
|:--------------:|:-----:|:-------:|
| Bend stiffness |  $1.5 \pm 50\%$  | $kNm^2$ |

--

### one manufacturer told us they didn't know

--

### one manufacturer recently sent us a proper curve

<img data-src="media/img/success_baby.jpg">

--

## Our approach
- Analytical model based on published literature
- Backed-up by some testing
- More work needed

<img height="400px" data-src="media/img/nonlinear.png">

--
<!-- .slide: data-background="#008080" -->
# Installation analysis

--
<!-- .slide: data-background="media/img/analyst.jpeg" -->

## Analysis is cheap

--
<!-- .slide: data-background="media/img/cable_ship.jpg" -->

## Vessels are expensive
--

## Analyse upfront:
- Installation
- Abandonment
- Recovery
- Repair

--
## Combinations of:
- Water depth
- Environment direction
- Sea-state
- Current

--
<!-- .slide: data-background="#000080" -->
# Other topics
- Lead sheath
- Free-hanging cables
- Thermal performance

--
<!-- .slide: data-background="#000080" -->
## Export cables
- Lead is awful in fatigue. Really terrible. 
- The fatigue curve is an odd shape. 
- Non-linear bend stiffness helps

<img height=300 data-src="media/img/lead-k-n.png">

--
<!-- .slide: data-background="#000080" -->
## Free-hanging cables
- The tower moving is not a problem. Promise.
- The newly installed condition will not persist
- Structural damping is important
- Unlikely to be a real problem

--
<!-- .slide: data-background="#000080" -->
## Thermal issues
- Proper accurate analysis is **very** difficult
- Simple analysis will show erroneous issues
- Convection is extremely important
- Cable in air is likely the worst condition