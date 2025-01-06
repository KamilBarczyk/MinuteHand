# MinuteHand

**MinuteHand** is a sleek and interactive timer application built with **Angular**. It allows users to set a timer for hours, minutes, and seconds, with intuitive controls for starting, stopping, resetting, and triggering an alarm when the timer ends.

---

## Features

- **Customizable Timer**:  
  Set precise durations with separate controls for hours, minutes, and seconds.
- **Interactive Controls**:  
  Start, stop, or reset the timer with responsive buttons.
- **Alarm Notification**:  
  Triggers an alarm sound when the timer reaches zero.
- **Error Handling**:  
  Prevents setting invalid values or running timers with zero duration.

---

## Technologies Used

- **Angular**:  
  Component-based framework for building scalable web applications.
- **TypeScript**:  
  Provides robust typing and clean syntax for application logic.
- **SCSS**:  
  Enables modular and reusable styles with a responsive layout.
- **HTML5 Audio**:  
  Alarm functionality using the `<audio>` element.

---

## Screenshots

**Timer Setup**  
The main interface for setting hours, minutes, and seconds, with action buttons for interaction.  
![MinuteHand](./src/assets/screen/MinuteHand.png)

---

## Getting Started

### Prerequisites

Ensure you have **Node.js** and **Angular CLI** installed. You can install Angular CLI globally using the following command:

```bash
npm install -g @angular/cli
```

### Installation and Local Development
1. **Clone the repository**:
   ```bash
   git clone https://github.com/KamilBarczyk/MinuteHand.git
   ```

2. **Navigate to the project folder:**
   ```bash
   cd MinuteHand
   ```

3. **Instal dependencies:**
   ```bash
   npm install
   ```

4. **Run the project:**
   ```bash
   ng serve
   ```
   
The app will be available at http://localhost:4200.