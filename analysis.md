# Analysis

## Layer 1, Head 11

This attention head seems to capture the relationship between verbs and their direct objects. The attention score seemed to appoint to the influence of the verb and the direct object. It also appeared to consider the influence of the complement of the object in the main part of the direct object

Example Sentences:
- The cat chased the [MASK] through the garden.

![Image from the layer 1, Head 11 for the sentence](bckp_analysis/Attention_Layer1_Head11_1.png "Image from the layer 1, Head 11 for the sentence")

- She quickly solved the [MASK] without any hesitation.

![Image from the layer 1, Head 11 for the sentence](bckp_analysis/Attention_Layer1_Head11_2.png "Image from the layer 1, Head 11 for the sentence")


## Layer 3, Head 9

This attention head seems to capture the relationship between pronouns and their antecedents. Even considering the noise in the result it is clear that it pays attention to the token representing the antecedent of a pronoun, indicating an understanding of pronoun context.

Example Sentences:
- John visited Mary at her [MASK].

![Image from the layer 3, Head 9 for the sentence](bckp_analysis/Attention_Layer3_Head9_1.png "Image from the layer 3, Head 9 for the sentence")

- The chef sip his wine with his [MASK].

![Image from the layer 3, Head 9 for the sentence](bckp_analysis/Attention_Layer3_Head9_2.png "Image from the layer 3, Head 9 for the sentence")
