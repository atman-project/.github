# Atman Project

## Rethinking the Web

The Web has become an integral part of our daily lives. We communicate, learn, entertain, and even exist through it. As the Web continues to evolve, there is a pervasive belief that expanding its role will inevitably make our world better.

The Atman Project arises from this question: Do we really need the Web to expand in its current direction? Expanding the Web isn’t without cost. The common misconception is that the Web is free because many services require no direct payment. However, nothing in our world is truly free. We implicitly trade our data, privacy, and time for the convenience the Web offers.

While I wouldn’t say the Web is corrupted, it has certainly become intrusive. Companies that sustain the Web with their profit-driven models are compelled to expand it, making it larger and more complex to accommodate increasing users, traffic, and multifaceted use cases. This growth consumes vast amounts of human energy, natural resources, and time. They continue to generate revenue under the guise of making the world a better place, but we must critically assess whether these efforts are truly necessary.

The Web doesn’t have to be this way. It can be simple. It can resemble the physical world we inhabit — a world where we aren’t overwhelmed with excessive information and stimuli. Imagine a Web where we only interact with those we wish to engage with, and where we access information that is truly relevant and manageable. This would be sufficient because that is how we live in the real world.

Of course, the Web and the Internet should continue to serve as vast reservoirs of knowledge that enrich our lives. But they should not delude us into thinking we can become superhuman, capable of accomplishing anything effortlessly and without cost. The Web shouldn’t be bloated to perpetuate this illusion faster and to more people.

We have the potential to build a minimal yet optimal Web—one that respects our privacy and time. In this vision, the Web would offer greater power and utility, but only when we consciously choose to contribute our fair share. This change would reorient us towards recognizing and valuing the real world, rather than becoming lost in an intrusive digital one. It would reduce the environmental toll we justify in the name of progress. Ultimately, this approach would help us focus on caring for ourselves and our tangible communities, rather than investing in the lives of strangers online.

## Objective

Atman Project hopes that Internet users can easily control who can access to their data.

Users should be able to continuously track and control access to all the data I shared or published through the internet. This capability should not be dependent on specific service providers, applications, or platforms. Regardless of which storage, application, or vendor I use to publish my data, that data should be entirely under my control (or someone authorized by me). The current architecture of the Web may not be well-suited for this goal. The Atman Project is focused on designing and implementing the essential, feasible protocols to achieve this objective.

## WIP: Protocols

Atman Project consists of several protocols. Each protocol targets its unique goals, but all ultimately pursue the same values.

### Universal Personal Data Sync/Backup

Universal data sync is one of the core protocols. Atman Project aims to define the universal data representations, so any end-user services built on top of Atman Project can serve the same quality of data privacy, security, and soundness.
As the first piece of Atman Project, the universal data sync protocol defines a core personal data availability layer for users to maintain their data on their own and publish it through multiple applications that they really want to use, in the secure and sustainable way.

Similar as iCloud, but without any centralized authority. Users should be able to have the seamless experience between their multiple devices without storing their personal data in the cloud storage that a centralized authority manages its funtionalities, policies, and costs, even if the authority guarantees that user data is always stored securely. This is the essential part of the permanent web for users, which can be sustained even if big tech companies stop their business someday. 

End-user decentralized applications should be able to sync user's personal data between the user's devices seemlessly. This data sync/backup can be done with peer-to-peer networking. Users should be able to choose to run their own node if they want. Or, they should be able to use nodes operated by others without comprimising privacy, but with paying compensations to them. 

Data should be basically stored in user's personal devices, even if data is delivered by decentralized peer-to-peer network through some of nodes operated by others, especially when user's devices are not reachable directly from the Internet.

### Universal Verifiable Personal Data Sharing

In the modern web where there are many contents produced in multiple ways that we have never imagined so far, it is very important to express what we think in trustworthy ways. The universal verifiable data sharing protocol defines the way how to prove that I produced the data and whom the data has been shared with, without relying on any centralized environments.

Similar as the `Share` button in iOS or Android mobile devices, but with the explicitly-managed data sharing history. This can be done by cryptographic signatures/encryption, zero-knowledge proof, and decentralized ledgers. Data shared on the Internet should be shaped by standard data sharing protocols, so that anyone can keep track of the history - who created the data initially and whom the data has been shared with. Also, this cryptographic history should be able to be used to detect and punish any malicious behaviour on the data.

### Personal Data Publishing 

Various Web3 infrastructures and frameworks enable users publish their data to the public Web without relying on centralized authorities. But still, it is not easy for end-users and even for application developers to shape their architecture to work with decentralized infrastructures. Atman Project should be able to fill in missing parts between applications in production and decentralized infrastructures, so that users can publish their posts, images, and videos, as if they have done in the traditional web.

### Mobile connectivity

The great advantage of decentralized peer-to-peer network is enabling mobile devices work as indenpendant decentralized nodes. Also, even a small laptop in home network can act as a decentralized node. However, there are still many challenging areas that need to be improved for better availability and performance. This is the fundamental part for all products introduced above. Atman Project is going to collaborate with many players who are crafting decentralized network infrastructure, and contribute to them in order to boosting the future of decentralized web.
