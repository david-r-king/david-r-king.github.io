---
layout: essay
type: essay
title: "Don't Be Dumb"
# All dates must be YYYY-MM-DD format!
date: 2025-09-11
published: true
labels:
  - Education
  - Python
  - Typescript
  - Java
  - C
---


<div class="essay-page">
  <img src="../img/essays/lightbulbs3.jpg" class="essay-header-img" alt="Light Bulbs">
</div>

<div class="text-center">
  <h2> How to Make Questions Smart </h2>
</div>

Asking questions is inevitable in every aspect of life, and the outcome or result of asking a question depends on a few key communication concepts and structure. This rings true especially in software engineering, where you will run into unexpected runtime issues. It's confusing enough with the complex systems, code and troubleshooting steps, so it's very important to communicate your question effectively. A well-structured question can save time, elicit the proper response, and lead to a real understanding or knowledge of what went wrong. While rushing a question and not thinking through what it is you're trying to convey can end in frustration and possibly even additional confusion. The difference between these two is what Eric Raymond describes as asking the "smart way" versus the "not smart way". Taking the time to analyze some real-world examples of each can change the way you ask questions and make it feel almost instinctual, increasing productivity and progress in the future.

---

<div class="text-center">
  <h2> Example of a Smart Question </h2>
</div>

### Example of a Smart Question

A great example of asking a question the "smart way", found on StackOverflow: [Why is processing a sorted array faster than processing an unsorted array?](https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array)

The asker noticed that iterating through a sorted array in C++ was significantly faster than iterating through an unsorted array. To illustrate the question, they included complete code that not only ran through each instance, but also measured the runtime performance of each over several iterations. They properly reported the timing results that reinforced the main problem they were facing and aligned well with the title of the question itself. This showed the question at hand, why was the unsorted array almost six times longer to execute? To rule out any language-specific issues, they also ran the same idea through Java and shared those results in the post.

They also showed that they had spent some time thinking about the problem before asking. They gave a theory that possibly the sorting was bringing the data into CPU cache, but wasn't sure that was the issue as the array was already stored in memory. After giving proper information and their own troubleshooting attempts/thoughts, they brought about two very simple and direct questions: "What is going on?" and "Why is processing a sorted array faster than an unsorted array?".

The clarity and simplification of the question resulted in outstanding responses. Some people explained how the CPU branch prediction and cache behavior made the sorted data easier to process, resulting in a faster runtime. Others reproduced the results and confirmed the output, then added their own thoughts and ideas. If that wasn't enough, the question has tens of thousands of upvotes as well as millions of views, which show its long-term educational value. This same question could have been asked in a vague, low-quality manner and provided little to no value. Instead, it showcases the benefit of doing your own research, including detailed troubleshooting, being clear and courteous - all of which can change the final outcome of a question.

---

### Example of a Not Smart Question

With the "smart way" fresh in our minds, let's see how another example compares:

> **Title:** *“Java program doesn’t work, urgent help needed!!!”*  
>   
> **Body:** 
> *Hi, I’m new to Java. I wrote this program for my class but it keeps giving me errors and I don’t know why. Please fix it for me. I need it to run by tomorrow!!!*
>   
> ```java
> public class Calculator {
>   private int total;
> 
>   public void add(int x) {
>     total = total + x;
>   }
> 
>   public void subtract(int x) {
>     total = total - x;
>   }
> 
>   public static void main(String[] args) {
>     Calculator c = new Calculator();
>     c.add("5");
>     c.subtract(3);
>     System.out.println("Total is: " + total);
>   }
> }
> ```
>   
> *It just says “error” when I try to run it. Sometimes it won’t even compile. I don’t know why it isn’t working. Can someone fix it? Please respond quickly, it’s urgent!*

Though this was an AI-generated post, it is a good example of a bad question. I would say this is as close to the opposite of the "smart way" as they come. The title is vague and insistent, it provides no useful context outside of "doesn't work". While the body of the post does include code, there is little to no evidence that this user made an effort to work through it themselves or what the actual error message is, which is one of the most important pieces of information when troubleshooting. All of this leads to frustration for the reader and makes it almost impossible to respond in a constructive, positive way.

When comparing to the earlier "smart question" example about sorted arrays, there is a stark difference. The array question showed clear thought and effort towards solving the problem themselves before passing the problem off. This post comes across in a "do my homework for me, and do it now" tone, showing no research, no clarity, and no respect for the audience. In the end, one of these questions draws minds in and encourages genuinely positive responses while one encourages readers to look for the block or report button. This highlights how putting in thought and effort can change the results dramatically.

---

### Conclusion

The importance of asking questions the "smart way", most notably for software engineers, cannot be overstated. Whether you take the time to solve the problem yourself, or don't, is often obvious when asking the question and can influence the response. Making this a habit builds credibility, accelerates learning, and strengthens the collaborative culture of open-source and problem solving communities. After comparing both the "smart" and "not smart" ways to ask a question, hopefully we have all learned how essential it is for long-term growth as a professional developer.
