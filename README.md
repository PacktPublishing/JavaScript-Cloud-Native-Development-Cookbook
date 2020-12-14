## $5 Tech Unlocked 2021!
[Buy and download this Book for only $5 on PacktPub.com](https://www.packtpub.com/product/javascript-cloud-native-development-cookbook/9781788470414)
-----
*If you have read this book, please leave a review on [Amazon.com](https://www.amazon.com/gp/product/1788470419).     Potential readers can then use your unbiased opinion to help them make purchase decisions. Thank you. The $5 campaign         runs from __December 15th 2020__ to __January 13th 2021.__*

# JavaScript Cloud Native Development Cookbook

<a href="https://www.packtpub.com/application-development/javascript-cloud-native-development-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781788470414 "> <img src="https://d1ldz4te4covpm.cloudfront.net/sites/default/files/imagecache/ppv4_main_book_cover/B08809.png" alt="JavaScript Cloud Native Development Cookbook" height="256px" align="right"></a>

This is the code repository for [JavaScript Cloud Native Development Cookbook](https://www.packtpub.com/application-development/javascript-cloud-native-development-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781789133806), published by Packt.

**Deliver serverless cloud-native solutions on AWS, Azure, and GCP**

## What is this book about?
Cloud-native development is a modern approach to building and running applications that leverage the merits of the cloud computing model. With cloud-native development, teams can deliver faster and in a more lean and agile way than traditional approaches. This recipe-based guide provides you quick solutions for your cloud-native applications.
This book covers the following exciting features:
* Implement patterns such as Event Streaming, CQRS, and Event Sourcing
* Deploy multi-regional, multi-master solutions
* Secure your cloud-native services with OAuth and OpenID Connect
* Create a robust cloud-native continuous deployment pipeline
* Run services on AWS, Azure, and GCP
* Implement autonomous services to limit the impact of failures
If you feel this book is for you, get your [copy](https://www.amazon.com/dp/B0787DF1FH) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
module.exports.hello = (event, context, callback) => {
  console.log('event: %j', event);
  console.log('env: %j', process.env);
  callback(null, 'success');
};
```

**Following is what you need for this book:**
To follow along with the recipes in this cookbook, you will need to configure your
development environment according to these steps:
  1. Install Node Version Manager (https://github.com/creationix/nvm or https://github.com/coreybutler/nvm-windows)
  2. Install Node.js with nvm install 8
  3. Install the Serverless Framework with npm install serverless -g
  4. Create a MY_STAGE environment variable with export MY_STAGE=<yourname>
  5. Create an AWS account (https://aws.amazon.com/free) and configure your credentials for the Serverless Framework (https://serverless.com/framework/docs/providers/aws/guide/credentials)

With the following software and hardware list you can run all code files present in the book.
### Software and Hardware List
| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1-11     | NVM                                 | Windows, macOS, and Linux (Any)    |
| 1-11     | Serverless Framework                | Windows, macOS, and Linux (Any)    |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://www.packtpub.com/sites/default/files/downloads/9781788470414_ColorImages.pdf).

### Related products
* Cloud Native Development Patterns and Best Practices [[Packt]](https://www.packtpub.com/application-development/cloud-native-development-patterns-and-best-practices?utm_source=github&utm_medium=repository&utm_campaign=9781788473927 ) [[Amazon]](https://www.amazon.com/dp/1788473922)

* Cloud Native Python [[Packt]](https://www.packtpub.com/application-development/cloud-native-python?utm_source=github&utm_medium=repository&utm_campaign=9781787129313 ) [[Amazon]](https://www.amazon.com/dp/1787129314)


## Get to Know the Author
**John Gilbert**
is a CTO with over 25 years of experience of architecting and delivering
distributed, event-driven systems. His cloud journey started more than five years ago and
has spanned all the levels of cloud maturity—through lift and shift, software-defined
infrastructure, microservices, and continuous deployment. He is the author of Cloud Native
Development Patterns and Best Practices. He finds delivering cloud-native solutions to be by
far the most fun and satisfying, as they force us to rewire how we reason about systems and
enable us to accomplish far more with much less effort.

## Other books by the authors
[Cloud Native Development Patterns and Best Practices](https://www.packtpub.com/application-development/cloud-native-development-patterns-and-best-practices?utm_source=github&utm_medium=repository&utm_campaign=9781788473927 )


### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.
