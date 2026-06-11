**Product name:** SnapCal

**One-sentence idea:** A photo-based calorie and nutrition tracker built specifically for Chinese cuisine, where users snap a picture of their meal and AI instantly analyses the ingredients, calories, and macros.

**Target audience:** Chinese young adults aged 18–35 who want to maintain a healthy, balanced diet but find traditional calorie tracking too complicated, especially given the complexity of Chinese cooking with its layered sauces, spices, and mixed ingredients.

**User journey:**

1. Sign up / log in
2. Land on the Meals tab — a dated, collapsible feed of all logged meals
3. Tap the central camera button in the bottom nav
4. Take a photo of their food and optionally add a text note or description
5. AI analyses the photo and identifies ingredients, calories, and nutrition info
6. User reviews the generated summary and confirms the log
7. Meal is added to today's dated entry in the feed
8. Daily calorie and nutrition summary updates at the top of the Meals tab
9. Visit Profile tab to update personal info and settings

**Core features (Level 1 MVP):**

- Photo capture with optional text/note input
- AI-powered food recognition using GPT-4o mini (vision) — optimised for Chinese cuisine
- Nutrition data lookup via Open Food Facts database
- Calorie and macro summary per meal
- Daily calorie and nutrition summary view
- Manual food search and entry as a backup option
- Dated, collapsible meal history feed
- Three-tab bottom navigation: Meals / Camera (central) / Profile
- User profile storing: name, age, gender, height, weight, and health goal (lose/gain weight/balance nutrition)
- User authentication and data storage via Supabase

**Suggested stack:**

- Frontend: Lovable (iOS-wrapped web app)
- Auth + database: Supabase (user accounts, meal logs, photos, physical info)
- AI vision: GPT-4o mini (food photo analysis, Chinese cuisine optimised)
- Nutrition database: Open Food Facts API (free, good Chinese food coverage)

**Vibe and design notes:**

- Soft lifestyle aesthetic — warm, fresh, and approachable
- Colour palette: avocado green, creamy yellow, with orange-red accents
- Futuristic but clean — rounded cards, soft shadows, prominent visuals
- Inspired by: concise card-based layouts with clear hierarchy, central floating camera button in bottom nav (similar to references shared)
- Typography: clean and modern, generous whitespace
- Feels closer to a Chinese lifestyle app (like Keep) than a clinical Western health tracker

**Future features:**

- Level 2: streak tracking, push notifications, Apple Health integration, Chinese recipe database, nutrition intake vs. physical profile analysis
- Level 3: personalised diet plans based on user goals, social sharing, contacts/friends, community space for tips and meal inspiration
