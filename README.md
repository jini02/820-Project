# Purchasing Intention with Machine Learning

Attribute Information:
The data used in this analysis is an Online Shoppers Purchasing Intention data set provided on the UC Irvine’s Machine Learning Repository. The data set shows each session that belong to a different user in a 1-year period.

The dataset consists of 10 numerical and 8 categorical attributes. The 'Revenue' attribute can be used as the class label. Of the 12,330 sessions in the dataset, 84.5% (10,422) were negative class samples that did not end with shopping, and the rest (1908) were positive class samples ending with shopping.

"Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" represent the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories.

The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action, e.g. moving from one page to another.

The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. The value of "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session.

The value of "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that were the last in the session. The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction.

The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction.

The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8.

The dataset also includes operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.onth of the year.

Column Descriptions
Administrative: This is the number of pages of this type (administrative) that the user visited.

Administrative_Duration : This is the amount of time spent in this category of pages.

Informational : This is the number of pages of this type (informational) that the user visited.

Informational_Duration : This is the amount of time spent in this category of pages.

ProductRelated : This is the number of pages of this type (product related) that the user visited.

ProductRelated_Duration : This is the amount of time spent in this category of pages.

BounceRates : The percentage of visitors who enter the website through that page and exit without triggering any additional tasks.

ExitRates : The percentage of pageviews on the website that end at that specific page.

PageValues : The average value of the page averaged over the value of the target page and/or the completion of an eCommerce transaction.
More information about how this value is calculated

SpecialDay : This value represents the closeness of the browsing date to special days or holidays (eg Mother's Day or Valentine's day) in which the transaction is more likely to be finalized.

Month : Contains the month the pageview occurred, in string form.

OperatingSystems : An integer value representing the operating system that the user was on when viewing the page.

Browser : An integer value representing the browser that the user was using to view the page.

Region : An integer value representing which region the user is located in.

TrafficType : An integer value representing what type of traffic the user is categorized into.
Read more about traffic types here.

VisitorType : A string representing whether a visitor is New Visitor, Returning Visitor, or Other.

Weekend : A boolean representing whether the session is on a weekend.
Revenue : A boolean representing whether or not the user completed the purchase.
