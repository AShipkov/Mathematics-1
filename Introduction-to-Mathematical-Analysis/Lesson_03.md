## Lesson 03.
### Тема "Математическая логика. Последовательность."

#### Проверить любым способ, является ли данная логическая формула тавтологией:
1. $(A \vee B) \to (B \vee \overline{A})$
$$
\begin{array}{|c|c|}
  A & B & A \vee B & \overline{A} & B \vee \overline{A} & (A \vee B) \to (B \vee \overline{A})\\
  \hline
  True & True & True & False & True & True\\
  True & False & True & False & False & False\\
  False & True & True & True & True & True\\
  False & False & False & True & True & True
 \end{array}
$$
Даная формула не является тавтологией.

2. $A \to (A \vee (\overline{B} \land A)$
$A \to (A \vee (\overline{B} \land A)) = A \to A$
Даная формула является тавтологией.

#### Сформулируйте словесно высказывания (А: сегодня светит солнце; В: сегодня сыро; С: я поеду на дачу.):
3. $(\overline{A} \vee B) \to \overline{C}$
Если сегодня не будет светить солнце или сегодня будет сыро, я не поеду на дачу.
4. $C \to (A \vee \overline{B})$
Если я поеду на дачу, сегодня будет светить солнце, и сегодня не будет сыро.

#### Пользуясь высказывания, следующим: правилом записать построения утверждения, противоположного противоположные следующим:
5. На любом курсе каждого факультета есть студенты, сдающие все экзамены на «отлично».
На всех курсах любого факультета нет студентов, сдающих все экзамены на «отлично»
6. Каждый студент философского факультета имеет друга, который умеет решать все логические задачи.
У любого студента философского факультета нет друга, который умеет решать все логические задачи.
7. В любом самолете на рейсе Вашингтон-Москва присутствует хотя бы один сотрудник силовых органов, в каждой пуговице одежды которого вмонтирован микрофон.
Во всех самолетах на рейсе Вашингтон-Москва нет ни одного сотрудника силовых органов, в каждой пуговице одежды которого вмонтирован микрофон.

### Тема "Множества. Предел последовательности"
#### Представьте в виде несократимой рациональной дроби:

8. $0.(216)$

$1000a = 216.(216)$

$1000a = 216 + 0.(216)$

$1000a = 216 + a$

$a = \frac{216}{999} = \frac{24}{111} = \frac{8}{37}$

9. $1.0(01)$

$10a = 10,(01)$

$10a = 10 + 0,(01)$

$b = 0.(01)$

$100b = 1,(01)$

$100b = 1 + 0,(01)$

$100b = 1 + b$

$b = \frac{1}{99}$

$10a = 10 + \frac{1}{99}$

$a = \frac{991}{990}$

10. Представьте 1 в виде суммы трех рациональных дробей с разными знаменателями и числителем равным 1.
$$\frac{1}{1} = \frac{1}{2} + \frac{1}{3} + \frac{1}{6}$$

11. *Тоже задание, только в виде суммы шести дробей.
$$\frac{1}{1} = \frac{1}{2} + \frac{1}{3} + \frac{1}{7} + \frac{1}{43} + \frac{1}{1807} + \frac{1}{3263442}$$

12. Найдите значение предела:
$$\lim\limits_{n \to \infty}(\frac{1}{1 \cdot 2}+\frac{1}{2 \cdot 3} + \frac{1}{3 \cdot 4} + \dots + \frac{1}{(n-1) \cdot n}) = \lim\limits_{n \to \infty}(1- \frac{1}{n}) = 1$$

13. Пользуясь последовательности: критерием Коши, докажите сходимость последовательности:
$$a_n = \frac{\sin{1}}{2} + \frac{\sin{2}}{2^2} + \frac{\sin{3}}{2^3} + \dots + \frac{\sin{n}}{2^n}$$
*Какой член последовательности можно взять в качестве
предела с точностью $ε = 10^{−7}$

$| a_n - a_{n+k} | = | \frac{\sin{n}}{2^n} - \frac{\sin{(n+1)}}{2^{n+1}} |$

14. *Пользуясь критерием Коши, докажите расходимость последовательности:
$$b_n = 1 + \frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n}$$
