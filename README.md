Learning Git and Github!
=============
Subheadline
-------------
**Version control** is an essential skill for developers to master, and ~~Git~~ is by far the most popular version control system on the web. In this fast-paced course, author Ray Villalobos shows you how to install Git and use the fundamental commands you need to work with Git projects: moving files, managing logs, and working with branches.
***

How to show code [^1]

[^1]: Tick mark not apostrophe

<details>
  <summary>Task list dropdown</summary>

- [x] task1
- [ ] task2
   - [x] task3
   - [ ] task4
- [x] task5
  
</details>


|data1|data2|data3|
|---|:---:|---:|
|one|two|$1.00|
|two|three|$20.00|
|three|four|$10,000.00|

``` java
import java.util.Random;
//@SuppressWarnings("unchecked")
public class SearchTest{
	public static int linearSearch(Comparable target, Comparable[] list) {
		int index = 0;
    		while (index < list.length) {
      			if (list[index].compareTo(target) == 0)
           			return index;
       			else
           			index++;
   		}
   		 return -1;
	}

	public static void main(String[] args){
		Integer[] numbers = new Integer[1000000];
		Random rand = new Random();
		for (int i = 0; i < numbers.length; i++) {
 			numbers[i] = rand.nextInt(1000000);
		}
		System.out.println(linearSearch(5, numbers));
	}
}

```

- Thing1
- Thing2
   - Sub1
   - Sub2
 
1. Yes
1. No

[Website for this code][1]


[1]: https://kylebalcerski.github.io/linkedin-learning-github/

>Plus, you'll learn how to work with the popular GitHub website to explore existing projects, clone them to your local hard drive, and use them as templates for your new projects.
