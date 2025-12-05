# 📝 Student Instructions: Resume Assignment

Welcome! These are **step-by-step instructions** to complete your resume project.  
**No coding experience required!** Go phase by phase and ask for help anytime.

---

## 🔑 Prerequisite – Create a GitHub account (if you don’t have one)

1. Go to `https://github.com` and click **Sign up**.
2. Choose a simple username you’re comfortable sharing (e.g., `firstname-lastname`).
3. Verify your email address.
4. Install GitHub Desktop: `https://desktop.github.com/` (Download and install).
5. Open GitHub Desktop and **Sign in** with your GitHub account.
6. You’ll use GitHub Desktop to clone, commit, and push—no terminal needed.

---

## 🚩 PHASE 0 – Instructor Setup (already done for you)
*You don’t need to do this! The instructor made this starter project for everyone.*

---

## ✅ PHASE 1 – Basic Info (COMPLETED)

- Open `index.html` and find the section with your name, email, and a short bio.
- **Edit only these details. Do not change any layout or style yet!**
- **Save** your changes.

---

## 🚧 PHASE 2 – Light layout and type polish (CURRENT)

**Goal:** Improve readability without changing structure.

**Tasks:**

**1. Add a two‑column layout (desktop only):**
- Add a two column layout for desktop only for Experience section using CSS only.
- On smaller screens, it should stay one column.
- Use simple CSS grid. No Javascript.

**2. Set a clear text size scale:**
- Use `rem` units for font sizes.
- Example:
    `h1` → 2rem
    `h2` → 1.25rem
    `p` → 1rem
- This makes text sizes consistent and easier to adjust later.

**3. Use the spacing tokens already in CSS:**
- Stick to the spacing values defined at the top of `styles.css` (`--space-1`, `--space-2`, etc.).
- Don’t invent random numbers like `10px` or `15px`.

- Add a wrapper grid for desktop.
- Limit line length to 65 to 75 characters.
- Ensure minimum target size 44px for links in header.

**Constraints:**

- No flexbox gymnastics. One grid or flex wrapper is enough.
- No JavaScript.

**Deliverable:** Write a clear PR titled `Layout and type polish`. Do not forget to add before and after screenshots. Always add your current resume Github Pages link while submitting PR.

---

## ▶️ PHASE 3 – Mobile first and images

**Goal:** Make it look solid on small screens.

### Tasks

- Replace your current picture/headshot with a 600x600 WebP image under 100 KB in `/img`.
- Use `<img alt="">` with meaningful alt text.
- Add a single media query at 480px for font sizing and spacing.

### Constraints

- No flexbox gymnastics. One grid or flex wrapper is enough.
- No JavaScript.

### Deliverable

Write a clear PR titled `Mobile Pass`. Include a 360x640 screenshot showing how it looks on the mobile screen. Always add your current resume Github Pages link while submitting PR.

---

## ♿ PHASE 4 – Accessibility basics

**Goal:** Make sure your resume page is usable by everyone.  

### Tasks
1. **Check heading order**
   - Use one `<h1>` for your name.  
   - Use `<h2>` for section titles (About, Skills, Experience, etc.).  
   - Use `<h3>` inside Experience for job roles.  
   - Learn online about why we need to do this as a good practice, and during raising a PR for this phase, make sure to write a brief (1 paragraph) explaining it in your own language to demonstrate that you've understood this.

3. **Make links easy to see when focused**
   - Add `:focus-visible` styles in CSS so links show a clear outline when tabbed.
   - Learn online about why we need to do this as a good practice, and during raising a PR for this phase, make sure to write a brief (1 paragraph) explaining it in your own language to demonstrate that you've understood this.

4. **Check color contrast**
   - Text should meet [WCAG AA contrast guidelines](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html).  
   - Use a free checker like [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/).
   - Learn online about why we need to do this as a good practice, and during raising a PR for this phase, make sure to write a brief (1 paragraph) explaining it in your own language to demonstrate that you've understood this.  
   - Adjust colors if needed (e.g., darker text or lighter background).

### Deliverable
- Create a clear PR titled: **“Accessibility Pass”**  
- In the PR description, list: 
  - Write a brief paragraph on why we did it for each of the tasks and how that translates into goood accessibility practice.
  - Heading structure (H1 → H2 → H3).  
  - Alt text you added.  
  - Focus-visible styles.  
  - Contrast ratios from the checker.

---

## 🔗 How to Submit (using GitHub Desktop)

1. **Fork** the main repository on GitHub (top-right ➔ Fork).
2. In **GitHub Desktop**:
    - File ➔ **Clone repository** ➔ select your fork.
    - Choose a local folder and click **Clone**.
3. Make your changes locally (e.g., edit `index.html`).
4. In **GitHub Desktop**:
    - At the bottom-left, write a short message like: `Finished Phase <number>`.
    - Click **Commit to main**.
    - Click **Push origin**.
5. **Enable and view your live resume** (GitHub Pages):
    - On GitHub: go to your repo ➔ **Settings** ➔ **Pages** ➔ set **Source** to `main` and `/ (root)`.
    - After a minute, copy the live site link shown there.
6. **Open a Pull Request** on the main class repo:
    - Go to your fork on GitHub ➔ **Pull Requests** ➔ **New Pull Request**.
    - Select your fork as the source and `main` branch.
    - **Paste your live resume link** and any phase notes.
    - Submit!

---

## Next phases will be added here as you complete the phases.

---

## 💬 Need Help?

- Don’t worry if you are lost! Ask on the class WhatsApp group or during lab hours.
- Find common questions near the bottom of this file.

---

## 📋 Checklist

- [ ] Forked repo
- [ ] Cloned to your computer
- [ ] Name, email, bio added
- [ ] Pushed changes
- [ ] Styled and added details (by phase)
- [ ] Submitted Pull Request with live link

---

## ❓ FAQ

**Q: What is a Pull Request?**  
*A: It’s how you tell the teacher “my work is ready for review!”.*

**Q: Will making mistakes break the assignment?**  
*A: No. You can always ask for help or redo parts. Don’t worry!*

---

