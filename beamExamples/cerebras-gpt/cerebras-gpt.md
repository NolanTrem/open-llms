# Cerebras-GPT deployment with Beam

[Cerebras-GPT](https://huggingface.co/cerebras/Cerebras-GPT-1.3B) can be deployed on Beam for development
on serverless GPUs. If you haven't already, be sure to [create an account
and follow installation instructions here](https://docs.beam.cloud/getting-started/quickstart).

## Deploying Cerebras-GPT-1.3B
This example is called through a webhook. Webhooks are used for deploying
functions that run asynchronously on Beam. Here, the webhook takes a prompt
as one of its input fields. An example prompt and the real response from the
model are given below.

Example prompt: Once upon a time

Example response: 
>>> Once upon a time, the world was a place of peace and prosperity. But the people of the land were not content with peace. They wanted to be free. The people were divided into two groups. The first group was the
