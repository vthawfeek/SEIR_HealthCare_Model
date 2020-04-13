This repo contains information on a model that describes a modified SEIR model integrated with healthcare resources usage with the aim of identifying the consumption rate of PPEs.

1. SEIR Modification: The infectious (I) is split into three types - 
I1: suspected cases
I2: patients with mild symptoms
I3: patients with severe symptoms

2. Healthcare resources model: The staff in frontline healthcare are divided into four categories and are avaialble depending upon the patients. The staffs are also at the risk of contracting the infection.
H1: Nurses
H2: Doctors
H3: Cleaners
H4: Assistants and others

3. PPE resources model: Personal protective equipments (respiratory/eye/body/hand protection) are modelled to be in five different states and are consumed by healthcare staff depending upon the patient severity status.
P1: Manufactured PPEs
P2: PPEs in transit/warehouse
P3: Complete set of PPEs containing all protective gears
P4: Defective PPEs
P5: Incomplete PPEs lacking some of the protective gears

