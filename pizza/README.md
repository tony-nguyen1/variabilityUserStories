```
java -jar ../fca4j-app-light-0.4.5.jar RCA ./pizzaLatece.rcft ./rai_aocposet/ -a HERMES -rai -e

java -jar ../fca4j-app-light-0.4.5.jar family -a EXPORT ./rai_aocposet/pizzaLateceextended.rcft  ./rai_aocposet/pizzeriaLateceExist.cex -x CEX -n Pizzeria

java -jar ../fca4j-app-light-0.4.5.jar  rulebasis ./rai_aocposet/pizzeriaLateceExist.cex ./rai_aocposet/rulesPizzeriasExist.txt -folder ./rai_aocposet/RulesExist

dot -Tpdf ./rai_aocposet/step3.dot -o ./step3.pdf

xdg-open step3.pdf
```