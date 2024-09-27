# imago-ad-illud
# OCR and AI-Powered Data Processing

This project demonstrates a pipeline for processing images using OCR (Optical Character Recognition) and leveraging generative AI for data interpretation.

## Project Structure

1. **Phase 1: OCR (Optical Character Recognition)**
   - Converts images to text using the pytesseract library.
   - Saves the extracted text to an output file.

2. **Phase 2: Generative AI Integration**
   - Uses OpenAI's API to analyze the OCR output.
   - Employs a language model (e.g., gpt-4o-mini, gemini-flash) to interpret the extracted text.
   - Provides insights and analysis based on the content of the image.

3. **Phase 3: Thematic Data Grouping (Not implemented yet)**
   - (Future development: Organizing extracted data into relevant themes or categories.)

## Dependencies

* `pytesseract`
* `Pillow` (PIL)
* `openai`
* `google-generativeai`
## Usage

1. Install the necessary dependencies.
2. Set up your OpenAI API key using `userdata.get('OPENAI_API_KEY')`.
3. Place the images you want to process in the same directory as the notebook.
4. Run the notebook to execute the OCR and AI processing.

## Note

- This project uses a lightweight language model to manage costs.
- Larger bodies of text may require more processing power and potentially higher API costs.
- Thematic data grouping functionality is planned for future development.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.
"""
