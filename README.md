# LifeOS: Getting Started Guide

**Everything in life, organized in one place.**

LifeOS is a personal dashboard for your tasks, money, subscriptions, habits, goals and important dates. It runs in your web browser, needs no sign-up, and keeps your information on your own device.

Open LifeOS here: **https://sayan-karak.github.io/LifeOS/**

---

## 1. Read this first: how your data is saved

LifeOS has no server and no online account. Your data is saved **inside your browser, on the device you are using**.

This is great for privacy: nobody else can see your information, and nothing is uploaded. It also means:

- Your data **does not move between devices**. A phone and a laptop each have their own separate LifeOS.
- Different browsers on the same device (for example Chrome and Firefox) are separate too.
- **Clearing your browser's site data or history can erase your LifeOS data.**
- A **private or incognito window** forgets everything when you close it.
- The web address matters. If you open LifeOS from a different address, it will start empty.

**The fix is simple: back up regularly.** See section 8. A backup file is your safety net, and it is also how you move to a new phone or computer.

---

## 2. Your first minute

1. Open the link above in any modern browser (Chrome, Edge, Safari, Firefox).
2. On the welcome screen, **create your profile**:
   - Type your **name**. LifeOS will greet you with it.
   - Optionally add a **PIN** (4 to 8 digits) to lock your profile.
   - Leave **Start with sample data** ticked if you want to explore with example tasks, bills and habits. Untick it to start with an empty workspace.
3. Click **Create**. You land on your dashboard.

You can clear the sample data at any time: **Settings → Clear all data & start fresh**.

**Tip:** on a phone, use your browser menu and choose **Add to Home Screen** to open LifeOS like an app.

---

## 3. Finding your way around

**On a computer:** the menu is on the left. **On a phone:** the menu is a bar at the bottom of the screen.

| Section | What it is for |
|---|---|
| **Dashboard** | Your day at a glance |
| **Tasks** | Things to do |
| **Money** | Income and expenses |
| **Subscriptions** | Recurring payments |
| **Goals & Habits** | Longer targets and daily routines |
| **Dates** | Birthdays, exams, appointments |
| **Reports** | Charts of your spending and progress |
| **Settings** | Personalization, backup and profile options |

### The greeting

The dashboard greets you by name and changes with the time of day: *Good morning* (5:00 to 11:59), *Good noon* (12:00 to 13:59), *Good afternoon* (14:00 to 17:59), *Good evening* (18:00 to 21:59) and *Good night* (22:00 to 4:59).

---

## 4. The dashboard

Your dashboard shows:

- This month's **income** and **expenses**
- Your **pending** and **completed** tasks
- A **weekly productivity chart** showing tasks completed over the last 7 days
- **Today's schedule**: tasks due today and any dates saved for today
- **Upcoming bills and subscriptions** with their next renewal date
- The next tasks waiting for you

The **+ Task**, **+ Transaction** and **+ Date** buttons at the top let you add things quickly from anywhere.

---

## 5. Using each section

### Tasks
- Click **+ Add task**. Give it a title, a **priority** (high, med or low) and a **due date**.
- Tick the box to mark a task as done. It moves to the **Completed** list and counts toward your weekly chart.
- Use **Edit** to change a task, or **✕** to delete it.

### Money
- Click **+ Add transaction**. Choose **in** (income) or **out** (expense), enter the amount, pick a category, add a short note and set the date.
- At the top you see this month's income, expenses, **net** (income minus expenses) and **savings rate**.
- Transactions are listed newest first. Use **Edit** or **✕** to fix mistakes.
- To change the currency symbol, go to **Settings** (section 7).

### Subscriptions
- Click **+ Add subscription**. Enter the name, cost, how often you are billed (**month, year or week**) and the **next renewal date**.
- The page shows your approximate cost **per month and per year**.
- After a renewal date passes, LifeOS moves it to the next one automatically, so you don't need to update it.

### Goals & Habits
- **Goals:** click **+ Goal**, set a **target** number and your **progress so far**. Use **Edit** to update your progress as you go and watch the bar fill.
  - Examples: save 5,000, read 12 books, run 100 km.
