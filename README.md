# Face recognition with Python, OpenCV, OpenAI CLIP model and PostgreSQL `pgvector`
Application of ML by training a model of facial recognition and then validating the model into testing and saving.

The below is the overall flow:

1. Take a starting picture
2. Detect as many faces as possible, if not all.
3. Calculate the embeddings on the faces.
4. Store in PostgreSQL in a vector column.
5. Get another picture for reference and detect face.
6. Caculate the embeddings here as well and use vector similarity to find other pictures.

this repo contains working code for the blog post here https://aiven.io/developer/find-faces-with-pgvector
