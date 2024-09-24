Lab 0 overview
In this lab, we'll focus on teaching you how to use these challenge notebooks, how to grade your work, and how to manage the general flow of setting up, running, and evaluating the results of your quantum code.

To complete this and the other labs, you'll need to know a little bit about the Python programming language. Each lab contains a mixture of tutorial content, pre-written code blocks, and challenge code blocks that require you to fill in your own Qiskit code. To complete an exercise, you'll need to type the required code underneath each line that has the ## Write your code below here ## comment.

It's important to note that you should run each code cell, even if you didn't write any new code there. This ensures that when you submit your answers later on, everything is up to date. There will be one or two exceptions to this rule, depending on what type of computer you are using.


Welcome to lab one! This lab is designed to introduce you to some of the new capabilities and functions of Qiskit 1.0. Later challenges will develop on these capabilities further and introduce the more complex new Qiskit functionalities.

Through this lab you will learn how to set up quantum states using Qiskit, and how to implement an optimization algorithm using VQE. These two tasks will be set in two sections:

Qiskit states, the new and the old
VQE with Qiskit 1.0
Let's get started!


Prologue - What is the transpiler?
Let's start with a hypothetical question:

When someone hands you their car keys and says "will you fill my car up with fuel?" - how do you know what to do?

Sure, you have your driver's license, but what type of car do they have? Where is their gear shifter? How do you turn on the blinker to turn the corner, or open the fuel tank once your arrive? What if it's an electric car that doesn't even have a fuel tank??

Luckily, the human brain is smart. It is able to take a set of instructions and adapt them to the vehicle being used.

That, in essence, is the transpiler.

Transpilation is the process of taking a given input circuit and rewriting it to an equivalent circuit for a specific quantum device, and/or to optimize the circuit for execution on a real quantum system.

This is necessary because not all quantum devices work the same way. The instructions you send to one device might not be compatible with a different quantum backend. Transpilation operates in terms of a device's basis gate set, the topology of the quantum chips, timing constraints, and more which we will explore in this lab.

The goal of a transpiler is to get the best performance from noisy quantum hardware. Most circuits must undergo a series of transformations that make them compatible with a given target device, and optimize them to reduce the effects of noise on the resulting outcomes.

Welcome to Lab 3! Today, we are thrilled to give you an exclusive sneak peek into some of the exciting new features that are being developed for the Qiskit stack. This educational challenge is split into separate notebooks, each showcasing a unique and groundbreaking innovation and invites you to explore and test these new features. Dive in to explore tools like the Circuit Knitting Toolbox to simplify complex quantum circuits, experience the workflow to setup seamless integration of quantum and classical computing with Qiskit Serverless and have a chance to leverage AI-Powered tools like the Qiskit Code Assistant for code generation and circuit optimization with AI-Powered Transpiler Passes. Dive in and discover how these innovations are set to revolutionize quantum development!
