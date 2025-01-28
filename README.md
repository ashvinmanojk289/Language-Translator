# Text Translation using Hugging Face and Google Translate

This repository demonstrates two methods for translating text between languages:
1. Using the Hugging Face MarianMT model.
2. Using the Google Translate API.

## Features

- **Hugging Face MarianMT**: Leverages the `transformers` library to translate text using pre-trained models from Helsinki-NLP.
- **Google Translate API**: Utilizes the `googletrans` library to perform translations through the Google Translate API.

## Requirements

The following Python libraries are required:

- `transformers`
- `torch`
- `googletrans==4.0.0-rc1`

You can install these libraries using the following command:

```bash
pip install transformers torch googletrans==4.0.0-rc1
```

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/text-translation.git
   cd text-translation
   ```

2. Run the script:

   ```bash
   python translate.py
   ```

3. Follow the prompts:
   - Enter the text you want to translate.
   - Specify the source language code (e.g., `en` for English).
   - Specify the target language code (e.g., `es` for Spanish).

4. The program will display translations using both methods:
   - Hugging Face MarianMT
   - Google Translate API

## Sample Output

Example input:
```
Enter a sentence to translate: Hello, how are you?
Enter the source language code (e.g., 'en' for English, 'es' for Spanish): en
Enter the target language code (e.g., 'es' for Spanish, 'fr' for French): es
```

Example output:
```
--- Translation using Hugging Face MarianMT ---
Original Text: Hello, how are you?
Translated Text (Hugging Face): Hola, ¿cómo estás?

--- Translation using Google Translate API ---
Original Text: Hello, how are you?
Translated Text (Google Translate): Hola, ¿cómo estás?
```

## Customization

- **Languages**: Update the `src_lang` and `tgt_lang` parameters to support different language pairs.
- **Model**: Use other pre-trained models from Helsinki-NLP for specific language pairs.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, feel free to open an issue or submit a pull request.

## Contact

For questions or feedback, please reach out to [your email address] or open an issue in this repository.

---

Thank you for exploring this text translation project! Happy coding!

