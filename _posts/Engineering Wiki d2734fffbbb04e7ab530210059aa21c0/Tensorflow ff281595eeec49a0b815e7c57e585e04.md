# Tensorflow

<aside>
💡 This is the notes taken from the youtube video

</aside>

[Google Colaboratory](https://colab.research.google.com/drive/1zWe5-fMarO7TK35Vo_5N5QhkGlgXpvPe#scrollTo=kO-45HNch1Il)

[https://www.youtube.com/watch?v=tpCFfeUEGs8&t=117s](https://www.youtube.com/watch?v=tpCFfeUEGs8&t=117s)

# AIcourse

### Date: June 19, 2022

### Topic:

### Recall

- What are neural networks?

- What are types of learning

- What is ML for?

- What we use to build deep learning architecture?

- What is a tensor?

- What to do?

### Notes

![Untitled](Tensorflow%20ff281595eeec49a0b815e7c57e585e04/Untitled.png)

![Untitled](Tensorflow%20ff281595eeec49a0b815e7c57e585e04/Untitled%201.png)

![Untitled](Tensorflow%20ff281595eeec49a0b815e7c57e585e04/Untitled%202.png)

![Untitled](Tensorflow%20ff281595eeec49a0b815e7c57e585e04/Untitled%203.png)

[https://www.youtube.com/watch?v=f5liqUk0ZTw](https://www.youtube.com/watch?v=f5liqUk0ZTw)

- It’s basically a mathematical way to represent all the forces in the universe, and a tensor is a vector space.
- No matter of what dimension you represent, the indices of a vector and the rank of a tensor are equal to it, which is also the number of how many basis vector you need to use to represent, so this concept can be applied to  all dimensions.
- And a vector can be represented by its components

![Untitled](Tensorflow%20ff281595eeec49a0b815e7c57e585e04/Untitled%204.png)

<aside>
📌 **SUMMARY:Intro of the course;Learned about what tensor is.**

</aside>

---

### Date: June 19, 2022

### Topic: How to approach this course?——CODE!!!!

### Notes

[00_tensorflow_fundamentals.ipynb - Colaboratory.pdf](Tensorflow%20ff281595eeec49a0b815e7c57e585e04/00_tensorflow_fundamentals.ipynb_-_Colaboratory.pdf)

<aside>
📌 **SUMMARY: The Colab page of this course**

</aside>

---

### Date: June 21, 2022

### Topic: Another coding day

### Recall

- Error when creating random tensors, need

```python
with tf.device('/cpu:0')
```

if you are on a apple silicon chip

- Understanding the tf.random.set_seed

- Four rules of `set_seed`
    - Global❌  Operation❌ ⇒ random pick a seed 变
    - Global✅  Operation❌ ⇒ pick a **deterministic** operation seed and conjunct them (might differ in different version of TensorFlow) 不变
    - Global❌  Operation✅ ⇒ random pick a  **default** global seed 变
    - Global✅  Operation✅ ⇒
        
        both are used to determine the random sequence 不变
        

### Notes

- 

![Untitled](Tensorflow%20ff281595eeec49a0b815e7c57e585e04/Untitled%205.png)

[tf.random.set_seed | TensorFlow Core v2.9.1](https://tensorflow.google.cn/api_docs/python/tf/random/set_seed)

![Untitled](Tensorflow%20ff281595eeec49a0b815e7c57e585e04/Untitled%206.png)

![Untitled](Tensorflow%20ff281595eeec49a0b815e7c57e585e04/Untitled%207.png)

<aside>
📌 **SUMMARY:**

</aside>

---