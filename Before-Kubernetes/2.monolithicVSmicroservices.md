<h2>In this one we will learn about Monolithic and Microservice architecture.</h2>
<img src="https://appinventiv.com/wp-content/uploads/sites/1/2019/10/Microservices-vs-Monolithic-Architecture-Advantages-and-Disadvantages-1.png" alt ="monolithic and microservices architecture"><hr>


<h3>What's monolithic architecture?</h3>
In monolithic architecture, all the components are tightly coupled, and all the communications that happen are internal to the system, whereas, in a microservices architecture, all components are separate. So basically, you will have users sign up as a separate component, ticket booking as a separate component, and so on. Communication happens where external interfaces act as separate APIs that communicate over the network.
<hr>

<h3>Latency in monolithic architecture</h3>
So when talking about latency, there is minimal latency in a monolithic application. So even though in microservices architecture, you apply the best practices and the best parallelism, there will still be a minimal latency, more significant than the monolithic application.
<hr>

<h3>Language flexibility in monolithic architecture</h3>
Talking about language flexibility, you have to write the code in a single programming language for a monolithic application. So all of the coding pieces are written in a single programming language, whereas in microservices, you get the flexibility to code each component in a different language.
<hr>

<h3>Scaling with monolithic architecture</h3>
When we come to the scaling perspective, monolithic architecture is more difficult to scale than the microservices, not in terms of adding the number of instances but in terms of the wasted CPU resource utilization. Consider an example where you have reached the maximum limit of a monolithic application deployed on an instance. Now you create another instance, deploy the same complete monolithic application, and you are good to go. But here, the resource utilization of the second instance becomes less because of the only traffic coming in on a single component. Now in a microservices architecture, you can scale individual components. So if the ticket booking component is the one that is getting heavy load so you can scale that to two to three folds so that your application is still intact, resources are appropriately utilized, and the cost is also saved.
<hr>

<h3>Deployment with monolithic architecture</h3>
In the deployment piece, monolithic applications take more time to deploy and are not a fail-fast model. In contrast, in microservices, you can deploy individual components. You can deploy daily, even hourly, when you have minimal changes. You can deploy those changes on individual components in a light production environment. So, yes, there are companies that are doing that. Whether you have a simple application or a simple component change that you want to deploy on a live application, you can do that. In contrast, in monolithic, a small change, you have to deploy the entire stack again, making a deployment a bit harder than in microservices architecture.
<hr>

<h3>In conclusion</h3>
So overall, there are benefits for monolithic where we have extremely low latencies, higher throughputs, and microservices. Also, you will get benefits where you have complete control over each of the components, which can be containerized, running on robust ecosystems like Kubernetes. So from there, you can choose which architecture you want to apply. For most organizations and the trend in cloud-native, the microservices architecture is getting much more adoption.
<hr>


