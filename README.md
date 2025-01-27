# BMI Calculator App  

This is a **BMI (Body Mass Index) Calculator** application built using **Jetpack Compose**. The app provides a simple and intuitive interface for users to calculate their BMI by entering their weight and height. The app follows key Android development principles such as **Separation of Concerns**, **Driving UI from Data Models**, and ensuring a **Single Source of Truth**.  

---

## Features  
- **Modern UI with Jetpack Compose**: Built entirely with Jetpack Compose for a seamless, declarative UI experience.  
- **Real-Time Calculation**: Automatically updates BMI results as the user inputs values.  
- **Responsive Design**: Adapts to different screen sizes and orientations.  
- **Clean Architecture**:  
  - **Separation of Concerns**: Organized into distinct layers for UI, business logic, and data.  
  - **Drive UI from Data Models**: The UI is reactive and observes data changes directly from ViewModel.  
  - **Single Source of Truth**: All state is managed centrally using ViewModel and flows.  

---

## Tech Stack  
- **Language**: Kotlin  
- **UI**: Jetpack Compose  
- **State Management**: StateFlow and ViewModel  
- **Architecture**: MVVM (Model-View-ViewModel)  
- **Build Tool**: Gradle  

---

## App Architecture  

The app is designed with a focus on maintainability, scalability, and testability. Below are the core principles applied:  

1. **Separation of Concerns**:  
   - **UI Layer**: Contains Compose Composables and observes state from ViewModel.  
   - **Business Logic Layer**: Encapsulated in ViewModel, responsible for handling user actions and calculating BMI.  
   - **Data Layer**: Provides the single source of truth for height, weight, and BMI values.  

2. **Drive UI from Data Models**:  
   - UI elements reactively display data from models.  
   - Ensures a consistent and predictable user experience.  

3. **Single Source of Truth**:  
   - ViewModel holds and manages app state, exposing it to the UI as immutable state flows.  
   - Prevents inconsistencies and simplifies debugging.  

---

## Getting Started  

### Prerequisites  
- Android Studio Giraffe or later.  
- Kotlin 1.9+  
- Gradle 8.0+  

### Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Ariful2016/BMI-Compose.git

