# ItemSniperApp

## What is this?

I was re-reading the fantastic book [Growing object-oriented software, guided by tests](https://www.amazon.de/Growing-Object-Oriented-Software-Addison-Wesley-Signature/dp/0321503627) (short GOOS), I few weeks ago. If you haven't read this book, go ahead and read it. I cannot recommend it enough.

My only problem with the book is that I'm not familiar enough with the tech stack. It uses Java with Swing, JUnit and Mockery (**TODO** Namen prüfen und Links einfügen). Don't get me wrong. I don't think it is "the wrong tech stack" or something silly like that. I worked with Java until 2013. So I'm totally fine with reading and maybe even writing Java code. But it is not the "Java" part I have a problem with. But I never **really** worked with Swing. The last time I used Swing was in... I don't know... 2006 maybe? (**TODO** check dates. Hat swing da schon existiert?)

I do know the concepts of mocks, stubs, fakes and all the things. But Mockery (**TODO** Name?) with it's concept of matchers is different from the stuff I normally use. So I do understand the code samples in the book, but it might take a little longer than it takes for professional Java devs.

## Playing with GOOS in my tech stack

I think you are most efficient in learning, if you can focus on a specific thing. And while reading through the book, I had to learn the concepts, but also pay attention to the Mockery syntax, the Swing-specifics and other stuff.

In short: If you try to internalize a new concept (like the London style of TDD), it is helpful if you are comfortable with the tech stack and your development environment. This way, you only have to learn the new concept and you don't have to understand a new IDE or a UI framework you are not familiar with.

This repo is my approach to the "AuctionSniper" example using "my tech stack". I'm still not sure if it will work out well, but we will see.

## What is my tech stack?

I'm a C# guy. I love all the things .NET. So here is the stack I use in this example. (**TODO** links)

* C#
* .NET Core 3.1
* NSubstitute
* xUnit.NET
* SignalR

If you already know the GOOS book, you might think "What about the UI? The end-to-end tests **including the UI layer** is a core concept of the book. You cannot leave it out."

You are right. And I'm not leaving it out. This example uses a command-line interface (CLI), which is also a UI. I was thinking about doing the UI part as a MVC project and I might add it later. But for now, the CLI will work just fine.

## Last paragraph

If you found this repo, chances are that you are interested in TDD and the London school. Maybe you are a C# enthusiasts just like me. In this case, this example might be helpful to you.

I try to commit often and early. Which means you can try to follow my process by checking the commit history. If you are familiar with GOOS and the concepts described in the book, I would love to hear your opinion on my example. Did I do something wrong? Is there some important stuff I missed or left out? Let me know. 