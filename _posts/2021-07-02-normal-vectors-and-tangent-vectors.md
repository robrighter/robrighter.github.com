layout: post
title: "Finding Normal Vectors and Tangent Vectors"
date: 2021-07-02 21:00:00 -0000
categories: CATEGORY-1 CATEGORY-2

Tangent and normal vectors show up all over the place in math and physics. You will often find yourself in situations where you need to calculate each one and use the resulting expressions to calculate a measure of work or force or even as a step in a longer multidimensional optimization calculation. In many of these cases you will want to use them as a unit vector. The unit vector version of a vector is the vector scaled down to a single unit of magnitude.

The problem with calculating these unit vectors is that they can be very messy and time consuming to calculate. In this notebook our goal is to better understand the steps of computation and write a simple python program that will do the computation. To simplify things a bit, we will be working in just 2 dimensions.
