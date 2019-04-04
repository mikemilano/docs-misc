# Issue Content

Issue content should be timeless. Someone new to the project should be able to understand the issue just as well as
someone who's close to the project. An issue should be clear when looked up a year after it was created.

Any lack of detail in the issue costs time to interpret, each time the issue is revisited. By the time an issue is
assigned to a developer, the issue should require no clarification and little to no interpretation.

It is acceptable and even encouraged for an issue to take five minutes or more to define. Adequate information reduces
'more info' requests and QA cycles, significantly.

## Descriptions

The issue description should always be populated. Even in the rare care the title seems sufficient to act on the item,
the description should not be empty.

The following is a list of detail that should be provided with a description, when applicable. If there's a question
of if it's applicable, then just provide it.

* url \(This gives us the environment, as well as the page\)
* User and\/or role
* Detail \(The action to be done if available, or the problem\)

The following detail would only be relevant for bugs:

* Steps to reproduce
* Actual behavior
* Expected behavior

### Description Detail

When clients request features or report issues, there is always interpretation to at least a high level of technical
understanding involved. Any effort spent interpreting the request should be documented in the detail. If not, time and
effort will be spent making that interpretation each time the issue is visited.

### Steps to reproduce

Steps to reproduce should be written as if you were explaining the steps to someone trying to reproduce over the phone.
Besides the fact that it doesn't take long to document, a high level of detail avoids any interpretation.

Here is an example:

> * Go to [http:\/\/example.com\/node\/5203\/edit](http://example.com/node/5203/edit) as user: admin
> * Enter the following text as the title: "It's National Donut Day"
> * Click Submit
> * Look at the landing page: [http:\/\/example.com\/node\/5203](http://example.com/node/5203)
> 
> Actual behavior: The apostophe in the title is missing in the title. It reads: "Its National Donut Day"
> 
> Expected behavior: The apostophe should not be missing. It should read: "It's National Donut Day"

---

This example is trivial but this level of detail will keep clarification cycles to a minimum.
Trivial: \/\/TODO

