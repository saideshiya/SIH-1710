# Smart India Hackathon Workshop
# Date: 16.10.2026
## Register Number: 212224220084
## Name: SAI DESHIYA K
## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Idea :
Project Name: RailGuide AI — Smart Railway Station Navigation and Accessibility System
RailGuide AI is a multi-platform navigation system designed to help passengers locate railway station facilities and reach their destinations efficiently. It provides interactive station maps, shortest-path navigation, step-by-step directions, voice assistance, and accessibility-aware routes for people with disabilities.
The system allows passengers to search for platforms, ticket counters, restrooms, food courts, waiting halls, lifts, and enquiry counters through a mobile-friendly application or digital kiosk. An administrative dashboard enables authorised railway staff to update facility information, report temporary closures, and maintain accurate station maps.
The proposed solution aims to reduce passenger confusion, save time, improve accessibility, and enhance the overall railway station experience.


## Proposed Solution / Architecture Diagram :
Proposed Solution:
RailGuide AI consists of five main modules:
1. Passenger Interface: Mobile application and touch-screen kiosk for searching station facilities.
2. Interactive Map Module: Displays station layouts, floors, platforms, entrances, and facilities.
3. Navigation Engine: Calculates the shortest suitable route using Dijkstra's algorithm or A*.
4. Accessibility and Voice Module: Provides voice-guided directions and routes that avoid stairs when suitable accessible alternatives are available.
5. Admin and Update Module: Enables authorised railway staff to update facility locations, route closures, and lift or escalator status.

Architecture Diagram: 

<img width="2010" height="1258" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/72b62066-3129-4529-8777-dbc924f4e706" />



## Use Cases :

1. Facility Search: Passengers can locate platforms, ticket counters, restrooms, food courts, waiting halls, and other facilities.
2. Indoor Navigation: Provides step-by-step directions from the passenger's current location to the selected destination.
3. Shortest-Path Navigation: Calculates an appropriate route based on distance, estimated travel time, and available paths.
4. Accessible Navigation: Helps wheelchair users and passengers with mobility difficulties find suitable routes using verified lifts, ramps, and accessible pathways.
5. Voice Assistance: Provides spoken navigation instructions for visually impaired passengers.
6. Digital Kiosk Navigation: Allows passengers to access maps and directions through touch-screen kiosks without installing an application.
7. Real-Time Updates: Reflects verified changes such as facility closures, lift unavailability, and temporary route restrictions.
8. Administrative Management: Enables authorised railway staff to maintain station maps and facility information.
9. Multilingual Support: Provides navigation instructions in multiple languages to assist passengers from different regions.
10. Railway Service Integration: Supports future integration with authorised railway applications and information services.


## Technology Stack :
<img width="1536" height="1024" alt="Professional Technology Stack Table" src="https://github.com/user-attachments/assets/ff89efe3-f5fa-4610-8c5a-a72998c57e80" />




## Dependencies :
1.React and React DOM


2.Vite for frontend development and testing


3.FastAPI for backend API development


4.Uvicorn for running the backend server


5.PostgreSQL and a suitable Python database driver


6.Mapping library and station map data


7.Graph-routing algorithm implementation


8.Text-to-speech support for voice guidance


9.QR code library or compatible indoor-positioning infrastructure


10.Authentication and role-based access control for administrator functions


11.Internet connectivity for online updates and approved external integrations


12.Android Studio and Android SDK if developing a native Android application


13.Git and GitHub for version control and collaboration
