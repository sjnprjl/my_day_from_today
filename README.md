# DAY 1 

**August 02 , 2020**

​	- ***Sunday***

---

*This is my daily log. From today I am going to change my life. I will learn everything everyday.* 

*Everyday will be the new and fresh day. Thank you!* :slightly_smiling_face:

---

## :notebook:  Today’s Todos

---

[x] Complete 2 or more competitive programming problems.       [ Points 20xp ]

[x] Learn about React.js. 							 [ Points 20xp ]	

[x] Learn about preincrement and postincrement		[ Points 10xp]

```
Today's total Xp: 50
```

---

## :diamond_shape_with_a_dot_inside: What I did on competitive programing problems today.

#### :arrow_forward: Sum of Digits

> *Write a program that accepts a number, **n**, and outputs the same.*

```c++
#include<iostream>
#include<string>   
using namespace std;

int main() {
    int T;
    cin >> T;
    for(int y = 0; y < T; ++y) {
        string s;
        cin >> s;
        int sum = 0;
        for(int x = 0; x < s.length(); ++x) {
            sum += (int)s[x] - 48;   
        }
        cout << sum << endl;
    }
}
```

---

#### :arrow_forward: Number Mirror

> *You're given an integer **N**. Write a program to calculate the sum of all the digits of **N**.*

```c++

#include <iostream>
int main() {
       int n;
       std::cin >> n;
       std::cout << n << std::endl;
}
```

---

#### :arrow_forward: Find Remainder

> ***Write a program to find the remainder when an integer A is divided by an integer B.***
```c++

#include <iostream>
int main() {
    int T;
    std::cin >> T;
    for(int x = 0; x < T; ++x) {
        int a , b;
        std::cin >> a >> b;
        std::cout << a % b << std::endl;
    }
}
```

---

## :diamond_shape_with_a_dot_inside: What I did on React.js today.

- I have created Hello world in reactjs today.

- I have learnt about **Components** in reactjs.

  

### :arrow_forward: How to create App components in reactjs?

```jsx
//this is a functional component
function Hello() {
    return (
        <h1>Hello, world!</h1>
    )
}
```
```js
// This is a class compoonent
class Hello extends React.Component {
	render() {
		return (
			<h1>Hellom world!</h1>
		);
  	};
};  
```
### :arrow_forward: How to render?
```jsx
// rendering
	ReactDOM.render(
		// takes component(s)
		<Hello />
		// takes the container to add component(s)
		document.getElementById("root")
	);
```

### :arrow_forward: Full Code
```jsx
function Hello() {
	return (
		<h1>Hello, world!</h1>
	)
}
// rendering
ReactDOM.render(
	// takes component(s)
	<Hello />
	// takes the container to add component(s)
	document.getElementById("root")
);
```
---

## :diamond_shape_with_a_dot_inside: What the heck is pre and post increment?

**Pre-increment operator**: A pre-increment operator is  used to increment the value of a variable before using it in a  expression. In the Pre-Increment, value is first incremented and then  used inside the expression.

​	courtesy - 

### :arrow_forward: What does that even mean?

```c++
int a = 10;
int b = ++a; 
cout << a << endl; // output is 11
cout << b << endl; // output is 11
```

```
Pre increment
a = 11
b = 11
```

---

**Post-increment operator**: A post-increment operator is  used to increment the value of variable after executing expression  completely in which post increment is used. In the Post-Increment, value is first used in a expression and then incremented.

​	courtesy - [geeksforgeeks](https://www.geeksforgeeks.org/pre-increment-and-post-increment-in-c/)

### :arrow_forward: Now, what is that even mean?

```c++
int a = 10;
int b = a++;
cout << a << endl; // output is 11
cout << b << endl; // output is 10
```

```
Post increment
a = 11
b = 10 (b takes the old value of a)
```

### :arrow_forward: brain teaser :laughing:

```c++
int a = 10 << endl;
cout << a++ << endl;
cout << a++ << endl;
cout << a << endl;
cout << ++a << endl;
cout << a++ << endl;
// output
10
11
12
13
13
```

----

---

## :sleeping_bed: Final note for today!

***Today was great day. I learned many things today. I will do even better tomorrow.*** :smile: 



  

