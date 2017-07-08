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
