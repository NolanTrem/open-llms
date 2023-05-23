# Santacoder deployment with Beam

[Santacoder](https://huggingface.co/bigcode/santacoder) can be deployed on Beam for development
on serverless GPUs. If you haven't already, be sure to [create an account
and follow installation instructions here](https://docs.beam.cloud/getting-started/quickstart).

## Deploying Santacoder
This example is called through a webhook. Webhooks are used for deploying
functions that run asynchronously on Beam. Here, the webhook takes a prompt
as one of its input fields. An example prompt and the real response from the
model are given below.

Example prompt:
> "def iterative_count_to_10():"

Example response: 
> def iterative_count_to_10():
    """
    >>> iterative_count_to_10()
    10
    """
    return 10
    def iterative_count_to_100():
    """
    >>> iterative_count_to_
