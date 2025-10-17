---
layout: person
title: 'Henrik Palme'
category: people
permalink: /people/henrik
image: /assets/people/hepalme.jpg
position: 'PhD Student'
status: 'current'
---

![Henrik](/assets/people/hepalme.jpg){:class="people-profile-image"}

## About me

My research is in biomechanical modeling for the non-linear inversion (NLI) process for Magnetic Resonance Elastography (MRE) that converts the acquired displacement field into material parameters.

Magnetic Resonance Elastography (MRE) uses Magnetic Resonance Imaging (MRI) along with a pneumonic driver that sends mechanical waves into the brain. to map the displacement of the tissue as a result the waves. From the acquired displacement field, a process known as inversion must be performed to obtain the material parameters, which are of clinical importance. While there are numerous methods for this process, Non-linear Inversion (NLI) is often used.

Non-linear inversion (NLI) creates a Finite Element Model (FEM), material parameters are then guessed and the simulated displacement field along with the measured displacement field are used to obtain an objective function. Which is then used for a gradient decent method of optimization to obtain the material parameters.

The NLI process assumes a material description which is typically viscoelastic. Another model which is the focus of my research is the poroelastic model, which instead of modelling the brain tissue as a monophasic continuum, instead sees it as a biphasic continuum with a solid matrix permeated by a fluid. This material model allows for better inversion for lower frequencies, allowing for the cardiac cycle to act as source of the mechanical waves.

While poroelastic inversion is the main topic of my project, deep learning techniques, phantom construction and other MRI modes will be included as well.
