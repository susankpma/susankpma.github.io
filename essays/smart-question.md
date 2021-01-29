---
layout: essay
type: essay
title: Asking Smart Questions
# All dates must be YYYY-MM-DD format!
date: 2021-01-28
labels:
  - Smart Questions
  - Learning
---

[“How To Ask Questions The Smart Way”](http://www.catb.org/esr/faqs/smart-questions.html#beprecise) by Eric Steven Raymond is a useful essay that guides developers on how effectively they should ask questions on forums, newsgroups, and email.

On StackOverflow, I found two examples of a smart way and not smart way to a question. The  [“How to connect to SQL Server in Win7 virtual machine from Mac host?”](https://stackoverflow.com/questions/26149305/how-to-connect-to-sql-server-in-win7-virtual-machine-from-mac-host) by Vincent is a smart way to ask a question, while [“Does this code look correct?”](https://stackoverflow.com/questions/12183606/does-this-code-look-correct) by Phill Fernandes is not a smart way.

Vincent’s question sought assistance on how to connect to a SQL Server Express from Navicat which are both hosted on a Mac. The developer provided background and network information on the virtualized Windows 7 with the SQL Server Express. The developer then describes which host applications (Apache), protocols (telnet), and ports that are able to connect to the SQL Server and the applications (Navicat) that could not. Vincent also describes the steps taken to resolve the issue as well as providing the SQL Server configuration.

A reason why Vincent’s question was asked in a smart way was because of a specific subject header that includes the task to be accomplished and the software and hardware environment setup. Another reason why this was a smart question was that the developer expanded the details of the subject header by including specific ports and database configuration. In detailing the issue, the developer described the route and methods they tried and asked if there were areas they overlooked. While the developer was able to resolve the issue, they posted their solution and the website reference where the solution was found.

On the other hand, Phill Fernandes’ “Does this code look correct?” is an example of a question that was asked in a not smart way.

The developer posted the question regarding the functionality of their PHP and MySQL code. The developer provides a cursory description that a form passses data to update a database record. They ask if someone can verify the code while mentioning that they do not recall the syntax of the code and do not want to look at documentation.

Based on Eric Raymond’s essay, this question violates several of the principles he describes. First, the subject header does not provide much information about the language or setup. There are spelling and grammar issues that may suggest that the developer is not considerate of the audience and could be perceived as not being a careful developer. The developer does not provide any specifics on the full project scope, setup, environment, and test cases they tried before posting the question. Lastly, the “without looking at documentation” shows that the developer acknowledges that there is documentation but could not be bothered to read through it.

The responses to the developer were similar to the examples Raymond provided. One of the responses was “Have you actually tested it to see if it works?” and another refers them to a Stack Exchange website. Not all the responses were unhelpful. A reviewer actually posted the correct syntax and pointed out the error in their code, which turned out to be the developer’s choice of using a reserved word for a variable name.
