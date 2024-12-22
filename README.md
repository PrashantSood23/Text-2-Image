# Text-2-Image

Welcome to the **Text-to-Image Generation** project! This repository contains a Flask-based web application that uses Hugging Face's Stable Diffusion model to generate images from textual prompts. The application supports multilingual prompts and includes cross-origin compatibility for seamless integration.

---

## Features

- **Text-to-Image Generation**: Generate high-quality images based on textual prompts.
- **Multilingual Support**: Translates prompts into English using Google Translate for a broader audience.
- **Random Seed for Variations**: Ensures unique image outputs for similar prompts.
- **Cross-Origin Resource Sharing (CORS)**: Allows cross-origin API calls for easy integration.
- **Interactive Web Interface**: User-friendly interface to input prompts and view results instantly.

---

## Getting Started

Follow these steps to set up and run the application on your local machine:

### Prerequisites

- Python 3.8 or higher
- Flask
- Requests
- Googletrans==4.0.0-rc1
- PIL (Pillow)

Install the required Python packages:

```bash
pip install flask requests googletrans==4.0.0-rc1 pillow flask-cors
```

### Clone the Repository

```bash
git clone https://github.com/yourusername/text-to-image-generation.git
cd text-to-image-generation
```

### Set Up the Hugging Face API

1. Get your Hugging Face API token by signing up at [Hugging Face](https://huggingface.co/).
2. Replace `"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"` in the code with your token.

### Run the Application

```bash
python app.py
```

Open your browser and navigate to `http://127.0.0.1:5000` to access the application.

---

## Usage

1. Enter a text prompt in the input field (supports multiple languages).
2. Click the "Generate" button.
3. View the generated image directly on the webpage.
4. Optionally, use the "Share" button to share generated images.

---

## Project Structure

```plaintext
text-to-image-generation/
├── app.py               # Flask application code
├── templates/
│   └── index.html       # HTML template for the web interface
├── static/
│   └── style.css        # CSS for styling (if applicable)
└── README.md            # Project documentation
```

---

## Screenshots

[Screenshot 1](https://drive.google.com/file/d/1zxuKo6nSLf1zyblSKB3_VHFybN3xIi_J/view?usp=drive_link)
*Figure 1: Application interface showcasing text-to-image generation.*

[Screenshot 2](https://drive.google.com/file/d/1a3QET7BbkqaRHSEeqTY5_5_CJmnr6tat/view?usp=drive_link)
*Figure 2: Example of a generated image.*

---

## Future Enhancements

- Add user authentication for personalized experience.
- Implement image editing tools for generated images.
- Enhance multilingual support with more robust translation APIs.
- Include model fine-tuning capabilities for custom datasets.
- Deploy on cloud platforms like AWS or Google Cloud.

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with a descriptive message.
4. Push the changes to your fork.
5. Open a pull request in this repository.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Hugging Face for providing the Stable Diffusion model.
- Google Translate API for enabling multilingual support.
- Flask and its contributors for the robust web framework.

---

## Contact

If you have any questions, suggestions, or issues, feel free to open an issue in this repository or contact me directly at `piyushsood89@gmail.com`.

---

## References

- [Hugging Face API Documentation](https://huggingface.co/docs)
- [Flask Documentation](https://flask.palletsprojects.com/)
- [Googletrans Library](https://py-googletrans.readthedocs.io/)
- [Stable Diffusion](https://stability.ai/)

---

Thank you for checking out this project! I hope you find it useful and inspiring.
