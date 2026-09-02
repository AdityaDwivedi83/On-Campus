# 🎓 On-Campus

> **Meet people. Make connections. Find your vibe — exclusively on campus.**

On-Campus is a college-exclusive social and dating platform inspired by modern dating apps like Hinge, but designed specifically around **college life**.

Instead of matching with random people from across a city, On-Campus lets students discover and connect with people who actually share their **campus, interests, courses, communities, and college experience**.

---

## ✨ Why On-Campus?

Most dating apps are designed around location.

But college students already live inside a unique social ecosystem.

Your campus has:

- 🎓 Classes
- 🏠 Hostels
- 🍕 Canteens
- 🎭 Clubs & societies
- ⚽ Sports
- 🎵 Events
- 📚 Departments
- 👥 Friend groups

**On-Campus brings that ecosystem into one platform.**

The goal isn't simply to swipe through profiles.

It's to make meeting someone new feel natural in a college environment.

---

## 🚀 Features

### 🔐 College-Only Access

Users must verify that they are genuine college students before joining.

Possible verification methods:

- College email verification
- Student ID verification
- Institution-based authentication

This keeps the community **student-focused and campus-specific**.

---

### 👤 Profile-Based Matching

Create a profile with:

- Name
- Age
- College
- Course / Department
- Year
- Interests
- Hobbies
- Societies & clubs
- Music preferences
- Favorite activities
- Short prompts

Instead of relying entirely on photos, users can express their personality through prompts.

> **"My ideal Sunday is..."**

> **"The quickest way to impress me is..."**

> **"Two truths and a lie..."**

---

### 💬 Hinge-Inspired Interaction

Instead of simply liking an entire profile, users can interact with specific parts of someone's profile.

For example:

> ❤️ Like a photo  
> 💬 Comment on a prompt  
> 🎵 React to their music taste

This gives users an **actual conversation starter** rather than a generic match.

---

### 💞 Matching

When two users express mutual interest:

**It's a match. 🎉**

Users can then start a conversation.

---

### 🏫 Campus Discovery

Users can discover people based on their college environment.

Potential filters:

- Department
- Year
- Course
- Interests
- Clubs / societies
- Events
- Hostel
- Shared interests

The platform can also support **college-specific communities**.

---

### 🎉 College Events

Discover people through campus events.

For example:

- Cultural fests
- Technical fests
- Hackathons
- Sports events
- Club meetups
- Workshops
- Concerts

This creates opportunities for **real-world connections**, not just online interactions.

---

### 🛡️ Safety & Privacy

Safety is a core part of the platform.

Planned features include:

- College verification
- Report / block users
- Profile moderation
- Fake-account detection
- Age restrictions
- Privacy controls
- Community guidelines
- Secure authentication

Users should always have control over who can interact with them.

---

## 🧠 Matching Algorithm

The platform can eventually use a compatibility score based on multiple signals:

```text
Compatibility Score
        │
        ├── Shared Interests
        ├── Common Communities
        ├── Music Taste
        ├── Course / Department
        ├── Campus Activities
        ├── Profile Preferences
        └── Interaction Patterns
```

A simple initial implementation could use a weighted scoring system:

```text
Score =
    30% Shared Interests
  + 20% Common Activities
  + 15% Music Compatibility
  + 15% Preference Compatibility
  + 10% Academic Similarity
  + 10% Interaction Signals
```

The algorithm can later evolve into a machine-learning recommendation system based on user interactions.

---

# 🏗️ Tech Stack

The exact stack can evolve as the project grows.

### Frontend

- React
- JavaScript / TypeScript
- Tailwind CSS
- React Router

### Backend

- Node.js
- Express.js

### Database

- MongoDB

### Authentication

- JWT
- College email verification

### Deployment

- Vercel / Netlify — Frontend
- Render / Railway / AWS — Backend
- MongoDB Atlas — Database

---

# 📁 Project Structure

```text
On-Campus/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   ├── context/
│   │   ├── services/
│   │   └── utils/
│   │
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   └── server.js
│
├── README.md
└── package.json
```

---

# 🔄 User Flow

```text
                    ┌───────────────┐
                    │    Sign Up    │
                    └───────┬───────┘
                            │
                            ▼
                  ┌───────────────────┐
                  │ College Verify    │
                  └─────────┬─────────┘
                            │
                            ▼
                  ┌───────────────────┐
                  │ Create Profile    │
                  └─────────┬─────────┘
                            │
                            ▼
                  ┌───────────────────┐
                  │ Discover People   │
                  └─────────┬─────────┘
                            │
                     ┌──────┴──────┐
                     ▼             ▼
                  Like          Pass
                     │
                     ▼
              ┌──────────────┐
              │ Mutual Like? │
              └──────┬───────┘
                     │
                    YES
                     │
                     ▼
                💞 MATCH
                     │
                     ▼
                  💬 CHAT
```

---

# 🎯 MVP

The first version will focus on the core experience.

### Phase 1 — Authentication

- [ ] User registration
- [ ] Login
- [ ] College verification
- [ ] JWT authentication
- [ ] Password security

### Phase 2 — Profiles

- [ ] Profile creation
- [ ] Profile editing
- [ ] Photo uploads
- [ ] Interests
- [ ] College / course / year
- [ ] Profile prompts

### Phase 3 — Discovery

- [ ] Profile feed
- [ ] Like / pass
- [ ] Basic filters
- [ ] Recommendation algorithm

### Phase 4 — Matching

- [ ] Mutual matching
- [ ] Match screen
- [ ] Match notifications

### Phase 5 — Messaging

- [ ] Real-time chat
- [ ] Message notifications
- [ ] Unmatch
- [ ] Block / report

---

# 🌱 Future Features

Once the core platform works, On-Campus could evolve beyond dating.

### 🧑‍🤝‍🧑 Friends Mode

Find people who share your interests without romantic intent.

### 🎮 Interest Groups

Communities for:

- Gaming
- Music
- Coding
- Photography
- Sports
- Movies
- Books

### 📍 Campus Map

Discover people and activities around campus.

### 🎪 Event Matching

> "Who's going to the fest tonight?"

Match with people attending the same event.

### 🤖 AI Conversation Starters

Instead of:

> "Hey"

the app could suggest:

> "You both listen to Arctic Monkeys — ask them about their favorite album."

### 📊 Compatibility Insights

Give users lightweight insights such as:

> **87% Match**

> You both love football, late-night food runs and indie music.

---

# 🔒 Privacy & Safety

On-Campus is designed around a verified student community.

We aim to:

- Minimize unnecessary personal data collection
- Keep authentication credentials secure
- Provide clear reporting mechanisms
- Prevent harassment and abuse
- Give users control over their visibility
- Restrict access to verified students

---

# 🧪 Development

Clone the repository:

```bash
git clone <repository-url>

cd On-Campus
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/amazing-feature
```

3. Commit your changes

```bash
git commit -m "Add amazing feature"
```

4. Push the branch

```bash
git push origin feature/amazing-feature
```

5. Open a Pull Request

---

# ⚠️ Disclaimer

On-Campus is an independent student project and is **not affiliated with Hinge or any other dating platform**.

The project takes inspiration from existing social and dating applications while attempting to build an experience specifically tailored to college communities.

---

# 📜 License

This project is licensed under the MIT License.

---

## 💡 Vision

> **College is one of the few times in life when thousands of people with completely different stories are placed in the same environment.**
>
> On-Campus is about making it easier to discover the people you might never have met otherwise.

**Meet beyond your classroom.**
**Connect beyond your circle.**
**Find your people.**

### On-Campus 🎓
**Your campus. Your people. Your vibe.**