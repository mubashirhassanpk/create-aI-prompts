# Generate better prompts in the developer console
https://www.anthropic.com/news/prompt-generator

😒 The 3 Major Problems with Creating AI Prompts

When it comes to creating prompts using ChatGPT, Claude, or any large language model, we're going to come across three major problems:

1. Staring at a blank page or just a blank prompt box. This is time-wasting.
2. Time-consuming tweaking.
3. Inconsistent results that waste your time and energy.

## Solution #1: Using Anthropic's Console

Our first solution for creating amazing prompts uses Anthropic's console and built-in AI prompt generator. Here's how:

1. Visit console.anthropic.com
2. Sign up for a free account
3. Find the "Generate a prompt" option
4. Describe what you want and provide context to Claude
5. Let it spit out an optimized prompt for you

## Practical Example

For this example, I will create a prompt for YouTube content creation. Here's what I entered:

Create a prompt that summarizes my YouTube videos and then generates completely new video ideas with a unique angle on that topic. The purpose of this is to continue creating content around that topic since it performed really well. The result should be YouTube video titles built on different things, such as curiosity, pain points, authority, SEO, and outlier ideas. Provide as many ideas in a table format as possible.

👏 Understanding Variables

One thing that's really important to understand is that Anthropic uses variables. These are just placeholders that make your prompt flexible and reusable for any use case, so you can use this with any other tool like Convergence AI, ChatGPT's thinking model, or Grok.

🧪 Testing the Prompt

Using one of my popular videos, I tested this prompt across Claude, ChatGPT, and Grok ("The Faster Way to Create Online Courses with AI"). I grabbed the video transcript using Tactic.io and plugged it into the variable section of each LLM.

The results were amazing! Here are some of the title ideas Claude generated:

Curiosity title: "I made 10k from a 60-minute AI course: Step-by-step process."
SEO title: "How to create a course sales page in 30 minutes using AI."
Authority title: "I tested five AI course platforms. Here's what actually works."
Outlier idea: "Why long courses fail and how AI creates better short courses."

## Refining Your Prompts

If you're unhappy with the initial results, click "Improve prompt" in Anthropic's console and provide more detailed feedback.

For my example, I added these refinements:

I did not like some of the ideas we got back, and I want to make sure that we primarily focus on Curiosity and SEO. The output should also come back to 40-50 ideas, and each idea should be less than 60 characters.

Claude then created a refined prompt that generated 45 video ideas, including:

"Five AI tools that create course outlines in minutes" (SEO-driven)
"Create a $997 mini-course this weekend with AI" (Curiosity)
"How I made 10k with a 60-minute AI-generated course."
"Seven-course marketing emails that AI writes better than you."

## Solution #2: Meta Prompting

Another powerful method is using meta prompting directly within the AI tool itself.
