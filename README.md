# School_District_Analysis
## Overview of the School District Analysis
The purpose of this project was to analyse the data of a School District, with the data about the schools and the students that go there. The school data contained the type, size, and budget of the school. The student data contained the gender, grade, school name, and reading and math scores. With this data we find missing information and fix it so that we can create data frames to visualize the data for the School District.
## Results
With the potential of academic dishonesty in the Thomas High School by ninth grade students we inserted NaN to omit their data from the calculations. Below is the summary of the district after the ommision of the ninth graders scores.
![District Summary](https://user-images.githubusercontent.com/110861876/188739858-11561c3e-aa34-46bf-a1f2-f23f6fe2023f.png)
- Replacing the ninth graders' math and reading scores with NaN resulted in the following changes for Thomas High School:
  - The overall passing percentage for Thomas High School fell to 65%
  - The overall passing percentage for the entire district fell to 64.9%
  - Thomas High School was no longer included on the list of top five schools.
- When the ninth graders' of Thomas High School had their scores replaced the calculations, the following changes occured:
  - The overall passing percentages of Thomas High School decreased by 0.11% and the average scores of Thomas High School for math and reading increased by 0.06
  - For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%
  - Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.
![Spending Summary](https://user-images.githubusercontent.com/110861876/188744961-b3b80188-7b0a-4a9b-961b-cfabf28fe52d.png)
With school spending <$584 has the best scores of all the other funding overall; therefor, there are more factors than more funding that lead to average student scores.
![Size Summary](https://user-images.githubusercontent.com/110861876/188745661-723b6c99-4912-463b-9ec6-ff102972f085.png)
With school size larger schools have the lowest student scores and passing percentages, and the medium and small are quite similar around a 1% difference. From this data we can conclude that with less students they are learning and performing better in a smaller setting.
![Type Summary](https://user-images.githubusercontent.com/110861876/188746349-9aab044e-bc30-4ea9-80d6-1dc25493db03.png)
With the two types of schools (charter and district) charter is better at math (by around 6 points and better at reading by 2 points. Overall passing is where the biggest difference is where charter schools have 36% better percentage than district schools.
## Summary
Replacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to decrease drastically. Also, this occurred throughout the district with both math and reading scores seeing a decrease, even with the overall passing of the students. Moreover, Thomas High School fell out of the top 5 schools in the district. Within the large schools it caused those scores and passing percentages to drop as well.
