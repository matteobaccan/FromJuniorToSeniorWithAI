# From Junior to Senior Programmers with AI 🚀

![GitHub contributors](https://img.shields.io/github/contributors/matteobaccan/FromJuniorToSeniorWithAI)
![GitHub last commit](https://img.shields.io/github/last-commit/matteobaccan/FromJuniorToSeniorWithAI)
![GitHub language count](https://img.shields.io/github/languages/count/matteobaccan/FromJuniorToSeniorWithAI)
![GitHub top language](https://img.shields.io/github/languages/top/matteobaccan/FromJuniorToSeniorWithAI)

A comprehensive guide on leveraging AI and Large Language Models to enhance your programming skills and accelerate your journey from junior to senior developer.

## 📑 Table of Contents

1. [Introduction](#introduction)
2. [Field Experience](#field-experience)
3. [Understanding ChatGPT and LLMs](#understanding-chatgpt-and-llms)
4. [LLMs Capabilities](#llms-capabilities)
   - [Not for Problem Solving](#llms-are-not-designed-to-solve-problems-or-riddles)
   - [Writing Prompts](#writing-prompts)
   - [Knowledge Limits](#knowledge-limits)
5. [Practical Applications](#practical-applications)
   - [Understanding Code](#understanding-code)
   - [Creating Tests](#creating-tests)
   - [Security Enhancement](#security)
   - [Code Refactoring](#refactoring)
   - [Boilerplate Generation](#boilerplate)
   - [Code Documentation](#how-annoying-is-commenting-code)
   - [Code Review in Pull Requests](#code-review-in-pull-requests)
   - [Project Analysis](#project-analysis)
   - [Translations](#translations)
   - [Code Formatting](#formatting)
   - [Code Conversion](#code-conversion)
   - [Test Data Generation](#generating-random-data)
   - [Regular Expressions](#regular-expressions)
   - [Assessment Tests](#self-assessment-tests)
6. [Conclusions](#conclusions)

## Introduction

By now, everyone is familiar with AI and Large Language Models (LLMs). This guide explores how these tools can help developers transition from junior to senior roles by leveraging AI capabilities effectively.

## Field Experience

This guide is based on months of hands-on experience with various LLMs including:
- ChatGPT
- GitHub Copilot
- Claude
- Gemini
- Other LLMs

## Understanding ChatGPT and LLMs

ChatGPT is an AI chatbot using natural language processing to create human-like dialogue. While it doesn't think, it effectively applies learned rules to generate responses for:
- Code generation
- Content writing
- Problem-solving assistance
- Documentation

[Read more about understanding LLMs](#understanding-chatgpt-and-llms)

## Practical Applications

### Understanding Code
Learn how LLMs can help analyze and understand unfamiliar code, making it easier to modify or extend existing projects.

### Creating Tests
Discover how to generate comprehensive test suites and focus on edge cases while letting AI handle the basic test coverage.

### Security Enhancement
Explore how LLMs can help identify potential security issues and suggest improvements to make your code more secure.

### Code Refactoring
Learn how to use AI for code optimization and improvement while maintaining functionality.

[See all practical applications](#practical-applications)

## Getting Started

1. Clone this repository
```bash
git clone https://github.com/matteobaccan/FromJuniorToSeniorWithAI.git
```

2. Explore the documentation and examples in each section

3. Try the provided examples with your preferred LLM

## Contributing

Feel free to contribute to this project by:
1. Forking the repository
2. Creating your feature branch
3. Committing your changes
4. Pushing to the branch
5. Creating a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

- Thanks to all contributors who have helped shape this guide
- Special thanks to the AI/ML community for their continuous support


# From Junior to Senior Programmers with ChatGPT

By now, everyone is familiar with AI and, more broadly, Large Language Models (LLMs). We've all written countless prompts to get sensible responses, with varying degrees of satisfaction. To understand how these tools can help us become better programmers, transitioning from junior to senior, or simply becoming more skilled technicians, we first need to grasp what prompt engineering is, why it's important, and the areas where an LLM like ChatGPT, Claude, or others can help us grow professionally.

## Field Experience

What I'm about to write comes from months of using ChatGPT, GitHub Copilot, Claude, Gemini, and other LLMs, as well as from a series of readings and studies on the subject. I acknowledge that in a few months, I might be proven wrong: better tools might emerge, or perhaps they already exist and I haven't used them yet, which significantly help developers (and not just them) grow professionally.
Some of you might use different tools than I do, but let's focus on what we can achieve with these kinds of products rather than which one is the best. Otherwise, we'd start an endless war from which, I'm sure, no one would emerge victorious.

## Understanding ChatGPT and LLMs More Broadly

Let's start from the beginning: ChatGPT is an artificial intelligence (AI) chatbot that uses natural language processing to create human-like dialogue. The language model can answer questions and compose various written content, including articles, social media posts, essays, code, and emails, making it an exciting tool for programmers of all levels.
It's a model that doesn't think but can effectively apply the rules it was taught during training. This means that if we give it a wrong input, we'll get a wrong output, but if we give it a correct input, we'll get a correct output.
Similarly, if we use an LLM trained on datasets with errors, we'll get an output with errors.
By their nature, models always try to provide answers, and consequently, there will always be a percentage of responses, more or less significant, that will be wrong, made up, or otherwise incorrect.

With this initial point established, aimed at focusing on the type of tool we're trying to use, let's try to understand the areas where the error threshold is higher and those where it is lower, allowing us to use it more successfully.

## LLMs Are Not Designed to Solve Problems or Riddles

LLMs were created to answer questions, write articles, generate code, but they were not designed to think and solve problems or riddles. This means that if we present them with a problem, they won't be able to solve it autonomously; however, if we provide a solved problem, they will be able to return the solution.

Every time I see a video where someone enjoys presenting a riddle to ChatGPT and then is surprised that it can't solve it, I can't help but smile. It's like asking a 5-year-old child to solve a quantum physics problem: these are tests that don't take into account the capabilities of the interlocutor and the way it was conceived. They add no value and don't prove that the model is inadequate, but rather highlight that the "creator" in question hasn't understood how to use the model correctly.

In the field of programming, solving a riddle matters little; what is needed is to speed up code production processes, improve code quality, and understand it better. In these areas, LLMs can make a significant contribution, but only if used correctly.

## Writing Prompts

There's often talk about how to write prompts to get the best result, but it's not always clear what that means. Writing a prompt means providing clear and precise instructions on what we expect from the model and what we want to achieve.

The first and most obvious guidelines are:

- Be clear and concise
- Be specific
- Include the necessary context and details
- Define input and output

If we apply these guidelines to programming, we realize that it's not as simple as it seems. Defining a software product clearly, concisely, and specifically requires experience and knowledge of best practices. The more complex the project, the harder it is to define it this way.

How many times have you faced unclear or changing specifications, lacking the necessary details? How many times have you written code without knowing exactly what the client expected?

In these cases, getting a correct result from an LLM becomes difficult, even with a clear and detailed prompt.

## What Prompts to Write?

We've understood that a prompt that's too large is unrealistic, while one that's too small doesn't yield the desired result. So, what to do?

The solution is to write prompts as specific as possible, including the necessary context and details, while maintaining clarity and conciseness.

An example could be:

```plaintext
Write a C# function to find the factorial of a given number.
```

Here, we've specified the programming language, the required functionality, and the necessary context, obtaining an effective and precise result.

Remember that models learn from previously encountered contexts. The more common the context, the higher the probability of getting a satisfactory result.

Conversely, the more specific the context, the higher the chance that the model won't be able to provide a correct answer, even with all the necessary data and a clear description.

In these cases, it's preferable to use a product like Copilot or Codeium, capable of analyzing the code and providing more relevant answers to the context and needs.

## Knowledge Limits

Another important point to consider is that LLMs don't possess infinite knowledge but are limited to what was included in the training datasets. This implies that if we provide an input not present in the datasets, the model won't be able to respond adequately.

When does this situation occur more frequently? When we try to ask an LLM for information about products that didn't exist or were just launched when the model started being trained.
Mitigations to this aspect are beginning to emerge, such as real-time network querying and continuous training, but these are all solutions that don't completely solve the problem. At the moment, they mitigate it, managing to provide some answers but more often making them up.
So, don't expect to get accurate answers from ChatGPT about recently released products, newly launched technologies, or recent events, because it won't be able to respond correctly or, if it does, it will be with made-up or low-quality answers.

No, querying the network in real-time isn't enough to get correct answers, because the model doesn't have the ability to understand if the information it's reading is correct or not, and normally, every new technology has a series of documentation and comprehension issues, as well as a scarcity of available applications on the Internet.

## How Can We Get Better Results?

Given this, it's easy to understand that to get the best results, it's better if the technology we're working on is well-established and the tool we're relying on can contextualize our questions as much as possible.

One way to make the most of LLMs is to rely on models that don't just limit themselves to the typed prompt but can add a series of data taken from the project we're working on.
This range of products can provide more accurate answers because they have broader and more detailed knowledge than a model based solely on prompts.

An example of these models is GitHub Copilot, which can provide better answers than ChatGPT, thanks to broader and more detailed knowledge.

The broader knowledge comes from the fact that to generate a suggestion, the code before and after the cursor position within the editor is analyzed, all open files at that moment are used, and the referenced GitHub repositories in the context are added.
All these data are part of the input sent to Copilot, and consequently, the suggested code isn't a simple copy-paste of something found in the training data but is code strongly contextualized to the environment in which it's used.

Let's take a small example, starting from this Java code, which could be written in any programming language:

```java
public static final int UNO = 1;
public static final int DUE = 2;
public static final int TRE = 3;
public static final int QUATTRO = 4;
public static final int CINQUE = 5;

public static void main(String[] args) {
    // Given the parameter, find the match with the static variables
}
```

Let's focus on the comment, which is very generic and goes against all prompt engineering rules that suggest strong typing. If we were, for example, in ChatGPT, the indication of the language to use would be missing, and we might get an insignificant response:

In this context, however, Copilot can understand that the comment refers to the static variables, that we're talking about Java, and consequently, it will suggest code that does exactly what we expect.

```java
int parametro = Integer.parseInt(args[0]);
switch (parametro) {
    case UNO:
        System.out.println("UNO");
        break;
    case DUE:
        System.out.println("DUE");
        break;
    case TRE:
        System.out.println("TRE");
        break;
    case QUATTRO:
        System.out.println("QUATTRO");
        break;
    case CINQUE:
        System.out.println("CINQUE");
        break;
    default:
        System.out.println("No match");
}
```

I understand that at this point, many of you might be saying: "the code is too simple," "it could have been done better," and you're right, but that's not the point. The point is that contextualized tools like Copilot can better understand our prompts or what we need and provide a correct answer, while ChatGPT wouldn't be able to do so unless we wrote a much more extensive prompt than that minimal comment inserted in the code.

Contextualizing the question or the help we want to get gives a huge advantage over writing a generic prompt because it allows the model to better understand what we expect from it and provide a better answer.

## Understanding Code

We often face code that we didn't write and don't know, but we need to modify or extend. In these cases, it's very useful to have a model that helps us understand what the code does and how it works.

A senior programmer usually doesn't have major problems understanding code, but lowering the level to junior or simply stepping out of the senior's comfort zone, we realize that it's not so obvious to understand what a piece of code written by someone else does.

Speaking from personal experience, you can ask me to describe any program with a C-derived syntax, but don't ask me to describe a program written in Perl because I'd probably fake a lethargy attack.

LLM models can help us in this phase because they can analyze the code and give us an explanation of what it does and how it works. This allows us to better understand the code and modify or extend it more effectively.

Even in this case, contextualization is very important, but let's still try to tackle the problem with a generic prompt and see what happens.

Let's start with this function taken from the repository <https://github.com/jetty/jetty.project>

```java
public static boolean matchesURI(URI uri1, URI uri2)
    {
        String scheme = uri1.getScheme();
        if (scheme.equalsIgnoreCase(uri2.getScheme()))
        {
            if (uri1.getHost().equalsIgnoreCase(uri2.getHost()))
            {
                // Handle default HTTP ports.
                int thisPort = HttpClient.normalizePort(scheme, uri1.getPort());
                int thatPort = HttpClient.normalizePort(scheme, uri2.getPort());
                if (thisPort == thatPort)
                {
                    // Use decoded URI paths.
                    return uri2.getPath().startsWith(uri1.getPath());
                }
            }
        }
        return false;
    }
```

Now let's ask Claude (but it would be the same with other LLMs) to explain what this function does.

```plaintext
Can you describe this code?
<code>
```

In response, we'll get:

```plaintext
This code defines a static method called `matchesURI` that compares two URI (Uniform Resource Identifier) objects to determine if they match according to specific criteria. Here's a detailed description of how it works:

1. The method takes two parameters: `uri1` and `uri2`, both of type URI.

2. It first compares the schemes (protocols) of the two URIs:
   - Extracts the scheme of `uri1`
   - Compares the schemes of `uri1` and `uri2` ignoring case

3. If the schemes match, it proceeds to compare the hosts:
   - Compares the hosts of `uri1` and `uri2` ignoring case

4. If the hosts also match, it moves on to compare the ports:
   - Uses a method `HttpClient.normalizePort()` to handle default HTTP ports
   - Compares the normalized ports of both URIs

5. If the ports match, it finally checks the paths:
   - Verifies if the decoded path of `uri2` starts with the decoded path of `uri1`

6. The method returns `true` if all these conditions are met, otherwise it returns `false`.

In summary, this method considers two URIs to match if they have the same scheme, host, port (considering default HTTP ports), and if the path of `uri2` starts with the path of `uri1`.
```

You can see that in all contexts where we face unknown code, an LLM can be very useful to understand what it does and how it works.

## Creating Tests

We often find ourselves writing tests for the code we've written or need to write, depending on the school of thought you've adopted or the time you're given to achieve a goal.
Writing tests, however, isn't always easy and requires some experience and knowledge of best practices.

An LLM can help us because it can understand portions of code and generate tests for that code, or imagine some for the code we need to write.
This allows us to quickly have ready tests and focus only on the uncovered or edge cases.

Clearly, we might also face partial tests: but it's much faster to integrate a test suite than to write it from scratch.

Starting again from the above example, we can ask:

```plaintext
Can you write tests for this function?
```

In this case, I used Claude, which I often prefer to ChatGPT, and as a result, I got:

```plaintext
Certainly, I can help you write some tests for this function.
I'll use JUnit, a widely used testing framework for Java, to create these tests. Here are a series of tests that cover different scenarios:

These tests cover various scenarios for the matchesURI function:

- Matching URIs
- Different schemes
- Different hosts
- Matching with default port
- Different ports
- Non-matching paths
- Case insensitivity for scheme and host
- URIs with query and fragment

These tests should provide good coverage for the matchesURI function. However, you might want to add additional tests for edge cases or specific scenarios of your function's use.
```

Below is the piece of code created, which represents an excellent starting point:

```java
import org.junit.Test;
import static org.junit.Assert.*;
import java.net.URI;

public class URIMatcherTest {

    @Test
    public void testMatchingURIs() throws Exception {
        URI uri1 = new URI("http://example.com/path");
        URI uri2 = new URI("http://example.com/path/subpath");
        assertTrue(URIMatcher.matchesURI(uri1, uri2));
    }

    @Test
    public void testNonMatchingScheme() throws Exception {
        URI uri1 = new URI("http://example.com/path");
        URI uri2 = new URI("https://example.com/path");
        assertFalse(URIMatcher.matchesURI(uri1, uri2));
    }

    @Test
    public void testNonMatchingHost() throws Exception {
        URI uri1 = new URI("http://example.com/path");
        URI uri2 = new URI("http://example.org/path");
        assertFalse(URIMatcher.matchesURI(uri1, uri2));
    }

    @Test
    public void testMatchingWithDefaultPort() throws Exception {
        URI uri1 = new URI("http://example.com/path");
        URI uri2 = new URI("http://example.com:80/path/subpath");
        assertTrue(URIMatcher.matchesURI(uri1, uri2));
    }

    @Test
    public void testNonMatchingPort() throws Exception {
        URI uri1 = new URI("http://example.com:8080/path");
        URI uri2 = new URI("http://example.com:9090/path");
        assertFalse(URIMatcher.matchesURI(uri1, uri2));
    }

    @Test
    public void testNonMatchingPath() throws Exception {
        URI uri1 = new URI("http://example.com/path1");
        URI uri2 = new URI("http://example.com/path2");
        assertFalse(URIMatcher.matchesURI(uri1, uri2));
    }

    @Test
    public void testCaseInsensitiveSchemeAndHost() throws Exception {
        URI uri1 = new URI("HTTP://EXAMPLE.COM/path");
        URI uri2 = new URI("http://example.com/path/subpath");
        assertTrue(URIMatcher.matchesURI(uri1, uri2));
    }

    @Test
    public void testWithQueryAndFragment() throws Exception {
        URI uri1 = new URI("http://example.com/path");
        URI uri2 = new URI("http://example.com/path/subpath?query=value#fragment");
        assertTrue(URIMatcher.matchesURI(uri1, uri2));
    }
}
```

As you can see, there are many ideas and several working tests that we can integrate without fear into our project structure.
The more we keep our approach to code KISS (Keep It Simple Stupid), the better tests we can receive from the model, limiting error cases.

## Security

Another area where an LLM can be very useful is security. Writing secure code isn't always easy and requires some experience and knowledge of best practices.

There are tools that help write better code, and in my life, I think I've looked at SonarQube logs more than my wife's face, but an LLM model can be a valuable aid in this area, mainly because its knowledge of programming languages is significantly superior to many other tools.

For example, always starting from the method we're analyzing, I tried asking:

```plaintext
Can you give me suggestions to make the code more secure?
```

And I got something I had already wondered while looking at the method:

```plaintext
Null handling:
The current method doesn't check if the input URIs are null. Add checks at the beginning of the method:

if (uri1 == null || uri2 == null) {
    throw new IllegalArgumentException("URIs cannot be null");
}
```

In this case, I cut the other suggestions: but it's important to note that the model hit a point of improvement given by parameter normalization.

## Refactoring

Refactoring is a very important area of programming. To do holistic refactoring, you need to have a global vision of the project, which is not yet within the capabilities of LLM models. However, if we focus on the KISS concept, wisely reducing the scope of an LLM, we can have significant advantages or at least a series of ideas to pursue.

Among the refactoring operations are also code optimization operations, which can be useful to make our programs more efficient.

On June 8, 2023, an article on code optimization and sorting algorithms was published in Nature: <https://www.nature.com/articles/s41586-023-06004-9>

It analyzed how, using deep reinforcement learning, they managed to optimize the assembler code used for a sorting algorithm.

Here's the English translation of your text:

Without achieving this type of results, we can still ask an LLM to optimize our code, starting from a generic prompt like:

```plaintext
Can you refactor this code to make it faster?
```

The test is always done on Jetty's code and the result was this:

```java
public static boolean matchesURI(URI uri1, URI uri2) {
    // Store the scheme, host, and port only once.
    String scheme1 = uri1.getScheme();
    String scheme2 = uri2.getScheme();
   
    if (scheme1 == null || !scheme1.equalsIgnoreCase(scheme2)) {
        return false;
    }
   
    String host1 = uri1.getHost();
    String host2 = uri2.getHost();
   
    if (host1 == null || !host1.equalsIgnoreCase(host2)) {
        return false;
    }
    // Normalized port once.
    int port1 = HttpClient.normalizePort(scheme1, uri1.getPort());
    int port2 = HttpClient.normalizePort(scheme2, uri2.getPort());
   
    if (port1 != port2) {
        return false;
    }
   
    // Compare the path at the end.
    String path1 = uri1.getPath();
    String path2 = uri2.getPath();
   
    return path2.startsWith(path1);
}
```

We probably haven't gained much in terms of performance, but from a readability perspective, the method seems clearer and more linear, avoiding nested code on multiple levels.
One of the purposes of refactoring is also to make the code more understandable, especially because behind hundreds of lines of code there are always people who, as complexity increases, will decrease their willingness or effectiveness in making changes.
Keeping code simple facilitates maintenance and avoids reading comments like these that have now become memes:

```java
// This code is a total mess and I have no idea what it does, but it works, so don't touch it!
```

## Boilerplate

How many of us have started a new project and used a boilerplate as a starting point? I believe most of us have, and every time the initial step requires time and attention to avoid mistakes or oversights.

For this reason, there are collections of boilerplates that offer a starting point. An example is this GitHub project: <https://github.com/melvin0008/awesome-projects-boilerplates>, which gathers many examples of minimal projects.

Here too, an LLM can help us write the boilerplate, starting from a generic prompt like:

```plaintext
Can you write a minimal VUE project consisting of an initial login screen that queries the service https://reqres.in/api/login by sending a JSON with the "email" and "password" parameters, and if the response has a 200 status code, it allows me to access a backend composed of a left panel with a menu and a central panel where data is displayed? The left panel should include a logout button.
```

I won’t reproduce the entire response here: I’ve included the result in a GitHub project <https://github.com/matteobaccan/VUEdashboard>, which I recommend you check out from the first commits, as it may have been extended with further changes by the time you read this.

What I obtained is basic but provides a starting point for juniors who need to set up a project and have no idea how to do it, and it speeds up the work for seniors who have the knowledge but want to focus on other things.

In my case, I took what ChatGPT produced, created a new VUE 3 project, corrected some naming issues, updated dependencies, and merged everything into a functioning project.

Yes, I know, the best approach is always to study and know how to do these things from scratch, even with one hand tied behind your back, but often a push in the right direction allows us to be faster and maybe discover something outside our comfort zone that we rarely step out of.

Just think about how many times we got stuck writing something, and a boilerplate could have sped things up, but we could never find one that was exactly what we needed? Well, an LLM bridges the gap between what we want and what we find, reducing the distance.

## How Annoying is Commenting Code

Raise your hand if you've ever written code without commenting on it, or if you've had to comment on code written by others without understanding it.

In this case as well, an LLM can help us comment on code, starting with a generic prompt like:

```plaintext
Add comments to the following code
private String readFile(String fileName){ 
    BufferedReader br; 
    try { 
        br = new BufferedReader(new FileReader(fileName)); 
        final StringBuilder sb = new StringBuilder(); 
        String line = br.readLine(); 
    
        while (line != null) { 
            sb.append(line); 
            sb.append(System.lineSeparator()); 
            line = br.readLine(); 
        } 
        br.close(); 
        return sb.toString(); 
    } catch (IOException e) { 
        e.printStackTrace(); 
    } 
    return ""; 
} 
```

As a result, we would get:

```java
/**
 * Reads the contents of a file and returns it as a string.
 * @param fileName The name of the file to read
 * @return The file's content as a string, or an empty string in case of error
 */
private String readFile(String fileName) {
    BufferedReader br;
    try {
        // Initialize a BufferedReader to read the file
        br = new BufferedReader(new FileReader(fileName));
        
        // Create a StringBuilder to construct the file content
        final StringBuilder sb = new StringBuilder();
        
        // Read the first line of the file
        String line = br.readLine();
   
        // Continue reading as long as there are lines in the file
        while (line != null) {
            // Append the current line to the StringBuilder
            sb.append(line);
            
            // Add a system line separator
            sb.append(System.lineSeparator());
            
            // Read the next line
            line = br.readLine();
        }
        
        // Close the BufferedReader
        br.close();
        
        // Return the file's content as a string
        return sb.toString();
    } catch (IOException e) {
        // Handle any I/O errors
        e.printStackTrace();
    }
    
    // Return an empty string in case of error
    return "";
}
```

In this way, the code is commented and much more understandable. Even though the example is simple, the underlying concept is clear: do you have an unfamiliar piece of software that needs commenting? Ask an LLM to do it, and you might transform your codebase from a nightmare to a paradise.

---

## Code Review in Pull Requests

Imagine managing Pull Requests (PR) in a repository and wanting to optimize the work. On GitHub, there are several actions we can implement to perform automatic code reviews. One of them is:

```text
https://github.com/magnificode-ltd/chatgpt-code-reviewer
```

This action allows you to perform an automatic code review in PRs, accurately identifying changes and suggesting improvements. It's just an example, but the interesting thing is that we can create our own custom actions to be triggered on PRs, helping us speed up work and improve code quality.

## Project Analysis

As a senior, I often find myself analyzing a project or reading documentation written by others, and it's always a complex task that requires time and attention. In the past, I used to approach this phase by studying and researching on the Internet, hoping to find useful information.

These searches often generated many ideas but were also distracting: despite being skilled in searching, it's easy to get lost in a sea of information and not find what you need.

Recently, I changed my approach: after an initial study phase to frame the project, I lose myself in some voice conversations with ChatGPT. This approach has several interesting advantages:

- It's much faster than searching the internet: the answers are targeted and contextual.
- You can brainstorm with the model: compared to traditional research, the conversation allows for cross-linking information without having to open new tabs and start new searches.
- It works even in the car: during long trips to clients, talking to a virtual assistant is much better than staying silent (no, I'm not a fan of silent travel).
- It provides continuous information that, even if not immediately usable, can stimulate new ideas.
- Speaking out loud makes it easier to remember compared to simply reading.
- Yes, there could be hallucinations, but considering how many errors you find in online posts, this might not be a problem.

Of course, anyone seeing me talking to myself at a stoplight might think I'm crazy, but in my mind, I feel like Michael Knight talking to KITT.

## Translations

One of the most tedious tasks for a programmer is "translating" project documentation into another language. It's a boring job that requires time and attention, but it's necessary to make the project understandable to those who don't speak our language.

Clearly, the best approach would be to write everything in English, but this may not always be the optimal solution.

```plaintext
We have project documentation in Spanish written by the Madrid branch, and we need to translate it into English for our colleagues in New York.
```

For a few years now, I've been using markdown for all the documentation I produce. It's a lightweight writing format that allows for creating documents quickly and easily without worrying too much about formatting and without the need to install anything on your computer.

This allows me to quickly create slides with tools like Marp and easily maintain version control.

Recently, I had to translate project documentation into English. Doing it manually, copying and pasting the text into an LLM and then into the file, is tedious and time-consuming. I was about to write a program to automate the process when I discovered the existence of GitHub extensions that do it automatically, like **GPT-Translate**.

```plaintext
https://github.com/3ru/gpt-translate
```

I'm sure there are other solutions, but this one integrated perfectly into the lifecycle of the projects I manage, greatly speeding up the translation work.

Through a simple issue, you can activate the GPT-Translate action, specify which markdown document to translate and into which language. In response, a PR with the translated document is produced, ready to be approved.

I'll let you in on a secret: if you're reading this document in English or Spanish, so far you've been reading translations done by GPT-Translate via ChatGPT.

## Formatting

Have you ever had to deal with code or data structures that weren't properly formatted? LLM models can help us with this as well.

For example, starting with a prompt like:

```plaintext
Can you format this JSON structure for me?

[{"field1":"aa11","field2":"aa22", "structField":{"sf1" : "aaa11","sf2" : "aaa22"}},
{"field1":"bb11","field2":"bb22","structField":{"sf1" : "bbb11","sf2" : "bbb22"}}]
```

We would get:

```plaintext
[
    {
        "field1": "aa11",
        "field2": "aa22",
        "structField": {
            "sf1": "aaa11",
            "sf2": "aaa22"
        }
    },
    {
        "field1": "bb11",
        "field2": "bb22",
        "structField": {
            "sf1": "bbb11",
            "sf2": "bbb22"
        }
    }
]
```

And if we need it in another format, we can ask:

```plaintext
Can you convert this JSON to XML format?
```

The result would be:

```xml
<items>
    <item>
        <field1>aa11</field1>
        <field2>aa22</field2>
        <structField>
            <sf1>aaa11</sf1>
            <sf2>aaa22</sf2>
        </structField>
    </item>
    <item>
        <field1>bb11</field1>
        <field2>bb22</field2>
        <structField>
            <sf1>bbb11</sf1>
            <sf2>bbb22</sf2>
        </structField>
    </item>
</items>
```

In this case, I used ChatGPT, but the logic is the same for all LLMs: they are capable of formatting data structures. Even though these features are already present in modern IDEs, having a model do it for us is certainly an advantage.

## Code Conversion

How many times have you needed to convert code from one programming language to another? A common example is the need to use libraries or APIs provided only in a specific language, with little or no standardized documentation.

For some projects where I struggled in the past, I spent hours converting C calls and feeding structures into Java calls using conversion libraries like JNA.

If I had access to an LLM back then, I could have simply done:

```text
Can you convert this code from Java to JavaScript?

public static void PrimeNumberCheck(String[] args) {
    int numberToCheck = 17;
    boolean isPrime = true;
    
    for (int i = 2; i <= numberToCheck / 2; i++) {
        int remainder = numberToCheck % i;
        System.out.println(numberToCheck + " divided by " + i + " gives a remainder " + remainder);
        
        if (remainder == 0) {
            isPrime = false;
            break;
        }
    }
    
    if (isPrime) {
        System.out.println(numberToCheck + " is a prime number");
    } else {
        System.out.println(numberToCheck + " is not a prime number");
    }
}
```

With a significant time-saving:

```javascript
function PrimeNumberCheck(args) {
    let numberToCheck = 17;
    let isPrime = true;
    
    for (let i = 2; i <= numberToCheck / 2; i++) {
        let remainder = numberToCheck % i;
        console.log(numberToCheck + " divided by " + i + " gives a remainder " + remainder);
        
        if (remainder == 0) {
            isPrime = false;
            break;
        }
    }
    
    if (isPrime) {
        console.log(numberToCheck + " is a prime number");
    } else {
        console.log(numberToCheck + " is not a prime number");
    }
}
```

The interesting thing is the wide range of possible conversions with these large models, which is generally much broader than what was possible just a few months ago.

## Generating Random Data

One of the most tedious tasks for a programmer is generating test data for their code. Once again, LLM models can help us with this.

```plaintext
Can you generate a JSON array with 10 elements containing first name and last name fields with random data?
```

And here are the ready-to-use data:

```json
[
    {
        "nome": "Giovanni",
        "cognome": "Rossi"
    },
    {
        "nome": "Maria",
        "cognome": "Bianchi"
    },
    {
        "nome": "Luca",
        "cognome": "Verdi"
    },
    {
        "nome": "Paola",
        "cognome": "Neri"
    },
    {
        "nome": "Marco",
        "cognome": "Gialli"
    },
    {
        "nome": "Sara",
        "cognome": "Blu"
    },
    {
        "nome": "Andrea",
        "cognome": "Rosa"
    },
    {
        "nome": "Giulia",
        "cognome": "Viola"
    },
    {
        "nome": "Alessandro",
        "cognome": "Arancione"
    },
    {
        "nome": "Francesca",
        "cognome": "Marrone"
    }
]
```

I could have requested much more complex structured data or different formats: XML, CSV, and so on, and the model would have helped me generate them. This is a very interesting aspect because generating test data is often a boring and repetitive task that can be automated with the help of an LLM model.

## Regular Expressions

There are two schools of thought regarding regular expressions: those who hate them and those who don’t love them. Unfortunately or fortunately, in some contexts, they are very handy because when they work as expected, they greatly reduce the code we need to write, for example, for validation.

```plaintext
Can you write a regular expression to validate a string with a maximum of 10 alphanumeric characters, with a digit at the third position?
```

The result, based on the request, is spot on.

```plaintext
^[a-zA-Z0-9]{2}\d[a-zA-Z0-9]{0,7}$
```

## Self-Assessment Tests

I spend part of my time teaching, and it’s certainly not the best-paid activity, but it’s definitely the most rewarding. The joy of sharing our knowledge with the next generation and seeing students grow is priceless.

One of the most annoying aspects, at least for teachers, is creating and grading assessment tests at the end of study sessions. At the school where I teach, we use Moodle, an excellent tool for distance learning, but creating tests is always a tedious and repetitive activity.

This year, I decided to get help from ChatGPT to create the assessment tests. I entered the markdown document with the study session I wanted to evaluate and asked ChatGPT to generate the XML, in Moodle format, for 30 multiple-choice quizzes focused on the content of the provided document.

The result was very satisfying: I obtained an XML file ready to be imported into Moodle, with questions and answers automatically generated by ChatGPT. An example can be found in my CSS course:

```plaintext
https://github.com/matteobaccan/CorsoCSS
```

You can understand how useful an LLM model can be for generating self-assessment tests whenever we need them.

## Conclusions

When approaching an LLM, it’s important to understand that it’s not a magic wand that solves all problems, but a tool that can help us speed up our work and improve code quality.

Writing a prompt and hoping that what’s in our head is magically converted into code exactly as we need it is unthinkable. Similarly, thinking that there is a single AI tool that solves all our problems is, for now, a mistaken approach.

The best way for a programmer to approach an LLM is to understand the tool’s limitations and identify the contexts in which it can be used successfully, beginning to mentally catalog these areas so that for each of them there is a technique or tool that can be used effectively.

Similarly, it’s unthinkable to gather an entire project into a single prompt: it’s much more effective to divide the project into parts and ask the model to work on these parts to achieve a better and more precise result.

Even in contexts where a model is not capable of generating code, it is likely able to document, comment, translate, and perform many other operations that can speed up our work.

We are not yet at a point where these tools can do everything automatically, but a programmer who knows how to use them can achieve very good results and improve the quality of their work.

Improving your quality means becoming increasingly effective and taking off the junior hat to wear the heavier, more worn hat of a senior programmer.

