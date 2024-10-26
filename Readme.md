When I start writing my code, I first add a whole lot of Java utilities by adding java.util.* in my imports. I find this particular import quite useful since I always have to use the Scanner(System.in) at some point.

In each of the code snippets, I have followed a convention of starting it with a public static int() and closing it with System.out.println(… ). I do not append the static tag in case of non – static methods, rather I make an object like, MathUtil mathUtil = new MathUtil(); to be able to use it within any class.

To sum up, the most distinct part that I would like to elaborate on is the creation of an instance. So, for instance, a non-static method is quite simple – an instance of the class is created and all the methods available in that class are accessible. However, to perform a call of static methods, no instance has to be created.
