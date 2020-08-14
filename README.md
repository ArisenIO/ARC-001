# ARC-001
### By: Jared Rice Sr. (@jared)
Welcome to the first ARISEN Request For Comments. As you will see in the new and final dWeb whitepaper, I'll begin sending out today, we have accomplished an amazing feat. Much testing will need to be done and I'll begin mailing out some smart contract code to Shikhar over the next few weeks to test. I do believe we have created a cluster of Singleton computers (blockchains) that can process a single application in parallel. I have spent months on what I call the "Orion" protocol, which is how 2 or more Singleton computers (ARISEN blockchains) can work together in the processing of a single contract (program), that is stored on both blockchains.

This births the distributed super computer.

I studied Amdahl's law, which was created in 1967 and deals with the potential speedup of a program using multiple processors, compared to a single processor:

Speedup = T(1-f) + Tf / T (1-f) + (Tf/N) = 1 / (1-f) + f / N

Where (1-f) is the fraction of the code that is inherently sequential on a single processor, T is the total execution time of the program using a single processor and N is the speedup using a parallel processor with N processors that fully exploit the parallel portion of a program.

Simply put:

Speedup = Time to execute a program on a single processor / Time to execute a program on N parallel processors

When f is small, the use of parallel processors has little effect and as N approaches infinity, speedup is bound by 1/(1-f), so that there are diminishing returns for using more processors, although, this is not true for blockchains and multi-threaded applications. This was the basis for much of my research and I have accomplished a lot in my vision because of it. Keep in mind, I have done all of this without a computer, just as Ada Lovelace and Alan Turing were able to do in the 1800s and the early 1900s. There is something magical about it :).

In this process, we're taking "clustering" to an entirely new level and in my opinion, this is where blockchain truly begins to replace cloud computing. Just when I thought dWeb was going to be our greatest achievement, now we roll out the distributed super computer:

1. One ARISEN network is made up of at least 21 computers, yet, they do not combine their resources. Together they form what I and others call a "Singleton" computer, since all computers on the network are EXACT copies of each other, contain the same state information and act in unison with one another. In truth, this network of computers act as one single computer (hence the name "Singleton") This is a well-established fact.

2. The ability for two ARISEN networks aka Singleton computers to work together in the processing of single program, one would have to create a cluster of 2 Singleton computers, which could then combine their ability to process a given stored program in parallel.

3. Through the creation of a "cluster middleware" or simply a "Root Singleton", that stores the state of all other Singletons, we can create what is called a "unified system image" or "single-system image", ultimately unifying all Singletons and thereby eliminating the need for singleton-to-singleton proofs when attempting to achieve singleton-to-singleton interoperability, as EOS wanted to do with Light Client Validation using Merkle Proofs.

4. This will require the creation of decentralized load balancing solutions, so that an application can be load balanced across multiple Singletons, through what is called "Application scheduling", in the same way BPs agree to block scheduling, one with applications across multiple Singletons. 

5. We will have to look into something that resembles a Parallelizing compiler, which will then lead to several "parametric computing" algorithms which will then allow us to ultimately create truly decentralized and parallelized applications. 

The question I pose in the dWeb paper and ARC-001 is if a super computer can be created through the clustering of Raspberry PIs, can a distributed super computer be created through the clustering of blockchains (Singleton computers)? 

#### Conclusion:
Through the math and research I have done, the answer is an obvious yes for me. I'm convinced that by next year, machine learning will be taking place on the ARISEN distributed super computer. Don't forget that one ARISEN Singleton can process 300,000 transactions per second, which ultimately works out to be 30,000,000 smart contract based instructions (on average from simulations), in a single second. Combine 100 Singleton computers and the Root Singleton computer (unified system image) could load balance a parallelized decentralized application across 100 Singletons which could process 3 billion smart contract actions in a single second.

In Amdahl's law, we can change N to equal the number of Singletons, multiplied by the total number of processors being used by each individual Singleton. The question then is, as N approaches infinity, are there diminishing returns? I realize that software typically incurs overhead as a result of the communication and distribution of work among multiple procfessors, although it has been proven that multicore architectures are majorly effective when handling numerous, relatively independent transactions in parallel and since ARISEN supports multithreading, I have determined that my findings are indeed an effective upgrade over the current system and does in fact birth a multi-chain distributed super computer that can indeed scale with the specification and needs of any and all of the dWeb's applications. Finally, it is my conclusion that a blockchain with these capabilities solves any scaling issues we may face with the dWeb and in-turn insures t hat dWeb's network is entirely elastic. 

For this reason, ARISEN is now an acronym for "Asynchronous Real-time Interoperable State Engine".

##### NOTE: 
This is the first ARISEN request for comment (ARC) and I would be happy to hear from other developers in the community via this respository's issues section, so that we can further the conversation surrounding the advancement of this very important topic.

I also wanted to publish this in the public domain so that abusers of our industry could not patent this concept. Together, I think we can perfect this concept and bring it to life over the next few months. Much of the foundation has already been written into ARISEN's functionality, since the capability of Deterministic Parallel Computing is already a feature of the system. In the coming days, I'll release the smart contracts that brings to life on all ARISEN-based systems, so that they can soon all communicate as one. This will mark the launch of  "ORION", the second ARISEN Singleton and the first ARISEN "Satellite Singleton".
