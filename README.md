# 🎬 YouTube Speed Toggle

A simple Tampermonkey user script to toggle YouTube playback speed between `1x` and `2x` using the `S` key.

---

## 📖 Story: Why I Made This

I was constantly switching between watching **music** (at 1x) and **lectures, podcasts, or tutorials** (at 2x). Manually going into YouTube settings every time was **annoying and time-consuming**.

So, I built this script. Now, with a single keypress (`S`), I can instantly toggle between normal speed and double speed — **no clicking required**.

---

## ⚙️ How to Use It

Follow these simple steps to install and use the script:

---

### 🧩 Step 1: Install Tampermonkey Extension

1. Open Chrome.
2. Go to the [Tampermonkey Chrome Extension Page](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo).
3. Click on **"Add to Chrome"**.
4. Click **"Add Extension"** when prompted.

## 📷 Tampermonkey Chrome Extension Page
<img width="900" height="487" alt="image" src="https://github.com/user-attachments/assets/92526199-9d14-4d09-bb66-ceb47703f1a0" />
---

### 🔧 Step 2: Enable Developer Mode for User Scripts

After installing Tampermonkey:

1. Click the **Tampermonkey icon** in the Chrome toolbar.
2. Click **"Dashboard"**.
3. In the Dashboard, click on the **Settings (⚙️)** tab at the top.
4. Scroll down to the **"Security"** section.
5. Turn **ON** the toggle for:  
   > ✅ **"Allow user scripts to run from file URLs"**
<img width="455" height="688" alt="image" src="https://github.com/user-attachments/assets/735be6d8-f7b2-435e-946f-c9662cd8327e" />
<img width="1043" height="150" alt="image" src="https://github.com/user-attachments/assets/e199ca2b-23ed-4abd-8481-b621978e26e1" />


---

### ✍️ Step 3: Create and Add the Script

1. In the Tampermonkey Dashboard, click on the ➕ **"Create a new script"**.
<br><br>
<img width="475" height="456" alt="image" src="https://github.com/user-attachments/assets/3aa44bd9-904a-4495-bb6b-e9a10c0977ec" />

2. Delete the default code.
3. Copy and paste the code from the file [`User_Script_YT_Speed_Toggle`](./YouTube-Speed-Toggle.user.js) in this repository.

<img width="1204" height="922" alt="image" src="https://github.com/user-attachments/assets/37888d93-4a16-4b02-8387-8d8730688704" />

---

### 💾 Step 4: Save and Enable the Script

1. Click **File → Save** (or use `Ctrl + S`).
2. Make sure the script is **enabled** (the toggle next to its name should be green).
3. Open YouTube in a new tab.

📷 _Image of enabled script in dashboard_
> _Upload image and replace this line._

---

## 🧪 Step 5: Test It Out

- Open any YouTube video.
- Press the `S` key:
  - If the speed was `1x`, it becomes `2x`.
  - If the speed was `2x`, it goes back to `1x`.
- Check the console (`F12 → Console`) for a message like:
  > `Playback speed: 2`

---

