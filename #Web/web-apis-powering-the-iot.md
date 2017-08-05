# Web APIs: Powering the IoT

_Captured: 2017-05-03 at 23:43 from [dzone.com](https://dzone.com/articles/web-apis-powering-the-iot-1?edition=294992&utm_source=Daily%20Digest&utm_medium=email&utm_campaign=dd%202017-05-03)_

The Internet of Things keeps rolling along. The latest estimates say the [IoT market will reach ](http://www.zdnet.com/article/internet-of-things-market-to-hit-7-1-trillion-by-2020-idc/)[$7.1 trillion by 2020](http://www.zdnet.com/article/internet-of-things-market-to-hit-7-1-trillion-by-2020-idc/), with [50 billion devices connected to the Internet](http://www.smartgridnews.com/story/50-billion-connected-iot-devices-2020/2015-04-21) and each person in the world projected to have [6 devices](http://www.wired.com/insights/2014/07/internet-things-will-disrupt-everything/) connected to the web.

And Cisco's new Global Cloud Index study predicts that by 2018 the data generated by [IoT devices will total ](http://www.theguardian.com/technology/blog/2011/jun/29/zettabyte-data-internet-cisco)[403 zettabytes every year](http://www.theguardian.com/technology/blog/2011/jun/29/zettabyte-data-internet-cisco) (1 zettabyte is approximately equal to a billion terabytes). That is a staggering amount of data.

But here's the reality: all the millions of applications available to billions of endpoints would be absolutely useless without APIs.

APIs drive the IoT as we know it. They are its backbone, the bridge between all those devices connected to the cloud. They turn millions of devices from useless into useful, transforming very limited devices into powerful information portals by exposing data.

With that in mind, let's take a look at the importance of APIs to you as developers, as well as some strategies for using APIs.

![Web-APIs](http://www.golgi.io/wp-content/uploads/2015/10/Web-APIs.png)

### **A Web API Primer**

First, we need to level set: when we talk about APIs and the IoT, we're really talking about _web APIs_ specifically. A web API is a framework for building HTTP services designed to be consumed by a wide range of client devices, such as browsers, phones, and tablets. Web API refers to the suite of device compatibility and access APIs that enable web apps and content to access device hardware and also access the data stored on devices.

At a very high level, web APIs are simply libraries of functions that transmit data from one device to another - typically a back-end server. In the IoT world, web APIs are especially useful because they are a very well-established communication language that's already widely used in web and mobile services development.

### **Making Your Development Easier - and Faster**

Web APIs are more than just effective ways of transmitting data: they're actually feature-rich tools that can help you significantly reduce your development time. They provide you with a large amount of functionality you wouldn't normally have.

The [Twilio](https://www.twilio.com/) API service is a great example of that functionality. When you use Twilio web APIs, you can easily enable an IoT device to communicate with users via SMS without needing to build all the infrastructure and integrate with a network operator. Instead, you simply call the Twilio SMS API from your application and boom! You can enable the functionality in only a few lines of code. Of course, the reduction in development time will depend on how much functionality you're trying to build out. But generally speaking, using a web API can dramatically reduce your effort.

### **Security and Scalability: API Must-Haves**

It goes without saying that the web APIs you use need to be secure. When you use a third-party API as part of your IoT application, you are exposing your users' data to others. So if the APIs you're utilizing lack good data security, they could become sabotaged. That danger is magnified in the IoT world, because of all the potential risks to different devices people use. As an example, if an automaker's API gets hacked, your car could actually be remotely locked or unlocked - and you wouldn't be able to stop it.

If possible, you should use APIs that have been through stringent security vulnerability testing. There are a few widely used security frameworks for securing web APIs, such as the [OAuth 2.0](http://oauth.net/2/) specification and the [OpenID authentication layer](http://openid.net/), that can help. But still, you should always proceed with caution. There are many open source OAuth 2.0 libraries out there, and you don't want to choose one until you are fully up to speed on its security capabilities.

Scalability is also an essential part of using web APIs. If your third-party API works well for the first 10,000 devices you ship, it also needs to scale so that it operates just as efficiently when you have 10 _million_ devices accessing that API. With an easily scalable web API, you'll be well on your way to meeting that goal.

### **Good Documentation Equals a Better API**

One more important point: you'll want to be sure to use only well-documented web APIs. From the API provider's point of view, having a thoroughly documented API basically guarantees that people will use it. And from your perspective as a developer, having in-depth documentation means that you can get into the API quickly, use the right calls in the right situations, and do things as smoothly and efficiently as possible.

On the flip side, if you're using a poorly documented API, you're more likely to experiment and try to figure things out on your own. That's not a good strategy when you're working on something as critical as IoT connectivity and compatibility!

At the end of the day, a good web API is one of the most important pieces of a successful IoT application. It not only can simplify your development but it can also ensure stronger security and scalability.

Keep in mind, though, that you will also need to have an effective web API management strategy in place.