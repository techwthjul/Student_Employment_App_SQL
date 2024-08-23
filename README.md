# 🎓 Finite U Job Search - SQL Project

Welcome to the **Finite U Job Search** project! This is a SQL-based application designed to solve a real-world problem faced by international students looking for on-campus jobs. Let's dive into what this project is all about, the technologies used, and the concepts covered!

## 📝 Introduction

When I first arrived at university as an international student, I noticed a common issue: some students ended up with multiple on-campus jobs, while others couldn't secure even one. This project aims to address that problem by prioritizing job allocations to students who don't yet have a job, ensuring a fairer distribution of opportunities.

## 🚀 Use Case

Imagine a scenario where the university's job portal gives priority to students who are still looking for their first job, rather than allowing one student to hold multiple positions. This SQL-based solution makes that possible by:

- **Preventing job hoarding:** Ensuring students with no jobs get priority.
- **Fair opportunity distribution:** Making sure everyone has a chance to get an on-campus job.
- **Simplified job matching:** Automating the matching process using SQL stored procedures and views.

## 🛠️ Technologies Used

- **SQL Server:** The core database where all the logic is implemented.
- **PowerApps & Power Automate:** Integrated with the SQL logic to provide a user-friendly interface for students and employers.
- **GitHub:** To track and share the progress of this project.

## 📚 Concepts Covered

1. **Views:**
   - `v_student_info`, `v_open_position_info`, etc.
   - Used to aggregate and organize data for easy access and processing.

2. **Stored Procedures:**
   - `sp_student_info_by_id`, `sp_student_match_by_position_id`, etc.
   - Automate the job matching process and manage student profiles.

3. **Common Table Expressions (CTEs):**
   - Examples: `fws_award_students_cte1`, `academic_year_percent_past_cte2`
   - Purpose: Break down complex queries into manageable parts.

4. **Window Functions:**
   - Examples: `COUNT(...) OVER (PARTITION BY ...)`, `DENSE_RANK() OVER (ORDER BY ...)`
   - Purpose: Rank students, calculate skill match percentages, and aggregate data.

5. **Error Handling in Stored Procedures:**
   - Examples: `p_remove_skill`, `p_insert_student_skill`
   - Purpose: Manage errors gracefully with `BEGIN TRY...END TRY` and `BEGIN CATCH...END CATCH`.

6. **Transaction Control:**
   - Examples: `BEGIN TRY...COMMIT...END TRY`, `BEGIN CATCH...ROLLBACK`
   - Purpose: Ensure data integrity by treating operations as a single unit of work.

7. **Conditional Logic:**
   - Examples: `CASE` statements, `IF EXISTS`
   - Purpose: Handle different scenarios and execute SQL statements based on conditions.

## 👤 Contribution

This project was created by **Rijul Ugawekar** with the goal of making on-campus job opportunities more accessible and fair for all students. If you're interested in contributing or have any suggestions, feel free to reach out!

## 🔗 Project Link

Check out the full project on GitHub: [Finite U Job Search - SQL Project](https://apps.powerapps.com/play/e/default-4278a402-1a9e-4eb9-8414-ffb55a5fcf1e/a/512ff569-154a-47af-abdb-c92141fc7b92?tenantId=4278a402-1a9e-4eb9-8414-ffb55a5fcf1e&source=AppSharedV3&hint=50d47059-1022-4afc-904f-6cfe72b417ed&sourcetime=1701466254899)

---

Thank you for exploring the **Finite U Job Search** project! Let's make job hunting easier and fairer for everyone. 🚀
