# Chapter 5 REST 

## Manifesto

Dr. Roy Fielding describes Representation State Transfer (REST) in
[Chapter 5 of his dissertation][dissertation].
There are [many popular styles][distractions] that differ from the architectural
style that Dr. Fielding describes; confusingly, these are often labeled as 
"REST", despite their significant dissimilarities from Chapter 5 REST.

This organization exists to increase industry-wide understanding and
implementing REST as described in [Fielding Chapter 5][dissertation].


### Understanding REST

Understanding Chapter 5 REST starts with reading [Fielding Chapter 5][dissertation].
The text is densely packed with meaning and may require multiple reads before
the meaning begins to crystalize.

Those with experience implementing other popular styles should be on the alert
for premature "a-ha" moments, when it is easy to see false similarities with
these other styles. Experience with Service-Oriented Architecture (SOA) makes
it particularly challenging to understand Chapter 5 REST, largely because SOA
uses similar terms.

There are many articles about REST online, with varying coherence to Chapter 5.
The [Reading List][reading] contains links to articles that conform highly to
Chapter 5 REST yet provide different (but accurate) perspectives.


### Implementing REST

Implementing a system according to Chapter 5 REST starts with these questions:

1. Who are the collaborators (people) who will be implementing/using the system?
2. What are the types of Resources?
3. What are the Content Types used to Represent those Resources?

These questions are addressed in greater detail in the [Reading List][reading].

The [REST Checklist][checklist] and [REST Testsuite][testsuite] help to guide
implementations and prove their conformance to Chapter 5 REST.

Refrence implementations in various languages and frameworks can be submitted
for review and inclusion in this GitHub organization's repository list.


## Other Information

### Connection to Dr. Fielding

Dr. Fielding was not involved in the creation of this organization. If he were
so inclined to participate, we would be honored.

### Submitting changes, forking, and collaboration

Chapter 5 REST is itself defined in [Dr. Fielding's dissertation][dissertation].
This organization does not seek to alter that definition.

Change submissions to this organization's repositories are welcome. These may be
easily done using GitHub's Fork and Pull Request features. All submissions are
reviewed thoroughly to ensure conformance with Chapter 5 REST.

This repository is the authoritative home for the Chapter 5 REST organization:

https://github.com/chapter5rest/

Issues should be reported using the appropriate sub-project's Issues on GitHub.


[dissertation]: https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm
[distractions]: http://www.slideshare.net/royfielding/a-little-rest-and-relaxation
[reading]: https://github.com/chapter5rest/manifesto/reading.markdown
[checklist]: https://github.com/chapter5rest/manifesto/checklist.markdown
[testsuite]: https://github.com/chapter5rest/rest-tests/README.markdown
