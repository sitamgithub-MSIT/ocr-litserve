# OCR LitServe

[![Open In Studio](https://pl-bolts-doc-images.s3.us-east-2.amazonaws.com/app-2/studio-badge.svg)](https://lightning.ai/sitammeur/studios/deploy-tangoflux-audio-generation-model)

GOT-OCR2 is a versatile OCR model handling various document types, including tables, charts, and formulas. It outputs plain text, but further processing enables formatted output. Interactive OCR with region specification is also supported. This project shows how to create a self-hosted, private API that deploys [optical character recognition model](https://huggingface.co/stepfun-ai/GOT-OCR-2.0-hf) with LitServe, an easy-to-use, flexible serving engine for AI models built on FastAPI.

## Project Structure

The project is structured as follows:

- `server.py`: The file containing the main code for the web server.
- `client.py`: The file containing the code for client-side requests.
- `LICENSE`: The license file for the project.
- `README.md`: The README file that contains information about the project.
- `images`: The folder containing test images for the OCR model.
- `assets`: The folder containing screenshots for working on the application.
- `.gitignore`: The file containing the list of files and directories to be ignored by Git.

## Tech Stack

- Python (for the programming language)
- PyTorch (for the deep learning framework)
- Hugging Face Transformers Library (for the model)
- LitServe (for the serving engine)

## Getting Started

To get started with this project, follow the steps below:

1. Run the server: `python server.py`
2. Upon running the server successfully, you will see uvicorn running on port 8000.
3. Open a new terminal window.
4. Run the client: `python client.py`

Now, you can see the model's output based on the input request. The model will generate OCR output for the input image.

## Usage

The project can be used to serve the GOT-OCR2.0 model using LitServe. It allows you to input an image and receive the OCR output, suggesting potential use cases in the real world, such as document scanning, text extraction, and more.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please raise an issue to discuss the changes you want to make. Once the changes are approved, you can create a pull request.

## License

This project is licensed under the [Apache-2.0 License](LICENSE).

## Contact

If you have any questions or suggestions about the project, please contact me on my GitHub profile.

Happy coding! 🚀
