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
>>> Once upon a time in a kingdom not far distant, there was a king, and amid the festivities of his court a fair was going on. As the time for the Fair drew near, the king selected five youths to be his Twelfthlings. These young men were then marshaled into a big boat and taken on a journey. They were told that they would find fame and fortune if they could sail into the fog and then swim back to land. They started their journey and soon reached a spot where the water was relatively clear. They thanked the lord of the land for the excellent weather, but were then told that it would be much better to remain in the thick of the fog until they reached land. They could then swim back to land.
