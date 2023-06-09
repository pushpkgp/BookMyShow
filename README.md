# Problem Statement
Design a movie booking system similar to BookMyShow.

## Requirements
### Functional Requirements
* Booking system should list down different cities where its affiliate cinemas are located.
* On selecting city, the system should display the movies released in that city.
* On selcting movie, the system should display the list of multiplexes along with show time and other details.
* On selecting a show time from the multiplex card, the system should display seating layout for booking the tickets.

### Non Functional Requirements
#### Highly Available & Fault Tolerant
Redundancy by replication
* System should be fault tolerant to network failure.
* System should be available all the time.

#### High Throughput & Low Latency
* System should be able to handle multiple concurrent views and bookings with low latency

#### Scalable

#### Authentication & Authorization
* User authentication and autoerization should be delegated to different server.

## Design Considerations

## Capacity Estimation
### Traffic Estimation
### Storage Estimation

## High Level System Design
### Design Diagram

### Components
#### Functional Components
* Search Service - In-Scope
* Booking Service - In-Scope
* Review Service - Out-of-Scope
* User Details Service - Out-of-Scope
* Authentication Service - Out-of-Scope
* Autherization Service - Out-of-Scope

#### Non Functional Components
* Load Balancer
* Service Registry & Discovery
* Circuit Breaker
* Health
* Logstash
* Cache

## Low Level System Design
### System APIs
#### Search Service
* Search

#### Booking Service
* Booking

### System Entities
![BookMyShow](https://user-images.githubusercontent.com/33038109/230956141-2a77bf91-e266-4f5c-a195-c81aeafb3cc2.png)

### System Flows
