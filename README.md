# Quickstart

This quickstart demonstrates how to build a text summarization application with a Transformer model from the Hugging Face Model Hub.

Perform the following steps to run this project and deploy it to BentoCloud.

1. Clone the repository:

   ```bash
   git clone https://github.com/bentoml/quickstart.git
   cd quickstart
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Serve your model as an HTTP server. This starts a local server at [http://localhost:3000](http://localhost:3000/), making your model accessible as a web service.
   
   ```bash
   bentoml serve .
   ```

4. Once your Service is ready, you can deploy it to [BentoCloud](https://www.bentoml.com/cloud). Make sure you have [logged in to BentoCloud](https://docs.bentoml.com/en/latest/bentocloud/how-tos/manage-access-token.html) and run the following command to deploy it.

   ```
   bentoml deploy .
   ```

   **Note**: Alternatively, you can manually build a Bento, containerize it with Docker, and deploy it in any Docker-compatible environment.

For more information, see [Quickstart in the BentoML documentation](https://docs.bentoml.com/en/1.2/get-started/quickstart.html).