# RedPajama-INCITE-Instruct deployment with Beam

[DLite](https://huggingface.co/togethercomputer/RedPajama-INCITE-Instruct-3B-v1) can be deployed on Beam for development
on serverless GPUs. If you haven't already, be sure to [create an account
and follow installation instructions here](https://docs.beam.cloud/getting-started/quickstart).

## Deploying RedPajama-INCITE-Instruct-3B-v1
This example is called through a webhook. Webhooks are used for deploying
functions that run asynchronously on Beam. Here, the webhook takes a prompt
as one of its input fields. An example prompt and the real response from the
model are given below.

Example prompt:
> The capital of France is

Example response: 
>  of Environmental Conservation to Provide $3.5 Million to Fund Restoration of New York’s High Peaks
New York State Department of Environmental Conservation to Provide $3.5 Million to Fund Restoration of New York’s High Peaks
The New York State Department of Environmental Conservation (DEC) announced today that it will provide $3.5 million to fund the restoration of the High Peaks region of the Adirondack Park. The funding is part of the $30 million that DEC has committed to restore and improve the Adirondack Park’s High
