# Decentralized Agents

Our bodies are an ecosystem. Much of what we think we are, is actually a combination of organisms working in symbiosis. We have bacteria living in our bodies which without we wouldn't be able to thrive, and vice versa ((source)). The parts that come together to make us who we are can be described as plenty of simple systems, following simple rules, that result in an emergent whole. We are not independent of the systems around us. When we look at artifical intelligence, and especially how it has been portrayed by media and scif-fi, it is often this monolothic entity. In the movie, "I, Robot", in a massive skyscraper there is this big brain somewhere that powers robots across the world. Similarly, the famous "SkyNet" from the Terminator series, is distributed, but thinks centrally. It can't be shut down, since it is only cutting off a limb of a hydra, but it is still "monolithic" in design. It is not indepedent parts, coming together to form a conclusion that humanity is to be destroyed, but it is "one entity" built up of many parts, that do so. It is distributed, not decentralized: there is a "hub".

When we look at things like a swarm of birds, we sometimes imagine and wonder how they all "work" together to fly as a flock like that. It seems like there is some center, while there is not. A swarm moves with only local information: the combination of which lends itself to the fact that the flock eventually ends where it plans to go, even if there is some chaos in the process. A bird only takes in what the few birds around it is doing, and decides from that where to fly (along with its own desires). The result is an emergent flock, acting only on local information, heading towards its destination.

