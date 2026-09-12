# 🌍 Where2 by Number 1
**Where2** is an AI-assisted collaborative travel planning platform designed to make planning, managing, and adapting a trip simpler for both solo and group travellers.

**Team**: JOEL CHONG XUE JIAN, LIM LI WEN, LAU ZI YEE

**Problem Statement**: Travel Planner 

**Video Presentation**: 

**Presentation Slides**: 

---

## 1.0 Project Overview

### 🚩 1.1 Problem Statement

Despite the large number of travel applications available today, travel planning remains a fragmented and time-consuming process. Travellers often need to coordinate destinations, activities, schedules, budgets, transportation, travel documents, and personal preferences across multiple platforms.

The challenge becomes even greater for group travellers, where differences in schedules, budgets, interests, travel styles, and personal preferences require significant coordination and compromise before an itinerary can be finalized.

Furthermore, unexpected situations such as poor weather, transportation delays, attraction closures, or changes in group plans can quickly make a carefully prepared itinerary ineffective, forcing travellers to manually reorganize their plans during the trip.

The main stakeholders are **solo travellers, groups of friends, and families** who need a simpler way to plan, organize, coordinate, and adapt their trips.

Existing platforms such as **Trip.com** and **Wanderlog** already provide extensive travel planning capabilities. Trip.com offers integrated booking, itinerary planning, destination information, and AI-assisted travel features, while Wanderlog provides itinerary management, group collaboration, expense tracking, and trip organization tools.

However, travellers may still face challenges when trying to reconcile different group members' preferences, budgets, schedules, and priorities into a single plan, especially when unexpected disruptions occur during the trip. This creates an opportunity for a platform that focuses more deeply on **group decision coordination and adaptive replanning**, while still bringing important planning information together in one place.

Therefore, there is a need for a unified travel platform that combines **AI-assisted itinerary planning, collaborative trip management, budgeting, travel preparation, group preference coordination, and adaptive replanning** into a more connected travel-planning experience.

---

### 💡 1.2 Our Solution

Where2 is an AI-assisted travel platform designed to bring the entire travel planning experience into one place.

Instead of forcing travellers to piece together plans across multiple apps, Where2 helps turn scattered ideas, preferences, budgets, and group decisions into one connected and manageable journey.

It gives travellers the flexibility to stay in control while using AI to reduce the time, effort, and stress involved in planning and adapting a trip.

Whether travelling solo or with others, Where2 aims to make every stage of the journey **simpler, more coordinated, and easier to adjust when plans change**.

---

### 1.3 Features

#### 🤖 Feature 1: AI-Assisted Travel Planner

The AI-Assisted Travel Planner generates personalized itineraries based on:

* Destination
* Travel dates
* Group size
* Budget
* Travel style
* Preferred pace
* Places or activities the user already wants to visit

If users already have places in mind, the AI organizes them into a practical itinerary and may recommend additional activities where appropriate.

If users are starting from scratch, the AI can generate the trip based on their travel preferences.

All generated itineraries remain editable, allowing users and their travel companions to:

* Add activities
* Remove activities
* Reorder activities
* Replace activities

The AI therefore acts as a **planning assistant rather than replacing the traveller's role in planning**.

##### Trip Preparation Dashboards

| Dashboard                 | Description                                                                                                                                                 |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🎒 **Luggage Packing**    | Generates a suggested packing checklist based on the destination, trip duration, expected weather, and planned activities.                                  |
| 💰 **Budget**             | Displays the estimated total trip budget with spending breakdowns by day and category such as accommodation, transportation, food, and activities.          |
| 🚨 **Emergency Contacts** | Provides quick access to important emergency information such as local emergency numbers, police services, and medical assistance.                          |
| 📄 **Travel Documents**   | Provides a centralized location for important travel documents such as flight tickets, boarding passes, accommodation confirmations, and booking documents. |
| 🌦️ **Weather Forecast**  | Displays expected weather conditions during the trip to help users prepare and adjust weather-sensitive activities when necessary.                          |