- **Habits:** click **+ Habit** and name it. Each habit shows the **last 7 days**. Tap a day to mark it done (tap again to undo). Your **streak** counts the consecutive days you've completed it.

### Important Dates
- Click **+ Add date**. Choose a type (Birthday, Appointment, Exam, Reminder or Other) and the date.
- Each entry shows a countdown such as *Today*, *Tomorrow* or *in 6 days*.

### Reports
Three simple charts: **spending by category** this month, **income versus expenses** for the last 6 months, and **tasks completed** over the last 7 days. They update as you add data.

---

## 6. Profiles and your PIN

LifeOS can hold **several profiles** on one device, for example one for you and one for a family member. Each profile has its own separate data.

- When the app opens, you may see **"Who's using LifeOS?"**. Choose your profile to continue.
- Use **Switch user** (in the sidebar, or in **Settings**) to change profiles.
- Add another person with **New profile**.

**About the PIN:** it keeps other people who share your device from opening your profile. It is a convenience lock, **not encryption**, so don't treat LifeOS as a vault for passwords or highly sensitive information.

**Forgot your PIN?** There is no way to reset it, because LifeOS has no online account. If you have a recent backup file, create a new profile and use **Restore backup** (section 8) to bring your data back. This is one more reason to back up regularly.

---

## 7. Make it yours (Settings)

Open **Settings** to personalize LifeOS:

- **Display name:** changes the name in your greeting.
- **Currency symbol:** use $, €, £, ₹ or any symbol of up to 3 characters.
- **Accent colour:** choose from 5 colour themes.
- **Theme:** Light or Dark.
- **Your modules:** switch off sections you don't need (for example, hide Subscriptions if you don't use it). The Dashboard and Settings always stay.
- **Set / change PIN:** add, change or remove your lock. Leave it empty to remove the PIN.

Changes apply immediately and are saved automatically.

---

## 8. Backup and restore (do this regularly)

### Make a backup
1. Go to **Settings → Export backup (JSON)**.
2. A file named like `lifeos-backup-2026-11-04.json` downloads to your device.
3. Keep it somewhere safe, such as your cloud storage or email it to yourself.

**How often?** Once a week is a good habit, and always before you clear your browser, switch phones or reinstall your system.

### Restore a backup
1. Open LifeOS in the browser or device where you want your data.
2. Create or open a profile.
3. Go to **Settings → Restore backup** and choose your `.json` file.
4. Confirm. **This replaces everything currently in that profile** with the contents of the backup.

### Export your transactions
**Settings → Export transactions (CSV)** downloads your income and expense history as a spreadsheet file that you can open in Excel or Google Sheets.

### Moving to a new phone or computer
Export a backup on the old device, send the file to the new one, open LifeOS there, and use **Restore backup**.

---

## 9. Troubleshooting

**My data disappeared.**
You may be in a private window, a different browser, or on another device, or your browser data was cleared. Check these first, then restore your latest backup.

**It says it could not save.**
Your browser's storage may be full or blocked. Allow site data for LifeOS in your browser settings, make sure you're not in private mode, and export a backup.

**The page looks blank or broken.**
Refresh the page. If it continues, try another modern browser and check your internet connection (LifeOS needs it only the first time you load the page).

**The greeting shows the wrong time of day.**
LifeOS uses your device's clock. Check that your device's time and time zone are correct.

**How do I start over?**
**Settings → Clear all data & start fresh** empties your current profile. **Delete this profile** removes the profile and all its data permanently. Both actions ask you to confirm.

---

## 10. Frequently asked questions

**Do I need an account or internet to use it?**
No account is needed. You need an internet connection to load the page the first time.

**Can the seller see my data?**
No. Your information stays in your browser and is never sent to the seller or anyone else.

**Can I use LifeOS on my phone and my laptop at the same time?**
Yes, but each device keeps its own separate data. To move data between them, use backup and restore.

**How much can I store?**
Browsers allow roughly 5 MB per website, which is far more than most people use for personal tasks and finances.

---

Thank you for choosing LifeOS. If something doesn't work as described here, contact the seller from the page where you purchased it, and mention your browser and device.