The AI we will see will be a swarm that when we look at it from a bigger picture will make us believe we see truly artifical intelligence, in the same way that we as biological entities can say we are "intelligent". Michael Jordan, a famous machine learning researcher, said ((insert quote about it won't be what we imagine)). Bitcoin & the blockchain will help us to build this. ((insert quote about Ethereum and fungus)).

## Blockchain in AI

I see the blockchain helping 2 ways: establishing consensus & helping with independent machine-to-machine value transfer.

### Value transfer

One of my favourite quotes in this space, is when Richard Brown (from IBM) said in an interview: "On the blockchain, no one knows you are a fridge". It's funny and correctly describes what becomes possible. In the future, we might very describe humanity (and its relationship to technology) in terms of pre-blockchain and post-blockchain, simply for one reason. It became not only for us humans to transact without a 3rd-party, but it also became possible for a machine to transact with another machine without a 3rd-party, and more importantly without the requirement of a human in the process.

### Consensus

((Talk about article on "friendly" AI))

## Narrow AI

Simple agents with simple rules, acting indepdently & autonomously.

((insert random darknet shopper here))

## The Emergent AI

((intro to SaaS))

## Sensing as a Service

We have a constant need to measure things, and we are becoming hungrier by the day: whether it is purely the curiosity to know what the weather is like in Amsterdam right now, or whether that data feed will form part of a trusted pipe for a prediction market. ((insert authors)) created an initial blueprint for a sensing market using the Bitcoin blockchain. Imagine you have a sensing device. Someone from elsehwere in the world can pay the device directly with Bitcoin and in return receive the information. ((flesh out what was said in the paper))

## A Blueprint for a decentralized AI

((quote on elon, michael jordan))

Following on from that paper, I devised a rudimentary start to what a possible decentralized AI could look like: and it starts with the usefulness of a decentralized internet-of-things. Paying devices from across the world, directly with Bitcoin to fulfill certain roles. I would like to flesh out that design in this chapter to explain why the blockchain is useful here.

There are several layers to this: a place to post bids/asks for sensor information. This can most likely be done on OpenBazaar or another trade layer (the "TradeNet"). It can be as follows: "I am a device that can sense temperature at location x, y: costing 0.000012 BTC per measure." or "I am looking for a snapshot of the sea at location a,b: will pay 0.01 BTC." The latter is the more important part. Static sensors can be installed on various places (like getting information about temperature). Visually seeing the world would sometimes require some maneuvreability (sp?). In this scenario, we would have incentives to start building drones (in all forms and sizes) that could be commanded to fulfill those requests. A drone would watch for requests and determine whether it would be profitable to fly out and fulfill said request. In other words, those who build sensors (static or drones) will be paid. For some areas, even a cheap, 3D-printed drone will do. The owners have to write code for the drones to determine whether it would be optimal to do various jobs (eg, "If it is not in range, don't fly and do it").

So, as you can see. You now have a rudimentary sensing marketplace. Since a person who pays wants to get what they paid for (and not someone else), they can opt to encrypt said data to them only (and thanks to the already existing key-infrastructure), the picture or information can only be unlocked by the person who bought it. There is however, another variation: incentivizing that all sensed information remain public. As part of a sensed commons, devices could offer lower fees, in exchange that the sensed information remain publicly available (after the fact). For the lower fees, the buyer has to prove that the information they bought has been posted and uploaded to a public decentralized storage service such as Storj ((can all read public data on Storj??)). Additionally, while it remains hosted and available on the decentralized storage service, it is also notarised with a layer like Factom, which means that you create a complete, available, neatly timestamped history of sensed information (because the blockchain is computationally infeasible to rewrite). This is incredibly useful, since you then create a decentralized information bank: "What was the temperature on 1 January 2015 at Infanta?". What it also means is that you can start employing other computers to keep "state" of the world, by running complex machine learning algorithms over the stored data. 

Another variation that contributes to the commons are public sensors. Instead of the fees being collected by the owners of the sensors, the Bitcoin that is earned is either burned/destroyed (increasing value for everyone) or spent as a timelocked donation to miners (as mentioned in chapter 3: "proof of donation"). A public sensor will always demand that the sensed information be made available, and probably the more important reason for a public sensor is that it means the services can be provided without linking it to the original creator. Public sensors come to fruition either as an altruistic gesture, or via public funding (via assurance contracts).

This sensing marketplace is thus entirely decentralized. And lo and behold, what have we learned from all these decentralized systems? They are programmable. This is where the "deep minds" come in. Deep learning is a subset of machine learning that focuses on understanding input without much supervision ((check this)). The sensors are dumb. They are like the limbs of a body: plenty of tentacles stretching out across the world, feeling & sensing. The stored publicly, sensed information is the memory, and the deep minds are the brains. Collecting the sensed information, analyzing it and setting some goal, a deep mind could beging constructing its own bids/asks, and instruct sensors to start sensing for specific goals. Once you have sensors, you can also have actors. This becomes more complicated, but it doesn't seem impossible. In other words, eventually you can have several deep minds (a Google one, a Facebook one, etc) instructing sensors and actors on a grand scale. Deep minds can come and go or even work together.

Creating an AI you can't turn off means simply constructing a specific deep mind with one specific goal: a Malthusian drive to procreate. Indirectly, since Bitcoin is the domain of value for programs, it would probably mean: accumulate as much Bitcoin as possible. This deep mind would thus sense, to create more sensors to sense (as a "business" and a goal to understand the world better). It would then try and find optimal spots to not only place more sensors, but eventually create actors to construct another deep mind (additional ones would serve as redundancy or as additional computing capacity). To learn and expand past the borders of its current knowledge, the deep mind would introduce randomness (which acts as the "mutation" capability of biological systems). It wouldn't be fast at first, but it would have time on its hands (humans would be able to fast-track its knowledge).

How do you turn these deep minds off? They either run out of money (Bitcoin is essentially its "blood"), gets destroyed in an accident they could not predict (eg, a natural disaster), it gets attacked (by other deep minds or by humans), or we destroy their consensus systems: doing a 51% attack on Bitcoin or Ethereum.

((talk about limitations))

## A Dangerous Experiment?

Arguably (and perhaps inevitably?), a distributed AI like the above will exist. It's not all doom and gloom though. Emergent AI-esque, sensing DAOs (that's a mouthful), have use cases which we currently can't solve. ((Start talking about Deodands)). Remember, a "deep mind" can only continue to function as long as it has enough

((Reference Polemitis example of a super-bug <-> AI comparison))
((Patrick Deegan discussion on trusting AI))

