# 9. Distributed Systems

**Prerequisites**: 
- Operating Systems
- Computer Networks
- System Design Basics
**Estimated Time**: 14-16 weeks (10-15 hours/week)

## Learning Objectives

- Master distributed systems concepts
- Understand consensus algorithms
- Learn distributed storage
- Gain practical distributed systems experience

## 9.1 Distributed Computing

**Time**: 4-5 weeks

### Resources

- 📚 **Books**:
  - "Distributed Systems" by Maarten van Steen (3rd Edition, 2017)
  - "Designing Distributed Systems" by Brendan Burns (2018)
  - "Building Microservices" by Sam Newman (2nd Edition, 2021)
  - "Distributed Systems for Practitioners" by Dimos Raptis (2023)
- 🎓 **Courses**:
  - [MIT 6.824: Distributed Systems](https://pdos.csail.mit.edu/6.824/)
  - [Cloud Computing Specialization](https://www.coursera.org/specializations/cloud-computing)
  - [Distributed Systems](https://www.edx.org/course/distributed-systems)
- 💻 **Tools**:
  - [Docker](https://www.docker.com/)
  - [Kubernetes](https://kubernetes.io/)
  - [gRPC](https://grpc.io/)
  - [Apache ZooKeeper](https://zookeeper.apache.org/)
  - [Jaeger](https://www.jaegertracing.io/)
  - [Grafana Tempo](https://grafana.com/oss/tempo/)

### Supplemental Resources
- 📺 **Videos**:
  - [Distributed Systems lecture series](https://www.youtube.com/watch?v=cQP8WApzIQQ)
  - [Distributed Computing Principles](https://www.youtube.com/watch?v=Y6Ev8GIlbxc)
- 📝 **Practice**:
  - [Distributed Systems Challenges](https://github.com/aphyr/distsys-class)
  - [System Design Primer](https://github.com/donnemartin/system-design-primer)
  - [Distributed Systems Reading List](https://dancres.github.io/Pages/)

### Core Concepts

- [ ] System Models
- [ ] Communication Patterns
- [ ] Synchronization
- [ ] Fault Tolerance
- [ ] Scalability
- [ ] Consistency Models

### Projects

1. **Beginner**: RPC framework implementation
2. **Intermediate**: Distributed load balancer
3. **Advanced**: Distributed cache system

## 9.2 Consensus Algorithms

**Time**: 3-4 weeks

### Resources

- 📚 **Books**:
  - "In Search of Consensus" by Leslie Lamport (2019)
  - "Paxos Made Simple" by Leslie Lamport (2001)
  - "Raft: In Search of an Understandable Consensus Algorithm" (2014)
- 🎓 **Courses**:
  - [Consensus Algorithms](https://www.coursera.org/learn/cloud-computing-2)
  - [Byzantine Fault Tolerance](https://www.edx.org/course/blockchain-technology)
  - [Distributed Consensus](https://www.udacity.com/course/distributed-systems--ud615)
- 💻 **Tools**:
  - [etcd](https://etcd.io/)
  - [Consul](https://www.consul.io/)
  - [Raft Visualization](https://raft.github.io/)
  - [Paxos Implementation](https://github.com/paxos)

### Supplemental Resources
- 📺 **Videos**:
  - [Raft Consensus Algorithm](https://www.youtube.com/watch?v=vYp4LYbnnW8)
  - [Paxos Made Live](https://www.youtube.com/watch?v=JEpsBg0AO6o)
- 📝 **Practice**:
  - [Raft Lab](https://pdos.csail.mit.edu/6.824/labs/lab-raft.html)
  - [Consensus Implementations](https://github.com/etcd-io/etcd/tree/master/raft)
  - [Byzantine Agreement Simulator](https://github.com/byzantine-lab)

### Core Concepts

- [ ] Paxos
- [ ] Raft
- [ ] Byzantine Fault Tolerance
- [ ] Leader Election
- [ ] Quorum
- [ ] State Machine Replication

### Projects

1. **Beginner**: Simple consensus protocol
2. **Intermediate**: Raft implementation
3. **Advanced**: Byzantine fault tolerant system

## 9.3 Distributed Storage

**Time**: 3-4 weeks

### Resources

- 📚 **Books**:
  - "Designing Data-Intensive Applications" by Martin Kleppmann (2017)
  - "Database Internals" by Alex Petrov (2019)
  - "Big Data" by Nathan Marz (2015)
  - "Database Reliability Engineering" by Laine Campbell (2017)
- 🎓 **Courses**:
  - [Distributed Storage Systems](https://www.coursera.org/learn/cloud-storage)
  - [Big Data Systems](https://www.edx.org/course/big-data-systems)
  - [Storage Systems](https://www.udacity.com/course/storage-systems--ud815)
- 💻 **Tools**:
  - [Apache Cassandra](https://cassandra.apache.org/)
  - [CockroachDB](https://www.cockroachlabs.com/)
  - [MongoDB](https://www.mongodb.com/)
  - [Redis](https://redis.io/)
  - [Apache Kafka](https://kafka.apache.org/)

### Supplemental Resources
- 📺 **Videos**:
  - [Distributed Storage Design](https://www.youtube.com/watch?v=S2-5CQ6j8HM)
  - [NoSQL Database Systems](https://www.youtube.com/watch?v=xQnIN9bW0og)
- 📝 **Practice**:
  - [Distributed Database Lab](https://github.com/pingcap/talent-plan)
  - [Storage Engine Implementation](https://github.com/facebook/rocksdb)
  - [Distributed Cache Design](https://github.com/redis/redis)

### Core Concepts

- [ ] Replication
- [ ] Partitioning
- [ ] Consistency Models
- [ ] CAP Theorem
- [ ] Storage Engines
- [ ] Data Models

### Projects

1. **Beginner**: Distributed key-value store with leader election
2. **Intermediate**: Event sourcing system with CQRS
3. **Advanced**: Distributed task scheduler with fault tolerance

## 9.4 Distributed Coordination

**Time**: 2-3 weeks

### Resources

- 📚 **Books**:
  - "ZooKeeper" by Flavio Junqueira (2013)
  - "Distributed Systems for Fun and Profit" by Mikito Takada (2013)
  - "Patterns of Distributed Systems" by Martin Fowler (2020)
- 🎓 **Courses**:
  - [Distributed Coordination](https://www.coursera.org/learn/cloud-services)
  - [Service Discovery](https://www.udacity.com/course/service-discovery--ud923)
  - [Configuration Management](https://www.edx.org/course/configuration-management)
- 💻 **Tools**:
  - [Apache ZooKeeper](https://zookeeper.apache.org/)
  - [etcd](https://etcd.io/)
  - [Consul](https://www.consul.io/)
  - [Netflix Eureka](https://github.com/Netflix/eureka)

### Supplemental Resources
- 📺 **Videos**:
  - [Service Discovery Patterns](https://www.youtube.com/watch?v=GboiMJm6WlA)
  - [Coordination in Distributed Systems](https://www.youtube.com/watch?v=8RtOI7WPqEQ)
- 📝 **Practice**:
  - [ZooKeeper Recipes](https://zookeeper.apache.org/doc/current/recipes.html)
  - [Service Mesh Implementation](https://github.com/istio/istio)
  - [Configuration Management](https://github.com/etcd-io/etcd)

### Core Concepts

- [ ] Service Discovery
- [ ] Configuration Management
- [ ] Leader Election
- [ ] Distributed Locking
- [ ] Barrier Synchronization
- [ ] Event Notification

### Projects

1. **Beginner**: Service registry
2. **Intermediate**: Distributed lock manager
3. **Advanced**: Configuration management system
