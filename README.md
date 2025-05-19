# Day 06 (22_04_2025) Practical Sessions – Collapsible Side Menu 🎬

Welcome to Day 05 of the **IT3213 Human-Computer Interaction (HCI)** practical sessions!
In today’s session, we will focus on creating an interactive **collapsible side menu** using **Dynamic Panels** and **Slide Animations** in **Axure RP 9**. This hands-on activity enhances the user's experience by enabling gesture-based navigation for compact UI layouts.

---

## 🚀 Practical Overview

In this session, we:

* Built a collapsible side menu using **Dynamic Panels**.
* Implemented **gesture-based swipe interactions** for sliding the menu.
* Added **interactive menus** that animate in and out smoothly.
* Designed with responsive layout pinning and animation effects.

---

## ✅ Day 05 – Collapsible Side Menu Navigation 📱

### 📦 01: Dynamic Panel Setup

**Steps:**

1. **Drag a Dynamic Panel** and place it on the **left side of the screen**.
2. **Duplicate** the panel on the same side and **increase its width**.
   Rename this second panel as **"Side Menu"**.
3. **Go inside the "Side Menu" panel:**

   * Change the **background color to grey**.

### 🎨 02: Menu UI Design

**Inside the Side Menu panel:**

* Add an **icon** and **heading**.
* Create a **menu using box elements**.
* **Remove left and right borders** from the boxes to simplify the design.

### 📌 03: Pin & Hide Panel

* **Pin the "Side Menu" panel**:

  * **Horizontal**: Left
  * **Vertical**: Bottom
* **Set the panel to Hidden** by default.

---

## 🔄 04: Swipe & Slide Animations

### 👉 Swipe to Open

* Select the **first dynamic panel** (original smaller one).
* **On swipe right**, add interaction:

  * **Action**: Show "Side Menu"
  * **Animation**: Slide Right (200ms)

### 👆 Tap to Close (Menu Box Items)

* Inside the **"Side Menu"** panel:

  * Select each **menu box**.
  * **On click/tap**:

    * Hide the panel with **Slide Left animation**.

> 💡 Tip: Copy the hide interaction to all menu items for consistent behavior.

### 👈 Swipe to Close

* Select the **"Side Menu"** panel:

  * **On swipe left**:

    * **Hide** the panel
    * **Animation**: Slide Left (200ms)

---

## 📸 Outputs & Screenshots

Here’s what the final prototype looks like in action:

### 🔍 Initial State (Side Menu Hidden)

* Only the thin dynamic panel appears on the left.
* Awaits swipe interaction.

### 👉 Swipe Right (Side Menu Slides In)

* Side menu expands with a smooth 200ms animation.
* Grey background, icon, heading, and menu items appear.

### 👆 Tap Menu Item (Slide Out Left)

* Tapping any menu item slides the panel out smoothly to the left.

### 👈 Swipe Left (Hide Menu)

* Swipe gesture on the open panel triggers a slide-left hide interaction.

📸 *Screenshot*

![Screenshot](https://github.com/user-attachments/assets/df8c70e8-38f5-434c-9393-48ba6996b5c7)

---

## 📂 How to Use the Axure RP 9 File

1. Install **Axure RP 9** (if not already).
2. Download the `.rp` file from this repository.
3. Open the file and preview the **"Side Menu"** interactions.
4. Try swiping, tapping, and sliding the menu live in the Axure preview mode.

---

## 📜 License

This project is licensed under the **MIT License**.
Please refer to the [LICENSE](./LICENSE) file for more information.
