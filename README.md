<!-- Place this tag in your head or just before your close body tag. -->
[![Medium Badge](https://img.shields.io/badge/Blog-black?style=flat&logo=medium&logoColor=white&link=https://medium.com/@roni-dover)](https://medium.com/@roni-dover)
[![Twitter Badge](https://badgen.net/badge/icon/twitter?icon=twitter&label)](https://twitter.com/doppleware)
[![made with love by digma-ai](https://img.shields.io/badge/made%20with%20%E2%99%A5%20by-digma-ff1414.svg?style=flat-square)](https://github.com/digma-ai)

<p align="center">
<img src="https://www.digma.ai/assets/img/digmatic.png" width="300" height="346" >
</p>

# What is Digma and why are we building it?

## Digma is about *Developer Observability*

We believe that understanding code real-world requirements and behavior is critical to making better software.
We see the right information being collected but not being processed and made available to developers early enough to make a difference.

<br/>
<br/>

## Can you give me some examples?

Sure! Think about any piece of code in your IDE. In fact, lets take this random snippet I came across exploring Github: [Source Here](https://github.com/saleor/saleor/blob/main/saleor/shipping/tasks.py).

<img src="images/sample_code.png" width="600" height="391">

Looking at the above call we can infer a lot about what it does but not so much about
**how it is used**

With *Developer Observability* we can use existing logs, traces and metrics to answer questions such as:

* Where is this function called from, is it even used
* What data is passed into its parameters in runtime? 
* What type of errors does it raise in runtime, under which conditions, and how do they impact the final end user

More important we can start correlating all of these data points. Does the performance of this function scale differently for different shipping methods? How is all of this information trending between releases, commits, types of users?  

<img src="images/sample_code_2.png" width="600" height="391">

<br/>
<br/>

## Digma is about Continuous Feedback

There are countless of CI/CD platforms out there, but almost no tool to provide feedback back from prod and test to the code.

With continuous feedback we can make code changes and design that are well informed on actual usage and real world expectations. 


<p align="center">
<img src="images/loop.png" width="500" height="232">
</p>

<br/>
<br/>

## How can I learn more about Digma?

We started publishing some more detailed blog posts explaining what we are trying to accomplish:

[CI-CD-CF The Devops Toolchain Missing Link](https://levelup.gitconnected.com/ci-cd-cf-the-devops-toolchains-missing-link-b5c88caf6282)

[Breaking the Fourth Wall in Coding](https://levelup.gitconnected.com/breaking-the-fourth-wall-in-coding-189055955c85)

<br/>
<br/>

## How do I contribute

### Consider starring this repo - it helps us know you care!

### Join our community

We are still debating where we want to host our community and which platform to use. In the meanwhile, if you want to get involved in the discussion please message us at community@digma.ai and we'll be happy to include you in some of our early discussion forums.

### Join as a contributor

We'll be releasing some of our Open Source code repos soon - still working on tidying things up. We welcome you as a contributer!




