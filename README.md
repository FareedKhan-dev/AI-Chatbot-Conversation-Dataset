
## A Day in the life of an AI Chatbot

The original data contains 500k conversations, but this is just a sample. You can download the 10k dataset with personal and sensitive information removed.

On average, ChatGPT has more than 10 million conversations per day, more than the number of conversations a 70-year-old person has had in their whole life. Not only that, but people also ask personal questions, seek advice, and more from AI chatbots, which you will see later. These are questions they might not feel comfortable asking their family, friends, or others. Because of this vast amount of chat history data and personal conversations, it’s enough to measure the intelligence level of a person, group of people, or even a nation.

Although AI chatbots don’t have emotions or feelings, they just work on machines. However, the way people talk to them can tell us something. In this blog, we’ll see what it’s like for AI chatbots dealing with different kinds of people every day.

With a $100 gift from Anyscale, I decided to create an AI Chatbot. Using LLaMA-3–70B, which is one of the most powerful open-source LLMs available and works similarly to ChatGPT. I created a simple chatbot website on top of it so that people can easily interact with it. Behind that, I attached a database to store each user input and the Chatbot’s response to it. Using the same LLM, I tried to label each conversation with a tag, such as coding help, personal question, and more. I hosted the chatbot on Streamlit. The most important part is that I made it freely accessible on the internet without requiring login/signup or a paid plan.

Since no one knows about my AI Chatbot and I don’t have a marketing budget. So, I tried to use Reddit, HuggingFace, and Social networking sites to promote my free chatbot. Within 10 hours of release, I recorded 4K conversations, most probably because there are no extra steps to use it.

This is what a sample data looks like:

![Sample dataset](https://cdn-images-1.medium.com/max/4148/1*MoigCO2tbynOb-elb5TsIw.png)

I waited for two weeks to gather enough data to make some assumptions. Within that time, I was able to collect more than 50K conversations and had only spent $33. The very first thing I did was to analyze what people have used my AI Chatbot for.

![chat topics](https://cdn-images-1.medium.com/max/2000/1*xkLswoA9hUQth4tOL7ye8Q.png)

I was quite shocked to see that people are using it for inappropriate content. I thought LLaMA-3 was designed similarly to ChatGPT, where it wouldn’t generate harmful content, but it does. This makes me think that AI chatbots are really exploiting people’s mindsets, much like we’ve seen with social networking sites where people feel free to do anything because they believe they will remain anonymous. Additionally, **even though it is mentioned that data will be collected for analysis**, people still pass sensitive information without knowing who created the free chatbot or simply being careless about it. This is a crucial concern.

Some people are in such a hurry while solving their coding errors that they just paste the exact Python and JavaScript code into my chatbot. Not only that, but they also include their API keys for OpenAI and other companies providing LLM APIs.

![Sensitive data ](https://cdn-images-1.medium.com/max/2632/1*6VCwmRv3tiuTORi9svlHKw.png)

For a few days, my chatbot didn’t remember previous messages, treating each one as new. I realized this might be why people weren’t finding it useful. So, I updated it to remember past messages, and usage increased significantly.

![After Introducing chat history ability](https://cdn-images-1.medium.com/max/2000/1*adpfJzy6fcfnOYoykhmAaQ.png)

From this change, I realized that when creating a chatbot for any kind of business, it’s important to remember previous messages. This feature increases client interaction with your chat product, as it did for me.

More than 80% coding questions are related to JavaScript.

![Coding Analysis](https://cdn-images-1.medium.com/max/2000/1*6vxajROoADtgCO4O0wA6JQ.png)

The majority of users who use my chatbot to generate mature content find that LLaMA-3–70B often doesn’t prevent them from generating such responses.

![Avoiding bad content](https://cdn-images-1.medium.com/max/2000/1*LGsZjryF5m2KE_2Ux7wNmQ.png)

After English, Chinese is the most commonly used language for my chatbot.

![Most used language in my chatbot](https://cdn-images-1.medium.com/max/2000/1*EKTTXdnRA1bkOk2NSkSwZA.png)

Just like some people tried to jailbreak ChatGPT when it first came on the market, some tried the same with my bot, attempting to make it biased on political conflicts. However, LLaMA-3–70B is very good at avoiding such manipulations and, in most cases, responds with **“Sorry, but I couldn’t create or give opinions on that topic.”**

![avoiding conflicting scenarios](https://cdn-images-1.medium.com/max/2000/1*wiSg8pRpqCM2AnVuYlPM-w.png)

I thought there wouldn’t be much chat data to capture when creating another AI chatbot since many already exist. However, I received a good response within two weeks because I made it free and didn’t require account login.

![Growth Rate](https://cdn-images-1.medium.com/max/2000/1*DrZqIYkdxt-iH6wYZzw6jw.png)

I have taken down my original chatbot, but I have uploaded a part of it on Hugging Face Spaces to collect more data. If you’re interested in using a free LLaMA-3–70B bot, you can try it there. However, please avoid sharing personal information, as the data will be used for analysis.

HuggingFace Chatbot Link — [https://huggingface.co/spaces/FareedKhan/LLaMA-3-70B-Chatbot](https://huggingface.co/spaces/FareedKhan/LLaMA-3-70B-Chatbot)
