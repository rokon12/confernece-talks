# Confernece Talks

## Virtual Threads: Ushering In a New Era of Concurrency

**Abstract:**
Project Loom introduces virtual threads, lightweight threads that aim to dramatically reduce the effort of writing, maintaining, and monitoring high-throughput concurrent applications on the Java platform.  We will begin with an overview of virtual threads and their evolution through JEPs 425, 436, and 444, discussing their design goals and integration into the JDK. We will then dive into practical examples, demonstrating how to create and manage virtual threads using the new Executors API, and showcasing their compatibility with existing Java code. Then this talk will explore a bit on how virtual threads are implemented,. how they solve our modern problems, and what, if any, shortcomings there may be.


## Breaking Java Stereotypes: It's Not Your Dad's Language Anymore

**Abstract:**

Challenging outdated stereotypes of Java, this talk spotlights the transformative evolution of this mature language, highlighting its transition into a modern, lean, and flexible tool for developers.

We'll explore its new features like flexible main methods, records, and sealed classes that enhance expressiveness and efficiency. We will touch upon the inclusion of pattern matching, Unnamed Patterns and Variables which usher in a new level of expressiveness.

The discussion will extend to Java's improved handling of concurrency with virtual threads and structured concurrency, and we'll also look at the ease and efficiency introduced by String Templates.

Join us as we rediscover Java: no longer a verbose and rigid relic, but a versatile, contemporary language ready for the challenges of modern software development.



## Jakarta Starter: Create, build and run Jakarta EE Applications in under a minute

**Abstract:**

Everyone has an idea for a killer app, but everyone has to start somewhere. It’s always a good idea to start with all the scaffolding needed for the project. We didn’t have a good starter application until now that could specify our requirements, such as runtime, dependencies, and so on, and build a project structure in a minute. Many developers crafted their own version of the Maven archetype, but now we have an official one from the Eclipse Foundation that is simple to download and use in a matter of minutes.

In this talk, I’ll show you how to use it to create a Jakarta EE application in under a minute. Furthermore, I will demonstrate how a developer can contribute to the ongoing project and help enrich the starter project.

## A tale of two cities: blocking code vs. non-blocking code

**Abstract:**

We don’t have to exert much mental effort when writing blocking code, but this has drawbacks. Non-blocking code, on the other hand, could be used to increase application throughput. This is why non-blocking code is recommended in many scenarios. Over the last two decades, many approaches have been introduced to writing code that does not block.

In this session, we will look into those options that are available to us. To begin, I’ll go over the evolution of the Java concurrency model since its inception with the vanilla thread. Then I will introduce Future/Callable, and CompletableFuture, briefly go over reactive programming, and finally conclude with the Project Loom that was added in Java 19.


## What You Won't Want to Miss: Top 10 Java Language Features
**Abstract:**
The pace at which new versions of Java are made available to the public remains exceptionally rapid. As a result, since Java 8, we have been introduced to a plethora of new features. Indeed, some of these brand-new features have already proven their worth in spades. Examples include lambda expressions, stream API, optional, immutable collections, enhanced switch statements, optionals, records, sealed classes, and many more.

In this talk, I will discuss the top 10 Java language features that are highly useful and worthwhile in our day-to-day programming.

## Java Threading Essentials: Novice to Expert
**Abstract:**

To be a proficient Java developer, you must learn Java Thread programming. "Thread" is the heart of the Java ecosystem. All the server-side programming models heavily depend on the Java concurrency model. In this session, I will explain a few essential aspects of the Java thread model from the ground up so that a beginner can build their concurrency knowledge on top of it.

The session will include;

- How to create a simple concurrent program
- Identify the benefits of Java threading.
- Understanding the bagasse that comes with threads and how to avoid them
- What are the threadsafe classes available in the JDK

## Your code on the Fastlane: catch up with everyone by using the new versions of Java
**Abstract:**
Moving your project to the latest Java can mean faster code, cheaper cloud bills, and many more. Just by using Java 11, you can save up to 25% of heap memory. Plus, If you write your code to the latest Java, it would become clearer, concise, and easy to read which means less chance to produce bugs.

Moving to the latest java version means many things. For example -

- You will be able to upgrade your Java skills with the latest version, which means you are no longer fall behind
- You will be able to write clear and concise code with the lambda expression, which means less chance to produce bugs
- You will be able to write declarative and expressive code easily, which means less code but more results
- You will learn how to refactor old legacy and imperative code with modern functional programming, which means less error in your code
- You will be able to process large data set in parallel, which means a faster result

In this short talk, I will demonstrate a few small and easy steps to upgrade your knowledge and java code to the latest version.


## Creating a Million Virtual Threads Using Project Loom to Improve Throughput
**Abstract:**

Project Loom introduces virtual threads, lightweight threads that aim to dramatically reduce the effort of writing, maintaining, and monitoring high-throughput concurrent applications on the Java platform.

We need threads to achieve high throughput. However, threads are not cheap and are limited in quantity. To get around this problem, various alternatives, such as the reactive programming style, have emerged. These techniques bypass creating a lot of threads at the expense of more difficult debugging. This makes developers grumpy. However, with virtual threads, we get the best of both worlds, cheap, lightweight threads and easy debugging, which would make developers happy again.

This talk will explore what virtual threads are, how they are implemented, how they solve our modern problems, and what, if any, shortcomings there may be.

## Let’s Use Optional to Fix Our Method Contract
**Abstract:**

A method is a contract; when we define one, we put our thoughts into it. We specify the parameters with their type and also a return type. When we invoke a method, we expect it to behave according to the contract. If it doesn’t, it’s a violation of the contract.
We deal with such a violation all the time. We invoke a method with its proper arguments, and we get a return. However, sometimes we end up getting a null, which is, in fact, a clear violation. We shouldn’t accept such a violation. If a method cannot return the value of the specified type, it should mention that in the method signature, the method may or may not be returning the value you are expecting. If we know it from the method signature, we write our code accordingly.

Now the question is, how do we define such a contract in a method signature? Well, that’s where Optional comes into play. Set your return type as Optional. Optional is a mystery box, a wrapping paper; it may or may not contain the value.

In this talk, we will discuss how to use Optional in Java and its patterns.

