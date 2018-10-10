# BioTech
## Git for BioTech Hackaton

Hello, everyone! We are the team "Smells like Team Spirit" and we want to present our view of supply chain for every marked product

Our presentation contains 3 main topics. First of all, we will tell about the problem we are going to solve. Then, we are going to speak about our solution. And, finally, we will compare our technology with simmilar popular companies projects.

### Problem

So let's start.
We asked ourselves: How can we reduce the cost of DNA-tags checking? And: What if transactions could be verified, recorded and coordinated autonomously without third parties? If this could be done, it would eliminate an entire layer of complexity from our global supply chains. So we would like to offer another solution for such problems.

as we know each DNA-sample examination is expensive, and checking of all delivery parts is impossible because of financial side. Instead of checking every product of supply we introduce next sequencing:
It is normal situation that before the raw material gets on the counter as final products it has a lot of stages in different factories. For example, T-shirts:
- Raw material supply
- Raw material processing
- Create fabric for the product
- Product tailoring

Between all we introduce smart-contracts. And to provide the information that every step was successfully passed we are logging the result of each smart-contract into Blockchain. For now, stores can easily check all information about products they sell. One the other hand, if there are any problems on any step of supplying to the store, top management can easily track at what stage the process has failed

### Solution

This is the promise Blockchain presents to the logistics
industry. Right now, this technology is still far from
maturity with many challenges to overcome before
it can be successfully deployed at scale in the logistics
industry. Likely the biggest challenge will be in achieving
successful industry adoption through collaboration
and even coopetition between diverse supply chain
stakeholders that have legacy processes and varying
interests.

But early applications of this emerging technology across
a number of industries – from finance to energy, and
manufacturing to retail – suggest blockchain has a
favorable chance of achieving its full potential in future.
When it does, this technology will facilitate greater
efficiency and new business models including faster and
leaner global trade logistics, superior transparency and
traceability in the supply chain, and increased automation
of commercial processes in logistics.

so we chose open source Etherium based Blockchain for our project, that mostly satisfied all our needs. The basic idea is pretty simple: it's a main Blockchain the consists Sub-Chains
of smart-contracts between participants of supply chain.

let's dive dipper in to the this process.
First of all we have factory who marks their product with DNA-Sample, then factory supplying further.
It's the main point of our idea. We creating time stamp smart contract about this deal then we add some
important information about product (like DNA-Sample hash) if contract was successful than we push in Blockchain. If it wasn't, Product would be send back with obvious consequences. In this way the last end-consumer, but also everyone in the supply chain, know everything about origins of a product. So we avoid unnecessary DNA-Sample verifications which is very expensive, but it is still possible.

### Another existing solutions

There are a lot of logistics companies all over the world, and some of them already use the Blockchain technology. For example, such British companies as Martin Yarlgaard and Everlegger label their products with qr-codes and enter the results of certification checks into blocks at the each stage. But what do we offer? We Offering our implementation, we are the first one who introduces DNA markers and Blockchain at the same time. Furthermore, compared to the above companies, helps to avoid code falsification better and completely trace at which stage the potential supply of raw materials failed.

### To sum up
To sum up, let's go through the key points again. We offer:
- reducing the number of information contacts and intermediaries
- we exclude the human factor
- reduction of expenses for checking DNA due to the use of methods of Blockchain technologies
- decentralized data storage
- saving the ability to check DNA
- information remains in the qr-code
- usage of time stamp contracts
