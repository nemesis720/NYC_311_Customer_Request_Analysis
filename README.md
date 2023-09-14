#Description

Background of Problem Statement:
NYC 311's mission is to provide the public with quick and easy access to all New York City government services and information while offering the best customer service. Each day, NYC311 receives thousands of requests related to several hundred types of non-emergency services, including noise complaints, plumbing issues, and illegally parked cars. These requests are received by NYC311 and forwarded to the relevant agencies such as the police, buildings, or transportation. The agency responds to the request, addresses it, and then closes it.

Problem Objective:

Perform a service request data analysis of New York City 311 calls. You will focus on the data wrangling techniques to understand the pattern in the data and also visualize the major complaint types.

Domain: Customer Service

Analysis Tasks to be performed:

(Perform a service request data analysis of New York City 311 calls) 

    1. Import a 311 NYC service request.
    2. Read or convert the columns ‘Created Date’ and Closed Date’ to datetime datatype and create a new column ‘Request_Closing_Time’ as the time elapsed between request creation and request closing. (Hint: Explore the package/module datetime)
    3. Provide major insights/patterns that you can offer in a visual format (graphs or tables); at least 4 major conclusions that you can come up with after generic data mining.
    4. Order the complaint types based on the average ‘Request_Closing_Time’, grouping them for different locations.
    5. Perform a statistical test for the following:
Please note: For the below statements you need to state the Null and Alternate and then provide a statistical test to accept or reject the Null Hypothesis along with the corresponding ‘p-value’.

    • Whether the average response time across complaint types is similar or not (overall)
    • Are the type of complaint or service requested and location related?

Dataset Description:

Description : Field
1. Unique Key (Plain text) - Unique identifier for the complaints
2. Created Date (Date and Time) - The date and time on which the complaint is raised
3. Closed Date (Date and Time)  - The date and time on which the complaint is closed
4. Agency (Plain text) - Agency code
5. Agency Name (Plain text) - Name of the agency
6. Complaint Type (Plain text) - Type of the complaint
7. Descriptor (Plain text) - Complaint type label (Heating - Heat, Traffic Signal Condition - Controller)
8. Location Type (Plain text) - Type of the location (Residential, Restaurant, Bakery, etc)
9. Incident Zip (Plain text) - Zip code for the location
10. Incident Address (Plain text) - Address of the location
11. Street Name (Plain text) - Name of the street
12. Cross Street 1 (Plain text) - Detail of cross street
13. Cross Street 2 (Plain text) - Detail of another cross street
14. Intersection Street 1 (Plain text) - Detail of intersection street if any
15. Intersection Street 2 (Plain text) - Detail of another intersection street if any
16. Address Type (Plain text) - Categorical (Address or Intersection)
17. City (Plain text) - City for the location
18. Landmark (Plain text) - Empty field
19. Facility Type (Plain text) - N/A
20. Status (Plain text) - Categorical (Closed or Pending)
21. Due Date (Date and Time) - Date and time for the pending complaints
22. Resolution Action Updated Date (Date and Time) - Date and time when the resolution was provided
23. Community Board (Plain text) - Categorical field (specifies the community board with its code)
24. Borough (Plain text) - Categorical field (specifies the community board)
25. X Coordinate (State Plane) (Number)
26. Y Coordinate (State Plane) (Number)
27. Park Facility Name (Plain text) - Unspecified
28. Park Borough (Plain text) - Categorical (Unspecified, Queens, Brooklyn etc)
29. School Name (Plain text) - Unspecified
30. School Number (Plain text)  - Unspecified
31. School Region (Plain text)  - Unspecified
32. School Code (Plain text)  - Unspecified
33. School Phone Number (Plain text)  - Unspecified
34. School Address (Plain text)  - Unspecified
35. School City (Plain text)  - Unspecified
36. School State (Plain text)  - Unspecified
37. School Zip (Plain text)  - Unspecified
38. School Not Found (Plain text)  - Empty Field
39. School or Citywide Complaint (Plain text)  - Empty Field
40. Vehicle Type (Plain text)  - Empty Field
41. Taxi Company Borough (Plain text)  - Empty Field
42. Taxi Pick Up Location (Plain text)  - Empty Field
43. Bridge Highway Name (Plain text)  - Empty Field
44. Bridge Highway Direction (Plain text)  - Empty Field
45. Road Ramp (Plain text)  - Empty Field
46. Bridge Highway Segment (Plain text)  - Empty Field
47. Garage Lot Name (Plain text)  - Empty Field 
48. Ferry Direction (Plain text)  - Empty Field
49. Ferry Terminal Name (Plain text)  - Empty Field
50. Latitude (Number) - Latitude of the location
51. Longitude (Number) - Longitude of the location
52. Location (Location) - Coordinates (Latitude, Longitude)
