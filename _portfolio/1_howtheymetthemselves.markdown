---
layout: post
permalink: /how-they-met-themselves/
title: How They Met Themselves
description: HD Video
img: /img/title.png
---

<iframe src="https://player.vimeo.com/video/534972032" width="480" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

<br>

How They Met Themselves is a software demonstration and research output of an ongoing investigation into how algorithmic and human schemas of facial identification, verification and perception differ and how these differences can be leveraged to control how our identity is coded in the images we put online.

Deepfake Dopplelganger is a software tool developed to exploit some of these differences. The application generates a bespoke avatar based on the user's uploaded portrait image that preserve the likeness of the face in the uploaded image whilst obscuring the biometric data linking the avatar to the user.

The software advances an adversarial approach to countering digital privacy threats by pitting generative machine vision against inferencing machine vision. The software utilises facial verification systems in the production of the avatars in order to ensure a specific and desired result is produced when that avatar is later fed into a similar system.

Within human schemas of identity perception and verification of the face sit within a larger assemblage of signals used to distinguish between individuals. Machine vision systems do not have such rich, adaptive and complex schema of identity and often rely on binary classification algorithms to distinguish identities.

These algorithms necessarily delimit a hard border at the edge of a category, an inflection point where subjects that are under observation are rolled into two distinct categories depending on which side they fall. This software locates the border of a facial verification systems' categorisation. It maps the extremity of a category in order to find the shortest distance between the original image and some image that falls into that category.

The software generates an avatar, or doppelgänger of the user by "projecting" their uploaded image into the StyleGAN2 FFHQ model, a generative machine learning architecture capable of producing endless images of convincing 'fake' faces.

When an image is projected in, the model searches for the closest match it can find to the input face by tuning its parameters at each step. This creates a continuum of difference between the closest match to the input face the network can produce, and the median face at the centre of the network's distribution.

Somewhere along this continuum, a facial verification algorithm comparing the face at each stage of the process to the input face will switch between outputting a positive and negative result. In other words, it will switch from classifying these faces as belonging to the same person to classifying these faces as belonging to two different people.

Given a stream of continuous data, such as the morphing faces produced here, a binary classification algorithm reveals the hard border at the inflection point between the categories of its classification. When we examine the images that surround this border, the location appears arbitrary; the images found either side of this border are nearly indistinguishable.

On one side of this border there is a face that shares a likeness with the uploaded image and is identified as the same person by a facial verification system. On the other side, there is a nearly identical face but one that the facial verification system identifies as an entirely different person. Once the process is complete, the user can then download the image found on the other side to use as an avatar.

The software also provides a free and open source method from controlling the doppelgänger with a webcam via Avatarify. Being too computationally intensive to run on a commercial laptop without a GPU, cloud computing is needed to run Avatarify. To handle the computation the software spins up a rendering server. The avatar can then be brought into a video conferencing platform with the aid of a virtual camera.

Through providing users a method for decoupling their likeness from their biometric data, Deep Fake Doppelgänger has the potential to reassert agency and disrupt the narrative framing of deep fake technology that renders us both helpless and passive.

<br>

This work was commissioned by the Centre for Design Informatics at the University of Edinburgh as part of the Zoom Obscura programme.

Special thanks to the Zoom Obscura team and to Murad Khan
