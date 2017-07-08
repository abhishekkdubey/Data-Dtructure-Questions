# Data Structure Questions.

## **1.** **Write a code which traverse this beloe tree**

![Tree](https://github.com/abhishekkdubey/data_structure_questions/blob/master/tree.PNG)

* Use this Node class(if using Java)
```
public class Node {

	private int data;
	private Node leftChild;
	private Node rightChild;

	public int getData() {
		return data;
	}

	public Node getLeftChild() {
		return leftChild;
	}

	public Node getRightChild() {
		return rightChild;
	}

}
```
* Expected Output:
```
6 8 9 7 3 2 1 
```

## **2. Write a program  which merge given two Linked List and generate sorted Linked List**
 
* Input: 
```
Linked List 1: 13->11->9->5  Linked List 2: 12->3->7->4
```
* Output:
```
13->12->11->9->7->5->4
```
 * Input: 
```
Linked List 1: 17->10->9->5   Linked List 2: 15->4->1
```
* Output:
```
17->15->10->9->5->4->1
```
## **3. Write a function which check tow Strings are isolated or not**

**NOTE:** Isolated in this questions means:
1. Size of both string should be same.
2. Each character of 1st String paired with another String character at same index will form a uniques combination.
3. One character can not paired with more than one character.
	  
**Example:**

* Isolated 
```
String str1= "aabd"; String Str2="xxnp"
	Pairing 
	a->x  
	a->x //a already pair with x so it won't be a problem  
	b->n
	d->p
```		 

* Non-Isolated

```
String str1= "aabx"; String Str2="xxnp"
	Pairing 
	a->x  
	a->x 
	b->n
	x->p // pairing of x is already with a so it won't pair with p. So it is not isolated.
```
