# School_District_Analysis
How is the district summary affected?

The school district summary remained unchanged in regards to total schools, students, and budgets. The average math score slightly fell, by less than a point, and the average reading score rmained unchanged. The percent passing math and reading, and overall, fell by about one percentage point. 

How is the school summary affected?

The only school that was affected was Thomas High School. It's average scores were not very affected, as it ignored the NaN values, but the % passing math, reading, and overall fell substantially. 

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?

The average scores remained relatively the same, as the NaN value gets ignored in the average calculation, but it makes Thomas significantly less competitive compared to other schools. The students in other grades still did well, but the failures in the 9th grade make the percentage overall passing fall for Thomas. 

How does replacing the ninth-grade scores affect the Math and Reading Scores by Grade, Scores by School Spending, Scores by School Size, and Scores by School Type? 

Scores by grade = no other cells are affected other than the 9th grade cell for Thomas, which is NAN
Scores by spending = the 630-675 buckeet takes a hit for % passing pmath and reading, and overall, while the rest are unchanged
scores by size = the large school group took a hit for % passing, math, reading, overall
scores by district - unaffected - interesting. 