---

#### 👥 Feature 2: Collaborative Trip Management

For group travel, users can invite their travel companions to access the same trip and collaboratively manage a shared itinerary.

Users can view and manage:

* Past trips
* Upcoming trips
* Ongoing trips

Instead of coordinating changes across multiple group chats, notes, or planning applications, everyone can work from a **single, up-to-date itinerary**.

This combines the efficiency of AI-assisted planning with the flexibility of collaborative decision-making.

---

#### 🔄 Feature 3: Adaptive AI Replanning

Travel plans do not always go according to plan.

Unexpected situations such as:

* Poor weather
* Transportation delays
* Attraction closures
* Schedule changes
* Unavailable activities

can make parts of an itinerary impractical.

Users can inform Where2 about the disruption, and the AI will generate suitable alternatives while considering the existing itinerary, remaining time, budget, and user preferences.

Where possible, unaffected activities are preserved so travellers do not need to rebuild their entire trip manually.

---

#### ✈️ Feature 4: Trip Sharing & Travel Inspiration

Users can share their completed trips and travel experiences with other users on the platform.

Shared trips can include:

* Destinations visited
* Activities completed
* Personal recommendations
* Reviews and experiences

This allows travellers to discover destinations through real travel experiences and use them as inspiration for their own future journeys.

Completed trips therefore continue to provide value even after the journey ends.

---

## 2.0 Ideation & Process

### 2.1 Ideas We considered 
The team explored several possible features for the travel-planning application. After discussion and mentor feedback, we prioritised ideas that directly support the main travel journey, while removing or simplifying features that increased complexity without adding enough value.

| **Idea** | **Why it was dropped / kept** |
|---|---|
| **AI Trip Planning (Chosen)** | Kept because it reduces the time and effort required to manually organise destinations, routes and daily schedules. The AI can generate a complete itinerary based on the user's trip details and preferences. |
| **Destination Discovery & AI Inspiration (Chosen)** | Kept to help users discover suitable destinations, especially when they are unsure where to go. Users can search destinations or ask AI for recommendations based on their travel interests and mood. |
| **Personalised Travel Preferences (Chosen)** | Kept because different travellers have different interests, travel pace, budgets and special requirements. These preferences help the AI generate a more suitable itinerary. |
| **Must-go & Nice-to-have Places (Chosen)** | Kept because users may already have specific places they want to visit. Must-go places are prioritised, while Nice-to-have places are included when time and travel distance allow. |
| **Editable Itinerary (Chosen)** | Kept to maintain flexibility after the itinerary is generated. Users can add, delete, reorder and adjust activities based on their needs. |
| **Collaborative Group Planning (Chosen)** | Kept because group travellers may have different preferences. The app allows members to compare preferences, vote between options and make travel decisions together. |
| **Traveller Reviews & Shared Trip Plans (Chosen)** | Kept because users can gain inspiration from other travellers' experiences, discover places and view useful trip plans. |
| **Trip Readiness Tools (Chosen)** | Kept to help users prepare before travelling by checking important areas such as travel documents, packing, weather and budget. |
| **Emergency Assistance (Chosen)** | Kept because travellers may face unexpected situations during a trip. The app provides emergency contacts, nearby hospitals, embassy information and location-sharing options. |
| **Ongoing Trip Mode (Chosen)** | Kept to support users during the actual trip by showing the current schedule, activity status and directions. |
| **AI Re-planning (Chosen)** | Kept because travel plans may change due to delays, missed activities or unexpected situations. AI can rearrange the itinerary while protecting important Must-go places. |
| **Manual Planning Mode (Dropped)** | Dropped because a separate manual-planning flow would make the planning process more complicated and create additional screens. Instead, users can directly tell the AI which places they must visit, and the AI will include them when generating the itinerary. |
| **Social Media Sharing Template (Dropped)** | Dropped because the application already contains many core features. Adding an automatic social-media template generator would increase the scope and complexity of the project, while contributing less to the core travel-planning experience. |

