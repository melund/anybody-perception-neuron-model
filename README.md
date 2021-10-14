# AnyBody model based on Perception Neuron data

An AnyBody MoCap model based on data from the perception neuron inertial motion capture suit.

> *WARNING:* Some user have pointed out that there are many versions of data output from perception neuron. Maybe due changes in different versions over time. See this [issue](https://github.com/melund/anybody-perception-neuron-model/issues/1)


This model is an adaptation from the original BVH model example in the AnyBody Managed Model Repository (AMMR). This model has been modified to work with the Perception Neuron inertial MoCap suit. 

> **Warning:** The Perception Neuron data is not suitable for very dynamic models, since the acceleration seem inconsistent with kinematics. Inverse dynamic models require correct accelerations to calculate forces correctly. The model may be suitble for more static tasks where accelations does not play an important role. 

Also note that this model example is 'work in progress' the 'virtual marker procol' needs to further tweaked so the AnyBody model better matches the perception neuron stick figure model. 
