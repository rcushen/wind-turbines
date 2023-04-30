# wind-turbines

This repo contains analysis and modelling over wind turbine data provided by Engie.

## Project Brief

The project is based on the IOT data made publicly available by Engie for four wind turbines in France in La Haute Borne.

A more complete data description is given by Engie on the site.

To get a better understanding of the data, its parameters and their relationships, it might be useful to read [this](https://en.wikipedia.org/wiki/Wind_turbine_design#:~:text=Other%20controls-,Generator%20torque) wiki. Import concepts like cut-in speed, rated speed, cut-out speed, tip-speed-ratio (TSR), torque control and pitch control should be understood.

For a more complete overview, see *Wind Turbine Fundamentals (Hau)*. This book is huge, so don't read it completely, but just look up what you want to find, because it is the most complete resource on the topic.

## Project Goal

The goal is to use this data and create machine learning models that can predict the output of the turbine (rotor torque, converter torque and/or power output).

These models can be used as 'benchmarks' or 'digital twins' to compare the actual behaviour with expected behaviour. If actual behaviour consistently underperforms expected behaviour (negative bias) this could be a tell-tale sign of a defect component and maintenance actions should be undertaken before it causes bigger components to fail.

NOTE: this 'Project Goal' is just a suggestion and if you believe there are other applications or ways to prove that ML can create value for Engie using this data, please go ahead!