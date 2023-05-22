# Parking Lot System Design

Hello everyone, in this project, we will be designing a parking lot object oriented system in Java.

## Problem Statement

1. Parking lot is an open area designated for parking cars.  

2. We will design a parking lot where a certain number of cars can be parked for a certain amount of time.  

3. The parking lot can have multiple slots. Each slot can have a single vehicle parked in it.

## System Requirements

1. The parking lot should have multiple slots where customers can park their vehicles.  

2. The system should not allow more vehicles than the maximum capacity. If the parking is full, the system should be able to show a message.  

3. It will have many parking spots. The system should support multiple types of parking spots such as Compact, Large, Motorcycle, etc.

## Classes

1. ParkingLot: The central part of the organization for which this software has been designed.  

2. ParkingSpot: Lot will have many parking spots. Our system will support different parking spots  
* Compact  
* Large  
* Motorcycle  
    
Vehicle: Vehicles will be parked in the parking spots. Our system will support different types of vehicles  
* Car,  
* Truck,  
* Motorcycle.