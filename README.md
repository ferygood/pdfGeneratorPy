# pdfGeneratorPy  
  
This project is to have a software that takes a `.csv` input file and output multiple pages of `.pdf` file.  

Key learning points:

- Use [FPDF](https://pyfpdf.readthedocs.io/en/latest/) to convert dataframe to pdf file.
- Combine **for loop** and **range** to create multi-pages PDF
- Add footer by setting parameters
- Concept of [PEP8](https://peps.python.org/pep-0008/)

* Install dependencies
    1. create virtualenv: `virtualenv --no-site-packages my-env`
    2. list environment, `lsvirtualenv`
    3. activate it using mkvirtualenv: `workon my-env`
    4. install packages `pip install -r requirements.txt`
    - use `pip freeze > requirements.txt` to record all dependencies
    - more information can be found on [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/command_ref.html) 

