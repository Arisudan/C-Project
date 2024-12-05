# C-Project
C++ Overall Project File

# Stack:
A stack stores multiple elements in a specific order, called **LIFO**.

LIFO stands for **Last in, First Out**. 

1) To vizualise LIFO, think of a pile of pancakes, where pancakes are both added and removed from the top. So when removing a pancake, it will always be the last one you added. 
2) This way of organizing elements is called LIFO in computer science and programming.

Unlike vectors, **elements in the stack are not accessed by index numbers**. Since elements are added and removed from the top, you can **only access the element at the top of the stack**.

# To use a stack, you have to include the <stack> header file:
        #include <stack>
# Queue:
A queue stores multiple elements in a specific order, called **FIFO**.

FIFO stands for **First in, First Out**. 

1) To visualize FIFO, think of a queue as people standing in line in a supermarket.
2) The first person to stand in line is also the first who can pay and leave the supermarket.
3) This way of organizing elements is called FIFO in computer science and programming.

Unlike vectors, elements in the **queue are not accessed by index numbers**. Since **queue elements are added at the end and removed from the front**, you can only access an element at the front or the back.

# To use a queue, you have to include the <queue> header file:
       #include <queue>
# Create a Queue:
      queue<string> cars;
      
**Note: You cannot add elements to the queue at the time of declaration, like you can with vectors:**

                        queue<string> cars = {"Volvo", "BMW", "Ford", "Mazda"};
# Add Elements to the Queue:

                        queue<string> cars;
                        cars.push("Volvo");
                        cars.push("BMW");
                        cars.push("Ford");
                        cars.push("Mazda");
                        
**In a queue, you can only access the element at the front or the back, using .front() and .back() respectively**

**You can also use .front and .back to change the value of the front and back elements**

**.pop() function to remove an element from the queue.**

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Arrow operator -> in C/C++ with Examples.**

An Arrow operator in C/C++ allows to access elements in Structures and Unions. It is used with a pointer variable pointing to a structure or union. The arrow operator is formed by using a minus sign, followed by the greater than symbol as shown below. 
**#Syntax**
(pointer_name)->(variable_name)

Operation: The -> operator in C or C++ gives the value held by variable_name to structure or union variable pointer_name.
Difference between Dot(.) and Arrow(->) operator:  

The Dot(.) operator is used to normally access members of a structure or union.
The Arrow(->) operator exists to access the members of the structure or the unions using pointers.
                
