<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />

# Runaway Login 🏃‍♂️🔐

## Basic Details

### Team Name: Danger boys

### Team Members

- Team Lead: Savad Rahman - Duxford
- Member 2: Abdullha Ameen - Duxford

## Project Description

**Runaway Login** is a playful login page where the Login button refuses to stay where the user expects it to be.

When the user moves the cursor close to the Login button, the button automatically escapes to a random position. If the user finally manages to click it, the page displays a successful login message and the button stops running away.

## The Problem (that doesn't exist)

Some login pages are far too easy to use.

Users can simply enter their email, enter their password, click Login, and continue with their lives. This project solves that completely imaginary problem by making the Login button unnecessarily difficult to catch.

The fake problem:

> **"What if logging in was actually a game?"**

## The Solution (that nobody asked for)

We created a login interface where the Login button has a mind of its own.

The interaction works like this:

1. The user opens the login page.
2. The user enters an email address.
3. The user enters a password.
4. The user moves the cursor toward the Login button.
5. The button detects the approaching cursor.
6. The button escapes to a random safe position.
7. A funny warning message appears in red.
8. The user keeps trying until they successfully click the button.
9. The success message appears in green.
10. The button stops moving.

It is a completely unnecessary login experience, which is precisely the point.

## Technical Details

### Technologies/Components Used

For Software:

- **HTML5** - Page structure and form
- **CSS3** - Responsive design, gradients, animations, and styling
- **JavaScript** - Button movement, cursor detection, login interaction, and messages
- **Modern Web Browser** - Chrome, Edge, Firefox, or Safari
- **VS Code** - Development and editing

For Hardware:

- Any laptop or desktop computer
- Keyboard and mouse/touchpad
- Smartphone or tablet for responsive testing
- No special hardware is required

## Implementation

### Main Features

- Modern dark login interface
- Responsive design
- Email input
- Password input
- Show/hide password button
- Runaway Login button
- Cursor proximity detection
- Random button movement
- Smooth GPU-friendly movement using `transform`
- Mouse event throttling to reduce lag
- Touch support for mobile devices
- Random funny warning messages
- Red warning messages while the button escapes
- Green success message after login
- Button stops moving after successful login
- No backend or database required

### Runaway Logic

The Login button checks the distance between the cursor and the button.

```text
Cursor approaches button
        ↓
Distance becomes smaller
        ↓
Danger zone detected
        ↓
Button moves
        ↓
Random position selected
        ↓
Red funny message appears
```

The movement is throttled so the button does not react to every single mouse event. This keeps the animation smooth instead of turning the browser into a small space heater.

### Success Logic

```text
User clicks Login
       ↓
Prevent normal form submission
       ↓
Set loginSuccess = true
       ↓
Stop button movement
       ↓
Remove warning style
       ↓
Add success style
       ↓
Show green success message
```

## Project Documentation

### User Flow

```text
Open Website
      ↓
Login Page
      ↓
Enter Email
      ↓
Enter Password
      ↓
Move Cursor Toward Login
      ↓
Button Escapes
      ↓
Red Funny Message
      ↓
Try Again
      ↓
Button Escapes Again
      ↓
Successfully Click Login
      ↓
Green Success Message
      ↓
Button Stops
```

### Interface Structure

```text
Runaway Login
│
├── Login Card
│   ├── Lock Logo
│   ├── Welcome Heading
│   ├── Description
│   │
│   ├── Email Field
│   │
│   ├── Password Field
│   │   └── Show / Hide Password
│   │
│   ├── Runaway Login Button
│   │
│   └── Status Message
│
└── Interaction
    ├── Cursor Detection
    ├── Random Movement
    ├── Warning Messages
    └── Success State
```

# Screenshots

### 1. Login Page

![Screenshot1](https://github.com/aminemp62-netizen/useless-login-btn/blob/main/Screenshot%202026-09-12%20053914.png)

_The initial Runaway Login interface with email and password fields._

### 2. Runaway Button

![Screenshot2](https://github.com/aminemp62-netizen/useless-login-btn/blob/main/Screenshot%202026-09-12%20053929.png)

_The Login button moves away when the cursor gets too close, while a funny warning message appears in red._

---

## Why This Project Is Useless

Normal login:

```text
Enter password → Click Login → Done
```

Runaway Login:

```text
Enter password
      ↓
Find button
      ↓
Button runs
      ↓
Chase button
      ↓
Button runs again
      ↓
Question your life choices
      ↓
Finally click Login
      ↓
Success 🎉
```

No productivity was improved.

No major problem was solved.

But the Login button had an excellent workout.

---

Made with ❤️ at TinkerHub Useless Projects

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)
