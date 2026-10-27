# Smart India Hackathon Workshop
# Date: 26/10/2026
## Register Number: 212224040012
## Name: ABISHA RANI S
## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Idea

1. RailGuide is a smart, multi-platform railway station navigation system that helps passengers locate facilities and reach their destinations within railway stations easily and efficiently.

2. The system provides interactive 2D/3D station maps, step-by-step indoor directions, QR-code-based location identification, multilingual voice guidance, and accessible route options for passengers with disabilities.

3. Passengers can use RailGuide through a mobile application or touchscreen digital kiosks installed at important station locations. The system also includes an administrator dashboard that enables authorized railway staff to update facility details, route closures, and accessibility information.

4. The proposed solution aims to reduce passenger confusion, save time, improve accessibility, and support smoother movement within railway stations.

5. Key innovation: A unified indoor navigation system combining QR-based location checkpoints, accessible route planning, voice assistance, and centrally managed station information.


## Proposed Solution / Architecture Diagram

The solution consists of the following major features:
1. Interactive station maps: Display platforms, ticket counters, restrooms, food courts, waiting halls, lifts, stairs, and exits.
2. Smart indoor navigation: Calculate routes and provide turn-by-turn instructions with estimated walking distance.
3. QR-code location identification: Let passengers scan QR codes at entrances and other mapped locations to establish their starting point.
4. Voice-guided navigation: Provide spoken directions for visually impaired passengers and support multiple languages.
5. Accessible route planning: Prioritize step-free routes and available ramps or lifts for wheelchair users and passengers with mobility difficulties.
6. Digital kiosk support: Offer touchscreen navigation for passengers who do not have the mobile application.
7. Station information updates: Allow authorized staff to update facility locations, temporarily closed paths, and lift availability.
8. Railway service integration: Support integration with authorized railway information services where APIs or data access are available.
9. 3D navigation: Offer an optional three-dimensional station view for easier understanding of complex station layouts.
For the initial prototype, navigation can work with a sample station map and simulated facility updates. Continuous indoor positioning, verified live status, and official railway integration require additional infrastructure and authorized data.

<img width="1012" height="567" alt="image" src="https://github.com/user-attachments/assets/f62f9dd0-aadb-490b-8462-550395ad9997" />


## Use Cases

The RailGuide system is designed to help passengers navigate railway stations easily and efficiently. Passengers can use the application to locate platforms, ticket counters, restrooms, food courts, waiting halls, lifts, and exits. QR-code scanning helps identify their current location and provides directions to their selected destination. The system offers voice-guided instructions for visually impaired passengers, accessible routes for wheelchair users, and multilingual support for passengers from different regions. Digital kiosks allow passengers to search for facilities using a touchscreen. Railway staff can use the administrator dashboard to update facility information, report route closures, and maintain accurate station maps. These features aim to reduce confusion, save time, and improve the overall passenger experience.
## Technology Stack

The RailGuide system uses a combination of frontend, backend, and database technologies. HTML5, CSS3, and JavaScript are used to develop a responsive user interface that works on mobile devices and digital kiosks. Leaflet.js is used to display interactive station maps and navigation routes. Java with the Spring Boot framework is used to develop the backend APIs and implement navigation logic. MySQL is used to store station layouts, facility details, route connections, and accessibility information, while MySQL Connector/J enables communication between the Java application and the database. A JavaScript QR-scanning library is used to identify mapped locations, and the Web Speech API provides voice-guided instructions in supported browsers. Git and GitHub are used for version control and team collaboration. Three.js can be added to support 3D station visualization in an advanced version of the project.


## Dependencies

The RailGuide project requires JDK 21 for Java development, Spring Boot for backend development, Maven for dependency management, and MySQL Server for storing station information. MySQL Connector/J is required to connect the Java application to the database. Leaflet.js is needed for interactive map display, and a QR-scanning library is required to identify passengers' locations through QR codes. The Web Speech API is used for spoken navigation instructions on compatible devices and browsers. The project also depends on accurate railway station maps containing platforms, entrances, corridors, stairs, ramps, lifts, and facility locations. QR-code labels must be placed at selected station locations, and a route graph must be created to calculate suitable paths between destinations. Internet or local network connectivity is required for communication with the backend and synchronization of updates. For real-world deployment, additional dependencies include authorized railway data access, verified accessibility information, digital kiosk hardware, and a secure administrator interface for maintaining station information.