After evaluating the ideas, the team focused on features that support the full travel journey: discovering destinations, planning the trip, collaborating with others, preparing before departure and adapting the itinerary during the trip.

### 2.2 Ideation Boards  
#### 1. Mind Map
<img width="1024" height="1280" alt="where2 problem mindmap" src="https://github.com/user-attachments/assets/dabeb7ca-b14c-4ff5-a836-7d9360722ee9" />
This mind map shows the key travel planning problems identified during our team discussions.

#### 2. Flowchart
<img width="1122" height="1402" alt="where2 flowchart" src="https://github.com/user-attachments/assets/b0871fa0-d4cd-43e6-9f5b-ae09be7a5a18" />
This flowchart shows the trip planning process and solution flow designed for Where2.

#### 3. Crazy Eights
<img width="1196" height="835" alt="image" src="https://github.com/user-attachments/assets/bd82879e-0656-4318-a6f5-014101034e50" />
The Crazy Eight exercise was used to quickly generate and compare different feature concepts. The team explored possible solutions before deciding which ideas should be developed further and which should be removed or simplified.

#### 4. Low-Fidelity User Flow

After selecting the main ideas, the team organised them into an end-to-end low-fidelity user flow covering **Explore → Plan → Collaborate → Prepare → Re-plan**. The flow shows how users move from destination discovery and AI trip creation to itinerary management, trip preparation and AI-assisted re-planning during the trip. The low-fidelity prototype also includes key flows such as destination discovery, editable itineraries, travel-group decisions, trip tools and ongoing-trip assistance. 

### 2.3 Mentor Consultation 
| **Date** | **Mentor** | **Feedback Received** | **What Was Changed** |
|---|---|---|---|
| **4 Sep 2026** | **Iris Yan** | 1. The overall UI/UX design was considered satisfactory.<br><br>2. We were encouraged to add unique features that are not commonly available in existing travel applications. | 1. We added destination reviews to help users understand whether a destination is more popular among local residents or mainly visited by tourists.<br><br>2. This helps users choose places that better match their travel preferences. |
| **10 Sep 2026** | **Teng Wei Herr** | 1. We initially prepared two project tracks, and the mentor recommended that we focus on Track 2.<br><br>2. For Track 2, we were encouraged to introduce more distinctive features. The mentor also suggested referring to Indie App for inspiration and research.<br><br>3. We were advised to prepare both a fixed prototype and a clickable demo, with Next.js suggested for developing the interactive version. | 1. We decided to focus fully on Track 2 and further develop the travel-planning application.<br><br>2. We added an Explore page to make the application more engaging. We also introduced an interactive Earth concept to improve the visual experience and make destination exploration more interesting.<br><br>3. We redesigned several application screens and started developing the clickable prototype using Next.js. |
| **10 Sep 2026** | **Lim Zi Yang** | 1. The mentor responded positively to features such as the Emergency screen and Documentation screen.<br><br>2. For the documentation, we were advised to include a direct comparison with existing travel applications to demonstrate how our application provides additional or improved features.<br><br>3. We were encouraged to conduct further research on the technical implementation and suitable technology stack. Supabase was suggested as one possible technology for backend and database development. | 1. We added a comparison between our application and existing travel applications in the documentation to clearly highlight our unique features and advantages.<br><br>2. We conducted further research on the technology stack required to develop the application.<br><br>3. We started evaluating suitable technologies, including Supabase, for database management, backend services, authentication, and future implementation of the application. |
| **12 Sep 2026** | **Daniel Koh Yu Hang** |  |  |

---
## 3.0 Design & Prototype
### UI Prototype： 

---
## 4.0 What Makes It Different 
---
## 5.0 Technical Architecture & Feasibility
---


