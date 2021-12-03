# Using machine learning in PHP

## Intro
Machine learning (AI) is getting used more and more in enterprise environments (think: Google Search, self driving cars, face unlock for your smartphone). Big enterprises have had the means to employ teams of highly trained mathematicians and engineers to develop custom machine learning applications for quite a while. With projects like tensorflow or pytorch it's now possible for smaller companies and even hobbyists to discover machine learning as well. However until recently it wasn't really easy to implement machine learning applications with PHP.

The following sections compare some of the options you have when wanting to use machine learning in your PHP application:


## FuncAI PHP
Machine learning library that uses the tensorflow c library under the hood. [FuncAI PHP](https://php.funcai.net)

* Pros:
  * Relatively easy to integrate into your project
  * Free
  * Offers ready-made applications for you to use
  * Offers pipelines to train your own machine learning applications
* Cons:
  * Is hosted on your server
    * Contact us to discuss managed access to FuncAI PHP: `funcai [at] sopamo.de`

## PHP-ML
Machine learning algorithms implemented in PHP. [Website](https://github.com/jorgecasas/php-ml)

* Pros:
  * Very easy to integrate into your project
  * Free
  * Good for simple things like k-nearest-neighbour
* Cons:
  * Not suitable for complex use cases (big models)
  * No ready-made machine learning applications


## Hosted machine learning APIs
Some companies offer APIs to access machine learning applications. For example: [OpenAI API](https://openai.com/api/)

* Pros:
  * Relatively easy to integrate into your project
  * Offers ready-made applications for you to use
* Cons:
  * Expensive
  * Can't be hosted on your own server
    * For some applications that require low latency / handle a lot of data this is a no-go
    * Might be problematic for data-privacy reasons


## Conclusion

We are a bit biased of course, but we created FuncAI PHP because we wanted to make it as easy as possible to use machine learning in all PHP applications without having to send your data to external companies and without having to pay for an API. Visit our Github repo to get started today:

[https://github.com/funcai/funcai-php](https://github.com/funcai/funcai-php)

Alternatively you can check out our sample application which teaches you how to use FuncAI PHP to train your own image classifier! The sample trains a classifier which is able to differentiate between cats and dogs. It's very easy to use your own images though and create your own image classifier for your usecase:

[https://github.com/funcai/funcai-image-classification-sample](https://github.com/funcai/funcai-image-classification-sample)