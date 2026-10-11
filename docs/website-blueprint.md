# trivediarya.me - Website Blueprint

Planning and content strategy for Arya Trivedi's personal website.

---

## Site Identity

| Field | Value |
|---|---|
| **Domain** | trivediarya.me |
| **Purpose** | Personal brand, online portfolio, resume, blog, and tutoring advertisement |
| **Tone** | Thoughtful, articulate, warm, intellectually curious |
| **Audience** | Potential employers, readers, prospective tutoring students, journalism peers |

---

## Site Architecture

The site will be **multi-page** with Astro's file-based routing. The blog must be separate because it is a distinct content type with its own listing, individual post pages, and ongoing publishing. The home page will feature a short "latest from the blog" section to drive discovery.

### Pages

| Route | Page | Purpose |
|---|---|---|
| `/` | Home | First impression, hero, quick intro, highlights from writing and teaching |
| `/about` | About | Full personal story, bio, philosophy, values |
| `/resume` | Resume | Education, experience, achievements, skills - the online CV |
| `/blog` | Blog Index | Listing of all published posts |
| `/blog/[slug]` | Blog Post | Individual article page |
| `/tutoring` | Tutoring | Advertisement for English and Science classes, batch details, how to enrol |
| `/contact` | Contact | Contact form + direct links |

---

## Page-by-Page Content Plan

---

### Home (`/`)

**Goal:** Make a strong first impression. Establish who Arya is in a few seconds. Draw visitors deeper into the site.

#### Sections

**1. Hero**
- Headshot photo
- Headline: `Arya Trivedi`
- Sub-headline (tagline): `Writer. Journalist-in-training. English Educator.`
- One-liner intro: `I am a journalism student at IIMC, New Delhi, studying to tell stories that matter. I write on life, philosophy, and politics. I also teach English to people who want to speak with confidence.`
- CTA buttons: `Read My Writing` (links to /blog) + `English Classes` (links to /teach)

**2. Newsletter Callout**
- Highlight her LinkedIn newsletter The Cation.
- Copy: `I write daily on media, journalism, and ideas. Subscribe to The Cation on LinkedIn.`
- CTA: `Subscribe on LinkedIn` (links to newsletter URL)

**3. A Little About Me**
- A short paragraph (3-4 sentences) that establishes her intellectual voice and background.
- Link to the full `/about` page.

**4. Latest from the Blog**
- Show the 3 most recent posts (title, date, short excerpt).
- Link: `View all posts`

**5. What I Teach**
- A short card-style callout promoting the English classes.
- Key details: Spoken English, 40 min/day, 6 days a week, Rs. 4,000/month.
- CTA: `Learn More` (links to /teach)

**6. Footer**
- Name, tagline, navigation links, email, LinkedIn, newsletter link.

---

### About (`/about`)

**Goal:** Let people know the real Arya - her story, what she cares about, and what drives her.

#### Sections

**1. Page Header**
- Title: `About Me`
- Sub-title: `Journalist. Writer. Educator. Chhapra, Bihar.`

**2. My Story**
Content copy (draft):
> I am Arya Trivedi, from Chhapra, Bihar. I am currently pursuing my Post Graduate Diploma in Journalism (English) from the Indian Institute of Mass Communication, New Delhi - an institution under the Ministry of Information and Broadcasting, Government of India. Before this, I completed my B.Sc from IGNOU.
>
> I cracked the CUET PG 2026 with an All India Rank of 86 in the open category to get here. I have always been drawn to the power of language - to argue clearly, to write precisely, and to communicate with impact. That curiosity about words led me to journalism, to teaching, and to writing.

**3. What I Believe**
- A short paragraph on her worldview and what she writes about.
- Copy (draft): `I write about life, politics, and philosophy. Not to have all the answers, but to ask better questions. I believe that good writing is really just honest thinking put into words.`

**4. My Background**
- Condensed timeline of education and key experiences.

**5. When I Am Not Writing**
- Reads newspapers. Debates (District Champion). Listens to what people say and what they don't.

---

### Resume (`/resume`)

**Goal:** Serve as an online, web-first version of her CV. Printable too.

#### Sections

1. **Education**
   - IIMC, New Delhi - PGD Journalism (English), 2027
   - IGNOU - B.Sc, 2021-2024

2. **Achievements**
   - CUET PG 2026 - AIR 86 (Open Category)
   - District Champion - Debating
   - District Champion - Article Writing and Script Writing

3. **Experience** (reverse chronological)
   - WayNova Learning - Science Teacher, Part-time (Sep 2025-Present)
   - Ostello - Educator, Part-time (Jul 2026, 1 month)
   - Indian Mass Communication Ed-tech - Content Development Intern (May-Jun 2026)
   - Pledge A Smile NGO - Winter Intern / Fundraiser (Dec 2025-Jan 2026)
   - Benchmark Pvt. Ltd. - Tutor (2024)
   - The Guideline Career Institute - Teacher (Mar 2022-Mar 2023)
   - Helpage India NGO - Fundraiser

4. **Skills**
   - Leadership, Strategic Communication, Debating, Article and Script Writing, Content Development, Prompt Engineering and AI

5. **Download / Print CTA**
   - Button: `Download Resume PDF`

---

### Blog Index (`/blog`)

