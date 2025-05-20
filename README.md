# Rolm OCR Streamlit app - WIP

Streamlit app to perform OCR using RolmOCR model.

Note:- uses the RolmOCR model from reducto/RolmOCR. 

The app currently produces outputs in Text format. 

## Setup
### Clone the repository
git clone git@github.com:ananyalahiri2003/RolmOCR-streamlit.git

cd src


### Install dependencies

`poetry lock --no-update`

`poetry install`

All dependencies in pyproject.toml file.


### Create .env
Under src/ create `.env` file with

HF_TOKEN={your_hf_token}


### Start the app
`poetry shell`

`streamlit run src/app.py`

This opens up streamlit interface on port 8501 and allows you to process.

#### NOTE

CPU is ok to use, things will be slow.

## License
MIT License

## Future Plans
Pls add your wish list.

