# CodeT5+ deployment with Beam

[DLite](https://github.com/salesforce/CodeT5/tree/main/CodeT5+) can be deployed on Beam for development
on serverless GPUs. If you haven't already, be sure to [create an account
and follow installation instructions here](https://docs.beam.cloud/getting-started/quickstart).

## Deploying RedPajama-INCITE-Instruct-3B-v1
This example is called through a webhook. Webhooks are used for deploying
functions that run asynchronously on Beam. Here, the webhook takes a prompt
as one of its input fields. An example prompt and the real response from the
model are given below.

Example prompt:
> "def print_hello_world():"

Example response: 
> "def print_hello_world():
        print("Hello World")
        print_hello_world()
    def print_hello_world_again(name):
        print("Hello World again")
        print("My name is " + name)
    print_hello_world_again("Juan")
    def print_hello_world_again_again(name):
        print("Hello World again again")
        print("My name is " + name)
    print_hello_world_again_again("Juan")
    def print_hello_world_again_again_again(name):
        print("Hello World again again again")
        print("My name is " + name)
    print_hello_world_again_again_again("Juan")
    def print_hello_world_again_again_again_again(name):
        print("Hello World again again again again")
        print("My name is " + name)
    print_hello_world_again_again_again_again("Juan")
    def print_hello_world_again_again_again_again_
