# Binary-Classification-with-a-Software-Defects-Dataset-KaggleS3-E23

## Data Information:

Number of attributes: 22 (5 different lines of code measure,
3 McCabe metrics, 4 base Halstead measures, 8 derived
Halstead measures, a branch-count, and 1 goal field)

Attribute Information:

1. loc             : numeric % McCabe's line count of code
2. v(g)            : numeric % McCabe "cyclomatic complexity"
3. ev(g)           : numeric % McCabe "essential complexity"
4. iv(g)           : numeric % McCabe "design complexity"
5. n               : numeric % Halstead total operators + operands
6. v               : numeric % Halstead "volume"
7. l               : numeric % Halstead "program length"
8. d               : numeric % Halstead "difficulty"
9. i               : numeric % Halstead "intelligence"
10. e               : numeric % Halstead "effort"
11. b               : numeric % Halstead 
12. t               : numeric % Halstead's time estimator
13. lOCode          : numeric % Halstead's line count
14. lOComment       : numeric % Halstead's count of lines of comments
15. lOBlank         : numeric % Halstead's count of blank lines
16. lOCodeAndComment: numeric
17. uniq_Op         : numeric % unique operators
18. uniq_Opnd       : numeric % unique operands
19. total_Op        : numeric % total operators
20. total_Opnd      : numeric % total operands
21. branchCount     : numeric % of the flow graph
22. defects         : {false,true} % module has/has not one or more  reported defects
