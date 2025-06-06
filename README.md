# 📅 Schedulerrr

**Schedulerrr** is a powerful and time-efficient SaaS tool that makes scheduling meetings, events, and appointments effortless. Whether you're organizing your own calendar or coordinating with others, Schedulerrr streamlines your workflow by integrating seamlessly with Google Calendar and popular video conferencing platforms like Google Meet and Zoom.

---

## 🚀 Features

* ✅ **Set Your Availability**<br>
  Customize your availability so others know when you’re free to meet.

* 📆 **Create Events & Appointments**<br>
  Easily create and manage your own events with a simple, intuitive interface.

* 🤝 **Schedule Meetings with Others**<br>
  Send invites, find common available time slots, and organize group meetings.

* 🔗 **Join Meetings via Google Meet or Zoom**<br>
  Automatically generate meeting links when creating events—no extra setup needed.

* 📌 **Google Calendar Integration**<br>
  All events are automatically synced to each participant’s individual Google Calendar.

* ⚡ **Time-Efficient Scheduling**<br>
  Designed to reduce the back-and-forth and help you manage your time better.

---

## 🛠️ Tech Stack

* **Frontend:** Next.js
* **Backend:** PostgreSQL via NeoDB
* **ORM / DB Connector:** Prisma 
* **Calendar & Meeting Integration:** Google Calendar API, Zoom API, Google Meet
* **Authentication:** Google OAuth
* **UI Framework:** ShadCN

---

## 📸 Screenshots

*photo

---

## 🧑‍💻 Getting Started

1. **Clone the repo**

   ```bash
   git clone https://github.com/your-username/schedulerr.git
   cd schedulerr
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file and add your Google API and Zoom credentials.
   ```.env
    DATABASE_URL=
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=

    NEXT_PUBLIC_CLERK_SIGN_IN_URL=
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=
   ```

5. **Run the app**

   ```bash
   npm start
   ```

---

## 📅 Use Cases

* Professionals managing multiple meetings
* Freelancers booking client appointments
* Teams organizing internal calls
* Anyone tired of manual scheduling!

---

## 📃 License

MIT License. See [LICENSE](LICENSE) file for more information.

---
