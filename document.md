## Design 
- Client Server Architecture 
![image](https://github.com/harshit-paneri/role-based-auth/assets/82382478/dbe6c821-bdb6-4ca8-8197-64ef4a917845)

- Why did I choose Monolithic Architecture?
  - Choosing a Monolithic Architecture for role-based authentication services may be preferred for simplicity, co-location of code, better performance due to low latency, faster development, single deployment unit, optimized resource utilization, vertical scaling, small team size, technology familiarity, and initial development speed. However, it comes with limitations in scalability, flexibility, and fault isolation compared to Microservices Architecture. The choice depends on the specific project requirements and constraints.

- How to Scale it?
  - Vertical Scaling: Monoliths can be scaled vertically by adding more resources to a single server, although this has limits compared to the horizontal scaling possibilities of microservices.

- Code Structure
  - ![image](https://github.com/harshit-paneri/role-based-auth/assets/82382478/bd458bb3-bc38-4593-aab1-5f04ca158bc4)
