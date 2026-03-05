# KPPMCH Service Hub (Digital Gateway)

This platform serves as a centralized digital portal developed for Kamphaeng Phet Municipal Community Hospital. It is engineered as a "Digital Front Door" to provide the public with seamless access to medical schedules, specialized clinical services, and telemedicine integration.

---

## Strategic Value

The system was architected to modernize public healthcare accessibility, eliminating manual inquiries and streamlining the patient journey from home to hospital.

| Core Challenge | Engineering Solution | Business & Patient Impact |
| :--- | :--- | :--- |
| **Schedule Fragmentation** | Dynamic Service Rosters | Real-time visibility of General Practice and NCD clinic availability. |
| **Service Inaccessibility** | Digital Service Routing | Efficient navigation for specialized services like Physical Therapy and Vaccines. |
| **Registration Barriers** | LINE OA Integration | Automated onboarding for Telemedicine via the hospital’s official digital channel. |

---

## Key Features

* **Dynamic Medical Rosters:** Comprehensive display of morning and afternoon shifts, ensuring data accuracy for patient planning.
* **Specialized Care Navigation:** Dedicated routing for Thai Traditional Medicine, Chinese Medicine, and Antenatal Care (ANC).
* **Telemedicine Onboarding:** Seamless transition to the hospital's LINE Official Account for remote consultations.
* **Accessibility-First Design:** Optimized UI and simplified navigation paths for elderly demographics and mobile users.

---

## Technical Stack

| Component | Technology |
| :--- | :--- |
| **Frontend Framework** | Next.js (App Router) |
| **Real-time Integration** | LINE Messaging API |
| **Deployment & Infrastructure** | Vercel (Optimized for edge performance) |
| **Environment Management** | Professional-grade CI/CD Workflows |

---

## Engineering Highlights

* **High Availability:** Built for reliable public access, ensuring fast load times during peak morning registration hours.
* **Mobile-First Architecture:** Optimized for the 90%+ of users who access hospital services via smartphones.
* **Domain-Driven Design:** Structured to mirror actual hospital workflows, allowing non-technical staff to manage service updates efficiently.
* **Performance Optimization:** Leverages Server-Side Rendering (SSR) and Static Generation to ensure immediate accessibility.

---

## Development Setup

To initialize the project environment locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/ratchanon-noknoy2318/kppmch-service.git](https://github.com/ratchanon-noknoy2318/kppmch-service.git)
