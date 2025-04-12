LIFO - last in first out 
push()
pop()
peek()
isEmpty()
clear()
size()


```javascript
class Stack{

constractor(){
	this.arr = [];
}

push(val){
	return this.arr.push(val);
}
pop(){
	return this.arr.pop();
}
peek(){
	return this.arr.at(-1);
}
isEmpty(){
	return this.arr.length ===0;
}
clear(){
	return this.arr.length = 0;
}
size(){
	return this.arr.length;
}
}

```