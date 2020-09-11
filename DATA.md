We are going to work with a dataset that contains the data of car accidents in the city of Seattle from 2004 to the present.

The dataset has the severity column, which describes the fatality of the accident, which will be the dependent variable that we will try to predict. Also, the dataset has 37 columns or attributes that will serve (probably some will not be useful or need to be transformed) to train our model with the supervised machine learning algorithm we choose.

Some of the attributes are: BJECTID INCKEY COLDETKEY REPORTNO STATUS ADDRTYPE INTKEY ...	ROADCOND LIGHTCOND....

 - ATTRIBUTE INFORMATION

LOCATION Text, 255 Description of the general location of the
collision
EXCEPTRSNCODE Text, 10
EXCEPTRSNDESC Text, 300
SEVERITYCODE Text, 100 A code that corresponds to the severity of the
collision:
• 3—fatality
• 2b—serious injury
• 2—injury
• 1—prop damage
• 0—unknown
SEVERITYDESC Text A detailed description of the severity of the
collision
COLLISIONTYPE Text, 300 Collision type
PERSONCOUNT Double The total number of people involved in the
collision
PEDCOUNT Double The number of pedestrians involved in the
collision. This is entered by the state.
PEDCYLCOUNT Double The number of bicycles involved in the collision.
This is entered by the state.
VEHCOUNT Double The number of vehicles involved in the collision.
This is entered by the state.
INJURIES Double The number of total injuries in the collision. This
is entered by the state.
SERIOUSINJURIES Double The number of serious injuries in the collision.
This is entered by the state.
FATALITIES Double The number of fatalities in the collision. This is
entered by the state.
INCDATE Date The date of the incident.
INCDTTM Text, 30 The date and time of the incident.
JUNCTIONTYPE Text, 300
Category of junction at which collision took
place
SDOT_COLCODE Text, 10 A code given to the collision by SDOT.
SDOT_COLDESC Text, 300 A description of the collision corresponding to
the collision code.
INATTENTIONIND Text, 1
Whether or not collision was due to inattention.
(Y/N)
UNDERINFL Text, 10 Whether or not a driver involved was under the
influence of drugs or alcohol
