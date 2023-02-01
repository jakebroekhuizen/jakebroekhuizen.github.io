---
title: Quantum Disruption?
tags: Tech
show_subscribe: false
sharing: false
comment: false
license: false
show_edit_on_github: false
---

Chuang, Gershenfeld and Kubinec. Remember the names. <!--more-->

In 1998, these three were responsible for [building the first quantum computer](https://www.britannica.com/technology/quantum-computer). Even though it was only 2-qubits (the quantum version of standard 1-0 binary bit that can take either value simultaneously), and represented the ability to encode only 1/8th of the data that the first computer could handle, it put a stake in the quantum-computing ground and paved the way for the developments to come as we launched into the 21st century.

Fast-forward to the present day and we now have IBM’s whopping [433-qubit quantum computer](https://newsroom.ibm.com/2022-11-09-IBM-Unveils-400-Qubit-Plus-Quantum-Processor-and-Next-Generation-IBM-Quantum-System-Two) aptly named ‘Osprey.’ For context, the modern day laptops we use typically run on a 64-bit architecture and because a qu-bit can either be a 1 or 0, n qu-bits equates to 2<sup>n</sup> bits. This means that Osprey can store 2<sup>427</sup> more bits than the industry standard machines we use today. That is an astronomically large number. In general, the more bits a computer has, the more data it can process at once and the more memory it can access. The implications of this potentially unprecedented level of computing power has been making ripples in different industries across the world, but where it has drawn some particular attention recently - as well as a hint of concern - is in the cybersecurity space.

RSA - named after its founders, Rivest-Shamir-Adleman - is the most commonly used encryption system to secure communications over the internet. I wont dive too deep into the details of how it works - you can read more about it [here](https://www.techtarget.com/searchsecurity/definition/RSA) - but its security relies on the fact that part of the ‘RSA keys’ used in its algorithm is the product of two large prime numbers, and that factoring this product to find the original prime numbers requires an insurmountable amount of computing power. To put it into perspective, a modern computer would take 300 trillion years on average to crack a 2048-bit RSA key. It is this reliance on the lack of computational resources of current technology that ensures the security of all cryptographic methods, including RSA, used today.

In early January this year, a team of researchers based in Beijing released a [paper](https://arxiv.org/pdf/2212.12372.pdf) that claims they have found an algorithm that can potentially break 2048-bit RSA.

> “*We estimate that a quantum circuit with 372 physical qubits and a depth of thousands is necessary to challenge RSA-2048 using our algorithm.”*
> 

This notion of only needing 373 qu-bits directly challenges the existing assumption of needing around 4,000 - something that is currently well out of technical scope. However, the underlying assumptions that lead to the derivation of this new algorithm have been fiercely questioned, and as expressed in this article by Ars Technica, have been labelled as “one of the most actively misleading quantum computing papers . . . in 25 years.” The general academic opinion seems to reassuringly assert that, even with the unveiling of Osprey by IBM, the threat of being able to crack RSA is highly overexaggerated. 

It is unsurprising that such a paper would be met with such fierce scrutiny. The security of modern communication systems, the authenticity of some of the most widely used software, the security underpinning our financial institutions and more are all at stake if RSA public-key cryptography was to be solvable by quantum computers in a feasible amount of time.

It seems that academic challenge like this over quantum computing and it’s increasing power levels the concerns we have over the threats to our current cybersecurity system. I wonder, however, how long it will be before this type of academic coverage acknowledges that the current systems in place will need to change because of the power of quantum computers. 

Chuang, Gershenfeld and Kubinec opened a box that can’t be closed.
