# The Four-Color Theorem

> *"The four-color problem asks whether the regions of every map drawn on a plane or sphere can be colored with just four colors in such a way that any two regions sharing a common boundary line receive different colors. First posed by Francis Guthrie in 1852, it was eventually answered in 1976 by Kenneth Appel and Wolfgang Haken, when it became known as the four-color theorem."*

## Overview & History
The Four-Color Theorem (or Four-Color Map Theorem) is a famous mathematical theorem within the field of topology and graph theory. It states that, given any separation of a plane into contiguous regions (like a political map of countries), no more than four colors are required to color the regions so that no two adjacent regions share the same color. 

*Note: "Adjacent" means they share a boundary segment of non-zero length. Regions that only meet at a single shared point do not count as adjacent.*

The problem remained one of the most famous unsolved problems in mathematics for over a century:
*   **1852:** First proposed by Francis Guthrie while coloring a map of the counties of England.
*   **1879:** Alfred Kempe published a "proof" which was widely accepted for over a decade.
*   **1890:** Percy John Heawood proved Kempe's proof was flawed (though Kempe's technique, finding "Kempe chains", became fundamental to the actual solution).
*   **1976:** Kenneth Appel and Wolfgang Haken of the University of Illinois finally proved the theorem.

## The Computer-Assisted Proof Controversy
The Apple & Haken proof in 1976 sent shockwaves through the mathematical world because it was the **first major mathematical theorem to be proved using a computer**. 

The mathematicians proved that if the map could not be colored with four colors, it had to contain at least one of 1,936 specific complex configurations. They then used a custom-built computer program to meticulously check every single one of those configurations to prove they were "reducible" (meaning they couldn't exist in a minimal counter-example).

This sparked intense philosophical debate: *Is it a "proof" if a human cannot manually verify each computation?* 
Over the years, the method became accepted. In 2004, Georges Gonthier formalized the proof using Coq (a mechanical theorem-proving software), completely cementing the theorem's validity.

## Recommended Books
*   **"Four Colors Suffice: How the Map Problem Was Solved"** by Robin Wilson - An excellent, highly readable history of the problem and the eccentric characters who tried to tackle it.
*   **"The Four-Color Theorem and Basic Graph Theory"** by Chris McMullen - A more structured, mathematical approach exploring how the map problem translates into planar graph theory.

## Recommended YouTube Resources
*   **[The Four Color Map Theorem - Numberphile](https://www.youtube.com/watch?v=NgbK43jB4rQ)** - Numberphile provides their trademark excellent, intuitive explanation using actual maps and markers.
*   **[The 4 Colour Theorem Explained (Graph Theory)](https://www.youtube.com/watch?v=11i_j9N-hKw)** - Focuses heavily on the underlying principles of graph theory and uses animations to demonstrate how the computer proof actually worked.
*   **[Georges Gonthier explains the 'Four colour theorem'](https://www.youtube.com/watch?v=uD9R_nE92U0)** - A discussion with the mathematician who formally verified the computer proof using the Coq proof assistant.
