### Cycle Bloom Application Overview

**Purpose**

Cycle Bloom is a lightweight, client-side web application designed to track menstrual cycles, predict upcoming periods, and calculate custom date offsets for two independent user profiles (Sasi and Maha).

**Core Features**

* **Dual Profile Management:** Independent tracking and date calculations for two distinct user profiles.
* **Period Prediction & Countdowns:** Automatic estimation of the next cycle start date based on a standard 28-day cycle length, complete with status tracking.
* **Date Offset Calculator:** Computes target dates prior to or following a selected base date using user-defined day intervals.
* **Local Data Persistence:** Utilizes browser LocalStorage to retain user entries and cycle history locally without external server dependencies.
* **Historical Logging:** Stores and lists past logged cycle start dates in readable date format.

**Technical Architecture**

* Single-page application structure built using HTML, CSS, and standard JavaScript.
* Operates locally or via static web hosting services such as GitHub Pages.
