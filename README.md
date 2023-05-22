# Parking Lot System Design

Hello everyone, in this project, we will be designing a parking lot object oriented system in Java.

## Problem Statement

Parking lot is an open area designated for parking cars.  

We will design a parking lot where a certain number of cars can be parked for a certain amount of time.  

The parking lot can have multiple slots. Each slot can have a single vehicle parked in it.

## System Requirements

The parking lot should have multiple slots where customers can park their vehicles.  

The system should not allow more vehicles than the maximum capacity. If the parking is full, the system should be able to show a message.  

It will have many parking spots. The system should support multiple types of parking spots such as Compact, Large, Motorcycle, etc.

## Classes

ParkingLot: The central part of the organization for which this software has been designed.  

ParkingSpot: Lot will have many parking spots. Our system will support different parking spots  
    o Compact  
    o Large  
    o Motorcycle  
    
Vehicle: Vehicles will be parked in the parking spots. Our system will support different types of vehicles  
    o Car,  
    o Truck,  
    o Motorcycle.