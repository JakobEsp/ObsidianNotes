En lille Desktop app og API bygget til at beregne opdeling af incomst.  Den skal kunne bruges til hurtig beregning af hvordan penge skal opdeles til nuværende budget samt eksperimentere med budgetter. 

Stacks - 

App
[[VueJS]] Frontend web app 
[[Wails]] Desktop app framework, tager brug a [[Go]]
[[Vite]] Frontend build tool

Api
[[Gin]] Go web Framework
[[GORM]] ORM 
[[MySQL]] Database
[[Air]] Go hot reload


Features 
- [ ] Beregn hvor meget og hvor penge skal hen baseret på procenter eller custom indsat
- [ ] Gem resultater
- [ ] mulighed for at lave eksperimentale budgetter
- [ ] lav opsparings mål, beregning på hvornår man har noget hvis man sparre op til nuværende rate, 
- [ ] predictions - ved brug af opsparingsmål og tidligere data kan man komme med predictions på hvornår man når sit mål, eller hvor meget man kommer til at have opsparet om x antal tid
- [ ] Dashboard - data summarization største udgifter, samlet incoms predictions og andre grafer maybe?
- [ ] goals - mulighed for at sætte mål som samlet incomst i x tidsperiode eller andet


Note til opsparingsmål:
Det skal tilføjes sådan man kan tilføje et opsparingsmål til en expence / tagge en expence som en opsparing og mulighed for tilføje et opsparingsmål


