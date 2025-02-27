Uber-Like App using Spring Boot and PostGIS

Overview

This is a backend service for an Uber-like ride-hailing application built with Spring Boot and PostGIS for geospatial data processing. The system enables real-time location tracking, ride matching, and route optimization.

Features

User Management: Riders and drivers can register, log in, and manage their profiles.

Geospatial Queries: Efficiently find nearby drivers using PostGIS spatial queries.

Ride Request & Matching: Riders can request rides, and drivers can accept or decline.

Live Location Updates: Store and update driver and rider locations in real time.

Trip Management: Track the status of ongoing and completed trips.

Payment Integration: Basic ride fare calculation (extendable to third-party payment gateways).

Tech Stack

Backend: Spring Boot (Spring MVC, Spring Data JPA, Spring Security)

Database: PostgreSQL with PostGIS extension

ORM: Hibernate Spatial

API Documentation: Swagger/OpenAPI

Build Tool: Maven

Setup Instructions

Prerequisites

Ensure you have the following installed:

Java 17+

PostgreSQL with PostGIS extension

Maven
