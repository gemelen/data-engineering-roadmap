# Programming languages

## Topics

* General purpose languages tied with project of interest
* Scripting languages
* DSLs
* Parsing fundamentals

## General purpose language

Keeping in mind data processing goals we need to focus on languages that helps to perform and interoperate 
with already existed solutions more easily. This leads to the situation when programming language of choice 
could be different from the one that is used for other parts of the project.

There could be compromises, but usually we should stick to Java (or JVM-based) and/or Python as main languages 
for data engineering role.

Such choice would result in operating in well-developed and supported ecosystem of tools, solutions and 
approaches which is quite important from different perspectives: easier and faster project kick-off, variety 
of generic development tools and libraries, easier solution integration, cheaper maintainance and transition, 
and so on.


## Scripting languages

Regardless of choice of primary language(s), data engineer should be capable to use, develop and maintain tools 
written in other languages that are widely used in modern environments.

First of all these languages are some variations of Shell scripting language. So, basic knowledge of sh/bash is 
required to operate in environment both during development and in production.

Another example is Groovy language used for extention of functionality in Jenkins CI/CD solution.

## DSLs

Second bucket of auxiliary languages is set of Domain Specific Languages tied to some solution which could be used 
in a project, be it Markdown for documentation, query language of Kibana or something else.

One should be able to grab required level of familiarity with particular DSL quickly.

## Parsing

Data parsing is vital part of data processing in general and in some problems in particular, so data engineer needs to
know how to use existing parsers or write new ones in her language of choice.

Data engineer should be aware of theory of translation and its application (formal languages, tokenization, parsers combinators, etc).
