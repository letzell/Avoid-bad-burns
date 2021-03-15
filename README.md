# Avoid bad burns

Predicts whether you will get a sun burn based on age, skin type, time spent in sun and UV-index
Final project for the Building AI course.

## Summary

The aim of this project is to be able to predict whether a person will get a bad sun burn, based on parameters such as UV-index, time spent in the sun, skin type, age and potenially SPF. The algorithm will eventually be able to give recommendations on how much time you can spend in the sun, or which SPF you should use. 

## Background

Most people have experienced sun burns. One could say that they are a part of life. Naturally, everyone is affected differently by the sun as we all have different skin types, different experience in exposure and so on. It can be very hard as an individual to know just how much time in the sun you can take, especially since the weather is constantly changing. My idea will help people to avoid sun burns, by giving advice on how much time they can spend in the sun. The goal is to make it simple and easy to enjoy the sun, and at the same time stay safe. Personally, I have experienced several bad sun burns that could have been avoided if I had known more about which SPF I should use or for how long I could stay in the sun. Sun burns is also a very important topic, as too much exposure to dangerous UV-light can cause skin cancer. Hopefully, this idea will also contribute to decrease the amount of skin cancer cases. 

## How is it used?

My idea is that the AI-algorithm will be part of an app that will be available for everyone who can download apps. If you submit your skin type and age, the app will take them as well as weather conditions (UV-index) into consideration and present a recommendation for how you should behave in the sun. Potentially, this could be developed using a timer that goes off when you've been in the sun for enough time. Anyone who spends time in the sun can use this solution. This idea will be particularly important in the summer months when people spend time at the beach, stay outdoors or work in the gardens, to give a few examples. Both people enjoying their free time as well as people who work outdoors could benefit. 

![Sunscreen](https://upload.wikimedia.org/wikipedia/commons/thumb/6/60/Sunscreen_on_back_under_normal_and_UV_light.jpg/320px-Sunscreen_on_back_under_normal_and_UV_light.jpg)


## Data sources and AI methods
This project will of course rely on data regarding the given parameters UV-index, time spent in the sun, skin type, age, SPF and how they are connected to if you get a bad burn or not. In Sweden, the Swedish Radiation Safety Agency yearly collects information regarding the Swedes habits in the sun. This is a potenital source of data. Some of the data needed will also be easier to collect than others. For example, how people use SPF might be hard to find and therefore this function could be added later. There is also an idea that if we can start this project, we will be able to collect information about our users to further improve the algorithm and its accuracy. Since sun burns are a matter of health, it is not an alternative to perform experiements to get data, as we do not want to risk anyone's health. 

There are several potential AI techniqes that could be used here. If we simply want to classify a case as sunburned or not sunburned, logistic regression is probably the most suitable. However, we might want to develop the algorithm further to have even more classes. Perhaps, "not sunburned", "tanned", "about to get bad" and "dangerous". In that case, a neural network that can handle several classes might be more sufficient. If we only want the perspective of how long much time a person can spend in the sun without getting burned, linear regression will do. 

## Challenges

Even if this project does succeed, it will still be up to each and every individual to follow the advice. The project does not automatically remove sunburns as a health issue. We must also accept that the algorithm may never be perfect, but almost. Even though we will do our utmost to have an accuracy rate as high as possible, the algorithm can not guarantee that you will never get burnt. This is something that potential users must understand. As previously mentioned, their may also be ethical considerations regarding the collection of data. We can not expect people to risk their lives in the sun, by staying out for too long or not using SPF. That kind of data must be collected in other ways, perhaps from previous research. 

## What next?

This project has endless potential. As it is an app, lots of other functions that are useful for us who want to enjoy the sun in a safe way could be added. For example, there could be a second timer function that tells you how long you should spend on each side of you (front and back). As mentioned earlier, the function regarding SPF recommendations might not be available from start, but it is definitely a way that we could develop the project. There might also other parameters that could be added to give an even more extensive prediction.

In order to get this project started, I would probably need assistance form someone who is slightly more experienced in programming and AI than I. I have a few ideas regarding the algorithm, but I would also need knowledge about building an app, what to think about and so on. Most importantly, I would need a good way of accessing more data, depending on how much could be found out from the Swedish Radiation Safety Agency. 

## Acknowledgments

This is my final project from the Building AI course, which has inspired me a lot. I would also like to thank my supervisor Karl Gafvert who have given me a lot of advice, inspiration and taught me more about AI and programming. 
