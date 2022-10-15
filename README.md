# stack
This is a snippet of code that utilizes the Pop and Peek operations on a stack that is not empty.

import java.util.Stack;
public class stackExample {
	
	public static void main(String[] args) {
		
		Stack <Integer> nums = new Stack<Integer>();
		
		nums.push(1);
		nums.push(2);
		nums.push(3);
		nums.push(4);
		
		System.out.println(nums.peek());
		System.out.println(nums);
		nums.pop();
		System.out.println(nums);
		nums.pop();
		System.out.println(nums);
		nums.pop();
		System.out.println(nums);
	}

}
![stackexample](https://user-images.githubusercontent.com/108758588/196001729-d63c2b9d-643c-44e1-ad0b-ec71ecd82918.png)
