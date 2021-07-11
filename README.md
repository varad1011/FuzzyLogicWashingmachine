# FuzzyLogicWashingmachine

Introduction

Fuzzy logic washing machines are gaining popularity. These machines offer the advantages of
performance, productivity, simplicity and less cost. Sensors continually monitor varying
conditions inside the machine and accordingly adjust operations for best wash results.
The fuzzy logic checks for extent of dirt and grease, the amount of soap and water to add,
direction of spin and so on. The machine rebalances washing load to ensure correct spinning.

Fuzzy Inference System
Fuzzy Inference System is a way of mapping and input space to output space using fuzzy logic.
The rules in FIS are fuzzy production rules like
• If (antecedent) then (consequent)
• If x is low and y is high and z is medium

Architecture:
o Rule Base: It contains the set of rules and the IF-THEN conditions provided by the
experts to govern the decision making system, on the basis of linguistic information. Recent
developments in fuzzy theory offer several effective methods for the design and tuning of fuzzy
controllers. Most of these developments reduce the number of fuzzy rules.

o Fuzzification: It is used to convert inputs i.e. crisp numbers into fuzzy sets. Crisp inputs
are basically the exact inputs measured by sensors and passed into the control system for
processing, such as temperature, pressure, rpm’s, etc.

o Inference Engine: It determines the matching degree of the current fuzzy input with
respect to each rule and decides which rules are to be fired according to the input field. Next, the
fired rules are combined to form the control actions.

o Defuzzification: It is used to convert the fuzzy sets obtained by inference engine into a
crisp value. There are several defuzzification methods available and the best suited one is used
with a specific expert system to reduce the error.

● Membership Function:
A graph that defines how each point in the input space is mapped to membership value
between 0 and 1. Input space is often referred as the universe of discourse or universal set
(u), which contain all the possible elements of concern in each particular application.

Algorithm

Antecedents(inputs)
• Laundry_weight
• Dirt_level

Consequents(output)
• Powder_amount

Rules
• If the laundry weight is small and dirt level is low then amount of powder required is
small.

• If laundry weight is medium and dirt level is low then amount of powder required is
medium.

• If laundry weight is large and dirt level is low then amount of powder required is
medium.

• If laundry weight is small and dirt level is high then amount of powder required is
medium.

• If laundry weight is medium is medium and dirt level is high then amount of powder
required is medium.

• If laundry weight is large is high and dirt level is high then amount of powder required is
high.
