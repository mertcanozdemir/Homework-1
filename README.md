# BMM411 - Biomedical Image Processing
## Week 3 Assignment: Pixel Operations and Image Enhancement

> **This is a GitHub Classroom template repository**

This repository contains the Week 3 assignment for BMM411 Biomedical Image Processing course.

---

## For Students: Getting Started

### Step 1: Accept the Assignment
1. Click the GitHub Classroom assignment link provided by your instructor
2. If prompted, link your GitHub account to your student ID
3. A private repository will be **automatically created** for you

### Step 2: Clone Your Repository
```bash
git clone <your-repository-url>
cd BMM411-Week3-YourUsername
```

### Step 3: Work on the Assignment
1. Open `Week3_Assignment.ipynb` in Jupyter Notebook
2. Fill in your student information at the top
3. Complete all parts of the assignment
4. Commit your progress regularly (minimum 5 commits required)

### Step 4: Submit Your Work
```bash
git add .
git commit -m "Your descriptive commit message"
git push
```

---

## For Instructors: Setting Up GitHub Classroom

### Prerequisites
- GitHub organization (create one if you don't have)
- GitHub Classroom account linked to your organization

### Step 1: Create Template Repository

**IMPORTANT:** The starter code repository **must be a template** so that a copy can be made in your organization.

1. Push this repository to your GitHub organization
2. Go to repository **Settings** > **General**
3. Scroll to **Template repository** section
4. Check the box ✅ **Template repository**
5. Save changes

### Step 2: Create Assignment in GitHub Classroom

1. Go to [GitHub Classroom](https://classroom.github.com)
2. Select your classroom or create a new one
3. Click **New Assignment**
4. Configure the assignment:
   - **Title:** BMM411 Week 3 - Pixel Operations
   - **Deadline:** Set your deadline
   - **Repository visibility:** Private (recommended)
   - **Add starter code:** Select this template repository
   - GitHub Classroom will create a **copy** in your organization
5. Enable GitHub Actions (optional, for auto-grading)
6. Click **Create assignment**
7. Share the invitation link with students

### Step 3: How Starter Code Works

When you add starter code:
- GitHub Classroom creates a **copy** of your template in your organization
- Student repositories become **forks** of this organizational copy
- Students cannot see each other's repositories (private repos)

**Without starter code:** Student repositories will be created empty.

### Step 4: Updating Starter Code (Sync Assignments)

If you need to fix bugs or update the assignment after students accept:

1. Go to the assignment dashboard in GitHub Classroom
2. Make changes to the **organizational copy** (not the original template)
3. Click **"Sync assignments"** button
4. GitHub will open **Pull Requests** in all student repositories
5. Students can review and merge the updates

**Example use cases:**
- Fix typos in instructions
- Add clarifications to questions
- Update test cases
- Provide additional helper functions

---

## Topics Covered

- Brightness and Contrast Adjustment
- Gamma Correction
- Histogram Equalization
- Thresholding and Segmentation
- Bit-Plane Analysis

## Requirements

- Python 3.8+
- NumPy
- Matplotlib
- SciPy

## Installation

```bash
pip install numpy matplotlib scipy
```

## File Structure

```
.
├── README.md
├── .gitignore
└── Week3_Assignment.ipynb
```


## Commit Guidelines

This assignment requires **minimum 5 commits** with descriptive messages. Example:

```bash
git add .
git commit -m "Implement brightness_contrast function"
git push
```

Good commit message examples:
- `Add brightness contrast function - initial implementation`
- `Fix overflow issue in gamma correction`
- `Complete histogram equalization with comments`
- `Add analysis for threshold selection`
- `Final cleanup and documentation`

## Grading

| Component | Points |
|-----------|--------|
| Part 1: Theory | 20 |
| Part 2: Brightness/Contrast | 15 |
| Part 3: Gamma Correction | 15 |
| Part 4: Histogram Equalization | 20 |
| Part 5: Thresholding | 15 |
| Part 6: Bit-Plane | 15 |
| Bonus | +10 |

## Student Information

> Fill in your information below after accepting the assignment

| Field | Value |
|-------|-------|
| **Student Name** | ___________________ |
| **Student ID** | ___________________ |
| **GitHub Username** | ___________________ |
| **Submission Date** | ___________________ |

## Penalties

| Violation | Penalty |
|-----------|---------|
| Less than 5 commits | -20 points |
| All commits in last hour | -15 points |
| Missing comments | -10 points |
| Cannot explain code | -50 points |

## License

This project is for educational purposes only - BMM411 Biomedical Image Processing Course.
