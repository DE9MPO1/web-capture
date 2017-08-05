# Not Everything That Can Be Counted Counts

_Captured: 2016-03-23 at 15:47 from [medium.com](https://medium.com/seek-product-management/not-everything-that-can-be-counted-counts-72ccc439d8d1)_

In the previous article [If you're not keeping score, you're only practising](https://medium.com/seek-product-management/if-you-re-not-keeping-score-you-re-only-practising-7d1c1e839998), we discussed why proper measurement and evaluation are important to search and online products in general. Without measurement, we will have no visibility over the performance of our products or the new features that we plan to roll out. Evaluation, which often takes the form of A/B testing, enables businesses to systematically introduce changes to their online products that they are confident will improve customer outcomes.

In this article, we look at the danger of taking Web metrics such as visits, pageviews, etc at face value. To illustrate, we will discuss two scenarios involving typical online products and in particular, our experience in testing search products. We want to highlight the importance of (1) thinking through what the success of each test looks like and turn them into a series of questions, (2) figuring out the appropriate metrics to help you answer those questions, and (3) tracking the right data for the metrics.

![](https://cdn-images-1.medium.com/max/800/1*fZYVNAVLu43Wxe5XsXOpZQ.jpeg)

#### **Why this fuss over proper testing?**

One of the common mistakes that product development teams make when they test the features of their products is to default to _vanity metrics_ and the approach of tracking everything and hope that something moves in the right direction. This way of testing not only lacks rigour but can potentially damage the experience we are supposedly improving.

> "A/B testing is all the rage in online marketing now, but you could be doing it all wrong. And the results of a poor test can do more harm than good, experts say. [[1](http://qz.com/181582/bad-ab-testing-is-worse-than-none-at-all/)]"

Vanity metrics are "_numbers that indicate improvement but is disconnected from the progress of your organization's mission_" [[2](https://litmus.com/blog/focusing-on-useful-analytics-vanity-metrics-vs-actionable-metrics)]. We are not suggesting that vanity metrics are all bad. Visits, registered users, page views, time on site, etc do provide us with indication that something is working. Sometimes, the focus on just these metrics might be warranted. For example in the case of start-ups, the mission might just be to initially fill the conversion funnel with more traffic. However, that is where it ends.

In the long run, no one ever builds any online products for the sake of just attracting more visits. We should always design proper tests and choose the right metrics and align them to the goal of improving customer experience and financial results. Often this requires the metrics to reflect the activities further down the funnel.

#### **Missing the point altogether**

Consider a case study here. A team is looking to improve conversion by encouraging registered users to return to the e-commerce site. There is an existing feature that the users can click on to explicitly request email alerts on activities about certain products of interest. For instance, how many other users have searched for these items, viewed them and purchased them. On average, this existing feature sends out about 400,000 emails a day, and a whopping 73% of them are clicked through. About 1 in 10 registered users get an email per day. Based on this, the team thought that one way to encourage the users to return and convert is to have more of them receiving emails. They decided to trial a new feature which pushes the email out to users automatically based on what they have viewed. After 3 weeks of monitoring, the number of users receiving the email alerts increased to 6 in 10, a 500% increase! The team celebrated and considered that initiative a success. Can you see what is missing here? What has the product team missed to monitor and report on?

In another scenario, a team is testing a new search interface for a small online book store with the help of some off-the-shelf analytics tool. After two weeks, the team went back to the tool and had a look at some of the default metrics and saw that the pageviews and time on site increased by 134% and 291%, respectively. The conversion rate remained steady and return visits dropped but only by 2.5%. Looking at the huge increase in the 'site engagement' metrics, it appears that the new interface has done its job. The team announced the initiative a success. In this case, do you think it was the right decision to switch over to the new experience?

#### **Going back to the customer outcomes**

In both the scenarios, the product development teams took the vanity metrics too literally. Simply concluding a test based on just one or two metrics that look best in isolation is reckless.

In the first one, the team was distracted by the increase in the number of emails sent. Instead, they should have stuck to the customer outcome that they expect to improve and focus on the clickthroughs and more importantly, the conversion. The 500% increase in emails sent is definitely not a success if the clickthroughs are not converting. On the contrary, the additional emails that the users did not explicitly ask for may constitute spam. This could very well have created the opposite effect, where the users are turned off from ever coming back to the site, let alone converting. Hence, especially with vanity metrics, more is not always better.

> "Spam is email that people do not want, period. There aren't really grey areas here. Of course, you should only be emailing people who have explicitly requested your emails but take that a step further: You should only be sending emails that improve the lives of the recipients" [[3](http://blog.linkbird.com/en/content-marketing/lead-generation-via-email-marketing/)].

In the second case, the team called the test too soon, combined with the focus on just the metrics that look good (and as long as the others are not worse off). The team might have just rolled out an experience that will see the eventual decline of a far more important metric: the conversion on the site. Getting to the bottom of any movement in vanity metrics like pageviews and time on site is close to impossible. Users might be clicking through more because the contents are good or they are simply struggling to find what they want. In fact, we might look at this as the calm before the storm. Loyal customers are beginning to show signs of struggling to find the items they want using the new interface and hence, the rise in pageviews and time on site during the two weeks. The nature of loyalty means that these existing customers will persist for a short period of time before the activities on site start to drop. This theory becomes more plausible when we look at the simultanous decrease in return visits during the same period. The product team should have extended the testing period and focus on the metrics which really matter to the business such as conversion.

> "…tie the data points you measure to the product vision and the product's key performance indicators (KPIs). [[4](http://www.mindtheproduct.com/2013/02/everything-a-product-manager-needs-to-know-about-analytics/)]"

#### **SEEK's focus on customer outcomes in testing**

At SEEK, we ensure that the initiatives we undertake are always aligned with the best customer outcomes. In particular, in the Search team, we have a best-of-breed measurement and evaluation framework [[5](https://medium.com/seek-product-management/if-you-re-not-keeping-score-you-re-only-practising-7d1c1e839998)] that helps us test our relevance improvement initiatives.

All our testing is hypothesis-driven where we are clear on what success looks like. Any deviation from that means the initiative is not delivering on the intended uplift. Under such circumstance, it is in the best interest of our customers and the business as a whole that we either drop or revisit the initiative by applying what we have learnt.

Typically, our hypotheses are formed around the effort and gain aspects of search experience. We want to reduce the amount of effort that users have to go through to achieve the maximum gain from our search products. What this means for candidates is to be able to find all jobs which are very relevant to their experience early on in the search result page rather than having to browse to the 20th page.

All our initiatives go through two stages of relevance testing. Initially, we use our internal relevance testing tool based on manual assessment (called GLASS). We want to make sure that the new relevance model is more likely to return only job ads or profiles relevant to the query and the super relevant ones are ranked higher up. Often, the hypothesis is that the improvement in perceived relevance should translate to more jobs being applied for and more profiles that hirers connect with.

During the testing, we use metrics to compare if the users are indeed applying for (more) jobs and connecting with (more) profiles higher up in the search results in the control group versus the group receiving the new relevance model. We use a tool called STEEL to achieve this. Note that more does not always mean better. If a candidate is able to find one or two highly applicable jobs quickly that he or she can apply for, that is a big win. Contrast this to a candidate who has to apply for 20 or more loosely relevant jobs over multiple searches.

The search specific metrics we use for our testing such as MAP and NDCG have been tuned to reflect the activities further down the funnel. These metrics enable us to align our relevance testing to what we consider as successful customer outcomes. Using vanity Web metrics such as visits and pageviews will not tell us what we need to know from our testing. Is an algorithm with more visits better than another with lower visits? Does pageviews or even the standard conversion rate tell us if candidates are applying for jobs higher up in the search result page?

#### **Conclusion**

Measurement and evaluation are the bread and butter of what we do in the Search team at SEEK. Ultimately, we want to reduce the friction that slows down or prevents candidates from connecting with hirers and vice versa. We have many ideas in place that we believe will help us achieve that goal. However, unless we carry out proper testing and use the right metrics, we can never be certain that these ideas will deliver the intended uplifts. This means that the metrics have to reflect the activities that happen further down the job seeking or vacancy filling funnels such as job applications instead of superficial metrics such as visits. We are not afraid of taking bold steps or risks when it comes to exploring ways to improve customer outcomes. However, they have to be calculated. Our rigorous testing platform makes sure of that.