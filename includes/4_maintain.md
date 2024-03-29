## Section 4: Concluding Your Project

<a name="top_4"></a>
### Table of Contents
###   Part A: [From Data Projects to Data Products](#projects)
###   Part B: [The Product Lifecycle](#lifecycle)
###   Part C: [Automating the Maintenance of Your Dataset](#automate)
###   Part D: [Retrieving and Implementing User Feedback](#feedback)

___

## <a name="projects"></a> Part A: From Data Projects to Data Products 

  Until now,  we’ve used the words “data product” and “data project” interchangeably, but the two concepts are worth differentiating before this section. A **project** might come to mind when you think of any enterprise or initiative related to engineering, science, and data, such as building a bridge  or conducting a research study. A **product** is more often associated with business, markets, and consumer satisfaction.
  Projects have a **short-term scope** (i.e. a set start and end-date), are meticulously **planned** through use of budgets, schedules, and deadlines, and are comprised of a team of **technical experts** (such as engineers, physicists, mathematicians, etc). They are intended to deliver an **output** timely, safely, and effectively.

![Project Life Cycle]({{ site.baseurl }}/assets/images/04_figure04.png )

  **Products** are different from projects mostly because they have a circular lifecycle — that is, a “product” never ends.  This is because a product is **anything intended to meet some need** of the customer, which is often a moving target that morphs and changes over time. Where projects are concerned with budgets and schedules, products rely on **markets, customers**, and **trends**, and require a team of flexible, creative, and intuitive individuals to effectively understand how to address the needs of the customer. 
  Since projects are so narrow in scope, they are often left unmaintained and unmanaged after completion. This is a huge waste of the time and resources that went into that project: what lessons did they learn? How could their strategy be utilized elsewhere? Even small efforts toward maintaining your project — such as getting stakeholder feedback every six months — transform your project's impact.
  What’s more, the product mindset can teach you to be adaptable, flexible, and creative; three skills necessary to building longer-lasting and more innovative solutions. The product design principles in this section will give some strategies for improving your project’s outcome/service over time by constantly seeking feedback and maintaining your data. 

>[Click for Back to Top](#top_4)

___

## <a name="lifecycle"></a> Part B: The Product Lifecycle

When planning for long-term maintenance of your project, it can be helpful to look at the principles behind long-term maintenance of a product. The product lifecycle is the natural process of conception and decline undergone by any product. It is made up of **four stages**:

>1. Introductory Stage:
>  * Also the "Market Development” stage; preliminary need of the user has been identified, but not proven demand exists
>2. Growth Stage
>  * This is the stage of highest growth; demand is high, size of market & competition expands rapidly
>3. Maturity Stage
>  * Demand levels off, product becomes dated
>4. Decline Stage
>  * The product becomes obsolete or maintenance is stopped

![Project Life Cycle2]({{ site.baseurl }}/assets/images/04_figure05.png )

With these stages in mind, **ask yourself the following questions:**

| - How can you predict each stage of your project?<br /> - Think about your market: anything technology, for example, typically has quickly changing trends and faster life cycles. Medical devices or healthcare services are the opposite. |
| - How can you determine what stage you are in? |
| - How can you use this knowledge to change your strategy **now?** |

Your answers will inform how you choose to maintain your product or project over time, and will help you anticipate the natural rise and fall that will occur. 

>[Click for Back to Top](#top_4)

___

## <a name="automate"></a> Part C: Automating the Maintenance of Your Dataset

A number of incredibly valuable research projects and compiled/cleaned datasets **become useless** over time because **they are not routinely updated with the latest data**. If your project required you to compile a dataset from publicly-available, regularly updated datasets (such as U.S. Census Bureau data), then consider automating your data’s year-to-year updates so it remains  valuable for years to come. This is a straightforward process that any technical employee can do.

  First, see the [Data De-Identification Guidelines](https://chhsdata.github.io/dataplaybook/documents/CHHS-DDG-V1.0-092316.pdf) to ensure your dataset is de-identified and all confidential information removed. Next, go to the [CHHS Open Data Portal](https://data.chhs.ca.gov/). [OpenGov.com](OpenGov.com), the host of the data portal, runs the site on an open-source data platform called [CKAN](ckan.org) which provides a FileStore API that enables **automation of dataset updates**. See Python documentation [here](https://docs.ckan.org/en/latest/maintaining/filestore.html#filestore-api).

>[Click for Back to Top](#top_4)

___

## <a name="feedback"></a> Part D: Retrieving and Implementing User Feedback

Understanding iterative product development — or the the process of prototyping, delivering, assessing, and adjusting your output— is foundational to understanding product design principles. By continually asking for feedback and implementing changes, your product will continue to be tailored to the needs of  your customer despite changing markets, attitudes, and trends. 

### Use the following framework to guide your feedback requests:

>1. **Ask** your customers about your product
>2. **Categorize** their feedback
>3. **Act** on their feedback

### Step 1: Understanding overall trends in customer satisfaction over time

To identify **trends** in customer satisfaction, ask feedback at regular intervals, and track them over time. 
Some popular ways to measure overall customer satisfaction trends are:
* [Net Promoter Score (NPS)](https://blog.hubspot.com/customer-success/what-is-nps): A single question, answered with a scale of 1 to 10 “How likely are you to refer us as a product or service?”:
* **Customer Satisfaction Score (CSAT)** is a measurement of how satisfied a customer is with a specific interaction with a company: “Please rate the quality of service provided to you”
* **Social media monitoring**: use google tracking to keep up with what people are saying about your product or service

### Step Two: Categorizing Customer Feedback

When it comes to organizing your feedback, it generally depends on the product or program you’re working on. Some common buckets are **product** and **customer service:**

1. **Product feedback:**
  * **Major bugs/points of frustration**. These are extremely urgent issues that prevent users from getting the core value out of your product.
  * **Minor bugs/points of frustration**. These are minor issues that don’t distract from the core product value.
  * **Requests**. Important to ask for feature requests, and prioritize them based on a mixture of volume of requests, potential impact of building that feature, and opportunity costs associated with each choice.
2. Customer service feedback:
  * **Consider designing an automated survey** if your product is digital and has some sort of customer assistance chat
  * **Include surveys after phone calls with customer service**

### Step Three: Act on Feedback

The most important part of getting feedback is **actually acting on it** — get your team together to brainstorm ways to meet the developing needs of the customer, and improve it in any way you can. 

>[Click for Back to Top](#top_4)

<!-- Pagination -->
<div class="pagination">
  <a class="pagination-item older" href="{{ site.baseurl }}/communicate">&laquo; Prev</a>
  <a class="pagination-item newer" href="{{ site.baseurl }}/resource_library">Next &raquo;</a>
</div>
