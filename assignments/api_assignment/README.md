# CS 335 — Assignment 01: Working with AI & ML APIs
**Northeastern Illinois University — Introduction to Artificial Intelligence**  
Iris Antunez

API key used was from Huggingface:
https://api-inference.huggingface.co/models/gpt2

Below is my output from my starter.py once modified.

==================================================
CALL 1 — GET Request
==================================================
{
  "_id": "621ffdc036468d709f17434d",
  "id": "openai-community/gpt2",
  "private": false,
  "pipeline_tag": "text-generation",
  "library_name": "transformers",
  "tags": [
    "transformers",
    "pytorch",
    "tf",
    "jax",
    "tflite",
    "rust",
    "onnx",
    "safetensors",
    "gpt2",
    "text-generation",
    "exbert",
    "en",
    "doi:10.57967/hf/0039",
    "license:mit",
    "text-generation-inference",
    "endpoints_compatible",
    "deploy:azure",
    "region:us"
  ],
  "downloads": 15304081,
  "likes": 3223,
  "modelId": "openai-community/gpt2",
  "author": "openai-community",
  "sha": "607a30d783dfa663caf39e06633721c8d4cfcd7e",
  "lastModified": "2024-02-19T10:57:45.000Z",
  "gated": false,
  "disabled": false,
  "widgetData": [
    {
      "text": "My name is Julien and I like to"
    },
    {
      "text": "I like traveling by train because"
    },
    {
      "text": "Paris is an amazing place to visit,"
    },
    {
      "text": "Once upon a time,"
    }
 

==================================================
CALL 2 — POST Request
==================================================
[ERROR] 404: <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>Error</title>
</head>
<body>
<pre>Cannot POST /models/gpt2</pre>
</body>
</html>


==================================================
CALL 3 — Parameterized  |  input: 'Explain supervised learning in one sentence.'
==================================================
[ERROR] 404: <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>Error</title>
</head>
<body>
<pre>Cannot POST /models/gpt2</pre>
</body>
</html>
