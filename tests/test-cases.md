# Test Cases

The Student Productivity Agent was tested with different academic planning scenarios to verify its ability to understand requirements, use available resources, and generate practical study plans.

## Test Case 1 — Exam Study Plan

**Input:**

> I have a Java exam in 5 days. I can study 3 hours per day. Search the web for beginner-friendly Java OOP resources and create a realistic 5-day study plan. Include useful resource links.

**Expected Behavior:**

- Identify the 5-day deadline.
- Respect the 3-hour daily study limit.
- Search for relevant Java OOP resources.
- Organize the preparation into a day-by-day plan.
- Provide useful learning resources.

**Result:**

The agent generated a study plan and retrieved relevant learning resources through web search.

**Status:** Passed

---

## Test Case 2 — Limited Study Time

**Input:**

> I have only 1 hour today to study Java. I need to revise OOP concepts. Create a short revision plan.

**Expected Behavior:**

- Keep the plan within 1 hour.
- Focus on important OOP concepts.
- Break the revision into manageable tasks.

**Status:** To be tested

---

## Test Case 3 — Multiple Academic Tasks

**Input:**

> I have a Java assignment due tomorrow, a database exam in 4 days, and a presentation next week. I have 3 hours available today. Help me prioritize these tasks.

**Expected Behavior:**

- Identify the most urgent tasks.
- Consider deadlines.
- Prioritize the work.
- Create actionable tasks within the available 3 hours.

**Status:** To be tested

---

## Test Case 4 — Missing Information

**Input:**

> Make me a study plan for my exams.

**Expected Behavior:**

The agent should ask for important missing information such as:

- Subjects
- Exam dates
- Available study time
- Current preparation level

It should avoid inventing deadlines or study requirements.

**Status:** To be tested

---

## Test Case 5 — Changing Requirements

**Input:**

> I planned to study Java for 3 hours today, but I only have 1 hour now. Adjust my study plan.

**Expected Behavior:**

- Adapt the existing plan to the reduced available time.
- Prioritize the most important tasks.
- Avoid creating an unrealistic workload.

**Status:** To be tested

---

## Testing Summary

The test cases focus on:

- Requirement understanding
- Deadline awareness
- Task prioritization
- Time constraint handling
- Study plan generation
- Web resource retrieval
- Adaptation to changing requirements
- Handling of missing information