**Goal:** Showcase writing. Simple, clean listing of all posts.

#### Sections

1. **Page Header**
   - Title: `Writing`
   - Sub-title: `Thoughts on life, philosophy, and politics.`

2. **Post List**
   - Each post: Title, date, category tag, 1-2 line excerpt.
   - Sorted newest first.

3. **Categories / Tags** (optional, can be added later)
   - Life, Philosophy, Politics

---

### Blog Post (`/blog/[slug]`)

**Goal:** A distraction-free, readable article page.

#### Sections

1. Article title
2. Date, reading time estimate
3. Full article body (MDX/Markdown)
4. Back to Blog link
5. Author byline (short, with photo)

---

### Tutoring (`/tutoring`)

**Goal:** Present Arya as an educator who teaches both English and Science. Convert interested visitors into enrolled students.

#### Sections

**1. Page Header**
- Title: `Tutoring`
- Sub-title: `English and Science classes designed to build confidence, clarity, and real understanding.`

**2. About Your Instructor**
- Copy (draft): `I am Arya Trivedi - a journalism student at IIMC New Delhi, and an educator with 6+ years of teaching experience. I have taught students in India, New Zealand, UK, Sri Lanka, and Australia. My approach is practical: I want you to actually be able to use what you learn.`
- Key credentials: IIMC New Delhi, B.Sc IGNOU, CUET PG 2026 AIR 86, 6+ years teaching

**3. Spoken English Classes**
- Sub-heading: `Learn to think clearly, speak confidently, and communicate professionally.`
- Why this class (draft): `Most people know English but freeze when they have to speak it. This class is not about grammar rules alone. It is a daily 40-minute practice session to make you comfortable, fluent, and articulate - whether for a job interview, a presentation, or just a conversation.`
- Three-part session structure:
  - Our Reading Ritual (5-7 min) - Newspaper reading for phonics and articulation
  - The Spotlight (25-30 min) - You present, pitch, or talk. Confidence built here.
  - Net Practice - Grammar and vocabulary reinforcement
- Evaluation: The Screen Test (recorded, tracked over time), written tests, monthly tests
- Batch details: Rs. 4,000/month | 6 days a week | 40 min/session

**4. Science Classes**
- Sub-heading: `Clear concepts. Strong fundamentals.`
- Copy (draft): `I teach Science to school-level students with a focus on building genuine understanding rather than rote memorisation. Whether you are struggling with a concept or preparing for exams, we work through it together.`
- Covers: Physics, Chemistry, Biology for grades 6-10 (CBSE / ICSE / State board)
- Session structure:
  - Concept walkthrough - clear explanation of the topic from first principles
  - Worked examples - solving problems together
  - Practice - student attempts problems independently, errors corrected in real time
- Evaluation: Chapter-end tests, monthly revision tests
- Batch details: Rs. 3,500/month | 5 days a week | 45 min/session

**5. Enrol / Contact CTA**
- Copy: `Interested in a class? Reach out on WhatsApp or email and I will get back to you.`
- WhatsApp: +91 93344 88962
- Email: trivediarya558@gmail.com

---

### Contact (`/contact`)

**Goal:** Make it easy for anyone to reach Arya, whether about her writing, her classes, or professional opportunities.

#### Content

- A simple contact form (name, email, message) - UI only, no backend wired up yet
- Direct links below the form:
  - Email: trivediarya558@gmail.com
  - WhatsApp / Phone: +91 93344 88962
  - LinkedIn: https://www.linkedin.com/in/arya-trivedi-44a729199/
  - Instagram: https://www.instagram.com/trivediarya42/
  - Newsletter: The Cation on LinkedIn

---

## Branding Direction

| Element | Decision |
|---|---|
| **Name display** | "Arya Trivedi" - no nickname |
| **Tagline** | `Writer. Journalist-in-training. Educator.` |
| **Voice** | First-person, direct, intellectual without being aloof |
| **Tone** | Confident, warm, literary |
| **Key credential to feature** | IIMC New Delhi + CUET AIR 86 |
| **Secondary credential** | 6+ years teaching English and Science, international students |

---

## Technology

- **Framework:** Astro (already scaffolded)
- **Blog content:** Astro Content Collections (Markdown/MDX files in `src/content/blog/`)
- **Styling:** Vanilla CSS (per project rules)
- **Fonts:** To be decided during design phase

---

## Decisions Resolved

| Question | Decision |
|---|---|
| Light / dark mode | Light mode by default. Accent color switcher as a fun dropdown microinteraction. |
| Color palette | Professional white. Clean, minimal, nothing flashy. |
| Accent colors (5) | Slate Blue `#4A7B9D` · Forest Green `#2D6A4F` · Terracotta `#C1694F` · Dusty Rose `#C06C84` · Amber `#D4A017` |
| Headshot | Confirmed. `/public/arya-headshot.avif` already in place. |
| Tutoring page scope | Single `/tutoring` page covering both English and Science classes. |
| Science class details | Grades 6-10, CBSE/ICSE/State. Rs. 3,500/month, 5 days/week, 45 min/session. |
| Resume PDF | A "Download Resume" link pointing to the PDF file. |
| Social platforms | LinkedIn + Instagram only. No Twitter/X. |
| Contact form | Include a UI-only form (name, email, message). Backend not wired up yet. |
