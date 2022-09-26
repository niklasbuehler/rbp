Interpretable Mechanistic Models for Predicting Tissue-specific RBP Expression
===

The term mechanistic model describes a model that is based on fundamental laws of the natural sciences.
A benefit of such models is that their variables have an actual meaning, allowing for easier interpretation.

In the domain of mRNA degradation, one fundamental law describes the way an mRNA interacts with its degradation factors.
A degradation factor is an RNA-binding protein, also called RBP, that contributes to the degradation of a bound RNA molecule.

A simplified version of this law states that the half-life of an mRNA, considering only a single degradation factor, is inversely proportional to its binding probability with this degradation factor, multiplied by the concentration of both molecules in some medium.
In this equation, the two concentrations measure how likely it is that the two molecules collide, while the binding probability defines the conditional probability of an actual interaction upon collision.
There is a variety of degradation factors that could possibly interact with a single mRNA molecule and influence its lifespan, so this simple law has to be applied for every single degradation factor and the results have to be aggregated.

Of course, there are other influences on mRNA half-life as well, but in this chapter, we will focus on this simplification.

In the following, we will fit, evaluate and interpret mechanistic models that try to exploit this relationship between RBPs and mRNA half-life.

The desired result of this approach is not so much a model with particularly high prediction capabilities, but rather to gain some insights about biological phenomena by interpreting the models.
With respect to the tissue-specific data we’re working with, interpretation could lead to the discovery of varying concentrations of different RNA-binding proteins in different tissue types.
