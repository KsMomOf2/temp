### Comparison of DE_DS_AA_Context (4).md with CourseScheduleTables_2025-2026 (1).md

The CourseScheduleTables_2025-2026 (1).md document serves as the standard reference, as specified. Below is a systematic comparison focusing on key elements: assignment names, points, due dates, quarter boundaries, and totals. Conflicts are highlighted where the context file deviates from the course tables. Minor inconsistencies (e.g., skipped numbering in the context file's assignment list) are noted but do not constitute functional conflicts unless they affect points or dates.

#### 1. Quarter Boundaries
Both documents align fully:
| Quarter | Start Date    | End Date      |
|---------|---------------|---------------|
| Q1      | 2025-09-02   | 2025-10-24   |
| Q2      | 2025-10-27   | 2026-01-16   |
| Q3      | 2026-01-19   | 2026-03-20   |
| Q4      | 2026-03-23   | 2026-06-02   |

**Conflicts:** None.

#### 2. Assignment Points and Percentages
The course tables list assignments under a "Grading Structure" category breakdown (Homework, Projects, Exams). Quizzes are referenced in a separate table but not explicitly included in the Grading Structure points (implying they contribute to quarter totals). The context file includes quizzes as line items in Section 5.

- **Overall Total Points:** Course tables sum to 2,040 (760 Homework + 400 Projects + 840 Exams), excluding quizzes. Context file sums to 2,000 (including 60 quiz points). **Conflict:** Course tables exceed the standard total by 40 points; quizzes should be integrated to reach exactly 2,000.
- **Quarter Totals (Context Section 6 vs. Course Tables, calculated from due dates in Q1 period):**
  | Quarter | Context Total | Course Tables (Calculated) | Notes |
  |---------|---------------|----------------------------|-------|
  | Q1      | 230           | 200                        | **Conflict:** Discrepancy of 30 points. Course Q1 includes 11 assignments (Java Class Hierarchy to Recursion Optimization); sum is 200. Suggests context overcounts (e.g., including pre-Q1 Hello World Program). |
  | Q2      | 720           | 720 (excluding quizzes; 750 with Fall Quiz) | Minor: Aligns if Fall Quiz (30 points, due 11/05/2025) is Q2-specific. |
  | Q3      | 310           | 310                        | Aligns. |
  | Q4      | 740           | 740                        | Aligns. |
  | **Total** | **2,000**   | **2,040** (adjusted to 2,000 with quizzes) | **Conflict:** As noted above. |

- **Individual Assignments:** Most align (names, points, percentages). Key conflicts:
  | Assignment (Course Tables)              | Points (%) | Context Equivalent                  | Conflict Details |
  |-----------------------------------------|------------|-------------------------------------|------------------|
  | Transit Graph Traversal                 | 20 (1.00) | None (combined into "Transit Graph Engine") | **Conflict:** Context combines with "Route Graph" into single 40-point (2.00%) assignment. Course treats as separate 20-point items. |
  | Route Graph                             | 20 (1.00) | None (combined as above)            | As above. |
  | Quiz – Fall Topics                      | 30 (1.50, implied) | Matches (Q1 line item)             | Minor: Course lists in separate Quizzes table without points; context integrates. |
  | Quiz – Spring Topics                    | 30 (1.50, implied) | Matches (Q2 line item)             | As above. |
  | All others (e.g., Hello World Program)  | Align     | Align                               | No conflicts. |

**Recommendation for Conformance:** Update context Section 5 to split "Transit Graph Engine" into two 20-point assignments matching course names. Adjust Q1 total to 200 and redistribute the 30-point discrepancy (e.g., explicitly include Hello World in Q1).

#### 3. Assignment Due Dates
Due dates are extracted from the course tables' "Assignments" table. Most align, but:
| Assignment                     | Course Due Date | Context Due Date | Conflict? |
|--------------------------------|-----------------|------------------|-----------|
| Quick Sort Optimization        | 2025-10-28     | 2025-10-30      | **Yes:** Two-day shift. Align to 10/28. |
| All others (e.g., Stop BST)    | Align          | Align            | No. |

**Recommendation for Conformance:** Correct Quick Sort Optimization due date in context Section 5.

#### 4. Other Elements (Class Meetings, Topics)
- Class meeting dates in context Section 2 partially overlap with course "Student Schedule" table but include additional details (e.g., lengths, notes). No direct conflicts, but context has more entries (e.g., 2025-08-25 orientation, absent in course).
- Topics/ZyBooks chapters align across both (e.g., Sorting Algorithms on 2025-09-11, Chapter 5).

**Overall Conformance Status:** Minor conflicts in points/totals and one due date; context largely conforms but requires updates for graph assignments and Q1 total.

### Comparison of Grading.csv with CourseScheduleTables_2025-2026 (1).md

The Grading.csv tracks student scores alongside assignment details. It serves as a gradebook, not a syllabus, but discrepancies arise in assignment names, points, and combinations relative to the course tables (standard). Only completed/partial entries (up to Q2) are analyzed; future quarters (Q3/Q4) align nominally.

#### 1. Quarter Totals
| Quarter/Semester | CSV Total | Course Tables (Calculated) | Notes |
|------------------|-----------|----------------------------|-------|
| Q1 Subtotal      | 130       | 200                        | **Discrepancy:** CSV undercounts by 70 points due to combinations/omissions (detailed below). |
| Q2 Subtotal (% of 720) | 720 (implied) | 720                   | Aligns (includes Midterm Exam, project). |
| Semester 1 Total | 850       | 850 (Q1 200 + Q2 650? Adjusted) | Minor: Aligns if Q1 adjusted; CSV uses compressed Q1. |
| Q3 Subtotal (% of 310) | 310 (implied) | 310                   | Aligns. |
| Q4 Subtotal (% of 740) | 740 (implied) | 740                   | Aligns. |
| Semester 2 Total | 1,150     | 1,050 (adjusted for total 2,000) | **Discrepancy:** CSV assumes 2,000 total but Q1 compression affects upstream. |
| Final Grade Total | 2,000    | 2,000                      | Aligns nominally. |

#### 2. Individual Assignment Discrepancies
CSV lists 28 assignments (including subtotals). Key issues: Several course assignments are omitted, combined, or renamed with altered points/dates. No scores affect analysis (focus on structure).

| CSV Assignment                        | CSV Points | CSV Due Date | Course Equivalent(s)                  | Discrepancy Details |
|---------------------------------------|------------|--------------|---------------------------------------|---------------------|
| Stop Object                           | 10         | 2025-09-17  | None (possible proxy for Algorithm Optimization) | **Omission/Extra:** Not in course; duplicates Stop Sorter slot. Course has Algorithm Optimization (10 pts, 2025-09-11) omitted entirely. |
| Stop Sorter                           | 20         | 2025-09-19  | Stop Sorter (20 pts, 2025-09-17)     | **Date Shift:** One day late. |
| Sort Optimization                     | 20         | 2025-09-24  | Sorting Optimization (20 pts, 2025-09-19) | **Date Shift:** Five days late; name simplified. |
| Route Linked List & Optimization      | 40         | 2025-09-25  | Route Linked List (20 pts, 2025-09-25) + Linked List Optimization (20 pts, 2025-09-30) | **Combination:** Doubled points; omits separate due date for optimization. |
| Delivery Route Planner and Optimizer  | 40         | 2025-10-06  | Delivery Stack/Queue (20 pts, 2025-10-06) | **Name/Points Change:** Altered name; doubled points (no matching optimizer). |
| Recursive Route Explorer & Optimization | 40       | 2025-10-15  | Recursive Route Explorer (20 pts, 2025-10-15) + Recursion Optimization (20 pts, 2025-10-20) | **Combination:** Doubled points; compresses two assignments. |
| Quiz (Fall Topics)                    | 30         | 2025-11-05  | Matches (30 pts, implied)            | Aligns. |
| Transit Graph Traversal               | 20         | 2025-11-18  | Matches                              | Aligns. |
| Route Graph                           | 20         | 2025-11-18  | Matches                              | Aligns. |
| All Q3/Q4 (e.g., AVL Route Query Tree)| Align     | Align        | Matches                              | No discrepancies. |
| Midterm Exam, First Semester Project, etc. | Align | Align        | Matches                              | Aligns. |

**Summary of CSV Discrepancies:**
- **Combinations:** 4 instances (Route Linked List, Delivery, Recursive, potentially Stop Sorter/Sort Optimization), inflating points and compressing timeline—explains Q1 undercount (130 vs. 200).
- **Omissions:** Algorithm Optimization (10 pts) missing; replaced by non-standard "Stop Object."
- **Name/Date Variations:** 3 minor shifts (e.g., Sorting Optimization due date).
- **Quarter Impact:** Q1 heavily affected; Q2 partially (combinations offset by inclusions like quizzes/exams).

**Recommendation:** Realign CSV to course standards by splitting combined entries, adding omitted assignments (e.g., Algorithm Optimization), and correcting dates/names. Recalculate Q1 subtotal to 200 for accuracy. This ensures the gradebook reflects the syllabus without inflating early scores. If combinations are intentional (e.g., for administrative reasons), document as overrides in CSV notes.
