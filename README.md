# Confernece Talks

## Just Pattern Matching: Java Catches Up (But Is It Enough?)
**Abstract:**

Ready to ditch those tangled if-else chains and say goodbye to clumsy type checks? Java's new pattern-matching features promise a cleaner, more elegant way to code. But can they truly match the power and expressiveness that Kotlin and Scala developers have enjoyed for years? This talk takes a deep dive into Java's pattern-matching evolution, comparing its capabilities side-by-side with these JVM heavyweights. Discover where Java excels, where it might still fall short, and whether it's time to refactor your projects confidently. We'll showcase specific examples from each language to highlight the differences and similarities.

Whether you're a Java loyalist, a Kotlin convert, or a Scala enthusiast, you'll leave with a fresh perspective on the pattern-matching landscape.

## Java Streams Revisited: Unleashing the Power of the Gatherer API
**Abstract:**

The Java Stream API revolutionized functional-style programming in Java, enabling developers to express complex data processing pipelines concisely. However, certain operations have remained challenging to implement, often requiring cumbersome workarounds. Enter the Gatherer API (JEP 461), a powerful extension designed to enhance the flexibility and expressiveness of streams.

This talk revisits the Stream API with a focus on the Gatherer API, delving into its inner workings and showcasing its practical applications. We'll explore how Gatherers empower developers to create custom intermediate operations for filtering, windowing, folding, unfolding, and more. Through real-world examples, we'll demonstrate how Gatherers streamline data analysis, algorithm implementation, and other stream-processing tasks. We'll also discuss specific challenges the Gatherer API addresses to make the benefits clearer.

Join us to discover how the Gatherer API unlocks new possibilities for harnessing the full potential of Java streams, making your code more elegant, efficient, and maintainable. Whether you're a seasoned Stream API user or just getting started, this talk will provide valuable insights and techniques to elevate your stream-processing skills.

## Virtual Threads: Ushering In a New Era of Concurrency
**Abstract:**

Project Loom introduces virtual threads, lightweight threads that aim to dramatically reduce the effort of writing, maintaining, and monitoring high-throughput concurrent applications on the Java platform. We will begin with an overview of virtual threads and their evolution through JEPs 425, 436, and 444, discussing their design goals and integration into the JDK. We will then dive into practical examples, demonstrating how to create and manage virtual threads using the new Executors API, and showcasing their compatibility with existing Java code. This talk will explore how virtual threads are implemented, how they solve modern concurrency problems, and what, if any, shortcomings there may be.

## Breaking Java Stereotypes: It's Not Your Dad's Language Anymore
**Abstract:**

Challenging outdated stereotypes of Java, this talk spotlights the transformative evolution of this mature language, highlighting its transition into a modern, lean, and flexible tool for developers.

We'll explore new features like flexible main methods, records, and sealed classes that enhance expressiveness and efficiency. We'll touch upon the inclusion of pattern matching, unnamed patterns, and variables, which usher in a new level of expressiveness.

The discussion will extend to Java's improved handling of concurrency with virtual threads and structured concurrency. We'll also look at the ease and efficiency introduced by String Templates.

Join us as we rediscover Java: no longer a verbose and rigid relic, but a versatile, contemporary language ready for the challenges of modern software development.

## Jakarta Starter: Create, Build, and Run Jakarta EE Applications in Under a Minute
**Abstract:**

Everyone has an idea for a killer app, but everyone has to start somewhere. It’s always a good idea to start with all the scaffolding needed for the project. Until now, we didn't have a good starter application that could specify our requirements, such as runtime, dependencies, and more, and build a project structure in a minute. Many developers crafted their own versions of the Maven archetype, but now we have an official one from the Eclipse Foundation that is simple to download and use in a matter of minutes.

In this talk, I’ll show you how to use this tool to create a Jakarta EE application in under a minute. Furthermore, I will demonstrate how a developer can contribute to the ongoing project and help enrich the starter project. We'll also discuss the specific benefits of using this official starter application compared to custom solutions.

## A Tale of Two Cities: Blocking Code vs. Non-Blocking Code
**Abstract:**

Writing blocking code requires less mental effort, but it has drawbacks. Non-blocking code, on the other hand, can increase application throughput. This is why non-blocking code is recommended in many scenarios. Over the last two decades, many approaches have been introduced to writing code that does not block.

