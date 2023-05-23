# DLite deployment with Beam

[DLite](https://huggingface.co/aisquared/dlite-v2-1_5b) can be deployed on Beam for development
on serverless GPUs. If you haven't already, be sure to [create an account
and follow installation instructions here](https://docs.beam.cloud/getting-started/quickstart).

## Deploying DLite-v2-1.5B
This example is called through a webhook. Webhooks are used for deploying
functions that run asynchronously on Beam. Here, the webhook takes a prompt
as one of its input fields. An example prompt and the real response from the
model are given below.

Example prompt:
> Once upon a time

Example response: 
>>> Once upon a time
