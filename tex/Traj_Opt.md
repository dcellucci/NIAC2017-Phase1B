# Cycler Architecture

**Objective:** Examine the logistics of constructing a series of large vehicles on a cycler trajectory using digital cellular solids

## Outline

1. Definition
   1. A cycler is an orbital trajectory where a body encounters two planets on a regular schedule without entering into the orbit of either planet. 
      1. These trajectories can vary in the frequency with which they encounter the planets, as well as the number and magnitude of maneuvers required to maintain the orbit
      2. Cyclers that require almost no fuel to maintain are known as "ballistic cyclers"
         1. Because ballistic cyclers require little fuel, an extremely large vehicle can travel on the orbit without excessive operating costs.
2. Background
   1. History of Cycler orbits
      1. Originally introduced by Hollister in the mid sixties, the most famous of these trajectories is the Aldrin cycler, which are capable of ~6-month traversals between Earth and Mars in one direction, and 1.5 year traverseals in the other. 
         1. These trajectories can be configured such that the ~6-month traversal is in either the Earth to Mars (Up-) or vice-versa (Down-) direction, 
         2. Typical cycler missions propose two vehicles, one on each of these orbits, in order to ensure minimal travel time in interplanetary space.
      2. The Astrotel NIAC examined a transportation infrastructure involving cyclers for travel between Earth and Mars
         1.  included several additional support vehicles, including freighters, spaceports, and taxis around multiple other bodies, including the Moon and Phobos.
         2.  The work culminated in the MAMA trade study: a full exploration of the range of dependencies which support a cycler architecture
   2. the MAMA trade study was designed to allow the identification of critical technologies that would enable the cycler infrastructure
      1. These included fuel storage, propulsion technologies, and ISRU
         1. the majority of the estimated cost of the mission was in development of these technologies
      2. The building blocks of the estimates used in the trade study were high-fidelity analyses of the engineering requirements of each capability
3. RHISE
   1. MAMA assumed the development and establishment of an entire infrastructure using a traditional approach
      1. Vehicles are reusable, but only in their original context. 

   2. Extensive reconfigurability afforded by digital cellular solids provides an alternative approach to the formulation of these missions
      1. the mass contained within vehicles can be actively repurposed to adapt to the current mission context.

   3. Reconfigurability and standardized parts are not new
      1. have been shown to provide a sizable reduction in the total mass required for a standard Mars exploration mission [spares paper]

   4. In order to understand the impact of reconfigurability on the logistics of an interplanetary transport infrastructure, a mission architecture such as the one introduced in the Astrotel NIAC can be extended and formalized as a problem in network flow theory and scheduling optimization.

      1. Network flow theory is a well-explored technique in operations research
         1. has been applied to the optimization of freight transportation networks, air traffic control, and resource distribution.
      2. Applied to the problem of interplanetary exploration, it can provide a means of exploring the entire problem space of transportation options, and finding the optimal solutions. 
         1. As an extension of MAMA, it will automate the process of technology selection.
         2. An important caveat of the approach, however, is that assumes a mature technological ecosystem, focusing instead on the optimal logistical infrastructure and 

   5. PROBLEM STATEMENT

      ​