In this session, we will explore these options. We will start with the evolution of the Java concurrency model from its inception with vanilla threads. Then, we will introduce Future/Callable, CompletableFuture, briefly cover reactive programming, and finally conclude with Project Loom, which was added in Java 19. Each concurrency model and approach will be briefly described to give the audience a clear understanding of what will be covered.

## What You Won't Want to Miss: Top 10 Java Language Features
**Abstract:**

The pace at which new versions of Java are released remains exceptionally rapid. As a result, since Java 8, we have been introduced to a plethora of new features. Many of these features have already proven their worth. Examples include lambda expressions, the Stream API, Optionals, immutable collections, enhanced switch statements, records, sealed classes, and many more.

In this talk, I will discuss the top 10 Java language features that are highly useful and worthwhile in our day-to-day programming. Each feature will be briefly explained and supported with practical examples to illustrate their usefulness.

## Java Threading Essentials: Novice to Expert
**Abstract:**

To be a proficient Java developer, you must learn Java thread programming. Threads are the heart of the Java ecosystem. All server-side programming models heavily depend on the Java concurrency model. In this session, I will explain essential aspects of the Java thread model from the ground up so that a beginner can build their concurrency knowledge on top of it.

The session will include:

- How to create a simple concurrent program
- The benefits of Java threading
- Understanding the baggage that comes with threads and how to avoid it
- The thread-safe classes available in the JDK

Each topic will be covered in detail with practical examples to enhance understanding.

## Your Code on the Fastlane: Catch Up with Everyone by Using the New Versions of Java
**Abstract:**

Moving your project to the latest Java can mean faster code, cheaper cloud bills, and much more. Just by using Java 11, you can save up to 25% of heap memory. Plus, writing your code in the latest Java makes it clearer, more concise, and easier to read, reducing the chances of bugs.

Moving to the latest Java version means many things, such as:

- Upgrading your Java skills with the latest version, ensuring you no longer fall behind
- Writing clear and concise code with lambda expressions, reducing the chances of bugs
- Writing declarative and expressive code easily, resulting in less code but more results
- Learning how to refactor old legacy and imperative code with modern functional programming, leading to fewer errors in your code
- Processing large data sets in parallel, resulting in faster outcomes

In this short talk, I will demonstrate a few small and easy steps to upgrade your knowledge and Java code to the latest version. Each benefit mentioned will be supported with concrete examples or data.

## Creating a Million Virtual Threads Using Project Loom to Improve Throughput
**Abstract:**

Project Loom introduces virtual threads, lightweight threads that aim to dramatically reduce the effort of writing, maintaining, and monitoring high-throughput concurrent applications on the Java platform.

We need threads to achieve high throughput. However, threads are not cheap and are limited in quantity. To get around this problem, various alternatives, such as the reactive programming style, have emerged. These techniques bypass creating a lot of threads at the expense of more difficult debugging, making developers grumpy. However, with virtual threads, we get the best of both worlds: cheap, lightweight threads and easy debugging, making developers happy again.

This talk will explore what virtual threads are, how they are implemented, how they solve modern concurrency problems, and what, if any, shortcomings there may be. Implementation details and practical examples will be covered thoroughly to provide a comprehensive understanding.

## Let's Use Optional to Fix Our Method Contract
**Abstract:**

A method is a contract; when we define one, we put our thoughts into it. We specify the parameters with their type and also a return type. When we invoke a method, we expect it to behave according to the contract. If it doesn’t, it’s a violation of the contract.

We deal with such violations all the time. We invoke a method with its proper arguments, and we get a return. However, sometimes we end up getting a null, which is, in fact, a clear violation. We shouldn’t accept such a violation. If a method cannot return the value of the specified type, it should mention that in the method signature, indicating that the method may or may not return the expected value. If we know this from the method signature, we can write our code accordingly.

Now the question is, how do we define such a contract in a method signature? Well, that’s where Optional comes into play. Set your return type as Optional. Optional is a mystery box, a wrapping paper; it may or may not contain the value.

In this talk, we will discuss how to use Optional in Java and its patterns. Practical examples of using Optional will be included to illustrate its benefits and patterns effectively.
