---
{"dg-publish":true,"permalink":"/personal/blog-posts/ship-software/","noteIcon":""}
---

Many of you probably read that title and thought “What is he talking about? Software and code are the same thing”, so I want to explain how it’s different, why it matters, and hopefully convince you to ship software instead of code going forward.

## What is software?

Take a moment to visualize what software is. What does it look like? What does it feel and smell like? You might think these are stupid questions to ask about something so abstract, but it’s not at all abstract to me. When you say “software” this is what I think it looks like.

$$image$$

Specifically I think about walking into any big box store in the early 2000s and going to their electronics department to see things like Microsoft Word, Doom, or Lotus 123. You’d grab the box of software off the shelf, bring it home, stick the media in your drive, and either run the installer or even run the software directly.

You might feel like this is an over simplistic exaggeration, so let’s dig a little deeper. Using pick a box of software off that shelf and ask yourself:

1. What programming language was the software written in?
2. What tools are required to build it?
3. How were the dependencies (if any) managed in the development of this software?
4. How is data persistence handled in that software?

Let me make this easy for you, the answer for all of the above is “who cares?”.

Let’s ask those same questions for a modern piece of commercial software. While you can’t walk into a big box store and bring it home, you still buy it from a store.

$$image$$

Obviously the answers to the questions are the same. Nobody looking to run this software knows or cares how the software was built.

Let’s look at a third example. This time some non-commercial, likely open source software. Let’s say you wanted to host a little photo gallery to share pictures of your vacation with your friends. While it’s not boxed software, and it’s not something from a centralized App Store, it’s still fair to assume that we can just download it and run it. It’s just software, after all.

$$image$$

But obviously something is different here. Not only do you know the answers to the questions, you **have** to know the answers in order to even begin the process of running anything.

## Why does this matter?

People who run self-hosted, open source, or non-commercial software are deeply knowledgeable about package managers, tool chains and programming languages, and I shouldn’t be so worked up about how software is shipped to them, right?

Well there lies the problem. We build the software assuming a software and technology professional. We need to build software targeting anybody who wants the software. If we’re going to offer alternatives to big tech and the centralized services that don’t have their best intentions in mind, we need to broaden our target audience.

## How did we get here?

I wouldn’t normally blame the language for the output, but the language choice and tooling surrounding each language has created a cultural change around shipping software.

As languages like PHP, Ruby, Python and Ruby became popular fewer and fewer people were writing software that was runnable, they instead pointed potential users at a repository of raw source code and said “good luck”. No longer were developers shipping software in a self-contained way because these tools simply don’t have a first-class way of doing so.

Before you knew it everyone wanting to run even the simplest of open source software was fighting multiple versions of runtimes to support different pieces of software. End users even need to run additional tools built to manage the different versions of the runtimes like nvm, rvm, pyenv, etc.

To make it all worse, we started treating database servers as a default dependency for almost any kind of software. Even for the most simple of data persistence cases. This means not only does a user have to understand how to get your software up and running, they have to understand how to spin up an entire database server just because you, as a developer, are most comfortable with PostgreSQL or MySQL.

The side effect of all of this is that the developer has pushed the effort and responsibility of knowing how to manage dependencies and build software onto potential end users instead of shipping software that can simply be run.

## The Docker Workaround

For some, Docker came to save the day. Many projects simply defaulted to shipping pre-configured images as their only installation method.

But I think we can all agree that if your software is so complex to install that you’ve given up, and instead started shipping entire copies of a computer with it pre-installed, something is wrong.

## Let’s fix this

### Shipping binaries

I think we’re on the right track. Languages that focus on shipping compiled, runnable binaries are on the rise. Go and Rust being two examples that are visibly changing the culture of shipping software to users. This **needs** to continue.

I’m not saying don’t use Node, or don’t use Python. But what I am saying is if you’re writing something for other people to run, you need to ship runnable software. And some languages are going to be better than others at having first-class ways to accomplish that.

People should be able to download your software and run it. Not download your code and build it.

### Databases

Let’s stop using database servers as the default. Start with an embedded database like SQLite. If your software has the requirements then you can also offer a migration path to a database server. But a local, embedded database is fine for many more things than you think.

## In conclusion

Write code with the intention of shipping it as software. Code is not software.

1. Let’s empower more people by getting more runnable software into their hands.
2. Pick tools that let you do that.
3. Chill it with the database requirements.
4. Git and Docker aren’t installation methods.
5. Any piece of software that requires the user to care, or even know, the details behind the software has failed the user.
6. If you do exclusively software-as-a-service stuff and nobody needs to run your code but you, then do whatever you want.