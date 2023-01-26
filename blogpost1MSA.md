# Overview, Benefits, and Drawbacks of MSA
MSA or microservices architecture seems to me like the newest best architecture for large applications. When reading the Gartner report 
I noticed while the benefits of microservice architecture are significant, the drawbacks are worth noting as well. The Gartner report 
also notes the difference between miniservices and microservices which is a new concept for me. I think that MSA is going to be adopted 
by large companies due to scalability and continuous delivery but the learning curve for the industry will be a long laborious task. 

## Benefits of Microservices 

### Scalability:
With a MSA applications are very easily scalable. This means that regardless of any major increase or drop of users, computational demands, 
storage demands, or networking demands, the app can be easily adjusted to serve its users without overspending on resources. 

### Continuous Delivery: 
With CD applications can implement new features and change their app outside of the typical “release” schedule. This is great as it allows 
software development teams to accomplish tasks without having to look at the entire application but the learning curve and change of culture 
for software development teams is significant.

### Distributed Development and Deployments:
With MSA development teams can focus in on their specific responsibility. This overall can make the development process more efficient 
because less time is wasted making sure a change can be incorporated into a monolithic application. This distribution of technological 
elements also makes the deployment process safer. When you deploy a new feature into a monolithic application you run the risk of it 
breaking many different components. When we use MSA this risk is lessened because the deployment will only affect one microservice. 

## Drawbacks/Costs of Microservices

### Technical:
MSA is a complex architecture to implement. This can become a huge burden on development teams and can end up costing more than 
benefiting an application if it doesn’t possess the need for an MSA. The development process, technical knowledge, and application 
as a whole changes drastically when we switch from a traditional monolithic application to one with an MSA. Teams will also experience 
increased autonomy and distribution of expertise which affects workplace culture and the development process. Any software development 
team looking to switch over to an MSA will experience a huge learning curve. These drawbacks need to be evaluated by any company considering 
switching their technical architecture to an MSA. 

### Administrative:
A company looking to switch from a traditional architecture to an MSA will have to consider a few significant possible drawbacks. 
The software team autonomy can make the management process more difficult and might require expanding the devops staff. 
Switching from a traditional architecture to an MSA can also be costly. Development hours, research, and resource costs all need to 
be considered. 

## Microservices Vs Miniservices 

Many of the goal of switching to an MSA can be accomplished easier and quicker by just implementing necessary Miniservices. 
A miniservice is like a microservice but experiences more relaxed constraints. Miniservices can accomplish multiple tasks as opposed 
to microservices which strictly focus on one task. Miniservices can publish APIs and share data with other components of the architecture. 
While miniservices can accomplish many of the goals of a microservice like scalability and CD, they are not as independent as microservices 
and this can present some of the traditional issues you might run into with a monolithic application. 
