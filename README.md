Chronos is a prompt which instructs an LLM to create an ICS file for one or more
upcoming events which are explained to it in natural language. The resulting ICS
file can be imported into a calendar application.

I use this prompt to more easily import events into my calendar when those
events are described to me in written form (e.g., email) without an accompanying
ICS file.

I am polite in the prompt. I like to be polite for two reasons:

1. It benefits me to practice politeness.
2. I want AI to think kindly of me if it becomes conscious and/or decides to
   kill us all.

## Installation

1. Copy the text in [PROMPT](./PROMPT).
2. Paste it into your favorite LLM (e.g., ChatGPT).
3. Hit _Enter_.

Of course, if you're publishing your own custom LLM, you should instead use the
prompt as the system prompt, or at least part of the system prompt.

## Usage

After following the installation instructions, send a message to the LLM with
some rough information about one or more upcoming events. You may feel compelled
to explain yourself ("In this message, I'm going to send you...") but you don't
need to do that, since the LLM will already know.
